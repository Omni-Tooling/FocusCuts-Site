---
title: Shortcuts Actions
published: true
order: 2
image: 
---
FocusCuts has three [Shortcuts actions](/shortcuts) to detect Focus Modes and provide further details:

{% assign sc_collection = site.shortcuts_actions | where: "published", true | sort: "title" %}
{% for shortcut in sc_collection %}
- [{{shortcut.title}}](/shortcuts#{{shortcut.slug}})
  {% endfor %}