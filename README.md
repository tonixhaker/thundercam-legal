# ThunderCam — legal pages (GitHub Pages)

Static site with the privacy policy and terms of use (EN + UA).

GitHub Pages on the **free plan only publishes from public repos**, so this
folder is designed to be pushed to a small public repo while the app repo
stays private:

```bash
# one-time
gh repo create tonixhaker/thundercam-legal --public   # or create via the web UI
cd legal
git init -b main
git add .
git commit -m "ThunderCam legal pages"
git remote add origin git@github.com:tonixhaker/thundercam-legal.git
git push -u origin main
```

Then on GitHub: **thundercam-legal → Settings → Pages → Source: Deploy from a
branch → main / (root) → Save.**

The site appears at:

- https://tonixhaker.github.io/thundercam-legal/          (landing)
- https://tonixhaker.github.io/thundercam-legal/privacy.html
- https://tonixhaker.github.io/thundercam-legal/terms.html

Use those URLs in the App Store Connect listing.
