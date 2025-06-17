# Zeytal Styles and Variables Generation

Here’s an example of how to extract and transform your Figma styles and variables using [Zeytal](https://zeytal.com).

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

“Zeytal Styles and Variables Generation” is an example of how to extract styles and variables from Figma and transform them with Zeytal CLI.

Your `zeytal.json` config file tweaks the styles and variables default config so you:

1. only extract styles from your `saved` Figma files
1. pass custom styles and variables directories to generate your design tokens into
1. generate styles and variables in `.ts`, and `.scss` files
1. generate color styles and variables in `hsla`
1. generate font styles in `rem`
1. ignore Figma variable collections prefixed with `_`

Click here for more info on [how to tweak your CLI config ](https://zeytal.com/docs/cli-config-files?utm_source=github&utm_medium=readme&utm_campaign=zeytal-example).

## Figma Sample File

To try this setup easily, you can use our [free Design System sample file](https://www.figma.com/community/file/1482453731920989064).
