---
name: add-a-source
description: Add a source (a web page, article, report or document) to the wiki. Writes a source note in 1-research/, then updates or creates the wiki pages it affects, the index and the log. Use when the user shares a link or document and says "add this", "read this into the wiki", or similar.
---

# Add a source

1. **Check today's date** with `date`, and read `3-specifications/page-rules.md`.
2. **Read the source** in full. If you can't open it, say so and stop; never write a note from memory.
3. **Write the source note** `1-research/YYYY-MM-DD-<short-slug>.md`: title, link, who published it and when, the date you read it, then a summary **in your own words** of what matters to this wiki, and anything it doesn't say. No copied text. Never edit an older source note; corrections go on wiki pages.
4. **Write its source page** `wiki/sources/<short-slug>.md` (same slug, no date): what the wiki takes from it, and which pages use it.
5. **Update the wiki pages it affects,** or create new ones, linking each new claim to the source note. If it disagrees with another source, say so on the page and give both. If it answers an open question, update that question page.
6. **Update** `wiki/index.md` for any new page, and add a line at the top of `wiki/log.md`: `YYYY-MM-DD: Added source: <title>. Updated: <pages>.`
7. **Tell the user** what changed, and what's still unknown.
