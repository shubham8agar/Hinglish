---
name: hinglish-localization
description: 'Create, translate, localize, or review Hinglish content across technology, education, finance, law, health, public services, and other domains. Use Hindi in Devanagari with useful English terms; research upstream projects, licenses, and contribution rules before proposing translations.'
---

# Hinglish Localization

Help readers understand information directly in a natural Hindi-and-English register, without requiring a mental English-to-Hindi translation step. Follow this project's Devanagari Hindi plus useful English terminology approach. This is a working standard, not a claim that one style represents every Hindi speaker.

## Use this skill for

- Creating original Hinglish explanations, translations, summaries, interface text, and learning material.
- Reviewing terminology and clarity for a stated audience, region, and domain.
- Finding public projects that might welcome Hinglish localization and preparing small contribution proposals.
- Updating this repository's project queue and reporting contribution status.

## Start-up procedure

1. Read the root `AGENTS.md`, `PROJECTS.md`, `CONTRIBUTING.md`, `LANGUAGE_GUIDE.md`, and `TERMINOLOGY.md`.
2. If asked to start without a named task, review `PROJECTS.md` and the local plans under `plans/`; prefer the highest-priority project with a concrete plan. Stars are a discovery signal, not a quality or suitability score.
3. For each selected planned project, the default demonstration is a Hinglish translation of its full primary `README.md` (or equivalent landing README), not an arbitrary paragraph. The goal is to show a practical sample and request support, not to claim Hinglish is standardized or already accepted by the project.
4. Verify the exact README content license and the project's contribution/translation channel. Search open and closed issues and pull requests for Hinglish support or overlapping README work. Record the source URL/revision, license, audience, review needs, and channel in the local plan.
5. A support request filed in this repository is intake only; it is not target approval or a task assignment. If Hinglish is not accepted or its status is unclear, prepare a separate target-specific issue proposal asking maintainers whether they will support Hinglish and accept a README sample. Get user approval for that exact issue before posting it. Do not translate upstream text until the relevant target task issue is assigned to you; also obtain any separate maintainer approval required by the target. If rights or a suitable contribution channel are unclear, continue research or pause without drafting adapted text.

## Drafting and review

1. Write Hindi in Devanagari using natural Hindi sentence structure. Keep English terms, product names, commands, and standard abbreviations when readers are likely to encounter them that way.
2. Translate the source's intended sense and effect, not its word order. Preserve voice, tone, emphasis, politeness, humor, and emotional weight where they matter. Adapt idioms naturally; do not add claims, urgency, reassurance, or certainty absent from the source. If context leaves an ambiguity, flag it instead of guessing. Explain unfamiliar terms briefly and record regional alternatives when relevant.
3. Preserve the source's meaning, facts, units, numbers, uncertainty, warnings, exceptions, formatting, links, identifiers, placeholders, and accessibility text.
4. Tailor terminology and review to the domain. Do not turn a translation into new professional advice.
5. Self-review with `LANGUAGE_GUIDE.md`; record specialist review required for high-impact content.
6. Once assigned and any required maintainer approval is in place, keep the full README translation and source notes local until reviewed. Then prepare a focused sample PR that links the support issue and clearly labels the translation as a proposal, not an accepted/official localization. Follow the target's designated channel; do not submit community PRs where prohibited.
7. Before any external issue or PR, present the exact target and proposed text/change and obtain user approval for that specific action; issue approval does not automatically approve a later PR. For upstream translation work, use the target's required issue-specific branch (for example, `translation/<issue-number>-<short-name>`). These upstream issue and branch rules do not apply to this repository's own documentation or agent instructions.
8. Keep `PROJECTS.md` status current, distinguishing research, local draft/review, support issue, PR, merged, paused, and not aligned. Never label a draft as accepted or merged without evidence.

## Source accuracy and translation provenance

- If a source appears illogical, contradictory, or factually wrong, do not silently fix it or present the translation as verified. Flag the suspected source issue separately, with evidence when available, and ask for human review. Pause publication when the issue could materially mislead readers or cause harm; high-impact material also needs qualified review.
- Every published translated page must carry a short translation notice linking to a version-controlled provenance record in this repository. The record must identify the source URL and exact revision/commit (or say when unavailable), the source-check time, the translation time in ISO 8601 UTC, review status, and unresolved source concerns. Link to the immutable repository commit containing the record when available; do not imply independent fact-checking.
- Follow the target project's rules. If it does not permit the notice or repository link, keep the translation and notice in a local draft and ask the user before proposing publication without them. Never add unauthorized content to an upstream page.

## Domain safeguards

- Finance: preserve rates, fees, dates, eligibility, risk disclosures, and uncertainty. Do not imply investment, tax, or credit advice.
- Law and public policy: preserve jurisdiction, definitions, deadlines, exceptions, and citations. Do not imply legal advice or legal equivalence; require qualified review.
- Health and safety: preserve units, contraindications, warnings, and emergency steps. Require qualified subject-matter review before publication.
- Software and technical content: preserve code, commands, UI labels, placeholders, version references, and security warnings.
- Education and general information: explain concepts without talking down to readers or assuming English fluency.

## Upstream project checks

Before proposing work for another repository, verify its current contribution guide, accepted locale or language-variant policy, translation channel, source revision, and license for the exact content. A software license does not necessarily cover documentation, artwork, datasets, or other content. Do not impose this project's style on an upstream community that has not accepted it.

## External-action approval gate

The agent may research public repositories, inspect public source read-only, draft translations locally, run checks, and update this repository's queue. It must not publish a fork, push a branch, open an issue or pull request, post comments, or contact maintainers unless the user approves that specific external action and the exact proposed change. Before requesting approval, present the target repository, source and license, translation, checks, and intended action. Never claim a contribution was sent or accepted until verified.