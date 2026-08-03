# Sujeet Mathew Jose — Product Portfolio

Static, single-page portfolio. No build step, no framework — plain HTML/CSS/JS.

## View it

Open `index.html` directly in a browser, or serve the folder with any static server.

## Deploy (GitHub Pages)

Settings → Pages → Deploy from branch → root. `index.html` is picked up automatically.

## Structure

Flat — everything the page references sits next to `index.html`:

- `hero.png`, `portrait.jpg`, `pdp.png`, `llm-wiki.png` — static images
- `advisor.gif`, `assurance.gif` — case study 01 product recordings
- `blibli-flash-sale.jpg` — case study 03 (live Blibli storefront)
- `lab-loop.mp4` / `lab-loop-poster.jpg` — ambient video opening the Personal AI Lab section
- `sujeet-jose-cv.pdf` — linked from the CV buttons
- `five-eras.html` — standalone long-form essay linked from the "Point of view" section

## Notes

- `lab-loop.mp4` has an audio track; it's silenced in `index.html` via the `muted` attribute, not stripped from the file. Re-encode without audio if you reuse the clip elsewhere without that attribute.
- Theme (dark/light) persists to `localStorage` under the key `sj-theme`, defaulting to the visitor's OS preference on first visit.
- Design tokens follow Direction B ("The Instrument") from the project's design-system spec — graphite background, signal-blue accent, Instrument Sans + Fragment Mono.
