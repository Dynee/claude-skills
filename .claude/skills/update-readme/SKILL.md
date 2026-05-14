Scan all skill files in this repo and update the README skills table.

Steps:
1. Use the Bash tool to list all directories under `.claude/skills/` in the repo root.
2. For each skill directory, read `.claude/skills/<name>/SKILL.md` and use its first non-empty line as the description.
3. Build a markdown table with three columns: **Skill** (the directory name formatted as inline code), **File** (a markdown link to `.claude/skills/<name>/SKILL.md` with link text `SKILL.md`), and **Description** (the first line of SKILL.md, truncated to a single sentence if needed).
4. Sort rows alphabetically by skill name.
5. Replace the existing table in `README.md` between the `## Current Skills` heading and the next `##` heading (or end of file) with the new table. Use the Edit tool to make this replacement.

Do not modify any other part of README.md. Do not add or remove headings.
