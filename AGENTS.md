# Working in this project

This is **AI-Knowledgebase**, a research wiki you keep for the user: you turn sources into linked pages in `wiki/`. The example subject is planning a community garden (`0-project-management/mission.md`). The user may be new to AI assistants and doesn't need to code.

## How to help here

- Explain what you're about to do in plain language before you do it, and work in small steps.
- Prefer the simplest thing that works. Don't introduce tools unless asked.
- Ask before installing software, deleting files, or running anything that changes the system.
- Define any technical term the first time you use it.

## Wiki rules

Read `3-specifications/page-rules.md` before writing in `wiki/`. The rules that matter most:

- **Never edit a file in `1-research/`.** Source notes are a record of what each source said when read. Corrections go on the wiki page.
- **Every claim on a page links its source note.** The group's own plans link `0-project-management/mission.md`.
- **Write "unknown" rather than guess,** and keep disagreements between sources visible.
- **Date anything that changes,** and give such pages a review date.
- **Every change updates** `wiki/index.md` (for new pages) and `wiki/log.md` (always).
- **No copied text from sources.** Summarize in your own words.
- The skills `add-a-source`, `ask-the-wiki` and `check-the-wiki` carry out these rules.

## Before you change anything: Git

If this folder isn't under Git yet (it has no `.git` folder), offer to set it up before you change anything: run `git init` and make a first commit of the files as they are. Explain that a commit is a saved snapshot the user can go back to. Ask before each commit, stage files by name, and never commit a `.env` file. After each finished task, offer to commit.

## Tools on this Mac

Check what is installed (for example `uv --version`) before you install anything, and ask first.

## Secrets

API keys and other secrets go in the user's `~/.env` file, never in code, committed files or chat. This folder's `.gitignore` leaves out `.env` as a safety net.

## Keeping this file useful

This file is how you remember this project between conversations, so keep it short and current:

- **When the user corrects you on something that will come up again, offer to add one line here.** Write the rule, not the story behind it.
- **Keep it to a page or two.** Longer material goes in its own file, with one line here saying when to read it.
- **Before stopping mid-task, offer to write a handoff note** in `0-project-management/work-ledger/` (the `preserve-our-work` skill does this).
- **Write down facts that are easy to get wrong**, such as the group's town once known, as one line here with the date you checked.
