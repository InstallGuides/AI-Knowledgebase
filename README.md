# Start here: AI-Knowledgebase

This folder is a research wiki that you build with an AI assistant. You give it sources, and it turns them into linked pages that say what's known, where it came from, and what's still unknown. The example wiki is for a neighborhood group planning a community garden.

*A side track: build a research wiki with an AI assistant. No coding needed.*

## Open this folder with your AI assistant

- **Claude Desktop:** click **Code**, choose **Open folder…**, and pick this folder.
- **ChatGPT app (Codex):** click **Add new project**, choose this folder, and start a Codex chat.
- **Claude Code or Codex in a terminal:** open a terminal in this folder ([how](https://mac.install.guide/terminal/open)), then type `claude` or `codex`.

## Try it

- *"What does the wiki say about water for the garden?"*
- *"Add this source to the wiki: (a link to a page about community gardens)."*
- *"Check the wiki."*

## How the wiki works

- **Sources** go in `1-research/`, one note each, written in your own words, with the link and the date you read it. A source note is never edited after it's added.
- **Pages** go in `wiki/`: topics, open questions, and one page per source. `wiki/index.md` lists them all, and `wiki/log.md` records each change.
- **Every claim links to its source.** When sources disagree, the page says so. When something isn't known, the page says "unknown" instead of guessing.

The rules are in `3-specifications/page-rules.md`. Three skills do the work: `add-a-source`, `ask-the-wiki` and `check-the-wiki`.

## What's in here

- `0-project-management/`: the wiki's mission, and handoff notes in `work-ledger/`.
- `1-research/`: the source notes.
- `3-specifications/`: the page rules.
- `wiki/`: the wiki itself. Start at `wiki/index.md`.
- `2-decisions/` and `4-playbooks/` are here for when you need them, such as recording a choice about the wiki's scope. Most wikis rarely do.

## Open it in Obsidian

The wiki is plain Markdown files with ordinary links, so you can read it in any editor or on GitHub. If you use Obsidian, open this folder as a vault and the links work there too.

## The instruction files

`AGENTS.md` holds the instructions your assistant reads. `CLAUDE.md` is one line that points Claude to the same file, so edit `AGENTS.md` and leave `CLAUDE.md` alone.

## Keep going

- Replace the garden with a subject of your own: rewrite `0-project-management/mission.md`, then add sources one at a time.
- Anything secret, such as an API key, goes in a file named `.env` in your home folder, never in this folder or in chat.

## Learn more

[Starter projects](https://mac.install.guide/developer-setup/starter-project) on Mac Install Guide.
