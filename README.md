# Documentation workspace

This repo is a clean slate for your docs. Everything currently in the `*.mdx` files is placeholder copy so you can swap in your own content and structure.

## Local preview

1. Install the [Mintlify CLI](https://www.npmjs.com/package/mint): `npm i -g mint`
2. From the folder containing `docs.json`, run: `mint dev`
3. Open `http://localhost:3000` to see your changes as you edit.

## Adding content

- Pages live next to `docs.json` (for example `index.mdx`, `quickstart.mdx`, `development.mdx`).
- Update navigation and brand details in `docs.json` to match your product.
- Add or remove MDX files as you grow the docs; keep `navigation.tabs` in sync.

## Deploying

Push changes to your default branch and deploy with your hosting setup. If you're using the Mintlify GitHub app, deployments will follow your Git workflow automatically.
