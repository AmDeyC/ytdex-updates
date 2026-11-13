<p align="center">
  <img src="assets/ytdex-icon.svg" width="88" alt="YTDex">
</p>

<h1 align="center">YTDex</h1>

<p align="center">Videos and music for Windows, in one app.</p>

<p align="center">
  <a href="https://github.com/AmDeyC/YTDex-releases/releases/latest"><img src="assets/download-button.svg" width="320" alt="Download YTDex for Windows"></a>
</p>

<p align="center"><sub>Windows 10 and 11 · 64-bit and 32-bit · free · unofficial</sub></p>

This is the **public pre-release update feed** for YTDex. The app downloads test builds from here. This page is not the Stable download.

`license-status.json` on the `main` branch is a signed list of SHA-256 key hashes. The app checks that file. It does not contain license keys, signing keys, or tokens. Do not add those to this repository.

- **Stable** (most people): [AmDeyC/YTDex-releases](https://github.com/AmDeyC/YTDex-releases/releases/latest) (currently 1.6.1)
- **Pre-release** (test builds): the releases on this repo. Current test build: [YTDex 1.6.2 Dev 7](https://github.com/AmDeyC/YTDex-updates/releases/tag/v1.6.2-dev.7)

**Dev 4, Dev 5, and Dev 6 cannot update themselves to Dev 7.** Install Dev 7 once from that release. Later public test builds can arrive through About › Updates after a Pre-release License Key is saved. No GitHub token is used.

## Features

- Tabs, Videos and Music modes, and a mini player
- Ad blocking and sponsor skipping
- Cast to TVs
- Equalizer with 3D Surround
- Playlist and Subscription managers
- Offline saving, a User manual and offline games
- Automatic updates

Dev 7 keeps your existing install folder and settings in `%APPDATA%\YTDex`, groups the status bar, uses the official tray icon, and adds 3D theme-matched tabs, a Hide Shorts toggle, a status-bar filter update control, and license-key ad-free.

## Install

1. For Stable, download **YTDex-Setup-&lt;version&gt;.exe** from the [latest Stable release](https://github.com/AmDeyC/YTDex-releases/releases/latest).
2. For this test build, download **YTDex-Setup-1.6.2-dev.7.exe** from the [Dev 7 release](https://github.com/AmDeyC/YTDex-updates/releases/tag/v1.6.2-dev.7).
3. Run it. If Windows shows "Windows protected your PC", click **More info**, then **Run anyway**.

## What is published here

A pre-release is not marked Latest. It has 8 files:

- `YTDex-Setup-<version>-x64.exe` and `.blockmap`
- `YTDex-Setup-<version>-x86.exe` and `.blockmap`
- `YTDex-Setup-<version>.exe`
- `beta.yml` and `beta-ia32.yml`
- `SHA256SUMS.txt`

The Pre-release channel reads `beta.yml` (64-bit) or `beta-ia32.yml` (32-bit). It does not read `latest.yml` or `dev.yml`, and it does not send a GitHub token.

Check `SHA256SUMS.txt` before you run a setup. The build is not code-signed.

Stable releases and the four-version Stable picker live on AmDeyC/YTDex-releases and AmDeyC/YTDex-releases-archive. Do not publish Stable files here.

## Privacy

No account, no analytics and no tracking. Your sign-in and settings stay on your PC.

## Help

Use **Help › Logs & health** and attach the exported log to an [issue](https://github.com/AmDeyC/YTDex-releases/issues).

## Repositories

| Repo | Role |
|---|---|
| AmDeyC/YTDex | Private source |
| AmDeyC/YTDex-updates | This public feed |
| AmDeyC/YTDex-prereleases | Private mirror of the same pre-release files |
| AmDeyC/YTDex-licenses | Private license registry |
| AmDeyC/YTDex-releases | Public Stable |
| AmDeyC/YTDex-releases-archive | Private Stable archive |

## Credits

Based on [the original desktop app](https://github.com/mikepruett3/youtube-desktop) by **Mike Pruett**.
YTDex isn't affiliated with any video or music service.
