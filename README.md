# JotaPromos — site estático

Static deals website (brand: **JotaPromos**) built to apply for the Amazon Associates
program and to serve as the public showcase for the Telegram deals channel.

Design inspired by the "Exclusive" e-commerce UI kit: white background, red accent
(`#db4444`), Poppins typography, a flash-sale section with countdown, product cards and a
dark footer. Plain HTML/CSS + a tiny inline countdown script — no build step.

Pages:

- `index.html` — home: hero, flash-sale deals with countdown, categories, footer
- `sobre.html` — about page (who we are + affiliate disclosure)
- `post-*.html` — one article per deal, with original content
- `style.css` — styles

## Publish (GitHub Pages)

The repository must be **public** for free GitHub Pages. After pushing, enable Pages with
source = branch `main`, folder `/ (root)`. The site is served at
`https://<user>.github.io/<repo>/`.

## Before going live / after Associates approval

- Replace every `#` placeholder on the Telegram buttons/links with your channel URL,
  e.g. `https://t.me/yourchannel` (search for `TODO` in the HTML).
- After approval, append your affiliate tag to each product link, e.g.
  `https://www.amazon.com.br/dp/ASIN?tag=yourtag-20` (see the TODO comments in each post).
- Prices shown are references captured on 2026-05-21 and should be reviewed periodically.
