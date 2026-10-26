# optometrics.co.za

The public website for Optometrics. It's a static site served by Cloudflare Workers (static assets), deployed automatically from `main`.

- `public/`: the site. `/privacy` and `/terms` are linked from the Google OAuth consent screen, so keep those URLs.
- `wrangler.jsonc`: Worker config. No build step.

Preview locally with `npx wrangler dev`.
