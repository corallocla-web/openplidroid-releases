# OpenPLiDroid — releases

Distribution channel for the [OpenPLiDroid](https://github.com/corallocla-web/openplidroid)
Android TV app (the source repository is private).

- **`update.json`** on the `main` branch is the manifest the app polls (~every 12 h,
  and on demand from *Box → Mise à jour*). It points at the APK for the latest build.
- The **APK** for each build is attached to the matching GitHub Release
  (`v<versionName>`), e.g. `openplidroid-0.2.0.apk`.

Every APK is signed with the same key, so the app installs updates over itself
without a reinstall.

## Manual install

Download the latest `openplidroid-*.apk` from
[Releases](https://github.com/corallocla-web/openplidroid-releases/releases) and
side-load it (Send Files to TV, a USB stick, or `adb install -r`).
