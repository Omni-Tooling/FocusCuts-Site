---
layout: landing
title: FocusCuts
---

## What is FocusCuts
FocusCuts by [Snailed It Development](https://snailedit.dev) is a status bar application for macOS which gives you three Shorcut actions to manage your Focus Modes. With FocusCuts you are also able to customise a list of Shortcuts to display and quickly run _per_ Focus Mode. So if you want to have an easily accessible list of Shortcuts available for Work, but a different list for your Personal Focus Mode, you can!

## Shortcuts Actions
FocusCuts has three [Shortcuts actions](/shortcuts) to detect Focus Modes and provide further details:

{% assign sc_collection = site.shortcuts_actions | where: "published", true | sort: "title" %}
{% for shortcut in sc_collection %}
- [{{shortcut.title}}](/shortcuts#{{shortcut.slug}})
{% endfor %}

## Requirements
FocusCuts requires macOS Monterey, as previous versions of macOS do not support Shortcuts or Focus Modes.

## Contact
Do you have a feature request or a bug report? Please get in touch!
- [Twitter](https://twitter.com/SnailedItDev)
- [Email](mailto:{{ site.email | encode_email }})
