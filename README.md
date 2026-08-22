<p align="center">
  <img src=".github/assets/logo.svg" alt="SaraTools" width="400"/>
</p>

<p align="center">
  <strong>Built for people with lives.</strong>
</p>

<p align="center">
  Signed builds for every <a href="https://saratools.pro">SaraTools</a> product.
</p>

<p align="center">
  <img src="https://img.shields.io/github/v/release/saratools/saratools-releases?style=flat-square&label=latest" alt="Latest release"/>
  <img src="https://img.shields.io/badge/platforms-windows%20%7C%20linux-blue?style=flat-square" alt="Windows | Linux"/>
  <img src="https://img.shields.io/badge/downloads-signed-green?style=flat-square" alt="Signed"/>
</p>

---

## Overview

This repository is a distribution bucket. It holds published builds and nothing
else — no source code, no issue tracker, no discussion. Every asset here is
signed before it is published.

Releases are tagged per product, so a single page carries whatever is current
for each. The launcher ships here today; anything else that gains its own
installer lands here too.

If you are looking for the products themselves, start at
[saratools.pro](https://saratools.pro).

## Downloads

Grab the latest build from the [Releases](../../releases/latest) page.

### Launcher

| Platform | File |
|----------|------|
| **Windows** | `SaraTools_<version>_x64-setup.exe` |
| **Linux (AppImage)** | `SaraTools_<version>_amd64.AppImage` |
| **Linux (Debian/Ubuntu)** | `SaraTools_<version>_amd64.deb` |

Every installer ships with a matching `.sig` file.

## Updates

The launcher updates itself. It checks for a newer release on start, and
verifies the signature before installing anything — a tampered or unsigned
asset is rejected rather than run.

## Notes

Releases are immutable once published: installed clients resolve them directly,
so editing or deleting one changes what those clients see. Older releases stay
up for that reason.

---

<p align="center">
  <sub><a href="https://saratools.pro">saratools.pro</a></sub>
</p>
