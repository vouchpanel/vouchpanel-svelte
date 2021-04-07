# @vouchpanel/svelte

[![Package Version][package-image]][package-url]
[![Open Issues][issues-image]][issues-url]
[![Build Status][build-image]][build-url]
[![Coverage Status][coverage-image]][coverage-url]
[![Dependencies Status][dependencies-image]][dependencies-url]
[![Dev Dependencies Status][dev-dependencies-image]][dev-dependencies-url]
[![Commitizen Friendly][commitizen-image]][commitizen-url]

Quickly embed a vouchpanel into your svelte project.

### How To Use

Install with yarn (or `npm install`):

```bash
yarn add @vouchpanel/svelte
```

Include it as a module.

```tsx



```

Add the following to the corresponding svelte template. Replace `id` with your wall id from [app.vouchpanel.com](https://app.vouchpanel.com).
```tsx
// *.component.html
<Wall darkMode="off" id="4"></Wall>
```

[project-url]: https://github.com/vouchpanel/vouchpanel-svelte
[package-image]: https://img.shields.io/npm/v/@vouchpanel/svelte
[package-url]: https://www.npmjs.com/package/@vouchpanel/svelte
[issues-image]: https://img.shields.io/github/issues/vouchpanel/vouchpanel-svelte.svg?style=popout
[issues-url]: https://github.com/vouchpanel/vouchpanel-svelte/issues
[build-image]: https://travis-ci.org/vouchpanel/vouchpanel-svelte.svg?branch=master
[build-url]: https://travis-ci.org/vouchpanel/vouchpanel-svelte
[coverage-image]: https://coveralls.io/repos/github/vouchpanel/vouchpanel-svelte/badge.svg?branch=master
[coverage-url]: https://coveralls.io/github/vouchpanel/vouchpanel-svelte?branch=master
[dependencies-image]: https://img.shields.io/david/vouchpanel/vouchpanel-svelte
[dependencies-url]: https://www.npmjs.com/package/@vouchpanel/svelte
[dev-dependencies-image]: https://img.shields.io/david/dev/vouchpanel/vouchpanel-svelte
[dev-dependencies-url]: https://www.npmjs.com/package/@vouchpanel/svelte
[commitizen-image]: https://img.shields.io/badge/commitizen-friendly-brightgreen.svg
[commitizen-url]: http://commitizen.github.io/cz-cli

## Consuming components

Your package.json has a `"svelte"` field pointing to `src/index.ts`, which allows Svelte apps to import the source code directly, if they are using a bundler plugin like [rollup-plugin-svelte](https://github.com/sveltejs/rollup-plugin-svelte) or [svelte-loader](https://github.com/sveltejs/svelte-loader) (where [`resolve.mainFields`](https://webpack.js.org/configuration/resolve/#resolve-mainfields) in your webpack config includes `"svelte"`). **This is recommended.**

For everyone else, `npm run build` will bundle your component's source code into a plain JavaScript module (`dist/index.mjs`) and a UMD script (`dist/index.js`). This will happen automatically when you publish your component to npm, courtesy of the `prepublishOnly` hook in package.json.
