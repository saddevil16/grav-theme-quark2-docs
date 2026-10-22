---
title: Navigation
visible: false
---

# Navigation

Navigation helps readers discover related documentation and understand the structure of the website.

A well-organized documentation website should make it easy to move between sections without overwhelming the reader.

### Hierarchical Structure

Documentation pages can be organized into parent and child relationships.

For example:

```text
Themes
└── Twig Tags, Filters & Functions
    ├── Twig Tags
    ├── Twig Filters
    └── Twig Functions
```
The hierarchy communicates that the three Twig pages belong to the same topic.

### Sidebar Navigation
The sidebar displays the documentation hierarchy.

A useful sidebar should:
- Show the current section clearly.
- Distinguish parent pages from child pages.
- Indicate the active page.
- Allow readers to discover related topics.
- Avoid unnecessary visual clutter.

### Page Titles
Use readable titles rather than exposing directory names directly.

For example:  

| Directory name | Display title |
|---|---|
| `getting-started` | Getting Started |
| `twig-tags-filters-functions` | Twig Tags, Filters & Functions |
| `custom-css` | Custom CSS |

Grav's page configuration can provide display titles independently of the directory names.

### Navigation Depth
Keep the hierarchy predictable.

For this project, the intended structure is:
1. Main section.
2. Topic.
3. Subtopic.
This provides enough flexibility for technical documentation without creating excessively deep navigation trees.

### Related Topics
- [Theme Settings](/docs/configurations/theme-settings)
- [Page Structure](/docs/configurations/page-structure)