# Documentation project instructions

## About this project

- The participant site for the **OCBC AI Creator Masterclass**, a 4-day build sprint by Algoritma for PT Bank OCBC NISP Tbk. Participants learn agentic AI by building an end-to-end AI-based system. The use case is the **IDX Market Assistant**, on Indonesian stock data from Sectors. Frame the assistant as the use case, never as the subject of the course.
- Built on [Mintlify](https://mintlify.com). Pages are MDX files with YAML frontmatter; configuration lives in `docs.json`; brand styling that `docs.json` cannot express lives in `style.css`.
- Day 1 and Day 2 content comes from the course materials repo `agentic-ai-ocbc-day1-2` (Pydantic AI with an OpenAI model; open-source `all-mpnet-base-v2` embeddings), published at https://github.com/angelaoryza/ai-agent-system. Day 3 and Day 4 content came from `agentic-ai-ocbc`. In both: the coursebooks become **Concepts** pages, the notebooks **Notebook walkthrough** pages, `examples/` **Worked example** pages and `exercises/` **Exercise** pages. The Day 3 and Day 4 coursebooks become the day overview, the Concepts pages (Day 4: one per part) and a glossary. The Day 3 starter pages come from `day3/starter/README.md` and the starter code; the Day 4 deployment guide pages from `day4/DEPLOYMENT.md` and `day4/deploy/`, one page per section of the guide.
- Keep `<server-ip>` and `<course-folder>` placeholders as they are. Never publish a real server address or a personal path.
- Use the Mintlify docs MCP server, `https://www.mintlify.com/docs/mcp`, to check component syntax and `docs.json` fields.

## Terminology

- "IDX Market Assistant": the system participants build.
- "Sectors": the data provider. Use "Sectors API" and "Sectors MCP server".
- "the OpenAI model": the LLM on Days 1 and 2, used through Pydantic AI. (Day 3 and Day 4 pages still say "Gemini".)
- "module", not "lesson".
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

- `day1/solutions/`, `day2/solutions/` (including `solutions/notebooks/`)
- Either `Trainer Handbook - Day N ...docx` file
- `_build/`
- `.env`, `token.json`, `credentials.json`, or any API key value

Knowledge-check answers stay in the notebooks (hashed). Show the question and options, then: "Answer this in the notebook; the check cell tells you if you are right." Never publish answers, solutions or cell outputs from solved notebooks. **Your turn** cells show the task and the starting code only.

Link to the course materials repo only at its root, https://github.com/angelaoryza/ai-agent-system. Do not link to individual files in it, and never to `solutions/` or the trainer handbooks.
