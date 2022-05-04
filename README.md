# Docusaurus + TailwindCSS Example

[Docusaurus 2](https://docusaurus.io/) with [tailwindcss](https://tailwindcss.com/) website created by following [Using TailwindCSS v3 in Docusaurus in 5 steps](https://dev.to/sajclarke_62/using-tailwindcss-v3-in-docusaurus-in-5-steps-5c26) 👍

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

Using SSH:

```
$ USE_SSH=true yarn deploy
```

Not using SSH:

```
$ GIT_USER=<Your GitHub username> yarn deploy
```

If you are using GitHub pages for hosting, this command is a convenient way to build the website and push to the `gh-pages` branch.
