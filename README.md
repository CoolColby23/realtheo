# realtheo [![License](https://img.shields.io/badge/license-MIT-111111?style=flat-square)](./LICENSE) [![GitHub](https://img.shields.io/badge/github-maria--rcks%2Frealtheo-111111?style=flat-square&logo=github)](https://github.com/maria-rcks/realtheo)

_A tiny unpacked browser extension._

## Install

Clone the repo:

```bash
git clone https://github.com/maria-rcks/realtheo.git
cd realtheo
```

Load it unpacked:

- Open `chrome://extensions`, `edge://extensions`, or `brave://extensions`.
- Enable developer mode.
- Click **Load unpacked**.
- Select this folder.

## What it does

- Uses Manifest V3.
- Redirects known static avatar URLs with declarative net request rules.
- Patches dynamic X and YouTube pages from a small content script.
- Keeps the replacement images local in `assets/`.

## Development

After editing files, reload `realtheo` from the browser extensions page.

If you add new local assets, include them in `manifest.json` under `web_accessible_resources`.

## Links

- Repository: https://github.com/maria-rcks/realtheo
- Issues: https://github.com/maria-rcks/realtheo/issues
