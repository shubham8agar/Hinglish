# Contributing

Thanks for helping make information easier to understand across technology, education, finance, law, health, public services, and everyday life. Contributions can be small: a clearer sentence, a reviewed explanation, a terminology suggestion, or feedback from readers.

## Ways to contribute

- Suggest or improve a Hinglish explanation.
- Review a contribution for technical accuracy and readability.
- Share common English technical terms and how Hindi-speaking audiences use them.
- Report wording that is confusing, too formal, or tied to a particular regional usage.
- Request investigation of Hinglish support for an upstream project through the [Hinglish support request form](https://github.com/shubham8agar/Hinglish/issues/new?template=hinglish-support-request.yml).
- Research an upstream project's locale policy, translation channel, and content license; record findings in [PROJECTS.md](PROJECTS.md).

## Before submitting

1. Read the [Hinglish language guide](LANGUAGE_GUIDE.md).
2. Preserve the source's intended sense, voice, and tone rather than its exact word order. Adapt idioms naturally while keeping all facts, warnings, and limitations; do not add emphasis or certainty that is not in the source.
3. If translating existing material, record its source URL, the license that permits adapting the content, and the exact passage or version you worked from. Translate the content, not the license: preserve license/legal notices, identifiers, and required attribution unchanged.
4. Add a short note describing the intended audience, domain, and any terminology choices that may not be obvious.
5. For legal, health, safety, financial, or other high-impact topics, identify what needs qualified domain review. A language review is not professional advice or validation.

Please be respectful when discussing language. A suggestion can be useful without being the only valid way to express an idea. This project is not about judging anyone's Hindi, English, or dialect.

## This repository and upstream projects

The assigned task issue, source-unit coordination, and `translation/<issue-number>-<short-name>` branch requirements below apply only when preparing a translation for another project. They do not require an upstream issue number for routine changes to this repository's own documentation, agent instructions, or original examples. For changes to this repository, use the contribution process described here; external changes to another project still require approval for the specific target and action.

## Translation accuracy and provenance

Do not silently correct a source while translating it. If it appears illogical, contradictory, or factually wrong, flag the concern separately and ask for human review; pause publication if it could materially mislead readers or cause harm. Do not describe a translation as independently verified unless it has been checked and that review is recorded.

Keep one version-controlled provenance record per translated source unit alongside its local draft. Every published translated page should include a brief notice linking to that record, preferably through an immutable repository commit permalink. Include:

- The source title and URL, exact source revision/commit (or state that it is unavailable), and when the source was checked.
- The translation timestamp in ISO 8601 UTC, such as `2026-11-17T09:45:00Z`.
- Review status and any unresolved source concerns. The immutable repository permalink identifies the commit containing the record; do not put that same commit's hash inside its own record.

Suggested notice:

> Translation notice: This is a Hinglish translation of [source title] ([source URL]), based on source revision [revision or “unavailable”] checked at [UTC time]. Translation prepared at [ISO 8601 UTC time]. This is not an independent fact-check. See the [provenance record](repository URL) for the source, commit, and review status.

Do not invent revision IDs, timestamps, review status, or commit hashes. If the target project's rules do not allow this notice or link, keep the translation and notice as a local draft and ask the user before proposing publication without them.

## Proposing a change

Open a GitHub issue to discuss a larger proposal or a term that needs community input. For a focused wording change, open a pull request with the text and a brief explanation of what it improves. Keep examples and their technical claims clearly sourced or flagged for review.

Contributors other than the repository owner must use a branch and pull request for changes to this repository; they must not commit directly to `main`. The repository owner may commit directly to this repository's `main`. This exception applies only to this repository and does not override another project's contribution rules.

GitHub provides a [Hinglish support request form](https://github.com/shubham8agar/Hinglish/issues/new?template=hinglish-support-request.yml) for intake, an upstream localization task form for assigned research/translation work, a translation form, a terminology form, and a pull request checklist. The contribution process will evolve as the project grows.

## Requesting Hinglish support for another project

Start with a **Hinglish support request** issue in this repository when a reader requests localization. It is intake and prioritization, not an issue in the target project and not approval to publish. For a selected project, keep upstream research focused on blockers: verify reuse rights for the README content, the contribution channel, and duplicate or claimed work; the license itself is never translated.

Do not wait for Hinglish to be listed as a supported language before starting the sample. Use an existing target task issue or propose one target issue that asks maintainers to add/support Hinglish and defines the full primary README as the sample task; avoid a separate support issue unless the target requires it. Obtain user approval before posting the exact issue, then wait for that target task issue to be assigned to you and get any other approval the target requires. Once assigned, translate the full README locally as the first deliverable and prepare a focused PR that presents it as a sample and asks maintainers to list/support Hinglish.

Keep the original-language README intact; place the translation in the target's documented locale structure. Translate the README content, not its license or legal notices; preserve required license notices and attribution unchanged. If the target does not accept PRs for translations, use its designated platform. If the README content's reuse rights or contribution channel blocks the sample, record the reason and pause instead of doing research indefinitely. A sample is a proposal, not a claim that Hinglish is standardized or already accepted.

Submitting an intake issue does not authorize an external issue or PR. Obtain the user's approval for the exact target issue and the later PR separately. If the sample PR is merged and maintainers list Hinglish as supported, update the tracker and continue with additional pages through the project's accepted workflow.

## Coordinating concurrent contributors and agents

This section applies to translation proposals for another project, not routine maintenance of this repository. Our working style is sample-led: for each selected project with a local plan under `plans/`, translate the full primary `README.md` (or equivalent landing README) as the first contribution and use the PR to propose Hinglish support. This demonstrates the approach; it does not claim Hinglish is a standardized language variety or already accepted by that project.

1. Verify that the README content's license/reuse terms permit adaptation and check the project's contribution/translation channel. A software license does not necessarily cover README text; do not translate license text. Search open and closed issues and pull requests for overlapping work.
2. Record the README URL/revision, reuse rights, current Hinglish policy or lack of one, audience, review needs, and required channel in the local plan. Do not represent an unaccepted locale as official.
3. Use the existing target task issue, or propose one combined target task/support issue if none exists. Search for overlaps, obtain the user's approval for the exact issue, and get assigned before drafting upstream text. Obtain any additional maintainer approval required by the project.
4. Once assigned, translate the README content as the first deliverable, leaving license text and notices unchanged. Keep the original README intact; use the target's documented locale structure and add provenance when allowed. Review it, then prepare a focused PR asking maintainers to list/support Hinglish. The PR is a sample proposal, not an accepted/official localization. Do not wait for locale acceptance before preparing the sample; use another channel or pause only if the target's rules require it.
5. Before any external issue or PR, present the target, exact proposed text/change, and relevant checks to the user and obtain approval for that specific action. An issue approval does not by itself approve a later PR. Never push or contact maintainers without this approval.
6. For upstream work, use the required issue-specific branch (`translation/<issue-number>-<short-name>` when applicable); do not work on the target project's `main`, reuse another person's branch, or force-push shared work.
7. Recheck assignment, source revision, and overlapping work before submitting. Update this repository's `PROJECTS.md` only through its contribution workflow; it is an aggregate tracker, not a lock.

If the issue assignment, source revision, or ownership is ambiguous, pause and ask in the task issue. External upstream actions remain subject to the approval gate below.

## Contributing to another project

Before translating upstream material, check its contribution guide, preferred translation channel, and the license for the exact content. Do not assume a repository's software license covers its documentation. Hinglish acceptance is not a prerequisite when the PR itself proposes support, but the task issue must be assigned to you and any required maintainer authorization obtained. Do not imply the locale is accepted until maintainers confirm it.

Agents may research upstream projects and prepare local drafts. They must not publish a fork, push a branch, open a pull request or issue, post comments, or contact maintainers until a human approves the specific target and exact proposed external action. For law, health, finance, safety, and other high-impact subjects, obtain qualified review before upstream submission.