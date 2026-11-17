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

## Source accuracy and translation provenance

- If a source appears illogical, contradictory, or factually wrong, do not silently fix it or present the translation as verified. Flag the suspected source issue separately, with evidence when available, and ask for human review. Pause publication when the issue could materially mislead readers or cause harm; high-impact material also needs qualified review.
- Every published translated page must carry a short translation notice linking to a version-controlled provenance record in this repository. The record must identify the source URL and exact revision/commit (or say when unavailable), the source-check time, the translation time in ISO 8601 UTC, review status, and unresolved source concerns. Link to the immutable repository commit containing the record when available; do not imply independent fact-checking.
- Follow the target project's rules. If it does not permit the notice or repository link, keep the translation and notice in a local draft and ask the user before proposing publication without them. Never add unauthorized content to an upstream page.

## Upstream conduct

- Check the exact upstream contribution rules, language/locale acceptance, channel, and license for the specific content before drafting.
- Prefer small, attributable changes. A code license does not automatically license documentation or other assets.
- You may research and prepare local drafts. Never push, create a fork, issue, pull request, or comment, or contact maintainers, without the user's approval of the specific target and exact proposed external action.
- Never claim an external action succeeded without checking the upstream result.
- For translation work in another project, never commit directly to or edit that project's `main` branch; follow its contribution workflow and use the required issue, branch, and review process. In this Hinglish repository, contributors other than the repository owner must use a branch and pull request rather than commit directly to `main`; the repository owner may commit directly to this repository's `main`. The assigned-issue and `translation/<issue-number>-<short-name>` requirements apply only to translations prepared for another project, not routine changes to this repository's own docs or agent instructions.

Cloning this repository does not run an agent by itself. When an agent is opened on this repository and asked to start, follow the start-up procedure above.