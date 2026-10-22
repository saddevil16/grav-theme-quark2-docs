---
title: Front matter
visible: false
---

# Front matter

Front matter is the YAML block at the top of a page. These are the keys that matter for a docs section.

## Common keys

| Key | Purpose |
| --- | --- |
| `title` | The page title, also used as the sidebar label |
| `menu` | A different label for navigation menus |
| `visible` | Show or hide the page in the main navigation |
| `template` | Use `docs` to select the documentation layout |
| `redirect` | Send visitors to another page |
| `published` | Set to `false` to hide a page everywhere |

## Example

```yaml
---
title: Installation
menu: Install
template: docs
---
```

## Unpublished pages

A page with `published: false` is hidden from the site entirely, including the sidebar. To hide a page only from the main menu, use `visible: false` instead.
