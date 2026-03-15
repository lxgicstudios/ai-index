# @lxgicstudios/ai-index

[![npm version](https://img.shields.io/npm/v/%40lxgicstudios%2Fai-index.svg)](https://www.npmjs.com/package/@lxgicstudios/ai-index)
[![npm downloads](https://img.shields.io/npm/dm/%40lxgicstudios%2Fai-index.svg)](https://www.npmjs.com/package/@lxgicstudios/ai-index)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub stars](https://img.shields.io/github/stars/lxgic-studios/ai-index)](https://github.com/lxgic-studios/ai-index/stargazers)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.0+-blue)](https://www.typescriptlang.org/)



Analyze your query patterns and get smart database index suggestions. Tells you exactly what to create and why.

## Install

```bash
npm install -g @lxgicstudios/ai-index
```

## Usage

```bash
npx @lxgicstudios/ai-index ./src/queries/
# Analyzes all query files and suggests indexes

npx @lxgicstudios/ai-index ./src/queries/users.ts -o indexes.sql
# Single file, saves SQL to file
```

## Setup

```bash
export OPENAI_API_KEY=sk-...
```

## Options

- `-o, --output <path>` - Save suggestions to file

## License

MIT


---

Built by [LXGIC Studios](https://github.com/LXGIC-Studios)

🔗 [GitHub](https://github.com/LXGIC-Studios) · [Twitter](https://x.com/lxgicstudios)

💡 Want more free tools like this? We have 100+ on our GitHub: [github.com/lxgicstudios](https://github.com/lxgicstudios)
