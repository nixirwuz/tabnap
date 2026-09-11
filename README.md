# tabnap

MV3 extension playground: page reading-time estimator

Built for my own use; public in case it helps someone.

## Install

```bash
# no build step needed
# chrome://extensions -> load unpacked -> select this folder
```

## Highlights

- No remote calls, everything stays local
- Per-tab time persisted to chrome.storage
- Manifest V3, service worker based
- Popup shows today's total focus time

## Examples

```bash
# click the toolbar icon to see today's reading time
```

## Project structure

```text
├── .github/
│   └── dependabot.yml
├── docs/
│   ├── configuration.md
│   ├── development.md
│   ├── faq.md
│   └── usage.md
├── .editorconfig
├── .gitignore
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── SECURITY.md
├── background.js
├── manifest.json
├── popup.html
└── popup.js
```

## Development

```bash
npm install
```
