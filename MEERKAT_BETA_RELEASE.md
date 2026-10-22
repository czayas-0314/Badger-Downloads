# Meerkat Envelope public beta

This public beta uses preview version `2.0.0-alpha.2`. It is marked as a prerelease and remains an early testing build.

## Downloads

| Computer | Installer |
| --- | --- |
| Mac with Apple silicon or Intel, macOS 14 or later | Universal DMG |
| Windows 11 with Intel or AMD | Windows x64 EXE |
| Windows 11 on ARM | Windows ARM64 EXE |

Use the matching EXE for a direct Windows installation. Badger Hub uses the `-hub.zip` files for managed Windows installs and updates.

## Changes in this preview

The Rust/Tauri version provides a shared Mac and Windows interface with native drawing and printing. Double-click text to edit directly on the envelope. Choose a standard envelope size or enter custom dimensions, add artwork, and save layouts to Favorites. PDF export is available.

The header uses the mail carrier mascot. The compact illustrated switch selects light or dark appearance and remembers your choice. Envelope paper and print colors stay independent of the interface theme. Discarding unsaved edits and deleting saved envelopes have separate actions.

## Installation warnings

The Mac app and DMG are Developer ID signed with hardened runtime. They are not notarized. macOS may require a per-app security exception before first launch.

The Windows installers and executables are unsigned. Windows may warn or block installation. Signing and notarization are planned for a later release. See [beta installation notes](https://github.com/czayas-0314/Badger-Downloads/blob/main/BETA.md) for platform guidance.

## Testing limits

The current Mac checks and installed Windows ARM64 checks passed. Windows x64 editing, Favorites and PDF export passed under emulation. Local Badger Hub tests exercised authenticated downloads, installation and opening. They also checked updates, profile retention and rejection of a corrupt package.

Physical printing alignment is unverified. Native Intel Mac and Intel/AMD Windows hardware still need testing. Clean-machine installs, spoken screen readers, real display-scaling changes and some printer/cloud-file scenarios remain unfinished. Use a sample envelope before printing a batch, and keep backups of important designs.

The preview installs separately from earlier Meerkat apps. It retains a separate data folder. Keep the earlier app available while testing.

## License and feedback

Meerkat Envelope is licensed for personal, non-commercial use. The app includes its license and third-party notices. The notices archive attached to this release also includes required third-party source material. `SHA256SUMS` identifies the published files.

Report issues at [Badger Downloads](https://github.com/czayas-0314/Badger-Downloads/issues). Include your operating system and app version, and remove private addresses from samples.
