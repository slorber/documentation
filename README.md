[![Netlify Status](https://api.netlify.com/api/v1/badges/b1747765-cebd-4b05-8b95-5ac85c0df626/deploy-status)](https://app.netlify.com/sites/muscat-docs/deploys)
[![Dependabot Status](https://api.dependabot.com/badges/status?host=github&repo=muscat-instrument/documentation)](https://dependabot.com)

# Website

This website is built using [Docusaurus 2](https://v2.docusaurus.io/), a modern static website generator.

### Installation

```
$ yarn
```

### Local Development

```
$ yarn start
```

This command starts a local development server and open up a browser window. Most changes are reflected live without having to restart the server.

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
