<p align="center">
  <img src="docs/images/badger-hub-icon.png" alt="Badger Hub honey badger icon" width="96" height="96">
</p>

<h1 align="center">Badger Hub</h1>

<p align="center"><strong>Your apps, together in one place.</strong></p>
<p align="center">Browse the Badger collection. Install an app. Keep it up to date.</p>

<p align="center">
  <a href="#download-hub">Download Hub</a> ·
  <a href="docs/badger-hub.md">Installation &amp; user guide</a> ·
  <a href="https://github.com/czayas-0314/Badger-Downloads/releases/tag/badger-hub-v0.6.3">Release notes</a> ·
  <a href="https://github.com/czayas-0314/Badger-Downloads/issues/new?template=bug_report.yml">Report a bug</a> ·
  <a href="https://github.com/czayas-0314/Badger-Downloads/issues/new?template=feature_request.yml">Request a feature</a>
</p>

Welcome to **Badger Downloads**, the public home for Badger Hub and the apps in its collection. Hub is a desktop launcher for Mac and Windows: browse app descriptions and screenshots, install compatible releases, open your apps, and manage available updates from one library.

**Downloads are free. No GitHub account or Hub sign-in is required.** Application source is maintained privately; this repository provides public installers, release information, and support. Each app has its own license and compatibility requirements.

<a id="download-hub"></a>

## Badger Hub

Badger Hub 0.6.3 has a shared Rust interface for Mac and Windows. Browse the library, install compatible apps, and update Hub and its apps from within Hub.

