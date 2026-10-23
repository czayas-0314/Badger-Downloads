# Badger Downloads

Official installers for Badger Hub and the apps in its collection. Source code is maintained separately.

## Badger Hub public beta

Badger Hub `0.1.1-beta.1` is also available as a public beta. [Download the launcher](https://github.com/czayas-0314/Badger-Downloads/releases/tag/badger-hub-v0.1.1-beta.1) for Mac or Windows, then install Meerkat from its library. Hub has no account or sign-in requirement. Its Mac app is signed but not notarized; its Windows installer is unsigned. Read the [Hub release notes](https://github.com/czayas-0314/Badger-Downloads/releases/tag/badger-hub-v0.1.1-beta.1) for testing limits.

| Badger Hub installer | Download |
| --- | --- |
| Mac, Apple silicon or Intel | [Universal DMG](https://github.com/czayas-0314/Badger-Downloads/releases/download/badger-hub-v0.1.1-beta.1/Badger-Hub-0.1.1-beta.1-macos-universal.dmg) |
| Windows, Intel or AMD | [Windows x64 installer](https://github.com/czayas-0314/Badger-Downloads/releases/download/badger-hub-v0.1.1-beta.1/Badger-Hub-0.1.1-beta.1-windows-x86_64.exe) |

<!-- meerkat-beta:start -->
## Meerkat Envelope Preview

[Download public beta 2.0.0-alpha.2 for Mac or Windows](https://github.com/czayas-0314/Badger-Downloads/releases/tag/meerkat-v2.0.0-alpha.2).

Design envelopes with text and artwork, save Favorites, and print or export a PDF. The Rust preview runs on Mac and Windows and supports light and dark appearance. Envelope paper and print colors stay independent of the interface theme.

| Computer | Package |
| --- | --- |
| Mac, Apple silicon or Intel, macOS 14 or later | [Universal DMG](https://github.com/czayas-0314/Badger-Downloads/releases/download/meerkat-v2.0.0-alpha.2/Meerkat-Envelope-Preview-2.0.0-alpha.2-macos-universal.dmg) |
| Windows 11, Intel or AMD | [Windows x64 installer](https://github.com/czayas-0314/Badger-Downloads/releases/download/meerkat-v2.0.0-alpha.2/Meerkat-Envelope-Preview-2.0.0-alpha.2-windows-x86_64.exe) |
| Windows 11 on ARM | [Windows ARM64 installer](https://github.com/czayas-0314/Badger-Downloads/releases/download/meerkat-v2.0.0-alpha.2/Meerkat-Envelope-Preview-2.0.0-alpha.2-windows-aarch64.exe) |

Badger Hub selects a compatible download and uses the Windows ZIP packages for managed installation and updates. Public downloads require no GitHub account.

The Mac app is Developer ID signed but is not notarized. Windows packages are unsigned. Your computer may warn or block installation. Read [the beta installation notes](BETA.md). Physical printing alignment and the remaining manual accessibility and hardware checks are unfinished. Keep copies of important designs and test a sample envelope before printing a batch.

The preview installs separately from earlier Meerkat apps. Meerkat Envelope is licensed for personal, non-commercial use; third-party components retain their own licenses. Notices and required third-party source material accompany the release.

![Meerkat Envelope beta in dark appearance, using fictional addresses](screenshots/meerkat-dark.png)

The screenshot shows version 2.0.0-alpha.2. [Release notes](https://github.com/czayas-0314/Badger-Downloads/releases/tag/meerkat-v2.0.0-alpha.2) describe this build's verification and limits. Report problems through [Issues](https://github.com/czayas-0314/Badger-Downloads/issues), including your operating system and app version. Remove real names and addresses from reports and screenshots.
<!-- meerkat-beta:end -->

## Updates

Each Meerkat version has one release containing its Mac and Windows packages. Checksums and dependency notices accompany the downloads. The signed Hub catalog points to version-specific assets. App updates keep documents and Favorites in their separate data folders.

The Hub catalog is published through the `catalog` release. App packages use `meerkat-vVERSION` tags. Hub installers use `badger-hub-vVERSION` tags.

## Other public downloads

[Mongoose Rail for Mac](https://github.com/czayas-0314/mongoose-rail) has its own download repository. It is not currently listed in Badger Hub.
