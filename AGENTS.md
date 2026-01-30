# Agent Instructions for this repository

## Logging
- After each user interaction in this repo, append an entry to `codex.log.md` at the repo root.
- Each entry must include:
  - An ISO 8601 timestamp (local time with offset), e.g. `2026-01-28T14:05:00-05:00`.
  - The full user prompt.
  - A short summary of the assistant’s answer (actions suggested or implemented).
- Append-only; never rewrite or delete prior entries. Create `codex.log.md` if missing.
- Keep summaries concise (1–3 sentences); no need to paste full answers.
