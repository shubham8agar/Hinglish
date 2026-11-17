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
2. If asked to start without a named task, review the candidate queue in `PROJECTS.md`. Prefer the highest-starred candidate that also has a compatible language policy, a clear contribution channel, and compatible content reuse terms. Stars are a discovery signal, not a quality or suitability score.
3. If no candidate is cleared, do read-only research and update the status to `Researching` or explain the blocker. Do not invent an accepted locale, license, or maintainer approval.
4. Choose a small source unit (for example, one short paragraph, one help article section, or a few interface strings). Record the source URL, source revision, repository and content license, target audience, and translation channel in the proposal.
5. Before drafting, search open and closed task issues for the same project and source unit. Use one assigned issue per source unit as the coordination claim; do not draft overlapping upstream-derived text when another contributor owns that task.

## Drafting and review

1. Write Hindi in Devanagari using natural Hindi sentence structure. Keep English terms, product names, commands, and standard abbreviations when readers are likely to encounter them that way.
2. Translate the source's intended sense and effect, not its word order. Preserve voice, tone, emphasis, politeness, humor, and emotional weight where they matter. Adapt idioms naturally; do not add claims, urgency, reassurance, or certainty absent from the source. If context leaves an ambiguity, flag it instead of guessing. Explain unfamiliar terms briefly and record regional alternatives when relevant.
3. Preserve the source's meaning, facts, units, numbers, uncertainty, warnings, exceptions, formatting, links, identifiers, placeholders, and accessibility text.
4. Tailor terminology and review to the domain. Do not turn a translation into new professional advice.
5. Self-review with `LANGUAGE_GUIDE.md`; record specialist review required for high-impact content.
6. Put drafts and source notes in this repository until a human has reviewed them. Keep `PROJECTS.md` status current; never label a draft as accepted or merged without evidence.
7. For translations prepared for another project, work on a dedicated branch named `translation/<issue-number>-<short-name>`. Recheck issue ownership, source revision, and overlapping pull requests before proposing changes. Update the shared tracker only in the same branch and pull request as the related work. These upstream issue and branch-name requirements do not apply to routine changes to this repository's own docs or agent instructions; follow this repository's contribution process instead.

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