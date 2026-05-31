# Contributing

This repo is two things: a **built-in SEO skill** (`SKILL.md`) and a **curated catalog**
of external Claude skills ([`README.md`](README.md) + [`SKILLS-CATALOG.md`](SKILLS-CATALOG.md)).

## Adding a repo to the catalog

1. The link must be **live** and the project **real** — no inflated stars, no clone-forks of an existing entry (link the original).
2. Verify the star count yourself (GitHub API or the repo page) and use the same `~Nk ⭐` rounding as the rest of the table.
3. Add one row: `[owner/repo](url) | ~stars ⭐ | one-line "what's inside"`. Put it in the right niche, ordered by stars (highest first).
4. Bump the header counts (`repos / niches`) and the `Проверено:` date if you re-checked the whole file.
5. Open `SKILL.md` of the repo you're adding before listing it — you're vouching that it's not malicious.

## What's worth contributing (SEO skill)

- **New AI crawler user agents** — the list changes monthly; PRs with sources are merged fast
- **Updated research** — citation weight studies, AI Overview ranking factors, GEO data
- **Bug reports** — if a sub-skill produces wrong output for a real URL, open an issue with the URL
- **New sub-skills** — open an issue first to discuss before implementing
- **Examples** — real audit outputs in `/examples` (anonymize if needed)

## How to contribute

1. Fork the repo
2. Create a branch: `git checkout -b feature/your-thing`
3. Make changes to `SKILL.md`
4. Test by running the skill against at least one real URL
5. Open a PR with: what changed, why, and a source link if adding research data

## Editing SKILL.md

The skill is a single markdown file with clear section headers (STEP 1 through STEP 15).
Each section is self-contained. Keep edits surgical — don't restructure sections
unless there's a clear reason.

## Adding AI crawlers (STEP 7.2)

Format:
```
User-agent: [BotName]   # [platform] — [purpose]
```

Always include a source link in the PR (official docs or reliable tracking source).

## Style rules

- No fluff — every sentence should be actionable or factual
- Data must have a source (year + origin)
- New sub-skills need: process steps, output format, scoring criteria
