# Vantage for Windows

Official installers and application update packages for Vantage. Application source code is private and is not distributed here.

## Install

Download **Vantage-win-Setup.exe** from the [latest Stable release](https://github.com/jyeager976/Vantage-Releases/releases/latest). Windows 10/11 x64 is required. Check the installer's digital signature before running it.

Existing Vantage installations update through the application. Version 0.16.6 is the final Supabase-delivered bridge; after installing it, future updates come from this repository automatically. Project repositories remain separate from the application installation.

## Channels

Each version has one release tagged `v<version>`. It starts as a **Canary prerelease** for users configured for Canary. Acceptance promotes the same release to **Stable**, preserving its signed files. Stable users receive normal releases; Canary users can receive both prereleases and accepted Stable releases.

Full and Delta `.nupkg` files and `releases.win.json` are consumed by the updater. Use the signed Setup executable for a first installation. A GitHub account is not required to download updates.

These downloads do not grant an open-source license to the application.
