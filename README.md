# northsoftware-preview

Public website previews for North Software's small-business outreach, served by GitHub Pages at
https://preview.northsoftware.pt/<slug>/

- One folder per business: `<slug>/index.html` plus its pictures; shared photos and fonts in `assets/`.
- Built by the outreach engine in `C:\Projetos\NorthSoftware-SmallBiz` (template/build.py), then copied here and pushed.
- Not indexed: `robots.txt` blocks crawlers and every page carries `<meta name="robots" content="noindex">`.
- `CNAME` holds the custom domain; `.nojekyll` makes Pages serve the files as they are.
