# Badger Downloads

Official installers for Badger Hub and the apps in its collection. Source code is maintained separately.

Downloads are free and require no GitHub account. Download Hub, then use its library to install compatible apps and their available updates. GitHub hosts the published downloads, so they remain available when the build computers are off.

## Badger Hub

Badger Hub 0.3.0 has a shared Rust interface for Mac and Windows. Browse the library, install compatible apps, and update Hub and its apps from within Hub.

| Computer | Download |
| --- | --- |
| Mac, Apple silicon | [0.3.0 DMG](https://github.com/czayas-0314/Badger-Downloads/releases/download/badger-hub-v0.3.0/Badger-Hub-0.3.0-macos-aarch64.dmg) |
| Windows on ARM | [0.3.0 ARM64 installer](https://github.com/czayas-0314/Badger-Downloads/releases/download/badger-hub-v0.3.0/Badger-Hub-0.3.0-windows-aarch64-setup.exe) |
| Windows, Intel or AMD | [0.3.0 x64 installer](https://github.com/czayas-0314/Badger-Downloads/releases/download/badger-hub-v0.3.0/Badger-Hub-0.3.0-windows-x86_64-setup.exe) |

Open Updates to check for app updates. To update Hub itself, choose Check for Hub updates, then Update & restart. Hub checks when opened or brought forward and every 15 minutes while visible. Close another app before updating it.

The Mac package is signed, notarized and stapled. Windows update ZIPs are signed by the publisher; Windows installers do not have an Authenticode signature. Windows x64 was tested through ARM64 emulation. Intel Mac users can find the earlier beta in [all releases](https://github.com/czayas-0314/Badger-Downloads/releases).

<!-- meerkat-beta:start -->
## Meerkat Envelope

[Meerkat Envelope 2.2.0 for Mac and Windows](https://github.com/czayas-0314/Badger-Downloads/releases/tag/meerkat-v2.2.0) shares its native Rust editor across both operating systems. Design envelopes with text and artwork, save Favorites and Templates, and print or export a PDF.

Edit and click away to keep working without saving. The sidebar has visible Save and Favorites controls. Closing with unsaved edits offers Save, Discard and Cancel. Light and dark appearance and the Meerkat mascot are included on both platforms.

| Computer | Download |
| --- | --- |
| Mac, Apple silicon or Intel, macOS 14 or later | [2.2.0 universal DMG](https://github.com/czayas-0314/Badger-Downloads/releases/download/meerkat-v2.2.0/Meerkat-Envelope-2.2.0-macos-universal.dmg) |
| Windows 11, Intel or AMD | [2.2.0 x64 installer](https://github.com/czayas-0314/Badger-Downloads/releases/download/meerkat-v2.2.0/Meerkat-Envelope-2.2.0-windows-x64-setup.exe) |
| Windows 11 on ARM | [2.2.0 ARM64 installer](https://github.com/czayas-0314/Badger-Downloads/releases/download/meerkat-v2.2.0/Meerkat-Envelope-2.2.0-windows-arm64-setup.exe) |

Install Meerkat through Badger Hub to receive managed updates inside Hub. Standalone Windows installations use the standalone installer for updates. Downloads require no GitHub account. Favorites and settings remain in their separate data folders.

The Mac app and disk image are Developer ID signed, notarized and stapled. Windows installers are unsigned. Hub authenticates the app catalog and verifies download checksums. The release includes checksums and dependency notices with required third-party source material.

Each platform passed 62 automated tests. The Mac editing workflow was checked live. Manual Windows editing and close-dialog acceptance, physical printer alignment, native Intel Mac hardware and remaining manual accessibility checks are unverified. Windows x64 was tested through ARM64 emulation. Test a sample envelope before printing a batch.

Meerkat Envelope is licensed for personal, non-commercial use; third-party components retain their own licenses.

![Meerkat 2.2.0 on Mac, showing unsaved editing and sidebar Save and Favorites controls with fictional addresses](https://github.com/czayas-0314/Badger-Downloads/releases/download/meerkat-v2.2.0/working-copy-edit.jpg)

[Release notes](https://github.com/czayas-0314/Badger-Downloads/releases/tag/meerkat-v2.2.0) describe the verification and limits. Report problems through [Issues](https://github.com/czayas-0314/Badger-Downloads/issues), including your operating system and app version. Remove real names and addresses from reports and screenshots.
<!-- meerkat-beta:end -->

## Updates

Each app release contains packages for its published platforms. Checksums and dependency notices accompany the downloads. The signed Hub catalog points to version-specific assets. App updates keep documents and Favorites in their separate data folders.

The Hub catalog is published through the `catalog` release. App packages use `meerkat-vVERSION` tags. Hub installers use `badger-hub-vVERSION` tags.

## Other public downloads

[Mongoose Rail for Mac](https://github.com/czayas-0314/mongoose-rail) has its own download repository. It is not currently listed in Badger Hub.
