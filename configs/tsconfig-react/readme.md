# `@kevinwolfcr/tsconfig-react`

[Kevin Wolf's](https://kevinwolf.cr) opinionated [TypeScript](https://typescriptlang.org) config optimized for [React](https://react.dev) projects.

## Features

- Specifically tailored for projects enhancing development experience with React's JSX syntax and features.
- Extends [`@kevinwolfcr/tsconfig-browser`](https://npmjs.com/package/@kevinwolfcr/tsconfig-browser) to inherit browser-specific settings and ensure consistent coding standards and best practices.

## When to Use

This configuration is designed for TypeScript projects using React. It's perfect for single-page applications (SPAs), static sites generated with React, or any web project that benefits from React's component-based architecture. Use this configuration to align your TypeScript setup with React's ecosystem and typing requirements.

## Installation

With `bun`:

```
bun add -D @kevinwolfcr/tsconfig-react
```

With `npm`:

```
npm install --save-dev @kevinwolfcr/tsconfig-react
```

With `pnpm`:

```
pnpm add -D @kevinwolfcr/tsconfig-react
```

With `yarn`:

```
yarn add --dev @kevinwolfcr/tsconfig-react
```

## Usage

To use this configuration, extend it in your `tsconfig.json`:

```json
{
  "extends": "@kevinwolfcr/tsconfig-react"
}
```

## Contributing

Contributions are welcome! If you wish to contribute to this project, please read the [Contributing Guidelines](https://github.com/kevinwolfcr/.github/blob/HEAD/contributing.md) first.

## License

This project is licensed under the MIT license - see the [license](../../license) file for details.
