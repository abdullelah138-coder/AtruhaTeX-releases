# AtruhaTeX

A desktop LaTeX editor for Windows.

This repository contains official Windows installers, update metadata, checksums, and third-party notices.

## Windows installation

[Download AtruhaTeX for Windows x64](https://raw.githubusercontent.com/abdullelah138-coder/AtruhaTeX-releases/main/windows/1.0.1/build-2/AtruhaTeX_1.0.1_Windows-x64.exe)

Run the EXE to install AtruhaTeX. Existing files and settings are preserved when upgrading an installation in the same location. Previous versions remain available in the `windows` directory.

The installer includes PDF viewing and the Texlab language server. LaTeX compilation requires a TeX distribution. WebView2 is installed when needed.

## Updates

Update-enabled installations check when the app opens and show a notice when an update is available. Review updates under **Settings → About → Application updates**. Download and installation require your action; open work is saved before installation proceeds.

Older installations without an update channel need one manual upgrade to an update-enabled installer. Subsequent updates replace the existing application in place.

Maintenance updates keep the release name and version unchanged. AtruhaTeX is currently **Pi 3.1 (1.0.1)**.

To experience an in-app update, install the [earlier update-enabled build](https://raw.githubusercontent.com/abdullelah138-coder/AtruhaTeX-releases/main/windows/1.0.1/build-1/AtruhaTeX_1.0.1_Windows-x64.exe), then open AtruhaTeX. It will offer the newer build while retaining version 1.0.1.

## Verification

Each version includes `SHA256SUMS` and an updater signature. The application verifies update signatures before installation. These signatures are separate from a Windows publisher certificate; Windows may display an unknown publisher prompt for these installers.

Required third-party notices accompany each release.
