# China Legal Tech Watch (static starter)
- Edit HTML files directly or switch to a static site generator later (Jekyll/11ty/Hugo).
- Hosted on GitHub Pages. Custom domain set via CNAME file + DNS A/CNAME records.

## Publishing
- Commit to `main`. GitHub Pages serves from root.
- Ensure repository Settings → Pages → Deploy from branch (`main` / root).

## Structure
- `/briefings`, `/deep-dives`, `/signals`, `/glossary`, `/about`, `/subscribe`.
- `/assets/style.css` for simple site-wide styles.

## Custom domain
- Root has a `CNAME` with `ChineseLegalTechWatch.com`.

## Next steps
- Swap the subscribe form with Substack/Buttondown embed.
- Add analytics (Cloudflare Web Analytics or GoatCounter) by inserting their script tag into `</head>` of each page.
