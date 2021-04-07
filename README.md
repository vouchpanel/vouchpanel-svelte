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

Include it as a module.  Replace `id` with your wall id from [app.vouchpanel.com](https://app.vouchpanel.com).

```tsx
// Component.svelte
<script>
	import Wall from '@vouchpanel/svelte/dist/index'
</script>

<Wall id="4" darkMode="off"></Wall>
```

If you are using `typescript`, you can import the typed component instead: `import Wall from @vouchpanel/svelte`.

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