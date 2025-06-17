# xsane-patched

This is a patched version of the [xsane](https://gitlab.gnome.org/Scanners/xsane) scanner utility to fix build and runtime issues found in the current official AUR package.

## Why this package exists

The official `xsane` AUR package is currently broken or unmaintained, failing to build or run correctly on recent systems. This package applies several patches to resolve these issues, including:

- Fixes to cancel save functionality.
- Updates to use `xdg-open` instead of deprecated browser launchers.
- Adjustments for recent library and API changes.
- Fixes related to gamma correction code.

## Installation

You can install this package via an AUR helper like `yay`:

```bash
yay -S xsane-patched
