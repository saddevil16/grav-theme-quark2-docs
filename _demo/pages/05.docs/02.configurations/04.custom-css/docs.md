---
title: 'Custom CSS'
visible: false
---

# Custom CSS

Custom CSS allows you to modify the appearance of the documentation without changing the underlying content.

It is particularly useful for adjusting spacing, typography, navigation, and other visual details.

### Recommended Approach

Keep custom styles in a dedicated stylesheet.

For example:

```text
user/themes/custom-quark2/
└── css/
    └── custom.css
```

The location may differ depending on your theme structure.

### Organize Styles by Purpose
Group related rules into clearly labeled sections.

For example:
```css
/*
 * 1. Global styles
 * 2. Typography
 * 3. Documentation layout
 * 4. Sidebar navigation
 * 5. Table of contents
 * 6. Footer
 */
 ```

 This makes it easier to locate existing rules before adding new ones.

### Avoid Duplicate Rules
Before introducing a new declaration, check whether an existing selector already controls the same element.

For example, if the sidebar heading already has a defined margin, modify that rule instead of creating another competing declaration.

Duplicate rules can make future maintenance more difficult.

### Use Specific Selectors
Prefer selectors that target the intended component without affecting unrelated pages.

For example:
```css
.documentation-content h2 {
    margin-top: 2rem;
}
```

The selector is illustrative. Replace it with a selector that matches your actual theme markup.

### Test Your Changes
After editing the stylesheet:
1. Refresh the page.
2. Check the desktop layout.
3. Check the mobile layout.
4. Inspect any unexpected spacing.
5. Confirm that other pages remain unaffected.

