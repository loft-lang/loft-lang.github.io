<!--
Copyright (c) 2026 Jurjen Stellingwerff
SPDX-License-Identifier: LGPL-3.0-or-later
-->

# loft-lang.github.io

The landing page served at <https://loft-lang.org/>.

GitHub Pages serves `index.html` from `main`; the `CNAME` file
claims the custom domain.

## Deploying

Just push to `main`.  GitHub Pages rebuilds within ~1 minute.

DNS records for the custom domain are at the
`loft-lang.org` registrar; see loft's
[REGISTRY_BOOTSTRAP.md](https://github.com/jjstwerff/loft/blob/main/doc/claude/REGISTRY_BOOTSTRAP.md)
companion docs for the full Pages setup runbook (apex `A` records
to GitHub's 4 IPs + a `www` CNAME).
