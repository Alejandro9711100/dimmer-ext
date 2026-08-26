# dimmer-ext

MV3 extension playground: page reading-time estimator

## Highlights

- Per-tab time persisted to chrome.storage
- Popup shows today's total focus time
- No remote calls, everything stays local
- Manifest V3, service worker based

## Installation

```bash
# no build step needed
# chrome://extensions -> load unpacked -> select this folder
```

## How to use

```bash
# click the toolbar icon to see today's reading time
```

## Project structure

```text
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   └── bug_report.md
│   ├── dependabot.yml
│   └── pull_request_template.md
├── docs/
│   ├── development.md
│   ├── faq.md
│   ├── roadmap.md
│   └── usage.md
├── scripts/
│   └── dev.sh
├── src/
│   └── config.js
├── .editorconfig
├── .gitignore
├── CHANGELOG.md
├── CONTRIBUTING.md
├── LICENSE
├── SECURITY.md
├── background.js
├── manifest.json
├── popup.html
└── popup.js
```

## Development

```bash
npm install
npm test
```

## Acknowledgments

- README structure inspired by popular OSS templates
- Thanks to everyone opening issues with ideas
