# mind-diver.com [![Netlify Status](https://api.netlify.com/api/v1/badges/105acc00-d61b-4e35-98c9-94973c67a9e8/deploy-status)](https://app.netlify.com/sites/mind-diver/deploys)
Landing page for Mind Diver.

## Prerequisites
Make sure you have [Hugo Extended](https://gohugo.io/getting-started/installing) installed and that your version matches the one specified in [netlify.toml](./netlify.toml).

## Commands
Run a development server on `localhost:8080`:
```bash
hugo server --port 8080 --buildDrafts
```

Build a production ready site under `public` dir:
```bash
hugo --gc --minify --verbose
```
