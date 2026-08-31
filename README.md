# laksa-web

The public site for LAKSA, served by GitHub Pages at https://laksa.app

Two static pages, no build step and no dependencies:

- `index.html` — what LAKSA is, and how to reach us
- `privacy.html` — the privacy policy

`privacy.html` is the reason this repo exists. Google Play rejects a
listing without a reachable privacy-policy URL, and both Meta Business
Verification and email deliverability lean on the domain resolving to
real content rather than a parked page.

The authoritative copy of `privacy.html` lives in the (private)
`dukaan-app` repo under `website/`, because its claims are tied to what
the code actually collects. **Edit it there and copy it here**, so the
policy and the audit it was written from cannot drift apart.
