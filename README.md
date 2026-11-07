# PairOnce interface translations

PairOnce — browser-to-browser file transfer between your devices. No app, no account, files never stored on a server.

[PairOnce](https://paironce.com) is a free web app for sending files, photos, text and links between your own devices
(iPhone, Android, Windows, Mac, Linux) with no app to install and no account. The two browsers connect directly and
end-to-end encrypted (AES-256-GCM, keys from P-256 ECDH, a 13-digit safety code to compare); when a network blocks a direct
connection, an encrypted relay passes on data it cannot read. Devices on the same Wi-Fi find each other on their own, and a
large file resumes after a dropped connection. PairOnce keeps no copy. Overview: [github.com/paironce](https://github.com/paironce)
· guides: [paironce.com/guides](https://paironce.com/guides/).

The words of the [PairOnce](https://paironce.com) interface in its 13 languages. English is the source: each file maps the
English sentence (the key) to its translation (the value).

| File | Language |
| --- | --- |
| [locales/de.json](locales/de.json) | de |
| [locales/es-419.json](locales/es-419.json) | es-419 |
| [locales/es-ES.json](locales/es-ES.json) | es-ES |
| [locales/fr.json](locales/fr.json) | fr |
| [locales/hi.json](locales/hi.json) | hi |
| [locales/id.json](locales/id.json) | id |
| [locales/it.json](locales/it.json) | it |
| [locales/ja.json](locales/ja.json) | ja |
| [locales/ko.json](locales/ko.json) | ko |
| [locales/pt-BR.json](locales/pt-BR.json) | pt-BR |
| [locales/zh-Hans.json](locales/zh-Hans.json) | zh-Hans |
| [locales/zh-Hant.json](locales/zh-Hant.json) | zh-Hant |

## Improving a translation

Open a pull request that changes the value, never the key. Keep the `{placeholders}` exactly as they are, and keep it
short: the text has to fit on a phone. Say in the pull request what was wrong, so a native speaker can review it.
Translations merged here ship with the next paironce.com release.

Version 2.33.1 is the text of paironce.com 2.33.1.

## License

Apache-2.0 (see `LICENSE`). The PairOnce™ name and logo are not covered: see `TRADEMARK.md`.
