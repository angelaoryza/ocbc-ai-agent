# Documentation project instructions

## About this project

- The participant site for the **OCBC AI Creator Masterclass**, a 4-day build sprint by Algoritma for PT Bank OCBC NISP Tbk. Participants build an end-to-end AI agent system with AI-assisted coding: they talk to an AI coding agent (OpenCode) and never write code by hand. The use case is a finance assistant for **Harapan Mitra Niaga**, a fictional company, on Indonesian stock data from Sectors. Frame the assistant as the use case, never as the subject of the course.
- Built on [Mintlify](https://mintlify.com). Pages are MDX files with YAML frontmatter; configuration lives in `docs.json`; brand styling that `docs.json` cannot express lives in `style.css`.
- All content comes from the four coursebooks `Coursebook - OpenCode x Sectors Day 1` to `Day 4` (.docx). Each day has `overview`, one page per session (`s0` to `s6`), `appendix-a` and a `glossary` (the coursebook's Appendix B). Day 1 has its own overview text; Days 2 to 4 get a session table. Figures live in `images/dayN/`.
- To update a page, change the coursebook text, not just the page: the site keeps the author's wording.
- Keep `<server-ip>` and `<course-folder>` placeholders as they are. Never publish a real server address or a personal path.
- Use the Mintlify docs MCP server, `https://www.mintlify.com/docs/mcp`, to check component syntax and `docs.json` fields.

## Terminology

- "finance assistant": the system participants build. "Harapan Mitra Niaga": its fictional company.
- "OpenCode": the AI coding agent, with its **Plan** and **Build** agents.
- "Sectors": the data provider. Use "Sectors API" and "Sectors MCP server".
- "session", as in the coursebooks (not "module" or "lesson").
- "participant", not "student".
- "trainer".

## Style preferences

- Sentence case for headings, labels and buttons. Keep section numbers such as `2.3`.
- Second person ("you"), active voice. One idea per sentence.
- Bold for UI elements: click **Run All**.
- Code formatting for files, commands, paths and environment variable names: `day1/examples/m2_example.py`, `SECTORS_API_KEY`.
- Keep the course author's wording when converting materials. Fix only conversion artefacts; do not add explanations, examples or summaries that are not in the source.
- Use callouts only where the source signals them: a boxed note becomes `<Note>`, a warning `<Warning>`, a scenario or "think about it" box `<Info>`.

## Content boundaries

The site is public. It holds participant materials only. Never read from, quote, paraphrase or link to:

- Trainer handbooks
- `.env`, `token.json`, `credentials.json`, or any API key value

Do not publish answers or solutions that the coursebooks do not already show participants.

Link to the training files repo only at its root, https://github.com/angelaoryza/starter-kit, and to the Google Drive folder, https://bit.ly/OCBCTrainingDrive. Do not link to individual files in the repo.
