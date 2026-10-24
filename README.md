# Badger Downloads

Official installers for Badger Hub and the apps in its collection. Source code is maintained separately.

## Badger Hub

[Badger Hub 0.1.3 for Apple silicon Mac](https://github.com/czayas-0314/Badger-Downloads/releases/tag/badger-hub-v0.1.3) is Developer ID signed, notarized and stapled. Browse the app collection, install compatible public releases, and open installed apps without an account.

| Computer | Download |
| --- | --- |
| Mac, Apple silicon | [0.1.3 DMG](https://github.com/czayas-0314/Badger-Downloads/releases/download/badger-hub-v0.1.3/Badger-Hub-0.1.3-macos-aarch64.dmg) |
| Mac, Intel, earlier beta | [0.1.1-beta.1 universal DMG](https://github.com/czayas-0314/Badger-Downloads/releases/download/badger-hub-v0.1.1-beta.1/Badger-Hub-0.1.1-beta.1-macos-universal.dmg) |
| Windows, Intel or AMD, earlier beta | [0.1.1-beta.1 Windows x64 installer](https://github.com/czayas-0314/Badger-Downloads/releases/download/badger-hub-v0.1.1-beta.1/Badger-Hub-0.1.1-beta.1-windows-x86_64.exe) |

Hub checks for app releases and its own updates when opened or brought forward, when connectivity returns, and every 15 minutes while visible. Newer compatible app releases show an Update button and update count. Close other apps before updating them.

To update Hub itself, open Updates or About & settings, choose Check for Hub updates, then Update & restart. Hub downloads and verifies the update, replaces its app and restarts. Copies older than 0.1.3 need one installer upgrade to gain the built-in Hub updater.

The earlier Intel Mac beta is signed but not notarized. The earlier Windows beta is unsigned. See their [release notes](https://github.com/czayas-0314/Badger-Downloads/releases/tag/badger-hub-v0.1.1-beta.1) for testing limits.

<!-- meerkat-beta:start -->
## Meerkat Envelope

[Meerkat Envelope 2.0.0 for Mac](https://github.com/czayas-0314/Badger-Downloads/releases/tag/meerkat-v2.0.0) includes Apple silicon and Intel executables for macOS 14 or later. The app and disk image are Developer ID signed, notarized and stapled.

Design envelopes with text and artwork, save Favorites, and print or export a PDF. The interface supports light and dark appearance. Envelope paper and print colors stay independent of the interface theme.

| Computer | Package |
| --- | --- |
| Mac, Apple silicon or Intel, macOS 14 or later | [2.0.0 universal DMG](https://github.com/czayas-0314/Badger-Downloads/releases/download/meerkat-v2.0.0/Meerkat-Envelope-2.0.0-macos-universal.dmg) |
| Windows 11, Intel or AMD, earlier testing release | [2.0.0-alpha.2 Windows x64 installer](https://github.com/czayas-0314/Badger-Downloads/releases/download/meerkat-v2.0.0-alpha.2/Meerkat-Envelope-Preview-2.0.0-alpha.2-windows-x86_64.exe) |
| Windows 11 on ARM, earlier testing release | [2.0.0-alpha.2 Windows ARM64 installer](https://github.com/czayas-0314/Badger-Downloads/releases/download/meerkat-v2.0.0-alpha.2/Meerkat-Envelope-Preview-2.0.0-alpha.2-windows-aarch64.exe) |

Badger Hub selects a compatible download and uses the Windows ZIP packages for managed installation and updates. Public downloads require no GitHub account. Windows packages remain unsigned; read the [earlier beta installation notes](BETA.md).

Mac version 2.0.0 uses the name Meerkat Envelope and retains the previous Rust app's identity and separate Favorites library. Check for Updates opens Badger Hub. Physical printing alignment, native Intel hardware and the remaining manual accessibility checks are unverified. Keep copies of important designs and test a sample envelope before printing a batch.

Meerkat Envelope is licensed for personal, non-commercial use; third-party components retain their own licenses. Notices and required third-party source material are included in the app and the release's notices archive.

![Earlier Meerkat interface in dark appearance, using fictional addresses](screenshots/meerkat-dark.png)

The screenshot shows the earlier 2.0.0-alpha.2 interface. [Mac 2.0.0 release notes](https://github.com/czayas-0314/Badger-Downloads/releases/tag/meerkat-v2.0.0) describe this release's verification and limits. Report problems through [Issues](https://github.com/czayas-0314/Badger-Downloads/issues), including your operating system and app version. Remove real names and addresses from reports and screenshots.
<!-- meerkat-beta:end -->

## Updates

Each app release contains packages for its published platforms. Checksums and dependency notices accompany the downloads. The signed Hub catalog points to version-specific assets. App updates keep documents and Favorites in their separate data folders.

The Hub catalog is published through the `catalog` release. App packages use `meerkat-vVERSION` tags. Hub installers use `badger-hub-vVERSION` tags.

## Other public downloads

[Mongoose Rail for Mac](https://github.com/czayas-0314/mongoose-rail) has its own download repository. It is not currently listed in Badger Hub.
