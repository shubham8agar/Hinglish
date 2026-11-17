# Agent Instructions

This repository develops a practical Hinglish writing standard and drafts small, well-sourced localization contributions across domains, not only technology.

## Start every task

- Read `PROJECTS.md`, `CONTRIBUTING.md`, `LANGUAGE_GUIDE.md`, `TERMINOLOGY.md`, and relevant examples in `EXAMPLES.md` before selecting or translating upstream content.
- For Hinglish writing or localization work, load `.agents/skills/hinglish-localization/SKILL.md`.
- If asked to `start` without a named task, review the candidate queue in star order and the local plans under `plans/`; prefer a candidate with a concrete plan. Stars are a discovery signal, not a quality or suitability score.
- For each selected planned project, the default demonstrator is a Hinglish translation of the full primary `README.md` (or equivalent landing README), not an arbitrary paragraph. The goal is to show a practical sample and request Hinglish support, not to claim that Hinglish is standardized or already accepted by that project.
- Treat a Hinglish request issue in this repository as intake only. Before translating, do the minimum blocking checks: verify that the exact README content may be adapted, confirm the project's contribution channel, and search open and closed issues and pull requests for overlapping work. This is a rights check only: translate the README content, never the license text or legal/license notices; preserve required notices and attribution unchanged. Hinglish being unlisted or unrecognized is not by itself a reason to stop; record the current status and present the contribution as a proposal to add support.
- Use an existing target task issue or prepare one target issue that both requests Hinglish support and claims the README sample task; do not open a second support issue unless the target requires separate issues. Do not translate upstream text until the target task issue is assigned to you, and obtain any additional maintainer approval the target requires. If the content rights or available contribution channel block a README PR, explain the blocker and pause.
- Once the task is assigned and any required approval is in place, translate the full primary README as the first deliverable. Record its source URL/revision, content license, audience, and review needs in the local plan. Keep the original-language README intact and use the target's localized-docs structure. Prepare a focused PR with the sample and a request to list/support Hinglish. Use the designated translation channel instead if required; do not submit where community translations are prohibited.
- Once rights, channel, duplicate-work, assignment, and any required maintainer approval checks clear, do not stop at research or wait for Hinglish to be pre-approved: complete the local README translation and PR draft in the same task. After merge, check whether the project lists Hinglish as supported before starting additional pages.
- Keep `PROJECTS.md` accurate: distinguish research, local draft, human review, support issue, upstream PR, merged, paused, and not aligned. Record when star counts were checked.

## Language and domain

Use Hindi in Devanagari with useful English terms, following `LANGUAGE_GUIDE.md`. This project covers technology, education, finance, law, health, public services, and other subjects. Preserve the source's meaning, detail, warnings, units, uncertainty, and formatting. Do not present translations as professional advice or verified without qualified review where required.

## Source accuracy and translation provenance

- If a source appears illogical, contradictory, or factually wrong, do not silently fix it or present the translation as verified. Flag the suspected source issue separately, with evidence when available, and ask for human review. Pause publication when the issue could materially mislead readers or cause harm; high-impact material also needs qualified review.
- Every published translated page must carry a short translation notice linking to a version-controlled provenance record in this repository. The record must identify the source URL and exact revision/commit (or say when unavailable), the source-check time, the translation time in ISO 8601 UTC, review status, and unresolved source concerns. Link to the immutable repository commit containing the record when available; do not imply independent fact-checking.
- Follow the target project's rules. If it does not permit the notice or repository link, keep the translation and notice in a local draft and ask the user before proposing publication without them. Never add unauthorized content to an upstream page.

## Upstream conduct

- Check the exact upstream contribution rules, channel, and reuse rights for the specific content before drafting; record language/locale acceptance status, but do not require prior acceptance for a sample proposal.
- Prefer small, attributable changes. A code license does not automatically license documentation or other assets.
- You may research and prepare local drafts. Never push, create a fork, issue, pull request, or comment, or contact maintainers, without the user's approval of the specific target and exact proposed external action.
- For each selected project, prepare one target task/support-issue proposal locally if none exists; after it is assigned and any required maintainer approval is in place, prepare the README translation and PR locally without waiting for locale acceptance. Before posting an external issue or PR, present the exact target and proposed text/change and obtain the user's approval for that action. A request issue in this repository does not replace the target issue or grant permission.
- Never claim an external action succeeded without checking the upstream result.
- For translation work in another project, never commit directly to or edit that project's `main` branch; follow its contribution workflow and use the required issue, branch, and review process. In this Hinglish repository, contributors other than the repository owner must use a branch and pull request rather than commit directly to `main`; the repository owner may commit directly to this repository's `main`. The assigned-issue and `translation/<issue-number>-<short-name>` requirements apply only to translations prepared for another project, not routine changes to this repository's own docs or agent instructions.

Cloning this repository does not run an agent by itself. When an agent is opened on this repository and asked to start, follow the start-up procedure above.