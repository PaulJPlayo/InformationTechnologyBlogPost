# Information Technology Blog Post

This project is a static website for the **Information Technology Blog Post** portfolio, featuring an 8-post blog layout with supporting pages and assets.

## Preview Locally

Run:

```bash
npx wrangler dev
```

Then open the local URL shown in your terminal.

## Deploy

Run:

```bash
npx wrangler deploy
```

## Configuration Note

The `wrangler.toml` file is configured to serve the current project directory as static assets:

```toml
[assets]
directory = "."
```
