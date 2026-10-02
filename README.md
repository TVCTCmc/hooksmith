# hooksmith

Small typed hooks: debounce, localStorage, media query, toggle

Started as a weekend hack, grew on me.

## Examples

```bash
import { useDebounce, useLocalStorage } from './src';

const debounced = useDebounce(value, 300);
```

## Getting started

```bash
npm install
npm test
```

## Highlights

- useLocalStorage with JSON serialization
- useDebounce with leading/trailing options
- useMediaQuery SSR-safe
- Tiny: no dependencies besides React

## Project structure

```text
├── .github/
│   ├── workflows/
│   │   └── ci.yml
│   ├── dependabot.yml
│   └── pull_request_template.md
├── docs/
│   ├── development.md
│   └── faq.md
├── examples/
│   └── quickstart.md
├── scripts/
│   └── dev.sh
├── src/
│   ├── index.js
│   ├── useDebounce.js
│   └── useLocalStorage.js
├── .gitignore
├── CHANGELOG.md
├── CONTRIBUTING.md
├── LICENSE
├── SECURITY.md
└── package.json
```

## Development

```bash
npm install
```

## License

MIT - see [LICENSE](LICENSE).
