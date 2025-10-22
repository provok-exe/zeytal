# zeytal

## 1.4.1

### Patch Changes

- fix(tokens): Cleaner tailwind config generation.
  - Global mode rewrites to rewrite matching parts of the generated scoped CSS mode declarations.
  - Support for tailwind separate `@theme inline` and `@theme` directive.
  - Optional unitless clones for number variables and styles.
  - Global root to theme option to move matching Figma styles and Figma variables from the generated `:root` scope to TailwindCSS `@theme` directive.
  - All generated variables and styles prefixed with `var-` and `style-` by default.
  - Shadow maker with spread support.

## 1.4.0

### Minor Changes

- 48972c6: feat(config): No more paid plans and better workload structure.
  - No limits on any features
  - Doing most of the processing on the CLI package side instead of on the API’s server. This way, assets, styles, and variables data fetching can last for more than 60 secs.
  - Using commander instead of citty
  - node-fetch instead of axios and ofetch
  - Updated dependencies
    - svgo@4.0.0

## 1.3.4

### Patch Changes

- chore(setup): Log new version if available

## 1.3.4-canary.0

### Patch Changes

- chore(setup): Log new version if available

## 1.3.3

### Patch Changes

- fix(config): Allowing Figma files pages batch size setting tweaks

## 1.3.2

### Patch Changes

- fix(config): no default styles and vars format targets

## 1.3.1

### Patch Changes

- fix(config): `zeytal.json` tailwind props docs

## 1.3.0

### Minor Changes

- a834fd1: feat(tailwind): Generating TailwindCSS v4 config files with mode support

## 1.3.0-canary.0

### Minor Changes

- feat(tailwind): Generating TailwindCSS v4 config files with mode support

## 1.2.1

### Patch Changes

- fix(config): package.json no canary name in stable releases

## 1.2.0

### Minor Changes

- b222198: feat(variables): Variables remodelling and translations feature v0

### Patch Changes

- 08227cc: feat(config): Figma variables collectionsIgnorePrefix feature
- 8e96c8a: fix(config): default values update
- 7065119: fix(types): Cleaner types after variables config update

## 1.2.0-canary.3

### Patch Changes

- feat(config): Figma variables collectionsIgnorePrefix feature

## 1.2.0-canary.2

### Patch Changes

- fix(types): Cleaner types after variables config update

## 1.2.0-canary.1

### Patch Changes

- fix(config): default values update

## 1.2.0-canary.0

### Minor Changes

- feat(variables): Variables remodelling and translations feature v0

## 1.1.7

### Patch Changes

- fix(schema): clean schema completions, validations, and docs for text editors

## 1.1.6

### Patch Changes

- fix(pkg): package.json exports config json schema

## 1.1.5

### Patch Changes

- fix(pkg): right deps/devDeps install

## 1.1.4

### Patch Changes

- ef2512c: fix(config): clean zeytal config w/ json schema

  Updated the config with clean types and json schema generation to support one clean type of config file instead of multiples extensions.

## 1.1.3

### Patch Changes

- 0ed7822: fix(config): supported config file extensions update

## 1.1.2

### Patch Changes

- fix(usage): clean --help usage texts update

## 1.1.1

### Patch Changes

- docs: zeytal header readme update

## 1.1.0

### Minor Changes

- fix(api): clean data streaming from zeytal API
