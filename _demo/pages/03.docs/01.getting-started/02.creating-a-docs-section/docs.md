---
title: Creating a docs section
visible: false
---

# Creating a docs section

Only pages that use the `docs` template get the documentation layout. The rest of your site keeps its normal templates.

## Create the docs landing page

Add a folder under `user/pages` and put a page named `docs.md` in it. Pages named `docs.md` use the documentation template automatically.

```markdown
---
title: Docs
---

# Documentation

Welcome.
```

## Add topics

Each topic is a child folder with its own `docs.md`. Folders can be nested as deep as you need.

```text
user/pages/docs/
  docs.md
  01.getting-started/
    docs.md
    01.installation/
      docs.md
  02.configuration/
    docs.md
```

## Order and titles

- Number prefixes (`01.`, `02.`) control the order in the sidebar.
- The `title` in each page's front matter is the label shown in the sidebar.
- A folder without a number prefix still works, it is just sorted by name.

## Use a different file name

If you prefer another file name, select the template in the front matter instead:

```yaml
---
title: Getting Started
template: docs
---
```

Every page that should show the sidebar must use the `docs` template, either through the file name or through this setting.
