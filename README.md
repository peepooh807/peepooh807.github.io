# Grado PH — Portfolio & Privacy Policy Site

Simple GitHub Pages site for Grado PH (Android + Windows Desktop), hosting the
app descriptions and the AdMob-required Privacy Policy.

## Structure

- `index.html` — landing page / portfolio
- `privacy.html` — privacy policy (required by Google AdMob / Play Console)
- `style.css` — shared styling
- `assets/` — app icon and DepEd logo

## Local preview

Open `index.html` directly in a browser, or serve the folder locally:

```
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deploying to GitHub Pages

1. Push this repo to GitHub.
2. In the repo's **Settings → Pages**, set the source to the `main` branch, root folder.
   (If the repo is named `<username>.github.io`, GitHub Pages publishes it
   automatically with no extra settings.)
3. The site will be live at either `https://<username>.github.io/` (if the repo
   is named `<username>.github.io`) or `https://<username>.github.io/<repo-name>/`.
