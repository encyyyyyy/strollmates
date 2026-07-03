# Strollmates Reviewer Site

This repository contains the static website used for Strollmates App Store review metadata. It only hosts the public reviewer links for marketing, privacy, terms, and support.

## App Store Reviewer Site

The reviewer site is a static Vercel deployment served from `docs/`.

Reviewer URLs:

- Marketing: `https://strollmatesappi.vercel.app/`
- Privacy Policy: `https://strollmatesappi.vercel.app/privacy.html`
- Privacy Choices: `https://strollmatesappi.vercel.app/privacy.html#choices`
- Terms and Conditions: `https://strollmatesappi.vercel.app/terms.html`
- Support: `https://strollmatesappi.vercel.app/support.html`

No build command is required. `vercel.json` rewrites root URLs to the static pages in `docs/`.
