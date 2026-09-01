# Karishma Premnath — Portfolio

Live at **https://karishmapremnath4.github.io**

Static site. No build step, no dependencies, no framework.

## Files

- `index.html` — all page content
- `styles.css` — all styling, including a print stylesheet
- `tech-motif.svg` — background drafting motif
- `karishma-premnath.jpg` — portrait
- `Karishma_Premnath_Resume.pdf` — linked from Contact and the footer

## Viewing it locally

```
python3 -m http.server 8731 --directory .
```

Then open http://localhost:8731.

## Editing

Content lives in `index.html`, grouped by commented blocks in page order:
about, skills, education, experience, projects, publication, contact.
To add a project, copy an existing `<article class="entry">` block and change
the date, title, body, stat grid and chips.

Colours, fonts and the page width are the CSS variables at the top of
`styles.css`. Each section carries a discipline "ink" via a `dom-*` class.
