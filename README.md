# PipeIt

**A fast, no-nonsense video downloader for Android.**

Paste a link, and PipeIt saves the video straight to your gallery. Powered by [yt-dlp](https://github.com/yt-dlp/yt-dlp) with ffmpeg bundled in, so it works out of the box.

[**⬇️ Download the latest APK**](../../releases/latest)

---

## Features

- **Wide site support**: YouTube, Instagram, and the many other sites yt-dlp supports
- **Always current extractors**: yt-dlp updates itself on the nightly channel, so sites that break get fixed quickly, with no app update needed
- **Verified in-app updates**: new versions download in the background, resume if interrupted, and are checked against a SHA-256 checksum before install. A release without a valid checksum is never installed

## Install

1. Download the latest `.apk` from the [Releases page](../../releases/latest).
2. Open the file on your phone.
3. If prompted, allow **Install unknown apps** for your browser or file manager.
4. Launch PipeIt and paste a link.

> **Note:** PipeIt supports **arm64-v8a** devices only, which covers most modern Android phones. The APK is large because the Python, ffmpeg, and yt-dlp runtime are bundled inside.

## Updating

PipeIt checks this repo's releases for new versions. Go to **Settings → Updates** to check manually, retry a failed download, or restrict update downloads to Wi-Fi. When a download finishes, the update installs the next time you open the app.

Every release is tagged in `vMAJOR.MINOR` format (e.g. `v1.9`), matching the app's version name.

## Reporting issues

Found a bug? [Open an issue](../../issues/new) and include:

- Your Android version and device model
- PipeIt version (Settings → About)
- The link that failed (if it's not private) and the error message shown

## Responsible use

PipeIt is a tool for saving content you have the right to download, such as your own videos, public-domain and Creative Commons media, and content for personal offline viewing where permitted. You are responsible for complying with the terms of the sites you use and with copyright law in your country.

## Credits

- [yt-dlp](https://github.com/yt-dlp/yt-dlp): the extraction engine
- [youtubedl-android](https://github.com/yausername/youtubedl-android): Android wrapper bundling Python and ffmpeg

---

<sub>This repository hosts release binaries only. Package: `com.pipeit.app`</sub>