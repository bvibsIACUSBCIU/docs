# Copilot Instructions for SwapX Documentation Codebase

## Overview
- This repository contains all documentation for SwapX, a decentralized token exchange system based on Uniswap v2/v3 protocols.
- The docs are organized for both end-users and developers, covering concepts, guides, technical specs, and integration details.
- The documentation site is built with Docusaurus 3.x and uses React 18 for custom components.

## Key Structure
- Main docs: `docs/` (contains contract, sdk, study, guides, and reference material)
- Docusaurus config: `docusaurus.config.js`, `sidebars.js`, `package.json`
- Static assets: `static/img/`
- Localization: `i18n/` (English and Chinese)
- Custom React components: `src/components/`

## Developer Workflows
- **Install dependencies:** Use `pnpm install` (preferred) or `npm install` in the `docs/` directory.
- **Start local dev server:** `pnpm start` or `npm run start` (runs Docusaurus locally)
- **Build static site:** `pnpm build` or `npm run build`
- **Deploy:** `pnpm deploy` or `npm run deploy`
- **Clear cache:** `pnpm clear` or `npm run clear`
- **Write translations:** `pnpm write-translations`

## Project Conventions
- All documentation content is in Markdown (`.md`) files, organized by topic and version (e.g., `docs/sdk/v2/`, `docs/contract/swapx-v3/`).
- Use `_category_.json` to define sidebar structure for each section.
- For new guides or references, add to the appropriate subfolder and update sidebars if needed.
- Custom React components for the site live in `src/components/`.
- Images and static files go in `static/img/`.
- Localization files are under `i18n/` and follow Docusaurus conventions.

## Integration Points
- Docusaurus plugins and presets are configured in `docusaurus.config.js`.
- React components can be imported into Markdown via MDX.
- No backend or smart contract code is present in this repo—focus is on documentation and site generation.

## Examples
- To add a new guide for SDK v3: place the Markdown file in `docs/sdk/v3/guides/` and update the relevant `_category_.json`.
- To add a new language: add translation files under `i18n/` and update config as needed.

## References
- See `README.md` and `README.zh-CN.md` for project introduction and contribution guidelines.
- For Docusaurus usage, see [https://docusaurus.io/docs](https://docusaurus.io/docs).

---
For questions, contact [support@swapx.exchange](mailto:support@swapx.exchange) or visit [https://x.com/SwapX009](https://x.com/SwapX009).
