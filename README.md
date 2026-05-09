# Bo Yang Academic Website

This is a static GitHub Pages-ready redesign of Bo Yang's personal academic website.

## Files

- `index.html`: homepage
- `research.html`: publications and projects
- `data.html`: data, replication materials, and methods
- `teaching.html`: teaching experience
- `community.html`: academic community activities
- `opportunities.html`: research assistant opportunity page
- `cv.html`: CV page
- `assets/styles.css`: site-wide styling
- `CNAME`: custom domain configuration for `bo-yang.org`

## What to replace

1. Add your portrait as `assets/portrait.jpg`, then replace the portrait placeholder in `index.html` with:

```html
<img src="assets/portrait.jpg" alt="Bo Yang" style="width:100%; border-radius:26px;">
```

2. Add your current CV as:

```text
assets/Bo_Yang_CV.pdf
```

3. Replace placeholder publication links with exact paper URLs, SSRN links, PDF links, and replication links.

## Deploy to GitHub Pages

1. Create a new public GitHub repository, for example `bo-yang.github.io`.
2. Upload all files in this folder to the repository root.
3. Go to **Settings > Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and root folder.
6. Save.
7. If using `bo-yang.org`, keep the included `CNAME` file and configure DNS with your domain registrar.

## Notes

This version uses plain HTML and CSS. No build tools are required.
