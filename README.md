# textmining_ukdri_share

Rendered slide deck and its Quarto source, shared from the private
`textmining_ukdri` pipeline.

## Contents

| File | What it is |
| --- | --- |
| `fair_slides.html` | Reveal.js slide deck (HTML, self-contained) |
| `fair_slides.qmd`  | Quarto source for the slides |
| `assets/surrey.png` | Logo referenced by the slides |
| `index.html` | Landing page that redirects to the slides |

## Viewing

The HTML is self-contained (Quarto `embed-resources: true`), but the
deck uses Reveal.js / Observable JS features that require a real HTTP
origin. Use the published URL:

- <https://andreifoldes.github.io/textmining_ukdri_share/>

To view locally without GitHub Pages, serve the directory:

```bash
python3 -m http.server 8000
# then open http://localhost:8000/
```

## Re-rendering

`fair_slides.qmd` is included for inspection only — it depends on
upstream pipeline state that is not part of this repository.
