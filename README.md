# jannatul-ferdous-rima.github.io

Source for my personal website: **https://jannatul-ferdous-rima.github.io**

I'm an experimental physicist finishing my Ph.D. in physics (quantum photonics)
at Louisiana State University. The site covers my research (quantum statistical
plasmonic metacrystals, quantum-enhanced plasmonic sensing, multiphoton quantum
coherence and imaging), technical skills, background, publications and talks.

## Structure

| Path | Contents |
|---|---|
| `index.html` | Home page: about, projects, skills, background, publications, contact |
| `project.html` | Detailed research case studies |
| `static/components/` | Shared header and footer, loaded by `static/js/load-components.js` |
| `static/css/` | Styles, one file per section |
| `static/js/scripts.js` | Navigation, scroll and animation effects |
| `assets/` | Photos, project cards and figures (`assets/docs/`: resume and CV) |

To preview locally: `python3 -m http.server` in this folder, then open
http://localhost:8000.

## Credits

Built on the open-source portfolio template by
[Trần Hữu Đạt](https://github.com/TranHuuDat2004) (MIT License, see
`LICENSE`). Content and research descriptions are my own. Figures adapted from
published papers are credited in their captions.
