---
title: Styling
visible: false
---

# Styling

The documentation layout is styled in the theme's `css/custom.css`, which loads after the Quark 2 styles.

## Override the styles

Add your own rules to a stylesheet that loads after the theme, using the classes below.

### Layout classes

- `.docs-layout`: the grid that holds the sidebar, article and table of contents
- `.docs-sidebar`: the left navigation column
- `.docs-content`: the article
- `.docs-toc`: the "On this page" column

### Navigation classes

- `.docs-nav-list`: a list of sidebar topics
- `.docs-nav-item`: one topic (it gets `active`, `activeChild` and `expanded` states)
- `.docs-nav-row`: the link and its expand button
- `.docs-toggle`: the expand and collapse button
- `.docs-subnav`: the nested list under a topic

## Change the sidebar width

Use the **Sidebar width** option in the admin, or set the CSS variable yourself:

```css
:root {
  --docs-sidebar-width: 300px;
}
```

## Light and dark mode

The layout uses Quark 2's color variables, so it follows the active light or dark theme automatically.
