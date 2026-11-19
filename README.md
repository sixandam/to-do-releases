# to-do

Downloads for **to-do**, a to-do list app for Linux and Android that syncs your tasks through a GitHub repository.

**[Download the latest release](https://github.com/sixandam/to-do-releases/releases/latest)**

| Platform | File |
| --- | --- |
| Linux (x86-64) | `to-do-<version>.AppImage` |
| Android | `to-do-<version>.apk` |

## Install

**Linux:** make the AppImage executable and run it once. It installs itself into `~/.local/share/to-do/` and adds to-do to your applications menu. Requires FUSE 2 (`fuse2` on Arch, `libfuse2` on Debian/Ubuntu).

```bash
chmod +x ~/Downloads/to-do-*.AppImage && ~/Downloads/to-do-*.AppImage
```

**Android:** open the release page on your phone, download the `.apk` and open it. If asked, allow your browser to install apps.

## Updates

Both apps check this repository for new versions and ask before installing. No GitHub account is needed to update.

## About this repository

This repository only hosts release builds. The source code is private. Each release lists its changes.
