# Agent Memory Skill Compounding

![npm](https://img.shields.io/npm/v/@phoenix-assistant/agent-memory-skill-compounding)
![CI](https://github.com/phoenix-assistant/agent-memory-skill-compounding/actions/workflows/ci.yml/badge.svg)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

> Persistent agent memory with skill accumulation and knowledge compounding

## Installation

```bash
npm install @phoenix-assistant/agent-memory-skill-compounding
```

## Quick Start

```typescript
import { create } from '@phoenix-assistant/agent-memory-skill-compounding';

const instance = create({ verbose: true });
const result = await instance.process(input);
console.log(result.success);
```

## API

### `create(config?)`

Create a new instance.

### `instance.process(input)`

Process input and return results.

## Development

```bash
npm install
npm test
npm run build
```

## License

MIT © [Phoenix Assistant](https://github.com/phoenix-assistant)
