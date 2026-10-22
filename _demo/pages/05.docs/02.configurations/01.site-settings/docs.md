---
title: 'Site Settings'
visible: false
---

# Site Settings

Site settings control general information and behavior across the website.

Depending on your Grav configuration, these settings may be managed through YAML configuration files or the administrative interface.

### Site Title

The site title identifies your website.

For example:

```yaml
title: Quark 2 Docs
```

A theme may use this value in the header, browser title, or other interface elements.

The exact behavior depends on the active theme.

### Metadata
Metadata provides information about individual pages and the website.

For example:
```yaml
title: Installation
description: Install and configure the documentation website.
```
The title identifies the page, while the description summarizes its purpose.

### Page-Level Settings
Individual pages can define their own frontmatter.

```yaml
---
title: Custom CSS
description: Customize the appearance of the documentation.
---
```

Page-level settings make it easier to maintain meaningful titles and descriptions throughout the website.

### Configuration Best Practices

#### Use Descriptive Titles
Choose titles that clearly communicate the purpose of each page.

#### Keep Descriptions Concise
A short description is generally easier to understand and maintain.

#### Avoid Unnecessary Duplication
Use shared configuration where appropriate, and override individual pages only when necessary.

### Related Topics
- [Theme Settings](/docs/configurations/theme-settings)
- [Navigation](/docs/configurations/navigation)