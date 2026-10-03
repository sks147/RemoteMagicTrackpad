# RemoteMagicTrackpad
Mac OS companion app for Remote Magic Trackpad Android app

## Download
**[RemoteMagicTrackpad-1.0-arm64.dmg.zip](https://github.com/sks147/RemoteMagicTrackpad/releases/download/1.0.0/RemoteMagicTrackpad-1.0-arm64.dmg.zip)** ([release notes](https://github.com/sks147/RemoteMagicTrackpad/releases/tag/1.0.0))

Requires a Mac with Apple silicon running macOS 13 or later.

## Install
1. Unzip the download, open the DMG and drag Remote Magic Trackpad to Applications.
2. Launch it. macOS will say "Apple could not verify…" because the app isn't notarized. Click **Done**.
3. Open **System Settings → Privacy & Security**, scroll down and click **Open Anyway**, then confirm.

Alternatively, run this in Terminal before opening the DMG:
```sh
xattr -dr com.apple.quarantine ~/Downloads/RemoteMagicTrackpad-1.0-arm64.dmg
```

### Upgrading from the earlier 1.0 download
If the app was already installed, remove its entries (–) under **Privacy & Security → Accessibility** and **Input Monitoring**, then grant access again when the app asks.
