---
title: 'Theme Settings'
visible: false
---

# Theme Settings

Theme settings determine how content is presented to visitors.

Depending on the theme, these settings may control navigation, page layout, typography, and other interface elements.

### Theme Configuration Files

Grav themes commonly provide configuration files that define their default options.

A theme may include a file such as:

```text
user/themes/quark2-docs/blueprints.yaml
```

The exact files and available options depend on the theme implementation.

### Layout Options
A documentation theme may provide separate layouts for:
- Section landing pages.
- Individual documentation pages.
- Nested topics.
- Pages with a table of contents.

Using consistent layouts helps readers understand where they are within the documentation.

### Navigation Options
Navigation settings may influence how page titles and nested pages are displayed.

For example, a page tree might look like this:
```text
Getting Started
├── Quark 2 Docs
├── Requirements
└── Installation
```

The sidebar should make the relationship between these pages clear.

### Customization
Before introducing a new theme option, check whether the theme already provides an equivalent setting.

This avoids unnecessary duplication between configuration files, Twig templates, and custom CSS.

### Related Topics
- [Navigation](/docs/configurations/navigation)
- [Custom CSS](/docs/configurations/custom-css)