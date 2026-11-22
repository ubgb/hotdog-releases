# Hotdog releases

Hotdog is a private desktop tool for SIAE microwave radios: script prep, path planning, alignment and read-only fleet monitoring. The source repository stays private.

This public repository holds only signed release installers, update bundles and `latest.json` for in-app updates. It contains no source code, radio credentials or customer/network data.

## Current version: 1.4.2

[Downloads and release notes](https://github.com/ubgb/hotdog-releases/releases/tag/v1.4.2)

- **Mac (Apple Silicon):** download `Hotdog_1.4.2_aarch64.dmg`, open it and drag Hotdog into Applications, replacing the old version. Developer signing/notarization is not set up yet, so macOS may warn on first open.
- **Windows (x64):** download and run `Hotdog_1.4.2_x64_en-US.msi`; it upgrades in place. Windows may show an unknown-publisher warning.
- **Future updates:** once 1.4.2 is installed, open **Updates → Check for updates**. Downloads must pass Hotdog's updater signature check, and nothing installs until you confirm. Updater signatures are separate from Apple/Windows developer signing.

The `.app.tar.gz` is for the Mac updater, not a manual installer. `.sig` files carry the updater signatures; `latest.json` also embeds those signatures.

## Update feed

https://github.com/ubgb/hotdog-releases/releases/latest/download/latest.json
