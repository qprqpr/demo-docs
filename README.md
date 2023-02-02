# Demo documentation portal

This website is built using [Docusaurus 2](https://docusaurus.io/), a modern static website generator.

### Installation

```
$ yarn
```

### Local Development

```
$ yarn start
<or>
$ yarn start -- --locale ru
```

This command starts a local development server and opens up a browser window. Most changes are reflected live without having to restart the server.

```
$ yarn run write-translations --locale ru
```

Write the JSON translation files that you will have to translate.

### Build

```
$ yarn build
```

This command generates static content into the `build` directory and can be served using any static contents hosting service.
