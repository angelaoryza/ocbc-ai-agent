# OCBC AI Creator Masterclass: participant site

The Mintlify site for participants of the OCBC AI Creator Masterclass, a build sprint by Algoritma for PT Bank OCBC NISP Tbk.

## Layout

| Path | Holds |
|---|---|
| `index.mdx`, `getting-started/` | Home, setup, pre-course checklist |
| `day1/` to `day4/` | Day overview, one page per session (`s0` to `s6`), Appendix A and the glossary, all from the day's coursebook |
| `images/day1/` to `images/day4/` | Figures from the coursebooks |
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
