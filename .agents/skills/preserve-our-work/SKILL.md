---
name: preserve-our-work
description: Save the session's progress so the next conversation can continue. Checks the wiki log and writes a handoff note. Use when finishing a chunk of work, wrapping up, or when the user says "preserve our work" or "checkpoint this".
---

# Preserve our work

**Why this exists:** you don't remember past conversations, and your working memory fills up within a long one. The next conversation knows only what's written in this folder. So before you stop, save what you did and what's next.

Steps:

1. **Check today's date** with `date` first.
2. **The log:** make sure `wiki/log.md` has a line for every change made in this session.
3. **Handoff note:** add `0-project-management/work-ledger/YYYY-MM-DD-<short-slug>.md`. Start with a title and a one-sentence `**Summary:**`, then **what** you did, **decisions** (for example, which sources were left out and why), and **what's next**, such as open questions and sources to look for. Add a one-line link to it at the top of `0-project-management/work-ledger/index.md`.
4. If the project uses Git, offer to commit. Stage files by name (`git add <file>`), never `git add -A`. **Never commit secrets** (`.env` is git-ignored).

Write a handoff note for a *meaningful chunk* of work, not every small edit.
