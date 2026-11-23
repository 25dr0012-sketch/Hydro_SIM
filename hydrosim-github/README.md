# HydroSIM Research Lab — website

Website of **HydroSIM**, the hydraulics and simulation research group led by Prof. Abhishek Kumar Pandey, Department of Civil Engineering, IIT (ISM) Dhanbad.

The site is a single static page (`index.html`) with four sections — Home, Team Head, Team and Gallery — and a live, touch-interactive fluid simulation in the banner (WebGL2, falls back to `flow.mp4`).

## Files

| Path | What it is |
|---|---|
| `index.html` | The whole website: layout, text, styles and scripts |
| `images/` | Portrait and student photos; gallery photos go here as `gallery-1.jpg` … `gallery-8.jpg` |
| `flow.mp4`, `flow.jpg` | Fallback banner video and its preview image |
| `emblem.svg`, `mark.svg`, `mark.png` | Lab emblem, round icon and browser-tab icon |

## Publish with GitHub Pages

1. In this repository, open **Settings → Pages**.
2. Under **Build and deployment**, set **Source** to *Deploy from a branch*, choose branch `main` and folder `/ (root)`, then **Save**.
3. After a minute the site is live at `https://<your-username>.github.io/<repository-name>/`.

## Updating

Edit the site on claude.ai, export a fresh copy, and upload the changed files here (**Add file → Upload files**). Text and team details live in the JSON block near the end of `index.html` (`<script id="state">`).
