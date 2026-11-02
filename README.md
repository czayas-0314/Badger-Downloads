<p align="center">
  <img src="docs/images/badger-hub-icon.png" alt="Badger Hub honey badger icon" width="96" height="96">
</p>

<h1 align="center">Badger Hub</h1>

<p align="center"><strong>Your apps, together in one place.</strong></p>
<p align="center">Browse the Badger collection. Install an app. Keep it up to date.</p>

<p align="center">
  <a href="#download-hub">Download Hub</a> ·
  <a href="docs/badger-hub.md">Installation &amp; user guide</a> ·
  <a href="https://github.com/czayas-0314/Badger-Downloads/releases/tag/badger-hub-v0.4.0">Release notes</a> ·
  <a href="https://github.com/czayas-0314/Badger-Downloads/issues">Get help</a>
</p>

Welcome to **Badger Downloads**, the public home for Badger Hub and the apps in its collection. Hub is a desktop launcher for Mac and Windows: browse app descriptions and screenshots, install compatible releases, open your apps, and manage available updates from one library.

**Downloads are free. No GitHub account or Hub sign-in is required.** Application source is maintained privately; this repository provides public installers, release information, and support. Each app has its own license and compatibility requirements.

<a id="download-hub"></a>

## Badger Hub

Badger Hub 0.4.1 has a shared Rust interface for Mac and Windows. Browse the library, install compatible apps, and update Hub and its apps from within Hub.

| Computer | Download |
| --- | --- |
| Mac, Apple silicon | [0.4.1 DMG](https://github.com/czayas-0314/Badger-Downloads/releases/download/badger-hub-v0.4.1/Badger-Hub-0.4.1-macos-aarch64.dmg) |
| Windows on ARM | [0.4.1 ARM64 installer](https://github.com/czayas-0314/Badger-Downloads/releases/download/badger-hub-v0.4.1/Badger-Hub-0.4.1-windows-aarch64-setup.exe) |
| Windows, Intel or AMD | [0.4.1 x64 installer](https://github.com/czayas-0314/Badger-Downloads/releases/download/badger-hub-v0.4.1/Badger-Hub-0.4.1-windows-x86_64-setup.exe) |

If your Hub is older than 0.4.1, download and install the current Hub once. The previous update-signing key is unavailable, so those installations cannot receive this release through the old updater. Your app libraries and settings are preserved. Subsequent Hub updates use Update & restart.

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

<!-- cappy-comm-preview:start -->
## Cappy Comm for Mac

[Cappy Comm 0.4.0-alpha.6](https://github.com/czayas-0314/Badger-Downloads/releases/tag/cappy-comm-v0.4.0-alpha.6) is a Mac alpha preview for keeping messaging accounts in separate browser stores.

| Computer | Download |
| --- | --- |
| Mac, Apple silicon or Intel, macOS 14 or later | [0.4.0-alpha.6 universal DMG](https://github.com/czayas-0314/Badger-Downloads/releases/download/cappy-comm-v0.4.0-alpha.6/Cappy-Comm-0.4.0-alpha.6-universal.dmg) |

The compact sidebar remembers its width. Right-click an account to mute or unmute its desktop notifications. Mac sessions use the local Keychain to restore session-only cookies after quitting.

The app and disk image are Developer ID signed, notarized and stapled. Open the DMG and drag Cappy Comm.app to Applications. The release includes checksums and dependency notices. Downloads require no GitHub account.

The installed Mac app kept its WhatsApp sign-in through normal Quit and relaunch. Broader provider delivery and stability checks remain unfinished. Providers can expire sessions. Signal is unavailable. Windows will follow separate testing.

[Release notes and verification limits](https://github.com/czayas-0314/Badger-Downloads/releases/tag/cappy-comm-v0.4.0-alpha.6) describe the preview. Screenshots show the updated layout with fictional accounts in a separate development app.
<!-- cappy-comm-preview:end -->

## Updates

Each app release contains packages for its published platforms. Checksums and dependency notices accompany the downloads. The signed Hub catalog points to version-specific assets. App updates keep documents and Favorites in their separate data folders.

The Hub catalog is published through the `catalog` release. App packages use `meerkat-vVERSION` tags. Hub installers use `badger-hub-vVERSION` tags.

## Other public downloads

[Mongoose Rail for Mac](https://github.com/czayas-0314/mongoose-rail) has its own download repository. It is not currently listed in Badger Hub.

## Help and feedback

Start with the [Hub installation and user guide](docs/badger-hub.md). If something still does not work, [open an issue](https://github.com/czayas-0314/Badger-Downloads/issues/new) with the app name and version, operating system, processor type, steps to reproduce, and the exact error. Screenshots help; remove private names, addresses, account details, and other personal information before posting.

For a direct installation, choose a **DMG** on Mac or a matching **setup EXE** on Windows. GitHub's automatically generated **Source code** archives are not installers. Release ZIPs, signatures, and update manifests serve separate purposes; the [Hub guide explains the files](docs/badger-hub.md#which-release-file-do-i-need).
