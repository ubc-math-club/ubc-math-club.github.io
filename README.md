# Website

This website is built using [Docusaurus 2](https://docusaurus.io/), a modern static website generator.

## Installation

```console
yarn install
```

## Local Development

```console
yarn start
```

This command starts a local development server and opens up a browser window. Most changes are reflected live without having to restart the server.

## Build

```console
yarn build
```

This command generates static content into the `build` directory and can be served using any static contents hosting service.

## Deployment
Deploys on the `main` branch of github, to be served on github pages. Code is stored in the `code` branch.

```console
GIT_USER=<Your GitHub username> USE_SSH=true CURRENT_BRANCH=code DEPLOYMENT_BRANCH=main yarn deploy
```

If using a non-standard ssh key, add:
```console
GIT_SSH_COMMAND="ssh -i ~/.ssh/<Your key>"
```
