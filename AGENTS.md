# Agent Instructions

This repository develops a practical Hinglish writing standard and drafts small, well-sourced localization contributions across domains, not only technology.

## Start every task

- Read `PROJECTS.md`, `CONTRIBUTING.md`, `LANGUAGE_GUIDE.md`, `TERMINOLOGY.md`, and relevant examples in `EXAMPLES.md` before selecting or translating upstream content.
- For Hinglish writing or localization work, load `.agents/skills/hinglish-localization/SKILL.md`.
- If asked to `start` without a named task, review the candidate queue in star order, then independently verify the candidate's current language-variant policy, translation channel, and license for the exact source content. Prepare a small local draft only after those checks clear; record its source revision, audience, and review needs. If no candidate is cleared, update its status to `Researching` or `Paused`, summarize the blocker, and propose the next compliant research step without drafting upstream-derived text.
- Keep `PROJECTS.md` accurate: distinguish research, local draft, human review, upstream PR, merged, paused, and not aligned. Record when star counts were checked.
- Before drafting an upstream passage, check open localization issues for the same project and source unit. Work only on a task issue assigned to you; follow the branch and tracker coordination rules in `CONTRIBUTING.md`.

## Language and domain

Use Hindi in Devanagari with useful English terms, following `LANGUAGE_GUIDE.md`. This project covers technology, education, finance, law, health, public services, and other subjects. Preserve the source's meaning, detail, warnings, units, uncertainty, and formatting. Do not present translations as professional advice or verified without qualified review where required.

## Upstream conduct

- Check the exact upstream contribution rules, language/locale acceptance, channel, and license for the specific content before drafting.
- Prefer small, attributable changes. A code license does not automatically license documentation or other assets.
- You may research and prepare local drafts. Never push, create a fork, issue, pull request, or comment, or contact maintainers, without the user's approval of the specific target and exact proposed external action.
- Never claim an external action succeeded without checking the upstream result.
- Work on a dedicated branch and propose changes to this repository through a pull request; never commit directly to `main` or edit another contributor's branch.

Cloning this repository does not run an agent by itself. When an agent is opened on this repository and asked to start, follow the start-up procedure above.