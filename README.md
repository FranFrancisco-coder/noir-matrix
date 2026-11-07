# NOIR / 001 — Digital Rain

A monochrome, editorial-style Matrix-inspired website. Includes animated grayscale code rain, pause/resume, density presets, monochrome inversion and responsive layout.

## Railway + GitHub deployment

1. Create a GitHub repository (e.g. `noir-matrix`) with default branch `main`.
2. Upload all these files at the repository root, including the `public` directory; commit to `main`.
3. Open [Railway](https://railway.com/new), choose **Deploy from GitHub repo**, connect your GitHub account, and select the repository.
4. Create the service and open **Settings → Networking → Generate Domain** to obtain the public URL.
5. Paste that URL into Canvas. Every new commit pushed to `main` will trigger a new Railway deployment if automatic deployments remain enabled.

Railway may require account verification or payment information depending on current free-plan rules. You can verify the current pricing on its website.

## Run locally

Requires Node.js 20+.

```bash
npm start
```

Open http://localhost:3000/ and check http://localhost:3000/health for the health check.

No runtime npm dependencies; external Google Fonts are optional and the site falls back to system fonts.
