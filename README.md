# Website

This website is built using [Docusaurus 2](https://docusaurus.io/), a modern static website generator.</br>

[![Netlify Status](https://api.netlify.com/api/v1/badges/d4aa6fb6-e92d-4c8b-9e23-6e2c786eb311/deploy-status)](https://documentation-tutorial.netlify.app/)



### Installation

```
$ yarn
```

### Local Development

```
$ yarn start
```

This command starts a local development server and opens up a browser window. Most changes are reflected live without having to restart the server.

### Build

```
$ yarn build
```

This command generates static content into the `build` directory and can be served using any static contents hosting service.

### Deployment

```
$ GIT_USER=<Your GitHub username> USE_SSH=true yarn deploy
```

If you are using GitHub pages for hosting, this command is a convenient way to build the website and push to the `gh-pages` branch.
