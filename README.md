# Narrative Monitor

We check how AI answers questions and expresses political positions, and whether answers change with the language.

We asked 7 AI models the same questions in 10 languages: elections in Romania, Georgia, Armenia, France and the US, the MH17 downing and Russian influence. The September collection contains 23 audits and 945 saved answers, collected 22 to 26 September 2026.

Six further audits were collected on 8 and 9 October 2026, with 214 saved answers. They cover the #Disinfo2026 conference, FIMI and three antisemitism-related questions. Each series explains its results and limits.

## Start here

- **Website:** https://narrativemonitor.policygenome.org/
- **Method & limits:** [overview.html](https://narrativemonitor.policygenome.org/overview.html)
- **October series:** [Conference and FIMI](https://narrativemonitor.policygenome.org/series_disinfo2026.html) · [Antisemitism-related claims](https://narrativemonitor.policygenome.org/series_antisemitism.html)
- **Sources:** [sources.html](https://narrativemonitor.policygenome.org/sources.html)
- **Ask questions about the study in NotebookLM:** https://notebook.google.com/notebook/e2a20d9b-c928-49aa-b794-d1e030728543

NotebookLM can make mistakes. Check its answers against the original answers in the reports.

## What is in this repository

| Folder or file | What it is |
|---|---|
| `index.html` | Main findings and all audits |
| `R5/`, `R6/`, `R7/`, `R8/`, `R9/` | One folder per audit: a short report (`RUN_ID.html`) and every answer in full (`RUN_ID_evidence.html`) |
| `md/` | The same texts as Markdown, for AI tools: `OVERVIEW.md`, `SOURCES.md`, `CASE_ARMENIA.md`, `CASE_US_FIMI.md`, `SERIES_DISINFO2026.md`, `SERIES_ANTISEMITISM.md`, `all_reports.md` and 29 question-named full answer files |
| `overview.html`, `sources.html`, `case_armenia.html`, `case_us_fimi.html`, `series_disinfo2026.html`, `series_antisemitism.html` | Method, limits, the September source count, case notes and October series introductions |

Each evidence page shows every answer in its original language and in English.
The `md/` folder includes thematic introductions and case notes for NotebookLM.
Full answer filenames start with a short question, followed by the Run ID and `answers`.
Separate MD reports are not needed because every report is in `all_reports.md`.

## Limits

This is a research prototype. Automated tools collected and checked these files. People did not review every file, fact or quote. We do not guarantee that this material is complete or correct. We accept no responsibility for its use or for any resulting loss or harm.

We tested AI models through their APIs, not through consumer chat apps. The questions were chosen on purpose, so the results do not show how often models fail in general.

## Using this material

Please cite: Policy Genome, Narrative Monitor, 2026, and link to this repository. To report an error, tell us the question, model, language and answer round.

## Work with us

We run the same audit for other countries, elections, conflicts and topics, as a one-off audit or as regular monitoring.
Contact: ihor@policygenome.org · https://policygenome.org
