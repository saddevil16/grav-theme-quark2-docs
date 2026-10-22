---
title: Installation
visible: false
---

# Installation

Quark 2 Docs is a child theme, so it needs its parent theme, **Quark 2**, to be installed.

## Requirements

- Grav 2.1 or later
- The Quark 2 theme

## Install with GPM

Once the theme is listed in the Grav repository:

```bash
bin/gpm install quark2-docs
```

## Install manually

Install the parent theme first:

```bash
bin/gpm install quark2
```

Then clone the theme into `user/themes`. The folder name **must** be `quark2-docs`:

```bash
cd user/themes
git clone https://github.com/saddevil16/grav-theme-quark2-docs.git quark2-docs
```

## Activate the theme

In the admin, open **Themes**, select **Quark 2 Docs** and activate it. You can also set it in `user/config/system.yaml`:

```yaml
pages:
  theme: quark2-docs
```

Clear the cache afterwards:

```bash
bin/grav clearcache
```

## Demo content

The theme ships sample pages in `_demo/pages`. When you install with `bin/gpm install`, GPM offers to copy them into `user/`. Demo content is **not** copied when the theme is installed from the admin. To add it by hand:

```bash
cp -r user/themes/quark2-docs/_demo/pages/. user/pages/
```
