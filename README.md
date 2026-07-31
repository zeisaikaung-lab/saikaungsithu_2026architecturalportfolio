# Sai Kaung Si Thu — Portfolio 2026

Personal portfolio site. Graduate architect based in Bangkok, working at the
intersection of physical craft and computational process.

**Live:** https://<your-username>.github.io/<repo-name>/

## What's here

```
index.html      the whole site — routing, styles and behaviour in one file
img/            33 project images and the portrait
.nojekyll       tells GitHub Pages to serve the files as-is
```

## The site

- **Projects** — an interactive network. Seven projects and twelve shared
  threads (Rhino + Grasshopper, brick & masonry, cultural heritage…). Hover a
  node to trace a thread, click a thread to hold it open, drag a card to place
  it, click the wordmark to reset the layout.
- **About / Services / Contact** — full-width text pages.
- **Project pages** — brief, diagram sequence, credits, uncropped drawings.

Dark and light themes, an opening sequence built from the Payan vault geometry,
and a parametric dot field that gathers into swept waves behind everything.

## Publishing on GitHub Pages

1. Create a repository and upload `index.html`, the `img/` folder and `.nojekyll`.
2. **Settings → Pages → Source: Deploy from a branch → `main` / `(root)`**.
3. The site appears at the URL above within a minute or two.

## Editing

Everything lives in `index.html`.

- **Add a project** — copy the commented template above the `PROJECTS` array,
  fill each field, add a glyph to `GLYPHS`, and drop the images in `img/`.
  Cards, filters and counts all derive from that array.
- **Threads** — `THEMES` and `PROJECT_THEMES` define the network.
- **Images** — referenced by filename through the `IMG` map near the top of the
  script.
