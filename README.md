# JotaPromos — site estático

Static deals/curation website (brand: **JotaPromos**) for the Amazon Associates program and
as the public showcase for the Telegram channel (https://t.me/jotapromosbr).

Plain HTML/CSS, no build step. Pages: `index.html`, `sobre.html`, `post-*.html`, `style.css`.

## Compliance notes (important)

To follow the Amazon Associates Program Policies, this site is intentionally **lean**:

- **No hardcoded prices, scraped images or star ratings.** Those may only be displayed when
  fetched live via the Product Advertising API (PA API) / SiteStripe, with a Brasília
  date/time stamp and the required legal disclaimer, refreshed at least every 24h.
- Each product shows: name + original review text + a **"Ver na Amazon"** button whose link
  carries the affiliate tag `?tag=jotapromos-20`.
- The required affiliate disclosure ("Como participante do Programa de Associados da Amazon,
  sou remunerado pelas compras qualificadas efetuadas") appears in the footer of every page.
- No price-tracking / price-alert feature is exposed to users (policy clause "y"): the site
  is editorial curation, not a price tracker.

## Roadmap

After Associates approval + PA API access, the bot (`amazon-deals-bot`) can populate prices,
images and ratings **via PA API** (with timestamp + disclaimer) so the cards/posts show that
data compliantly.

## Publish

GitHub Pages, public repo, source = branch `main`, folder `/ (root)`. Live at
https://joaogalhard0.github.io/jotapromos/
