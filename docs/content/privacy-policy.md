# Privacy Policy

**Last updated:** September 29, 2026

This privacy policy describes how PipeIt ("the app") handles information. PipeIt is developed and maintained by an independent developer, not a company.

## Summary

PipeIt does not collect, store, or transmit any personal data to the developer or any third party. No account is required to use the app, and no analytics or advertising SDKs are included.

## What PipeIt does on your device

- Videos you choose to download are saved locally to your device's shared storage (Movies/Pipeit) and are never uploaded anywhere by the app.
- A local record of your downloads (title, file location, download date) is kept on your device only, so the app can show you your download history. This record is not sent anywhere and is deleted if you clear the app's data or uninstall it.
- Your device's own backup system (such as Android's built-in backup) may include this locally-stored app data as part of its standard backups, the same as it does for other apps on your device. PipeIt does not control or initiate this — it's a general Android feature, not something PipeIt actively sends anywhere.

## Network connections the app makes

PipeIt connects to the internet for two purposes only:

1. **Fetching videos you request.** When you paste or share a link, the app contacts the site the video is hosted on to retrieve it, the same way opening that link in a browser would. This involves a standard HTTP request to that site — which, like any web request, includes your device's IP address and a User-Agent identifying the app. PipeIt does not add any additional tracking identifiers, analytics, or advertising identifiers to these requests.
2. **Checking for app updates.** PipeIt periodically checks a public GitHub repository ([pipeit-releases](https://github.com/qasimsyed16/pipeit-releases)) for newer versions. If an update is found, it is downloaded in the background and cryptographically verified before you're prompted to install it. This check is a standard network request and does not send any information about you beyond what any such request includes.

No data collected by PipeIt is sold, rented, or shared with advertisers, because none is collected.

## Permissions

PipeIt requests the following device permissions, each used only for its stated purpose:

- **Internet access** — to download videos and check for updates.
- **Foreground service / data sync** — to keep an active download or update running reliably, shown to you as a visible, ongoing notification while it's in progress.
- **Post notifications** — to show you download and update progress and completion.
- **Install unknown apps** — requested only when installing an app update you've approved; used solely for that purpose.
- **Storage (legacy)** — on older Android versions (9 and below), used to save downloaded videos to shared storage. Not requested on newer Android versions, which use a more limited, scoped storage method instead.

## Third-party content

PipeIt is a tool for downloading videos from links you provide. It does not host, index, or promote any content. Videos are retrieved directly from the source site at your request. You are responsible for ensuring you have the right to download and use any content you access through the app, and for complying with the terms of service of the sites you download from.

## Advertising and analytics

PipeIt does not currently include any advertising or analytics software. If this changes in a future version, this policy will be updated first, and the change will be noted in the app's release notes.

## Children's privacy

PipeIt is not directed at children and does not knowingly collect information from anyone, including children, since it does not collect information at all.

## Changes to this policy

If this policy changes — for example, if ads or analytics are added in the future — this page will be updated, and the "Last updated" date above will reflect the change.

## Contact

Questions about this policy can be raised via [GitHub Issues](https://github.com/qasimsyed16/pipeit-releases/issues) or by contacting the developer directly.
