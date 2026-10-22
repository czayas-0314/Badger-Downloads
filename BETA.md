# Installing the public beta

Meerkat Envelope `2.0.0-alpha.2` is an early public beta for personal, non-commercial use. Its packages and app use the name Preview. The preview has a separate app identity and data folder. Keep the earlier app and a copy of important designs while testing.

## Mac

Use the universal DMG on macOS 14 or later. Open it and drag Meerkat Envelope Preview into Applications.

The app has a Developer ID signature. Apple notarization is unfinished, so macOS may block its first launch. If you trust the official download, Apple's [opening-app guidance](https://support.apple.com/en-us/102445) explains the per-app Open Anyway option in System Settings, Privacy & Security. Managed Macs may restrict this option.

## Windows

Use the x64 EXE for an Intel or AMD computer, or the ARM64 EXE for Windows on ARM. Windows 11 is the current testing target. Installation is for your user account. Initial WebView2 setup may need internet access.

The installers and app executables are unsigned. Windows may show an unknown-publisher or SmartScreen warning. Smart App Control or your organization's policies may block the app. See [Microsoft's explanation](https://learn.microsoft.com/en-us/windows/apps/package-and-deploy/smartscreen-reputation). Do not disable your computer's security protections to install this beta.

Files ending in `-hub.zip` are managed packages for Badger Hub. Use the EXE if you are installing Meerkat yourself.

## What remains unverified

Physical printer alignment has not been accepted. Select the envelope size that matches the loaded paper and check one sample before printing a batch.

Testing on native Intel Mac and Intel/AMD Windows hardware remains unfinished. Windows x64 checks used emulation on an ARM64 VM. Clean-machine installation, spoken screen-reader output and actual display-scaling changes still need testing. Some printer-dialog and cloud-file scenarios also remain open.

## Saved designs and updates

The preview keeps its documents and Favorites outside the app installation. It can copy saved data from an earlier Meerkat profile while retaining the originals. Updates are intended to preserve those separate data folders. Keep your own backup during beta testing.

Badger Hub verifies its catalog signature and package checksums. Those checks do not replace Apple notarization or Windows code signing.

## Feedback and licenses

Report problems through [Badger Downloads Issues](https://github.com/czayas-0314/Badger-Downloads/issues). Include your platform and version, the steps taken, and what happened. Use fictional addresses in shared samples.

Meerkat's personal-use license and third-party notices are included in the app. The release also includes a separate notices archive with the required third-party source material.
