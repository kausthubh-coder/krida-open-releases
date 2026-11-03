# Krida apps

This repo holds the app builds of open Krida, the free, open-source streaming app at
https://krida-open.vercel.app. There's no code here, only releases:

- **Krida for Mac** (Apple Silicon): the `.dmg` in the newest `desktop-v*` release. It isn't notarized, so the first
  time you open it, go to System Settings, Privacy & Security, and choose Open Anyway.
- **Krida for Android**: the `.apk` in the newest `android-v*` release.
- **Krida for Windows**: coming soon.

Installed apps update themselves from here: the desktop apps read `latest.json` in the latest release, and Android
reads `android.json` on this branch.
