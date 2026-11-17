# Hinglish Language Project

Hinglish is a community language project for making information easier to understand for people who think and learn in Hindi and English. We develop practical Hinglish examples and standards across technology, education, finance, law, health, public services, and everyday life.

Our writing pairs Hindi in Devanagari with English words and domain terms when those are clearer, widely used, or part of the reader's everyday tools. The goal is not word-for-word translation. It is to explain an idea naturally, without making readers mentally translate every sentence first.

This is a helping hand, not a rule about how anyone should speak. It is one more way to make information, services, and learning resources approachable, especially for Hindi speakers who find English-only material tiring and pure Hindi translations unfamiliar or hard to follow.

## The approach

- Write the Hindi parts in Devanagari.
- Keep useful terms in English when they are familiar or used in the relevant field, such as `Backup`, `Interest Rate`, or `Deadline`.
- Prefer clear, natural sentences over literal translation or unnecessarily formal Hindi.
- Explain unfamiliar technical ideas in context; do not assume that leaving a term in English explains it.
- Keep the meaning accurate. Simpler wording must not remove important details or warnings.
- Choose wording for the intended audience. Hindi varies by region and person, so avoid treating one phrasing as the only correct Hinglish.

## Example

अपनी ज़रूरी फ़ाइलों का Backup हमेशा Cloud Server पर रखें।

More detailed writing conventions and the full sample are in the [Hinglish language guide](LANGUAGE_GUIDE.md). See [Contributing](CONTRIBUTING.md) to suggest an example, improve a translation, or help shape the project.

The [starter terminology list](TERMINOLOGY.md) records example terms and explanations. These are proposals for discussion, not mandatory translations.

See [starter examples](EXAMPLES.md) for short English source sentences paired with draft Hinglish translations.

To request Hinglish support for another project, open a [Hinglish support request](https://github.com/shubham8agar/Hinglish/issues/new?template=hinglish-support-request.yml) here. This starts research only; the target project's own issue, assignment, policy, content rights, and approval still govern any translation or contribution.

## Work with an agent

This repository includes shared instructions for Continue, Codex, Claude Code, and GitHub Copilot. Continue loads its project rules from [`.continue/rules/hinglish-localization.md`](.continue/rules/hinglish-localization.md); the other clients use their respective project instructions and the shared localization skill. Clone and open the repository in a supported agent, then ask it to `start` or name a project. For a selected project with a local plan, the default sample is a translation of its full primary README: first verify source-content rights and the contribution channel, then prepare a target-support issue proposal and seek task assignment before translating. After assignment and any required maintainer approval, the agent prepares the local README sample and linked sample-PR draft. A support-request issue filed in this repo is intake only, not upstream approval. Cloning alone does not run an agent. External comments, pushes, issues, and pull requests require your explicit approval of the exact change.

The rules are model-provider-neutral and can guide Continue with local or OpenRouter models. Tool execution depends on the selected model and Continue mode: use only tools actually exposed to the agent, never treat generated text as command output, and report when a model cannot call a required tool. Review model-generated translations, especially for high-impact subjects.

The [upstream project tracker](PROJECTS.md) records research status, star-count snapshots, contribution fit, and next steps. For a selected project with a local plan, our default demonstrator is a Hinglish translation of its primary README, paired with a proposal asking maintainers to support Hinglish and a sample PR when the project's rules allow it. This is a practical example, not a claim that Hinglish is standardized or already accepted there. Star counts help prioritize discovery; they do not prove quality, permission, or language support.

## Working in parallel

Each upstream README sample is coordinated through a task issue assigned to the contributor, and contributors use the target project's required branch and review workflow. Check [Contributing](CONTRIBUTING.md) before starting; the project tracker is an overview, not a lock, so it is updated through this repository's contribution workflow.

## Agent skill

The project provides the same portable Agent Skill for Codex, Claude Code, and GitHub Copilot. The canonical file is [`.agents/skills/hinglish-localization/SKILL.md`](.agents/skills/hinglish-localization/SKILL.md); identical copies are kept in `.claude/skills/` and `.github/skills/` so each agent can discover it in its native project location. Keep all three copies in sync when editing the skill.

## Get involved

You can contribute by sharing clear examples, reviewing technical accuracy, suggesting commonly used terms, or pointing out wording that feels unnatural to its intended readers. Please include context for terminology choices; the project should be guided by how people actually understand and use language.

## Project status

This repository is an early community foundation. Its conventions are open to discussion and improvement. There is no single official Hinglish vocabulary, and the project does not claim to represent every Hindi speaker or regional variety.