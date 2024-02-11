# `@kevinwolfcr/tsconfig-next`

[Kevin Wolf's](https://kevinwolf.cr) opinionated [TypeScript](https://typescriptlang.org) config optimized for [Next.js](https://nextjs.org) projects.

## Features

- Tailored for Next.js projects, enhancing development experience with Next.js-specific TypeScript settings and plugins.
- Extends [`@kevinwolfcr/tsconfig-react`](https://npmjs.com/package/@kevinwolfcr/tsconfig-react) to inherit React and browser-specific settings, ensuring a smooth development experience in Next.js projects.

## When to Use

This configuration is designed for TypeScript projects using Next.js. It is ideal for building server-side rendered (SSR) applications, static sites (SSG), or full-stack applications that leverage Next.js's features. Use this configuration to align your TypeScript setup with Next.js's ecosystem, including custom Next.js TypeScript plugins and settings.

## Installation

With `bun`:

```
bun add -D @kevinwolfcr/tsconfig-next
```

With `npm`:

```
npm install --save-dev @kevinwolfcr/tsconfig-next
```

With `pnpm`:

```
pnpm add -D @kevinwolfcr/tsconfig-next
```

With `yarn`:

```
yarn add --dev @kevinwolfcr/tsconfig-next
```

## Usage

To use this configuration, extend it in your `tsconfig.json`:

```json
{
  "extends": "@kevinwolfcr/tsconfig-next",
  "compilerOptions": {
    "paths": {
      "@/*": ["./src/*"]
    },
  },
  "include": ["next-env.d.ts", "**/*.ts", "**/*.tsx", ".next/types/**/*.ts"],
  "exclude": ["node_modules"]
}
```

## Contributing

Contributions are welcome! If you wish to contribute to this project, please read the [Contributing Guidelines](https://github.com/kevinwolfcr/.github/blob/HEAD/contributing.md) first.

## License

This project is licensed under the MIT license - see the [license](../../license) file for details.
