# Zeytal SVGs Optimization

Here’s an example of how to extract and optimize your Figma SVGs efficiently using [Zeytal](https://zeytal.com).

## How to use

1. Create a `.env` file based on `.env.sample` with your Zeytal project secret key inside.
1. Install the `package.json` dependencies using `npm`, `yarn`, or `pnpm`.
1. Execute [`zeytal`](https://npmjs.com/package/zeytal) commands like so:

```bash
npm x zeytal assets
```

```bash
yarn zeytal assets
```

```bash
pnpm zeytal assets
```

The CLI will extract and transform data based on the Figma source files you provide in your project’s dashboard.

Click here for more info on [how to use the CLI](https://zeytal.com/docs/zeytal-cli?utm_source=github&utm_medium=readme&utm_campaign=zeytal-example).

## What this example does

“Zeytal SVGs Optimization” is an example of how to extract SVGs from Figma and optimize them with Zeytal CLI.

Your `zeytal.json` config file tweaks the assets default config so you:

1. only extract SVGs from your `published` Figma files
1. pass a custom assets directory to generate SVGs into
1. optimize your SVGs using a custom SVGO config

Click here for more info on [how to tweak your CLI config ](https://zeytal.com/docs/cli-config-files?utm_source=github&utm_medium=readme&utm_campaign=zeytal-example).
