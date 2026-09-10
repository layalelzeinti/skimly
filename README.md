# skimly

MV3 extension: one click, tl;dr of any article

## Installation

```bash
# chrome://extensions -> load unpacked -> select this folder
# set your API base + key on the options page
```

## How to use

```bash
# open any article, click the icon, get a 5-bullet summary
```

## What it does

- Popup shows a 5-bullet summary
- Manifest V3 service worker, no build step
- Reads the page, extracts main text, sends to your endpoint
- Options page for API base and key

## Project structure

```text
├── .github/
│   └── dependabot.yml
├── docs/
│   ├── configuration.md
│   ├── roadmap.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── scripts/
│   └── dev.sh
├── .gitattributes
├── .gitignore
├── CHANGELOG.md
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── LICENSE
├── SECURITY.md
├── background.js
├── manifest.json
├── options.html
├── popup.html
└── popup.js
```

## Development

```bash
npm install
```

## Changelog

- `0.1.1` - fix edge case in argument parsing
- `0.1.0` - first working version

## License

MIT. Do whatever you want.
