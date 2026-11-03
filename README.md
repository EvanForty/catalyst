# CATALYST ($CATALYST)

Spark an idea. Launch a movement.

Landing page for CATALYST, the AI-powered token creation launchpad on Solana. One static page: no build step, no dependencies.

## Files

- `index.html` – the whole site (HTML, CSS and JS in one file)
- `logo.png` – favicon and social preview image
- `vercel.json` – Vercel settings

## Deploy on Vercel

1. Push these files to the root of a GitHub repo.
2. In Vercel, click **Add New → Project** and import the repo.
3. Framework preset: **Other**. Leave the build command and output directory empty.
4. Deploy.

## Before launch

Edit the `CONFIG` block at the top of the script in `index.html`:

```js
const CONFIG = {
  xUrl: "https://x.com/CatalystFun",
  buyUrl: "",     // DEX link
  chartUrl: "",   // chart link
  contract: ""    // $CATALYST contract address
};
```

The launch fee in the Flywheel section shows `[SET AT LAUNCH]`; search for it in `index.html` to fill it in.
