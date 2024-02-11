# `@kevinwolfcr/biome-config`

[Kevin Wolf's](https://kevinwolf.cr) opinionated [Biome](https://biomejs.dev) config.

## Features

- Applies best practices and consistent coding standards for projects using Biome.
- Enhances code quality and developer experience by configuring Biome's linter and formatter.
- Customizes JavaScript and JSON parsing and formatting rules to align with modern development standards.
- Provides overrides for specific files to adjust linting rules according to project needs.

## When to Use

This configuration is specifically designed for TypeScript and JavaScript projects leveraging Biome as their code quality tool. It's ideal for projects looking for a sensible default setup that enforces code quality while being flexible enough to accommodate specific project requirements.

For more specialized needs, consider adjusting the `biome.json` configuration or defining overrides to suit your project's unique environment.

## Installation

With `bun`:

```
bun add -D @kevinwolfcr/biome-config
```

With `npm`:

```
npm install --save-dev @kevinwolfcr/biome-config
```

With `pnpm`:

```
pnpm add -D @kevinwolfcr/biome-config
```

With `yarn`:

```
yarn add --dev @kevinwolfcr/biome-config
```

## Usage

To use this configuration in your project, ensure your `biome.json` file is configured to extend `@kevinwolfcr/biome-config`:

```json
{
  "$schema": "https://biomejs.dev/schemas/1.5.3/schema.json",
  "extends": ["./node_modules/@kevinwolfcr/biome-config/biome.json"]
}
```

Please refer to the [Biome Configuration documentation](https://biomejs.dev/reference/configuration/) for more details on extending configurations.

## Contributing

Contributions are welcome! If you wish to contribute to this project, please read the [Contributing Guidelines](https://github.com/kevinwolfcr/.github/blob/HEAD/contributing.md) first.

## License

This project is licensed under the MIT license - see the [license](../../license) file for details.
