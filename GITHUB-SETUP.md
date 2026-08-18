# GitHub Pages Setup — Whimsical Wanderer

GitHub username: `greenberryhair`
Recommended repository name: `whimsical-wanderer`

With that repository name, the live project site will be:

`https://greenberryhair.github.io/whimsical-wanderer/`

## Upload

1. Create a new repository named `whimsical-wanderer`.
2. Make it public if you are using GitHub Free Pages.
3. Upload the CONTENTS of this folder to the repository root.
4. Commit the files to `main`.
5. Open **Settings → Pages**.
6. Under **Build and deployment**, choose **Deploy from a branch**.
7. Select branch **main** and folder **/(root)**, then save.
8. After GitHub publishes the site, open:
   `https://greenberryhair.github.io/whimsical-wanderer/`

## JCink CSS imports

Put these at the TOP of a JCink site's stylesheet:

```css
@import url("https://greenberryhair.github.io/whimsical-wanderer/assets/css/single-v1.css");
@import url("https://greenberryhair.github.io/whimsical-wanderer/assets/css/multiple-v1.css");
```

## JCink HTML

Use:

- `jcink/single-want-ad-selfhost.html`
- `jcink/multiple-want-ad-selfhost.html`

Those copies already point at your GitHub Pages artwork and sample silhouettes.

The ordinary HTML copies are also included if you want to keep the existing external image URLs.
