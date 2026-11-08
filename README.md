# Shelf Life: downloads and updates

Shelf Life is a Mac app that shows what is taking up space on your Mac and in iCloud Drive and helps you clear it. This repository only holds the builds and the update feed. It contains no source code.

## Download

Get the newest `Shelf-Life-<version>.dmg` from [Releases](../../releases/latest), open it and drag Shelf Life to Applications.

Needs a Mac with Apple silicon (M1 or newer) running macOS 26.

## First launch (once)

Shelf Life is not notarized by Apple, so macOS asks you to confirm the first launch:

1. Open Shelf Life. macOS says it can’t verify it. Click Done.
2. Open System Settings > Privacy & Security, scroll down, and click Open Anyway next to Shelf Life.
3. Confirm with your password or Touch ID.

After that it opens normally, and new versions install from inside the app (Shelf Life > Check for Updates…).

## Updates

Shelf Life can check this repository for new versions. It asks you once, and you can turn it off in Settings. The check sends the version numbers of Shelf Life and its updater, nothing about your files. Every update is signed, and the app refuses one that does not match its key.
