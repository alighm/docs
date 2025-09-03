# Krypto Key Documentation

Welcome to the Krypto Key documentation site. This repository contains the complete documentation for the Krypto Key platform.

Click the green **Use this template** button at the top of this repo to copy the Krypto Key documentation template. The template contains examples with

- Guide pages
- Navigation
- Customizations
- API reference pages
- Use of popular components

**[Follow the full quickstart guide](https://docs.kryptokey.com/quickstart)**

## Development

Install the [Krypto Key CLI](https://www.npmjs.com/package/mint) to preview your documentation changes locally. To install, use the following command:

```
npm i -g mint
```

Run the following command at the root of your documentation, where your `docs.json` is located:

```
mint dev
```

View your local preview at `http://localhost:3000`.

## Publishing changes

Install our GitHub app from your [dashboard](https://dashboard.kryptokey.com/settings/organization/github-app) to propagate changes from your repo to your deployment. Changes are deployed to production automatically after pushing to the default branch.

## Need help?

### Troubleshooting

- If your dev environment isn't running: Run `mint update` to ensure you have the most recent version of the CLI.
- If a page loads as a 404: Make sure you are running in a folder with a valid `docs.json`.

### Resources
- [Krypto Key documentation](https://docs.kryptokey.com)
- [Krypto Key community](https://community.kryptokey.com)
