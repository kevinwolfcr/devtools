# `@kevinwolfcr/tsconfig-browser`

[Kevin Wolf's](https://kevinwolf.cr) opinionated [TypeScript](https://typescriptlang.org) config optimized for browser-based projects.

## Features

- Tailored for projects intended to run in a web browser environment.
- Extends [`@kevinwolfcr/tsconfig`](https://npmjs.com/package/@kevinwolfcr/tsconfig) for consistent coding standards and best practices.

## When to Use

This configuration is ideal for vanilla JavaScript (or TypeScript) projects meant for the browser, such as dynamic websites, web apps not using a modern framework, or browser extensions. Use this configuration to ensure your project is optimized for browser-specific typings and standards.

## Installation

With `bun`:

```
bun add -D @kevinwolfcr/tsconfig-browser
```

With `npm`:

```
npm install --save-dev @kevinwolfcr/tsconfig-browser
```

With `pnpm`:

```
pnpm add -D @kevinwolfcr/tsconfig-browser
```

With `yarn`:

```
yarn add --dev @kevinwolfcr/tsconfig-browser
```

## Usage

To use this configuration, extend it in your `tsconfig.json`:

```json
{
  "extends": "@kevinwolfcr/tsconfig-browser"
}
```

## Contributing

Contributions are welcome! If you wish to contribute to this project, please read the [Contributing Guidelines](https://github.com/kevinwolfcr/.github/blob/HEAD/contributing.md) first.

## License

This project is licensed under the MIT license - see the [license](../../license) file for details.
