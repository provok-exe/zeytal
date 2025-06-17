# Zeytal TailwindCSS Config Generation

Here’s an example of how to generate TailwindCSS config files from your Figma styles and Figma variables using [Zeytal](https://zeytal.com).

## How to use

1. Create a `.env` file based on `.env.sample` with your Zeytal project secret key inside.
1. Install the `package.json` dependencies using `npm`, `yarn`, or `pnpm`.
1. Execute [`zeytal`](https://npmjs.com/package/zeytal) commands like so:

```bash
npm x zeytal variables && npm x zeytal styles
```

```bash
yarn zeytal variables && yarn zeytal styles
```

```bash
pnpm zeytal variables && pnpm zeytal styles
```

The CLI will extract and transform data based on the Figma source files you provide in your project’s dashboard.

Click here for more info on [how to use the CLI](https://zeytal.com/docs/zeytal-cli?utm_source=github&utm_medium=readme&utm_campaign=zeytal-example).

## What this example does

“Zeytal TailwindCSS Config Generation” is an example of how to generate TailwindCSS config files from your Figma styles and Figma variables with Zeytal CLI.

Your `zeytal.json` config file tweaks the `styles`, `variables`, and `tailwind` default config so you:

1. pass custom styles and variables directories to generate your design tokens into
1. generate styles and variables in `styles-tw.css` and `variables-tw.css` files
1. generate color styles and variables in `rgba`
1. generate font styles in `rem`
1. ignore Figma variable collections prefixed with `_`
1. auto-configures `styles-tw.css` and `variables-tw.css` to work with TailwindCSS v4 out of the box

Click here for more info on [how to tweak your CLI config ](https://zeytal.com/docs/tailwind-config?utm_source=github&utm_medium=readme&utm_campaign=zeytal-example).

## Figma Sample File

To try this setup easily, you can use our [free Design System sample file](https://www.figma.com/community/file/1482453731920989064).
