# Water Challenge Connections Interactive Map

This folder is ready to host with GitHub Pages and embed in another website with an iframe.

## Files

- `index.html`: the self-contained interactive map.
- `embed-fixed-height.html`: simplest iframe snippet.
- `embed-auto-height.html`: iframe snippet with optional height resizing.
- `.nojekyll`: tells GitHub Pages to publish files as-is.

## Publish With GitHub Pages

1. Create a new GitHub repository.
2. Upload all files from this folder to the repository root.
3. In GitHub, go to `Settings` -> `Pages`.
4. Under `Build and deployment`, choose:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
5. Save.
6. GitHub will publish the map at a URL like:

```text
https://YOUR-GITHUB-USERNAME.github.io/YOUR-REPOSITORY-NAME/
```

## Embed On Your Website

Replace the placeholder URL in either embed snippet with your real GitHub Pages URL.

Use `embed-fixed-height.html` if your CMS only allows iframe code.

Use `embed-auto-height.html` if your CMS allows a small script below the iframe. The hosted map sends its height to the parent page so the iframe can resize.

## Notes

- The map uses plain HTML, CSS, SVG, and JavaScript.
- It does not use external libraries.
- It does not require a database or API.
- The iframe height can be adjusted manually if needed.
