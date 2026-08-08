WPG Project 1.0 - Cloudflare Workers Static Assets

Cloudflare configuration:
- Worker name: a-wpg-project
- Static assets: ./public
- SPA fallback: enabled via wrangler.jsonc

Important:
The _redirects file is intentionally not included. The previous rule `/* /index.html 200`
caused Cloudflare to detect an infinite redirect loop. SPA fallback is now handled by
`not_found_handling: "single-page-application"` in wrangler.jsonc.
