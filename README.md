# OCBC AI Creator Masterclass: participant site

The Mintlify site for participants of the OCBC AI Creator Masterclass, a build sprint by Algoritma for PT Bank OCBC NISP Tbk.

## Layout

| Path | Holds |
|---|---|
| `index.mdx`, `getting-started/` | Home, setup, pre-course checklist, course data, folder map |
| `day1/`, `day2/` | Day overview, then one folder per module: `concepts`, `notebook`, `example`, `exercise` |
| `images/day1/`, `images/day2/` | Figures from the coursebooks |
| `docs.json` | Site settings and navigation |
| `style.css` | Algoritma brand styling that `docs.json` cannot express |
| `AGENTS.md` | Writing rules and the content boundary |

## Preview locally

```bash
npx mint dev
```

Before you open a pull request:

```bash
npx mint validate
npx mint broken-links
```
