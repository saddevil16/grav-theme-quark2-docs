---
title: Theme options
visible: false
---

# Theme options

Open **Themes** in the admin, select **Quark 2 Docs**, and find the **Documentation layout** section.

## Documentation options

| Option | Default | Description |
| --- | --- | --- |
| `docs.root` | `/docs` | Route of the page whose children appear in the sidebar |
| `docs.include_hidden` | `true` | List pages that are not visible in the sidebar |
| `docs.show_toc` | `true` | Show the "On this page" list on child pages |
| `docs.remember_state` | `true` | Remember expanded sidebar sections during the browser session |
| `docs.sidebar_width` | `250` | Sidebar width in pixels (180 to 400) |

## Set options in a file

The same values can be set in `user/config/themes/quark2-docs.yaml`:

```yaml
docs:
  root: /manual
  include_hidden: true
  show_toc: true
  remember_state: true
  sidebar_width: 280
```

## Options inherited from Quark 2

Everything else in the theme settings (theme mode, accent color, header, logos, footer and Font Awesome) comes from Quark 2 and works as it does there.
