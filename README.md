# Financial Economics for Citizens

This repository contains the materials for the course [Financial Economics for Citizens](https://agnes.hu-berlin.de/lupo/rds?state=verpublish&status=init&vmfile=no&publishid=208440&moduleCall=webInfo&publishConfFile=webInfo&publishSubDir=veranstaltung) taught by [Alex Stomper](https://amor.cms.hu-berlin.de/~stompera/) and [Christoph Scheuch](https://christophscheuch.github.io/).

## Website

The course website is a [Quarto](https://quarto.org) project that GitHub Pages serves from `docs/`. It has two parts:

| Path | Contents |
| --- | --- |
| `index.qmd` | Home page with the entry points to the app and the wiki |
| `app/index.html` | The rating app, a self-contained HTML page that Quarto copies as is |
| `wiki/index.qmd` | Wiki placeholder page (the wiki is coming soon) |
| `styles/` | Theme, styles, and the tooltip script for source references |
| `docs/` | Rendered site (committed, served by GitHub Pages) |

To update the site, render it and commit `docs/`:

```bash
quarto render
```

Use `quarto preview` to see changes locally while editing styles or hand-written pages.
