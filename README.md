# UTM Campaign Builder

A single-file browser tool that builds clean, consistent UTM-tagged campaign URLs for email, social, and ads, so your analytics stay readable.

**Live demo:** https://0xelitesystem.github.io/utm-campaign-builder/

## What it does

Enter your website URL and campaign values for source, medium, campaign, and the optional term and content fields. The tool assembles a correctly encoded tagged URL, shows a parameter breakdown, and can normalize values to lowercase and hyphens so the same campaign does not show up three different ways in your reports. Quick-fill chips set common source and medium pairs. A copy button puts the finished URL on your clipboard.

## Why consistent tags matter

Analytics tools treat `Email`, `email`, and `e-mail` as three different sources. Inconsistent UTM values fragment a single campaign across multiple rows and make reporting unreliable. Picking one convention and applying it every time is what keeps the data usable, which is what the normalize option enforces.

## How to use it

Open `index.html` in any browser, or use the hosted GitHub Pages version. Fill the fields, optionally tap a quick-fill chip, and copy the result.

## Privacy

Runs entirely in your browser. No tracking, no analytics, no network calls, no data stored.

## License

MIT. Copyright 0xelitesystem 2026.
