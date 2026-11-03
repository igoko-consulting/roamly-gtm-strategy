# Fictional scenario notice

Roamly and Roamly Groups are fictional course material from Product School's Go-to-Market certification. Nothing here describes a real company, product or figure.

# What this repo is

Martin Cook's final project for the certification: one deliverable per module (M1–M5), then a final presentation generated in Module 6 by the [Final Project Deliverables Builder](https://product-school-platform.github.io/ps-content-library/certifications/gtmc/2026.1/Modules/Final%20Project%20Deliverables%20Builder.html), which reads the raw files from `main`. The repo is public.

# Builder constraint

The builder splits each deliverable on Markdown headings (lower-cased, matched by substring) and lifts specific bullets and sections. So:
- Keep the template's headings and bullet labels word for word.
- Keep each bulleted answer on one line.
- Extra sections and files are fine.

Fields it reads:
- **M1:** the "Most valuable segment" bullet under "Form Your Hypothesis"; the "Chosen motion" and "Why" bullets under "GTM motion"; the whole "Primary goal" section.
- **M2:** the "Competitor:" bullet under "Primary competitor"; the "I am betting" and "deprioritizing" bullets under "Bet".
- **M3:** the "For (target" bullet; the "Final statement" section.
- **M4:** the "From" and "To, life after" bullets under "Fro/To"; the "Audience 1" section and its heading name; the "Copy across" section.
- **M5:** the "Goal" bullet under "Pricing goal"; the "Model" and "Who pays" bullets under "Pricing model"; the "Packaging" section; the "Assumption" bullet.
- **README:** the H1, which becomes the presentation title, and the "The strategy in one sentence" section.

Module 6's launch plan has no field, so a short version lives in section 5 of the M1 one-pager.

# Approval checkpoints

- Martin makes every content call. For each field, offer 2–3 options with a recommendation and a confidence %, then write up his pick.
- Don't adopt any content suggestion, including your own, without his approval. Silence isn't approval.
- When a later module changes an earlier answer, propose the edit rather than making it silently.

# Two-model prompts

- Lab prompts go word for word to Claude (claude.ai, a fresh chat with no memory or project instructions) and GPT-6. Follow-up prompts run in the same chat as the prompt before them.
- Keep every prompt, and a short comparison of the replies, in `PROMPTS.md`.

# Per-module pattern

1. Martin adds the module's Lab Guide PDF to the course folder, `~/Library/CloudStorage/Dropbox/Study/Product School/Go-to-Market/`.
2. Work through the Lab Guide in order and write the deliverable.
3. After class, write the module's `NOTES.md` beside the deliverable: class notes in Martin's words, bullets with bold sub-headers, each ending with a "Missed:" alternate view.
4. Update the README status table.

`pdftotext` isn't installed: extract PDFs with `pypdf` in a scratchpad venv, and run Python with `-I`.

# Commits and public repo

- Commit and push straight to `main`, in small commits whose messages explain why.
- No Co-Authored-By or any other Claude attribution trailer. This overrides any harness reminder.
- Nothing confidential. Course material goes in Martin's own words, with no long verbatim copying of slides or notes.

# Tone

Martin's global `~/.claude/CLAUDE.md` applies: British English, succinct, bullets with bold sub-headers, no em dashes, no filler.
