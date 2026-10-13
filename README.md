# Facundo Rodriguez — Personal website

English-first static portfolio for https://rodriguezfacundo.com.

## Preview

Run `npm run dev`, then visit http://localhost:3000.

## Deploy: Vercel + Cloudflare DNS

Import this repository into Vercel. `vercel.json` selects the static `dist/` directory with no build step. Add `rodriguezfacundo.com` and `www.rodriguezfacundo.com` in the Vercel project Domains settings; redirect www to the root domain. In Cloudflare, use the exact DNS records Vercel provides and initially set them to DNS-only. Wait for Vercel to verify the domain and issue HTTPS.

Publish the contents of `dist/` on any static host and connect `rodriguezfacundo.com` using the DNS records supplied by that host. No framework, build step, or backend is required. Enable HTTPS and redirect www to the canonical root domain.

## Content

Project descriptions and the GYMPASS member count come from Facundo. Employment, skills, education, and contact details come from his supplied CV. Olivia and MCP capabilities were checked against the local repositories’ README files. LinkedIn was inaccessible during research. The visual project panels are brand illustrations, not application screenshots. No private customer data is displayed.

Edit `dist/index.html` for copy, `dist/styles.css` for design, and replace `dist/assets/Facundo-Rodriguez-CV.pdf` to update the downloadable résumé. Employment dates reflect the provided CV and should be confirmed before public launch.

English is the initial language; Spanish can be added in a second stage with translated content, an accessible language switcher, and language-specific metadata.

Google Fonts are optional; local sans-serif fallbacks are provided. All other assets are included.

## Deployment references

- https://vercel.com/docs/project-configuration/vercel-json
- https://vercel.com/docs/domains/set-up-custom-domain

## Verification

JavaScript syntax, internal anchors, downloadable assets, and JSON configuration were checked. Browser visual QA remains pending because the local preview server was blocked by the execution environment. No deployment to Vercel or DNS changes have been performed.
