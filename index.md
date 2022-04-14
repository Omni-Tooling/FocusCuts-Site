---
layout: landing
title: FocusCuts
---

## What is FocusCuts
FocusCuts by [SnailedIt](https://snailedit.dev) is a status bar application for macOS which gives you two actions for Shortcuts to get your current Focus Mode and a list of all of your Focus Modes. FocusCuts also lets you customise a list of Shortcuts to display and quickly run _per_ Focus Mode. So if you want to have a quick list of Shortcuts available for Work, but different ones for Personal, you can!

## Shortcuts Actions
FocusCuts has three [Shortcuts actions](/shortcuts) to detect Focus Modes and provide further details:

{% assign sc_collection = site.shortcuts_actions | where: "published", true | sort: "title" %}
{% for shortcut in sc_collection %}
- [{{shortcut.title}}](/shortcuts#{{shortcut.slug}})
{% endfor %}

## Requirements
FocusCuts requires macOS Monterey, as previous versions of macOS do not support Shortcuts or Focus Modes.

## Contact
Do you have a feature request or a bug report? Feel free to reach out!
- [Twitter](twitter.com/SnailedItDev)
- [Email](mailto:{{ site.email | encode_email }})