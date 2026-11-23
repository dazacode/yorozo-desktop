# Yorozo for macOS

Downloads of the Yorozo desktop app, and the feed it updates itself from.

**Install:** download the `.dmg` from [Releases](https://github.com/dazacode/yorozo-desktop/releases/latest), open it and drag Yorozo to Applications. The app is not notarised yet, so the first launch needs right-click → **Open**.

The app is the website ([yorozo.vercel.app](https://yorozo.vercel.app)) plus what a browser can't do: offline downloads, built-in playback for files a browser can't open, the companion and torrent support. Website changes reach the app on their own; this repository's releases carry native updates, which the app installs itself.

Each release carries `SHA256SUMS`; `latest.json` and the `.sig` file are for the app's updater.

Licensing: Yorozo is AGPL-3.0-or-later. The app bundles libmpv and FFmpeg libraries under the LGPL-2.1; their notices are in `Yorozo.app/Contents/Frameworks/`.
