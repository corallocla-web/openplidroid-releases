# OpenPLiDroid — releases

Distribution channel for **OpenPLiDroid**, an Android app that turns a
Dreambox / OpenPLi (enigma2) satellite receiver into a full-screen, remote-driven
experience — browse, watch, record and manage the box over your LAN.
The source repository is private.

## Downloads

Grab the latest APK from the
[Releases](https://github.com/corallocla-web/openplidroid-releases/releases) page
and side-load it (Send Files to TV, a USB stick, or `adb install -r`).

| Build | Release tag | Package | Notes |
|---|---|---|---|
| **Android TV** | `tv-foss-v*` | `com.openplidroid.foss` | public TV build |
| Phone / tablet | `mobile-v*` | `com.openplidroid.mobile` | (when published) |

Each APK is signed with a stable key, so the app updates itself in place — no
reinstall. `update*.json` on the `main` branch are the manifests the apps poll
(~every 12 h, and on demand from the app).

## Support

If OpenPLiDroid is useful to you, you can leave a tip — it's appreciated but
never expected:

☕ **[paypal.me/corallocla](https://paypal.me/corallocla)**
