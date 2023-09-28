# prettier-config-cvs

> A reusable configuration for Prettier

This package supplies a Prettier configuration to the entire monorepo.
By exporting this config file, you can extend it and customize it within your apps.

For more information on Prettier, see the [docs](https://prettier.io/docs/en/index.html).

## Troubleshooting

Prettier does not support `.ts` files, so `index.js` must remain a `.js` file.
Depending on where Prettier is running, you may need to vary the use of ESM and CommonJS export syntax and corresponding file extensions.
