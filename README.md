# Private Preflight



Private Preflight is a browser-only inspection tool for CSV files and image metadata. Selected files are processed in the browser; the app is not a compliance, safety, or security guarantee.



## Run locally



```bash

pnpm install

pnpm dev

```



## Quality checks



```bash

pnpm check

pnpm exec vitest run

pnpm build

```



## GitHub Pages



The `main` branch runs `.github/workflows/deploy-pages.yml`. The workflow builds the static client at the GitHub Pages root and publishes `dist/public` to GitHub Pages. `404.html` mirrors `index.html` so direct links to browser routes remain available.

This public root-site repository mirrors the browser-only application. The deployed Pages address is:

```text
https://mohummadsultan0-sudo.github.io/
```

The Pages build is self-contained: the brand mark, local-only seal, ledger artwork, and favicon are all CSS/SVG-native application assets, so the published site does not depend on an external asset host.

## License



MIT
