# scoop-apps

[![Tests](https://github.com/ro0c/scoop-apps/actions/workflows/ci.yml/badge.svg)](https://github.com/ro0c/scoop-apps/actions/workflows/ci.yml) [![Excavator](https://github.com/ro0c/scoop-apps/actions/workflows/excavator.yml/badge.svg)](https://github.com/ro0c/scoop-apps/actions/workflows/excavator.yml)

A [Scoop](https://scoop.sh) bucket for Windows command-line applications.

## Available manifests

- `uniterm` — Lightweight all-in-one terminal emulator with built-in AI Agent.
- `keepass-plugin-keeonedrivesync` — KeePass plugin for synchronizing password databases with OneDrive and SharePoint.

## How do I use this bucket?

Add the bucket and install a manifest:

```pwsh
scoop bucket add scoop-apps https://github.com/ro0c/scoop-apps
scoop install scoop-apps/uniterm
scoop install scoop-apps/keepass-plugin-keeonedrivesync
```
