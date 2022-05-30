---
title: Shortcuts Actions
published: true
order: 2
image:
  asset: auto/shortcuts-actions.svg
  alt: FocusCuts Shortcuts Actions
---
FocusCuts has three [Shortcuts actions]({% link shortcuts.md %}) to detect Focus Modes and provide further details:

{% assign sc_collection = site.shortcuts_actions | where: "published", true | sort: "title" %}
{% for shortcut in sc_collection %}
- [{{shortcut.title}}]({% link shortcuts.md %}/#{{shortcut.slug}})
{% endfor %}