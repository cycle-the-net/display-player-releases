# Display Player releases

Signed APKs of **Display Player**, Cycle the Net's full-screen web display app for Google TV and
Android TV boxes. Source code is private; this repository only holds the signed releases.

**Latest APK (stable link):**
https://github.com/cycle-the-net/display-player-releases/releases/latest/download/display-player.apk

**Downloader code: 4913123** (`aftv.news/4913123`). It points at the stable link above, so it
always gives the latest release.

- Install on a box with the **Downloader** app: enter the code **4913123**. If the code doesn't
  work, type the full link above instead. Or install from a laptop with `adb install -r`.
- Boxes check `latest.json` here once a day. A newer version downloads and waits; it installs when
  someone presses **Install update** on the box's admin screen.
- Every APK is signed with CTN's release key. Boxes refuse anything else.
