# ts-toolkit-cli

Learning TypeScript by building tiny CLIs

## How to use

```bash
npx . convert data.csv -d ';'
# or after npm link: cliparse convert data.csv
```

## Highlights

- npm link friendly
- commander-based subcommands
- Strict tsconfig, no any
- Ships as an ESM binary

## Installation

```bash
npm install
npm run build
```

## Project structure

```text
├── .github/
│   └── workflows/
│       └── ci.yml
├── docs/
│   ├── configuration.md
│   ├── development.md
│   ├── faq.md
│   ├── roadmap.md
│   └── usage.md
├── src/
│   └── index.ts
├── .gitignore
├── CONTRIBUTING.md
├── SECURITY.md
├── package.json
└── tsconfig.json
```

## Development

```bash
npm install
```
