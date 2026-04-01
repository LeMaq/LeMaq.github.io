# Rafael Maquine Portfolio

Static portfolio site built with plain HTML, CSS, and JavaScript so it can be hosted for free on Cloudflare Pages or GitHub Pages.

## Files

- `index.html` contains the page structure and portfolio content
- `styles.css` contains the full visual design
- `script.js` handles the mobile nav and reveal-on-scroll behavior
- `assets/Rafael-Maquine-Resume.pdf` is the downloadable CV

## Local preview

From this folder, run:

```powershell
python -m http.server 8000
```

Then open [http://localhost:8000](http://localhost:8000).

## Deploy to Cloudflare Pages

1. Push this folder to a GitHub repository.
2. In Cloudflare Pages, create a new project from that repository.
3. Use these settings:
   - Framework preset: `None`
   - Build command: leave empty
   - Build output directory: `/`
4. Deploy.

## Deploy to GitHub Pages

1. Push this folder to a GitHub repository.
2. In the repository settings, open `Pages`.
3. Set the source to deploy from the main branch root.
4. Save and wait for the site URL to be generated.

## Notes

- The `Chasers` itch page appears to be restricted right now, so the portfolio currently shows an embed-ready placeholder instead of a live iframe.
- Once the itch page is public, the project section can be updated to include the provided embed snippet.
