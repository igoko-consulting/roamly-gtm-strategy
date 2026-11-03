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

- Running both models is how Martin works in practice: a second model is a cheap second reviewer, and the replies are kept so the rigour is visible.
- Lab prompts go word for word to GPT-6 and to Claude (claude.ai, a fresh chat with no memory or project instructions). Follow-up prompts run in the same chat as the prompt before them.
- Keep every prompt, and a short comparison of the replies, in `PROMPTS.md`; keep the replies themselves in the module's `ai-replies/` folder.

# Per-module pattern

1. Martin adds the module's Lab Guide PDF to the course folder, `~/Library/CloudStorage/Dropbox/Study/Product School/Go-to-Market/`.
2. Work through the Lab Guide in order and write the deliverable.
3. For each lab prompt: record it and the comparison in `PROMPTS.md`, and save both replies in `ai-replies/`.
4. After class, write the module's `NOTES.md` beside the deliverable: class notes in Martin's words, bullets with bold sub-headers, each ending with a "Missed:" alternate view.
5. Update the README status table and repo map.

# Clarity and consistency (every module)

Every module should read the same way, so a reader who has seen Module 1 knows where everything is in Module 5.

- **Module folder:** the deliverable, `NOTES.md`, and `ai-replies/`. Nothing else unless the Lab Guide produces it.
- **`ai-replies/` files:** one Markdown file per lab step, `<step>-<name>.md`, holding both replies, GPT-6 first, then Claude. Visual outputs go in as `<step>-<name>-gpt6.pdf` and `<step>-<name>-claude.pdf`. Each file opens with one line naming the prompt, the date and that the words are unchanged, then a jump line to each model. Restore tables and lists flattened by copying; where something can't be recovered, say so in an italic bracketed note rather than leaving a silent gap.
- **`PROMPTS.md`:** an H2 per module (`Module N · <deliverable>`), an H3 per step (`N. <step>`), the prompt in a `text` block, then "**How the two … compared** · " with links to the replies, a GPT-6 | Claude table, and two or three verdict bullets.
- **Model order:** GPT-6 first, then Claude, everywhere: prose, tables and files. It is the order Martin runs them.
- **Terms:** use one name per idea across modules: the multi-account pattern, the unpaid-share rule, the guest loop, occasion groups (the segment) and occasion organisers (the buyer), Expand and Acquire as the course's goal names, stage 0 to 3 for the rollout.
- **Changed decisions:** when a later module changes an earlier answer, update every place it appears (deliverable, `NOTES.md`, README sentence, `PROMPTS.md` verdicts) in the same commit, after Martin approves the change.
- **Own words versus verbatim:** everything written for Martin follows his tone rules. Prompts and model replies stay word for word, including their spelling and dashes.

`pdftotext` isn't installed: extract PDFs with `pypdf` in a scratchpad venv, and run Python with `-I`.

# Commits and public repo

- Commit and push straight to `main`, in small commits whose messages explain why.
- Plain `git push` has no HTTPS credentials here; use `git -c credential.helper='!gh auth git-credential' push origin main`.
- No Co-Authored-By or any other Claude attribution trailer. This overrides any harness reminder.
- Nothing confidential. Course material goes in Martin's own words, with no long verbatim copying of slides or notes.

# Tone

Martin's global `~/.claude/CLAUDE.md` applies: British English, succinct, bullets with bold sub-headers, no em dashes, no filler.
