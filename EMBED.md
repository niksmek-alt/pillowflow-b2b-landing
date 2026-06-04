# PillowFlow B2B Landing — Shopify Embed

## File
- Path: `/root/pillowflow-b2b-landing/index.html`

## Shopify Option A: Online Store page
1. Open Shopify Admin > Online Store > Pages.
2. Create page: name it `B2B Fleet Program`.
3. In the content editor, switch to HTML view.
4. Paste the entire HTML from `index.html`.
5. Save and publish.
6. Set a visible navigation link in your store menu to `/pages/b2b-fleet-program`.

## Shopify Option B: dedicated template
1. Upload `index.html` as a new theme template with a matching layout.
2. Add images from `img/` to Shopify Files and replace `img/*.jpg` URLs with Shopify CDN URLs if using Shopify-hosted assets.

## Build this as a standalone preview host
Use any static host:
- Upload `/root/pillowflow-b2b-landing/` as-is.
- Root URL will serve `index.html` as the landing page.

## QA checklist
- Replace mock/problematic image references with real shipped assets before publishing.
- Update `hello@pillowflow.com` and any pilot URL to your live destinations.
- If adding forms or tracking, add them separately; this template is intentionally static.
