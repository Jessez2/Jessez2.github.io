# Personal GitHub Pages Site

This folder contains a static academic homepage inspired by the layout of https://neoyanghc.github.io/.

## How to use

1. Create a repository named `Jessez2.github.io`.
2. Copy all files from this folder into that repository.
3. Replace placeholder values in `index.html`, `publications.html`, and `cv.html`.
4. Replace `assets/profile-placeholder.svg` with your real profile photo.
5. In your DNS provider, add a `CNAME` record:

```text
Name:   www
Type:   CNAME
Value:  Jessez2.github.io
```

6. In GitHub, open `Jessez2.github.io` -> Settings -> Pages, set Custom domain to:

```text
www.juncaizhang.site
```

7. Commit and push to GitHub. After DNS finishes propagating, enable "Enforce HTTPS".

GitHub Pages will publish it at:

```text
https://www.juncaizhang.site/
```
