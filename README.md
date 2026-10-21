# Tephra Global

A small, dependency-free landing page for the holding company behind Arc Signal, K MEANS AI, and snUAEkerhead. Plain HTML and CSS; no build, JavaScript, analytics, or remote asset requests.

## Local preview

From this repository:

```sh
python3 -m http.server 4173 --bind 127.0.0.1
```

Open <http://127.0.0.1:4173>. Stop the server with Ctrl-C when finished.

## Editing

- `index.html`: introduction, venture descriptions and public links.
- `assets/css/site.css`: responsive layout and the Bodoni Moda / Inter visual system shared with the neighboring company sites.
- `assets/images/`: optimized volcanic artwork and the favicon.
- `assets/fonts/`: local fonts, with their original SIL Open Font License notices.
- `CNAME`: existing `tephra.global` GitHub Pages domain. Preserve this value.

The landscape is an original AI-generated illustration of an imagined volcanic setting, not a photograph of an identified place. Generation details and content sources are in `docs/design-notes.md`.

No deployment is necessary for local review. Publishing is separate from editing or previewing this checkout.
