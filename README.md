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

To request a Hinglish sample for another project, open a [Hinglish support request](https://github.com/shubham8agar/Hinglish/issues/new?template=hinglish-support-request.yml) here. This starts intake, not upstream approval. After the minimum rights/channel/duplicate checks and an assigned target task, the first deliverable is the README content translated into Hinglish; license text is left unchanged.

## Work with an agent

This repository includes shared instructions for Continue, Codex, Claude Code, and GitHub Copilot. Continue loads its project rules from [`.continue/rules/hinglish-localization.md`](.continue/rules/hinglish-localization.md); the other clients use their respective project instructions and the shared localization skill. Clone and open the repository in a supported agent, then ask it to `start` or name a project. For a selected project with a local plan, the agent should do only the blocking checks—README content reuse rights, contribution channel, duplicate work, and task assignment—then translate the README content as the first deliverable. License text and legal notices stay unchanged. Hinglish does not need to be accepted beforehand: the sample PR can ask maintainers to list/support it. A support-request issue filed here is intake only. External comments, pushes, issues, and pull requests still require your explicit approval of each exact action.

The rules are model-provider-neutral and can guide Continue with local or OpenRouter models. Tool execution depends on the selected model and Continue mode: use only tools actually exposed to the agent, never treat generated text as command output, and report when a model cannot call a required tool. Review model-generated translations, especially for high-impact subjects.

The [upstream project tracker](PROJECTS.md) records project status, research, and next steps. For a selected project with a local plan, the default first contribution is a Hinglish translation of its full primary README in the target's locale structure. The PR demonstrates the sample and asks maintainers to list/support Hinglish; it does not claim Hinglish is standardized or already accepted. If the PR is merged and the project lists Hinglish as supported, continue with additional pages through the accepted workflow.

## Working in parallel

Each upstream README sample is coordinated through a task issue assigned to the contributor, and contributors use the target project's required branch and review workflow. Check [Contributing](CONTRIBUTING.md) before starting; the project tracker is an overview, not a lock, so it is updated through this repository's contribution workflow.

## Agent skill

The project provides the same portable Agent Skill for Codex, Claude Code, and GitHub Copilot. The canonical file is [`.agents/skills/hinglish-localization/SKILL.md`](.agents/skills/hinglish-localization/SKILL.md); identical copies are kept in `.claude/skills/` and `.github/skills/` so each agent can discover it in its native project location. Keep all three copies in sync when editing the skill.

## Get involved

You can contribute by sharing clear examples, reviewing technical accuracy, suggesting commonly used terms, or pointing out wording that feels unnatural to its intended readers. Please include context for terminology choices; the project should be guided by how people actually understand and use language.

## Project status

This repository is an early community foundation. Its conventions are open to discussion and improvement. There is no single official Hinglish vocabulary, and the project does not claim to represent every Hindi speaker or regional variety.