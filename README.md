# Folio updates

Update files for the **Folio PDF Editor** Mac app. The app checks this repository about once a day
and downloads a newer version of its editor when one is published.

- `latest.json` — the current version and the list of files, each with its SHA-256 fingerprint
- `latest.json.sig` — Ed25519 signature of `latest.json`; the app ignores any update that is not signed by Folio's developer
- `blobs/` — the files themselves, named by their fingerprint

Nothing here is meant to be used directly. This repository contains no user data.

Third-party components included in the app: [pdf.js](https://github.com/mozilla/pdf.js) (Apache-2.0),
[pdf-lib](https://github.com/Hopding/pdf-lib) (MIT), and fonts from [Google Fonts](https://fonts.google.com)
(SIL Open Font License / Apache-2.0).
