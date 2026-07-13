# Xuhui Liu — Personal Website

This is a lightweight static academic website designed for GitHub Pages.

## Add your photo

Place your photo at:

```text
assets/profile.jpg
```

A square or nearly square image works best. The website crops it to a circle automatically. Until the image is added, the included placeholder is displayed.

## Publish with GitHub Pages

1. Sign in to GitHub and create a new **public** repository named exactly:

   ```text
   liu-xuhui.github.io
   ```

2. Upload everything in this folder to the root of that repository. `index.html` must be in the repository root, not inside another folder.
3. Open the repository's **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and the `/ (root)` folder, then click **Save**.
6. After GitHub finishes publishing, visit:

   ```text
   https://liu-xuhui.github.io
   ```

## Update the AdaMP publication

In `index.html`, find the section with `id="research"`. Replace “Preprint coming soon” with the arXiv link and final author list when available.

## Edit website content

Most content is in `index.html`. Colors, spacing, and mobile layout are in `styles.css`.
