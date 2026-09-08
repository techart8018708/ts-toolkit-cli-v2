# ts-toolkit-cli-v2

Small TypeScript CLI: CSV to JSON converter

Started as a weekend hack, grew on me.

## What it does

- npm link friendly
- Ships as an ESM binary
- commander-based subcommands
- Strict tsconfig, no any

## Usage

```bash
npx . convert data.csv -d ';'
# or after npm link: cliparse convert data.csv
```

## Installation

```bash
npm install
npm run build
```

## Project structure

```text
├── .github/
│   ├── workflows/
│   │   └── ci.yml
│   └── dependabot.yml
├── docs/
│   ├── configuration.md
│   ├── faq.md
│   ├── roadmap.md
│   └── usage.md
├── src/
│   └── index.ts
├── .gitignore
├── CHANGELOG.md
├── LICENSE
├── SECURITY.md
├── package.json
└── tsconfig.json
```

## Development

```bash
npm install
```

## 说明

个人练习项目, 谨慎用于生产环境。
