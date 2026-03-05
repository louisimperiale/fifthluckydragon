# Fifth Lucky Dragon — Website

## Deployment (GitHub Pages)

### 1. Create a GitHub repo
- Go to github.com and create a new repository
- Name it anything (e.g. `fifthluckydragon-site`)
- Make it **public**

### 2. Upload these files
Upload everything in this folder to the repo:
- `index.html`
- `CNAME`
- `images/` folder (with all images inside)

### 3. Enable GitHub Pages
- Go to repo **Settings → Pages**
- Under "Branch", select `main` and `/ (root)`
- Click Save

### 4. Point your domain to GitHub Pages
In your domain registrar (wherever you bought fifthluckydragon.com), set these DNS records:

**A Records** (point to GitHub):
```
185.199.108.153
185.199.109.153
185.199.110.153
185.199.111.153
```

**CNAME Record**:
```
www → yourusername.github.io
```

GitHub Pages will handle the SSL cert automatically within a few minutes.

### Updating the site
Just edit `index.html` directly on GitHub (or push changes) and the site updates live.

---

To update music/videos, swap out the YouTube embed IDs or Spotify links directly in `index.html`.
