# `@kevinwolfcr/tsconfig`

[Kevin Wolf's](https://kevinwolf.cr) opinionated [TypeScript](https://typescriptlang.org) config.

## Features

- Applies best practices and consistent coding standards for TypeScript.
- Includes [`@total-typescript/ts-reset`](https://npmjs.com/package/@total-typescript/ts-reset) to enhance TypeScript's built-in typings.

## When to Use

This configuration is specifically designed for TypeScript projects that need a solid foundation with sensible defaults. Use this configuration to ensure your TypeScript setup aligns with best practices and consistent coding standards.

It's ideal for server-side applications, scripts, or utilities, for projects with more specific needs, consider using one of the specialized configurations:

- For Bun projects: [`@kevinwolfcr/tsconfig-bun`](https://npmjs.com/package/@kevinwolfcr/tsconfig-bun)
- For browser-based projects: [`@kevinwolfcr/tsconfig-browser`](https://npmjs.com/package/@kevinwolfcr/tsconfig-browser)
- For React projects: [`@kevinwolfcr/tsconfig-react`](https://npmjs.com/package/@kevinwolfcr/tsconfig-react)
- For Next.js projects: [`@kevinwolfcr/tsconfig-next`](https://npmjs.com/package/@kevinwolfcr/tsconfig-next)

_Note: Each specialized configuration is tailored to its respective environment and use case, providing optimizations and settings relevant to those specific scenarios._

## Installation

With `bun`:

```
bun add -D @kevinwolfcr/tsconfig
```

With `npm`:

```
npm install --save-dev @kevinwolfcr/tsconfig
```

With `pnpm`:

```
pnpm add -D @kevinwolfcr/tsconfig
```

With `yarn`:

```
yarn add --dev @kevinwolfcr/tsconfig
```

## Usage

To use this base configuration in your project, extend it in your `tsconfig.json`:

```json
{
  "extends": "@kevinwolfcr/tsconfig"
}
```

## Contributing

Contributions are welcome! If you wish to contribute to this project, please read the [Contributing Guidelines](https://github.com/kevinwolfcr/.github/blob/HEAD/contributing.md) first.

## License

This project is licensed under the MIT license - see the [license](../../license) file for details.
