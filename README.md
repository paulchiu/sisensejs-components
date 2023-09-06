# SisenseJS Components - Beta

**A package for embedding analytics with SisenseJS in a component-based approach.**

This repository is a monorepo containing several versions of the [SisenseJS] Component Library as well as code samples for them.  
These libraries make it easier to embed [SisenseJS]-based widgets in modern web applications.

> **PLEASE NOTE**  
> This library is a beta - Some APIs and behaviors may change as the library evolves. This may include breaking changes.

## Packages

 - **[`@paulchiu/sjs`]** is the core library, based on WebComponents, and can be used with vanilla Javascript or Typescript client applications
 - **[`@paulchiu/sjs-react`]** is a `React` component version of [`@paulchiu/sjs`]

## Using these packages

Please refer to the [/docs](/docs/) subdirectory for documentation.

## Examples

You can find several examples of using these libraries in the [/examples](/examples/) folder.


[SisenseJS]: https://sisense.dev/guides/embedding/sisense.js.html  "SisenseJS documentation"
[`@paulchiu/sjs`]: https://github.com/sisense/sisensejs-components/pkgs/npm/sjs
[`@paulchiu/sjs-react`]: https://github.com/sisense/sisensejs-components/pkgs/npm/sjs-react

## Build and publish

Before publishing, remember to bump package versions.

```shell
yarn install
yarn build
yarn npm login
yarn workspace @paulchiu/sjs npm publish --access public
yarn workspace @paulchiu/sjs-react npm publish --access public
```