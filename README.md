# Reforge Insights Documentation

Reforge Insights (formerly Monterey AI) is the Copilot for Product Development. The docs are available at [docs.monterey.ai](https://docs.monterey.ai)

### 👩‍💻 Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mint) to preview the documentation changes locally. To install, use the following command

```
npm i -g mint
```

Run the following command at the root of your documentation (where docs.json is)

```
mint dev
```
You can provide a `--port` flag to run on a different port.

### 😎 Publishing Changes

Changes will be deployed to production automatically after pushing to the default branch.

You can also preview changes using PRs, which generates a preview link of the docs.

#### Troubleshooting

- `mint dev` isn't running - Run `mint install` it'll re-install dependencies.
- `mint dev` is updating really slowly - Run `mint clear` to clear the cache.