| Computer | Download |
| --- | --- |
| Mac, Apple silicon | [0.6.3 DMG](https://github.com/czayas-0314/Badger-Downloads/releases/download/badger-hub-v0.6.3/Badger-Hub-0.6.3-macos-aarch64.dmg) |
| Windows on ARM | [0.6.3 ARM64 installer](https://github.com/czayas-0314/Badger-Downloads/releases/download/badger-hub-v0.6.3/Badger-Hub-0.6.3-windows-aarch64-setup.exe) |
| Windows, Intel or AMD | [0.6.3 x64 installer](https://github.com/czayas-0314/Badger-Downloads/releases/download/badger-hub-v0.6.3/Badger-Hub-0.6.3-windows-x86_64-setup.exe) |

If your Hub is older than 0.6.0, download and install the current Hub once. The previous update-signing key is unavailable, so those installations cannot receive this release through the old updater. Your app libraries and settings are preserved. Subsequent Hub updates use Update & restart.

Open Updates to check for app updates. To update Hub itself, choose Check for Hub updates, then Update & restart. Hub checks when opened or brought forward and every 15 minutes while visible. Close another app before updating it.

The Mac package is signed, notarized and stapled. Windows update ZIPs are signed by the publisher. Windows installers do not have an Authenticode signature. Windows x64 was tested through ARM64 emulation. Intel Mac users can find the earlier beta in [all releases](https://github.com/czayas-0314/Badger-Downloads/releases).

<!-- meerkat-beta:start -->
## Meerkat Envelope

Meerkat Envelope shares its native Rust editor across Mac and Windows. Design envelopes with text and artwork, save Favorites and Templates, and print or export a PDF.

Edit and click away to keep working without saving. The sidebar has visible Save and Favorites controls. Closing with unsaved edits offers Save, Discard and Cancel. Light and dark appearance and the Meerkat mascot are included on both platforms.

<!-- app-downloads:meerkat-envelope:start -->
| Computer | Download |
| --- | --- |
| Mac, Apple silicon or Intel | [2.2.0 DMG](https://github.com/czayas-0314/Badger-Downloads/releases/download/meerkat-v2.2.0/Meerkat-Envelope-2.2.0-macos-universal.dmg) |
| Windows on ARM | [2.2.0 setup EXE](https://github.com/czayas-0314/Badger-Downloads/releases/download/meerkat-v2.2.0/Meerkat-Envelope-2.2.0-windows-arm64-setup.exe) |
| Windows, Intel or AMD | [2.2.0 setup EXE](https://github.com/czayas-0314/Badger-Downloads/releases/download/meerkat-v2.2.0/Meerkat-Envelope-2.2.0-windows-x64-setup.exe) |

Release notes and verification limits: [Mac, Apple silicon or Intel: 2.2.0](https://github.com/czayas-0314/Badger-Downloads/releases/tag/meerkat-v2.2.0) · [Windows on ARM: 2.2.0](https://github.com/czayas-0314/Badger-Downloads/releases/tag/meerkat-v2.2.0) · [Windows, Intel or AMD: 2.2.0](https://github.com/czayas-0314/Badger-Downloads/releases/tag/meerkat-v2.2.0).
<!-- app-downloads:meerkat-envelope:end -->

Install Meerkat through Badger Hub to receive managed updates inside Hub. Standalone Windows installations use the standalone installer for updates. Downloads require no GitHub account. Favorites and settings remain in their separate data folders.

The Mac app and disk image are Developer ID signed, notarized and stapled. Windows installers are unsigned. Hub authenticates the app catalog and verifies download checksums. The release includes checksums and dependency notices with required third-party source material.

For the 2.2.0 release, each platform passed 62 automated tests. The Mac editing workflow was checked live. Manual Windows editing and close-dialog acceptance, physical printer alignment, native Intel Mac hardware and remaining manual accessibility checks are unverified. Windows x64 was tested through ARM64 emulation. Test a sample envelope before printing a batch.

Meerkat Envelope is licensed for personal, non-commercial use; third-party components retain their own licenses.

![Meerkat 2.2.0 on Mac, showing unsaved editing and sidebar Save and Favorites controls with fictional addresses](https://github.com/czayas-0314/Badger-Downloads/releases/download/meerkat-v2.2.0/working-copy-edit.jpg)

Use the platform release notes above for current verification and limits. [Report a bug](https://github.com/czayas-0314/Badger-Downloads/issues/new?template=bug_report.yml&app=Meerkat%20Envelope) with private names and addresses removed.
<!-- meerkat-beta:end -->

<!-- cappy-comm-preview:start -->
## Cappy Comm

Cappy Comm is an alpha preview for keeping messaging accounts in separate browser stores. Mac and Windows have separate preview releases; use the version offered for your platform.

<!-- app-downloads:cappy-comm:start -->
| Computer | Download |
| --- | --- |
| Mac, Apple silicon or Intel | [0.4.0-alpha.8 DMG](https://github.com/czayas-0314/Badger-Downloads/releases/download/cappy-comm-v0.4.0-alpha.8/Cappy-Comm-0.4.0-alpha.8-universal.dmg) |
| Windows, Intel or AMD | [0.4.0-alpha.7 setup EXE](https://github.com/czayas-0314/Badger-Downloads/releases/download/cappy-comm-windows-v0.4.0-alpha.7/Cappy-Comm-0.4.0-alpha.7-windows-x64-setup.exe) |

Release notes and verification limits: [Mac, Apple silicon or Intel: 0.4.0-alpha.8](https://github.com/czayas-0314/Badger-Downloads/releases/tag/cappy-comm-v0.4.0-alpha.8) · [Windows, Intel or AMD: 0.4.0-alpha.7](https://github.com/czayas-0314/Badger-Downloads/releases/tag/cappy-comm-windows-v0.4.0-alpha.7).
<!-- app-downloads:cappy-comm:end -->

Install through Badger Hub when a compatible package is offered, or use the standalone download above. Downloads require no GitHub account. Read the matching platform release notes for signing status, tested behavior, provider limitations, and update instructions. Providers can expire sessions; broader provider delivery and stability checks remain unfinished.

[Report a bug](https://github.com/czayas-0314/Badger-Downloads/issues/new?template=bug_report.yml&app=Cappy%20Comm) or [request a feature](https://github.com/czayas-0314/Badger-Downloads/issues/new?template=feature_request.yml&app=Cappy%20Comm). Remove account details and private messages from reports and screenshots.
<!-- cappy-comm-preview:end -->

## Updates

Each app release contains packages for its published platforms. Checksums and dependency notices accompany the downloads. The signed Hub catalog points to version-specific assets. App updates keep documents and Favorites in their separate data folders.

The Hub catalog is published through the `catalog` release. Meerkat packages use `meerkat-vVERSION` tags. Cappy previews use platform-specific `cappy-comm` tags. Hub installers use `badger-hub-vVERSION` tags. Use the per-app links above; this repository's latest release can belong to any app.

## Other public downloads

[Mongoose Rail for Mac](https://github.com/czayas-0314/mongoose-rail) has its own download repository. It is not currently listed in Badger Hub.

## Help and feedback

Start with the [Hub installation and user guide](docs/badger-hub.md). [Report a bug](https://github.com/czayas-0314/Badger-Downloads/issues/new?template=bug_report.yml) or [request a feature](https://github.com/czayas-0314/Badger-Downloads/issues/new?template=feature_request.yml) using the public forms for Hub, Meerkat Envelope, Cappy Comm, or another app. Include the app version, operating system and processor type. Review pre-filled fields before submitting.

Reports and attachments are public. Remove passwords, tokens, credentials, customer data, real names and addresses, private account details, and unredacted logs or screenshots. The [support and triage guide](docs/support.md) explains the `needs-info`, `accepted`, `in-progress`, and `released` statuses. Application code changes use a separate private-source workflow.

For a direct installation, choose a **DMG** on Mac or a matching **setup EXE** on Windows. GitHub's automatically generated **Source code** archives are not installers. Release ZIPs, signatures, and update manifests serve separate purposes; the [Hub guide explains the files](docs/badger-hub.md#which-release-file-do-i-need).
