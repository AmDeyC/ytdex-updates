# YTDex updates

Public update files for YTDex. The app downloads them. This page is not the Stable download.

- **Stable** (most people): [AmDeyC/YTDex-releases](https://github.com/AmDeyC/YTDex-releases/releases/latest)
- **Pre-release** (test builds): the releases on this repo. Current test build: [YTDex 1.6.2 Dev 5](https://github.com/AmDeyC/YTDex-updates/releases/tag/v1.6.2-dev.5)

Dev 4 cannot update itself to Dev 5. Install Dev 5 once from that release. Later public test builds can arrive through About › Updates after a license key is saved.

## What is published here

A pre-release is not marked Latest. It has 8 files:

- `YTDex-Setup-<version>-x64.exe` and `.blockmap`
- `YTDex-Setup-<version>-x86.exe` and `.blockmap`
- `YTDex-Setup-<version>.exe`
- `beta.yml` and `beta-ia32.yml`
- `SHA256SUMS.txt`

The Pre-release channel reads `beta.yml` (64-bit) or `beta-ia32.yml` (32-bit). It does not read `latest.yml` or `dev.yml`, and it does not send a GitHub token.

`license-status.json` on the `main` branch is a signed list of SHA-256 key hashes. The app checks that file. It does not contain license keys, signing keys, or tokens. Do not add those to this repository.

Stable releases and the four-version Stable picker live on AmDeyC/YTDex-releases and AmDeyC/YTDex-releases-archive. Do not publish Stable files here.

## Repositories

| Repo | Role |
|---|---|
| AmDeyC/YTDex | Private source |
| AmDeyC/YTDex-updates | This public feed |
| AmDeyC/YTDex-prereleases | Private mirror of the same pre-release files |
| AmDeyC/YTDex-licenses | Private license registry |
| AmDeyC/YTDex-releases | Public Stable |
| AmDeyC/YTDex-releases-archive | Private Stable archive |
