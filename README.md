# PolSim builds

Test builds of PolSim for Android (the app was called iCall until build 207). PolSim lets an iPhone use the calls and text messages of an Android phone.

This repository holds builds only. It has no source code.

## Android

1. Open the latest release (the "Releases" page of this repository).
2. Download the APK. Its name ends in `-buildNNN`, where NNN is the build number. From build 208 the same file is there under two names, `PolSim-POCO-…` and `iCall-POCO-…`; take either.
3. Open the APK on the Android phone. Android will ask you to allow installing apps from this source (your browser or file manager). Allow it for that one app, then install.
4. To check the download, compare its SHA-256 with the one in the release notes or in `SHA256SUMS.txt`.

The release also holds a test package with step-by-step sheets, and a Windows helper for collecting logs.

These builds are made for a POCO X3 Pro test phone. Other phones may not work.

## iPhone

The iPhone app is not here. It comes only by TestFlight invitation.

## Licence

PolSim is licensed under the PolyForm Noncommercial License 1.0.0 (see `LICENSE` and `NOTICE`; the notice keeps the project's original name as the licence requires). That licence allows personal, learning and research use, and other non-commercial uses it lists. It does not allow commercial use. PolSim is not open source.
