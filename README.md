# Sakshi Chandel | Portfolio

A fast, responsive, single-page portfolio built with plain HTML, CSS and a little JavaScript. There is no build step and no dependencies. It follows the visitor's light or dark system theme.

## Files

| File | Purpose |
| --- | --- |
| `index.html` | All content (hero, about, skills, experience, tools, education, contact) |
| `styles.css` | Styling, colors and layout. Colors are variables at the top of the file |
| `script.js` | Mobile menu and footer year |
| `assets/favicon.svg` | Browser tab icon |
| `.github/workflows/pages.yml` | Automatic deploy to GitHub Pages |

## Preview locally

```bash
python3 -m http.server 8000
```

Open http://localhost:8000.

## Deploy to your own GitHub account

1. Create a new empty repository on GitHub, for example `portfolio` (public). Name it `<username>.github.io` if you want the site at `https://<username>.github.io`.
2. Push this code to it:
   ```bash
   git remote add origin https://github.com/<username>/<repo>.git
   git push -u origin main
   ```
3. In the repository go to **Settings → Pages → Build and deployment → Source** and choose **GitHub Actions**.
4. The **Deploy to GitHub Pages** workflow runs on each push to `main`. After it finishes, the site is live at `https://<username>.github.io/<repo>/`.

## Customize

- **Text and content:** edit `index.html`.
- **Colors:** change the `--accent` and `--accent-2` variables in `styles.css`.
- **Custom domain:** add it under Settings → Pages, then add a `CNAME` file if GitHub asks.
- **Photo:** add `assets/photo.jpg` and replace the `SC` avatar in the hero card with an `<img>`.
