# AI-tainment Studios — public homepage

Static site for **AI-tainment Studios**, intended for GitHub Pages.

Primary domain: `ai-tainment-studios.co.uk`  
Also owned: `ai-tainment.co.uk` (brand protection / redirect)

## Local preview

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8080 --directory .
```

## Deploy to GitHub Pages

Repo already exists: [TheAutomationGuy-HackerOne/AI-tainment-Studios](https://github.com/TheAutomationGuy-HackerOne/AI-tainment-Studios)

1. Copy these files to the repo root (`index.html`, `styles.css`, `CNAME`, this `README.md`).
2. Ensure Pages is enabled for the `main` branch (root).
3. After the first Pages deploy, point DNS at Porkbun:
   - **Apex** `ai-tainment-studios.co.uk`: GitHub Pages A records (or ALIAS/ANAME if Porkbun supports it), **or** a CNAME to `theautomationguy-hackerone.github.io` where allowed.
   - **www** (optional): CNAME → `theautomationguy-hackerone.github.io`
4. Keep the `CNAME` file content as `ai-tainment-studios.co.uk` so GitHub binds the custom domain.
5. For `ai-tainment.co.uk`, add a redirect/forward at Porkbun to the primary domain (no second Pages site required).

Do not commit secrets. This site is public.

## Project links used on the page

| Project | Public link |
|---|---|
| IONWAKE | https://theautomationguy-hackerone.github.io/IONWAKE-Play/ |
| GridForge | https://github.com/TheAutomationGuy-HackerOne/GridForge-Play |
| Modbus 40001 | App Store + privacy page (see `index.html`) |
| Roastie | Blurb only (no public product URL) |

Sampson Boats is intentionally omitted.
