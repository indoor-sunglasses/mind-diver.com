# mind-diver.com [![Netlify Status](https://api.netlify.com/api/v1/badges/62418d54-a339-4d4d-807a-75039d95a2d9/deploy-status)](https://app.netlify.com/sites/flamboyant-pasteur-6b3716/deploys)
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
