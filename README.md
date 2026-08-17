# Vinted Sold Image Generator — first complete version

This version has the real app flow: paste a public Vinted listing URL, server-side endpoint attempts to read public listing metadata, the product image is proxied, and the browser composes the photo + Sold banner + listing information into one PNG.

## Deploy
GitHub Pages cannot run the `/api` server functions. Keep this project in GitHub, then import the repository into Vercel and deploy it. No build command is needed.

## Limitation
Vinted can block automated requests or change its HTML. This app uses public page metadata only. For reliable production use, use a permitted Vinted data/API integration or a user-assisted import flow.
