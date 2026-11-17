# Contributing

Thanks for helping make information easier to understand across technology, education, finance, law, health, public services, and everyday life. Contributions can be small: a clearer sentence, a reviewed explanation, a terminology suggestion, or feedback from readers.

## Ways to contribute

- Suggest or improve a Hinglish explanation.
- Review a contribution for technical accuracy and readability.
- Share common English technical terms and how Hindi-speaking audiences use them.
- Report wording that is confusing, too formal, or tied to a particular regional usage.
- Research an upstream project's locale policy, translation channel, and content license; record findings in [PROJECTS.md](PROJECTS.md).

## Before submitting

1. Read the [Hinglish language guide](LANGUAGE_GUIDE.md).
2. Preserve the source's intended sense, voice, and tone rather than its exact word order. Adapt idioms naturally while keeping all facts, warnings, and limitations; do not add emphasis or certainty that is not in the source.
3. If translating existing material, include its source URL, license, and the exact passage or version you worked from. Only contribute text you have permission to adapt.
4. Add a short note describing the intended audience, domain, and any terminology choices that may not be obvious.
5. For legal, health, safety, financial, or other high-impact topics, identify what needs qualified domain review. A language review is not professional advice or validation.

Please be respectful when discussing language. A suggestion can be useful without being the only valid way to express an idea. This project is not about judging anyone's Hindi, English, or dialect.

## Proposing a change

Open a GitHub issue to discuss a larger proposal or a term that needs community input. For a focused wording change, open a pull request with the text and a brief explanation of what it improves. Keep examples and their technical claims clearly sourced or flagged for review.

GitHub provides a translation form, a terminology form, and a pull request checklist for contributions. The contribution process will evolve as the project grows.

## Coordinating concurrent contributors and agents

Clones are independent, but two people can still duplicate a translation or conflict while editing shared files. Use one GitHub issue for each upstream source unit (for example, one article section or a small group of related UI strings).

1. Search open and closed issues for the upstream project and exact source URL before creating a task. Reuse an existing issue when it covers the same passage.
2. Record the source revision, exact scope, audience, accepted-locale evidence, translation channel, and content license in the issue. Use the `Upstream localization task` issue form.
3. Have one contributor assigned to the task issue at a time. Do not prepare an upstream-derived translation until the task is assigned and the source, locale policy, and rights checks are clear. Others may review or do separate research, but should coordinate in the issue before drafting overlapping text.
4. Work on a separate branch named `translation/<issue-number>-<short-name>`. Do not work on `main`, reuse another person's branch, or force-push shared work.
5. Before opening a pull request here, check that the issue is still assigned to you, the source has not changed, and no overlapping pull request has appeared. Link the task issue and update only the relevant tracker row in your branch.
6. Treat `PROJECTS.md` as an aggregate status tracker, not a locking mechanism. Link active task issues there through a pull request; do not use simultaneous direct edits as claims.

If the issue assignment, source revision, or ownership is ambiguous, pause and ask in the task issue. External upstream actions remain subject to the approval gate below.

## Contributing to another project

Before translating upstream material, check its current contribution guide, accepted language variants, preferred translation channel, and the license for the exact content. Do not assume a repository's software license covers its documentation or other assets. If Hinglish is not an accepted locale, ask maintainers before preparing a contribution.

Agents may research upstream projects and prepare local drafts. They must not publish a fork, push a branch, open a pull request or issue, post comments, or contact maintainers until a human approves the specific target and exact proposed external action. For law, health, finance, safety, and other high-impact subjects, obtain qualified review before upstream submission.