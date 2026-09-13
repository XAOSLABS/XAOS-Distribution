# XAOS Distribution

Public signed Android APK releases and the stable update manifest for XAOS.

`stable.json` is intentionally small and contains only release metadata, an HTTPS APK URL, exact byte size, and SHA-256. The Android client additionally verifies the downloaded APK package name, versionCode, and signing certificate against the installed XAOS app before opening Android's package installer.

Application source remains in the private `XAOSLABS/XAOS` repository. GPL/LGPL notices and PRoot source provenance are shipped inside each APK and documented by the XAOS project.
