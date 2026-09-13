# portfolio-website

Personal portfolio site for Tiya Agarwal — a single-page site covering about,
experience, projects, and skills, with a security-focused section and a
contact form.

## Stack

Plain HTML, CSS, and JavaScript — no build step, no dependencies, no
framework. Everything lives in `index.html`.

- Fonts are loaded from Google Fonts (Space Grotesk, Inter, JetBrains Mono).
- The contact form posts to [Formspree](https://formspree.io) (form ID
  configured via `FORMSPREE_ID` in `index.html`).
- Dark/light theme toggle, section reveal animations, and a project filter
  grid are implemented in vanilla JS.

## Running locally

No build or install step is required. Serve the directory with any static
file server, e.g.:

```sh
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Files

- `index.html` — the entire site (markup, styles, and scripts).
- `profile.png` — hero section profile photo.
- `Tiya_Agarwal_Resume.pdf` — résumé linked from the nav and hero sections.

## License

MIT — see [LICENSE](LICENSE).
