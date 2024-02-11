# `@kevinwolfcr/tsconfig-bun`

[Kevin Wolf's](https://kevinwolf.cr) opinionated [TypeScript](https://typescriptlang.org) config optimized for [Bun](https://bun.sh) projects.

## Features

- Optimized for projects using the Bun runtime.
- Extends [`@kevinwolfcr/tsconfig`](https://npmjs.com/package/@kevinwolfcr/tsconfig) for consistent coding standards and best practices.
- Includes support for Bun-specific types with [`bun-types`](https://npmjs.com/package/bun-types).

## When to Use

This configuration is specifically designed for TypeScript projects that are developed with the Bun runtime. It's ideal for server-side applications, scripts, or utilities that leverage Bun's fast execution and built-in package management. Use this configuration to ensure your TypeScript types align with Bun's unique environment and capabilities.

## Installation

```
bun add -D @kevinwolfcr/tsconfig-bun
```

## Usage

To use this configuration, extend it in your `tsconfig.json`:

```json
{
  "extends": "@kevinwolfcr/tsconfig-bun"
}
```

## Contributing

Contributions are welcome! If you wish to contribute to this project, please read the [Contributing Guidelines](https://github.com/kevinwolfcr/.github/blob/HEAD/contributing.md) first.

## License

This project is licensed under the MIT license - see the [license](../../license) file for details.
