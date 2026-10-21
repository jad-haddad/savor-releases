# Savor for Android — releases

Install and update **Savor** for Android here. The app's source lives in a private
repository; this one only carries signed APK releases.

## Install

**[Download the latest APK](https://github.com/jad-haddad/savor-releases/releases/latest/download/savor.apk)**

Sideload it once. After that the app checks this repository's latest release on launch and offers
updates in-app — no account or token needed.

Updates keep the app's data: the package id (`net.jadarr.savor`) and signing key never change, and
every release increases `versionCode`.

## Releases

Each release is tagged `mobile-v<version>` and built by CI from a `mobile-v*` tag in the source
repository, with a changelog generated from the commits since the previous tag.
