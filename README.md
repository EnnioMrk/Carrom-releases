# Dabbu Carrom — build downloads

This repository carries only the release builds of **Dabbu Carrom**
(source: a private repository).

- Every release of the source repository is mirrored here with its debug-signed
  APK (`dabbu-carrom-vX.Y.Z-debug.apk`, Android 7.0+ / minSdk 24) as the asset.
- The Android app reads this repository at startup and offers the newest
  version as an in-app update.
- Do not change or delete existing releases and assets: an installed app
  compares its own version with them.
