---
title: Hiding pages from the menu
visible: false
---

# Hiding pages from the menu

Grav lists a page in the main navigation when its folder has a number prefix or `visible: true`. Documentation topics usually belong in the sidebar, not in the top menu.

## Hide a page

Set `visible` in the page's front matter:

```yaml
---
title: Troubleshooting
visible: false
---
```

Set it on every page that should stay out of the top menu. The pages in this demo do exactly that, while the docs landing page uses `visible: true` so the "Docs" link stays in the main menu.

## Folders without a number prefix

A folder without a number prefix is not visible by default, so it needs no `visible` setting. The trade-off is ordering: without prefixes the pages are sorted by folder name rather than by a number you choose.

## Keep hidden pages in the sidebar

The sidebar lists pages that are not visible as long as **Include non-visible pages in sidebar** (`docs.include_hidden`) is enabled, which it is by default. Turn it off if you want the sidebar to follow the main menu instead.

## Send visitors to a first topic

Use `redirect` on the landing page to send visitors straight to a topic:

```yaml
---
title: Docs
redirect: /docs/getting-started
---
```

Append a status code in square brackets for a permanent redirect: `redirect: /docs/getting-started[301]`.
