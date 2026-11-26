# Triage releases

Built copies of Triage, a light daily checklist for macOS. This repository holds only the releases; the app looks here for updates.

Each release has:

- `Triage-x.y.z.zip`: the app, for Apple Silicon and Intel Macs (macOS 12 or later). This is what **Settings → Updates** downloads.
- `Triage-x.y.z.zip.sha256`: the checksum the app verifies the download against.
- `Triage-x.y.z.dmg`: the same app as a disk image, for installing by hand.

## Installing by hand

Open the DMG and drag Triage to Applications. The app is ad-hoc signed and not notarized, so macOS blocks the first launch of a downloaded copy: try to open it once, then choose **System Settings → Privacy & Security → Open Anyway**. Updates installed from inside the app do not need this step.
