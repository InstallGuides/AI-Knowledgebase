---
name: check-the-wiki
description: Check the wiki's health and report problems: pages missing from the index, claims without a source, broken links, source notes without a source page, and pages past their review date. Use when the user says "check the wiki", "audit the wiki", or before sharing it.
---

# Check the wiki

Read `3-specifications/page-rules.md` first. Then check, and list every problem with its file:

1. **The index:** every page in `wiki/topics/`, `wiki/questions/` and `wiki/sources/` is listed in `wiki/index.md`.
2. **Sources:** every claim on a topic or question page links a note in `1-research/`, or `0-project-management/mission.md` for the group's own plans.
3. **Links:** every link between files points to a file that exists.
4. **Source pages:** every note in `1-research/` has a page in `wiki/sources/` with the same slug.
5. **Review dates:** check today's date with `date`, and list pages whose `**Review by:**` date has passed.
6. **Open questions:** list question pages still marked open, as a reminder.

**Report first; fix only when the user agrees.** Then add a line at the top of `wiki/log.md`: `YYYY-MM-DD: Checked the wiki: <what was found and fixed>.`
