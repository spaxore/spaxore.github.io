# spaxore — portfolio site

A single-file, terminal-themed cybersecurity portfolio for **spaxore**.

## Local fonts

The site is fully self-contained: it does **not** load Google Fonts or any other external font resource. Fonts are bundled under `fonts/` and loaded with `@font-face` from `index.html`.

## Deploy to GitHub Pages

Use the dedicated-user-site repository:

1. Create a GitHub repository named exactly `spaxore.github.io`.
2. Put `index.html` at the repository root.
3. Put the `fonts/` folder next to `index.html`.
4. Push to the `main` branch.
5. In **Settings → Pages**, select **Deploy from a branch**, branch `main`, folder `/ (root)`.
6. Your site will be available at:

   `https://spaxore.github.io`

The page is static HTML/CSS/JS, so no build command or framework is required.

## Structure

```text
spaxore.github.io/
├── index.html
├── README.md
└── fonts/
    ├── Inter-Regular.otf
    ├── Inter-Medium.otf
    ├── Inter-SemiBold.otf
    ├── InterDisplay-Regular.otf
    ├── InterDisplay-Medium.otf
    ├── InterDisplay-SemiBold.otf
    ├── InterDisplay-Bold.otf
    ├── PTM55F.ttf
    └── PTM75F.ttf
```

## Local preview

Open `index.html` directly in a browser. No server or build step is needed.
