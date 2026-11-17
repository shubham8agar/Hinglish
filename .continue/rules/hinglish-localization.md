# Hinglish Localization

Apply these project rules in Continue Agent, Chat, and Edit modes, regardless of whether the selected model is local or hosted through OpenRouter.

## Project workflow

- For localization or upstream research, follow the canonical workflow in `.agents/skills/hinglish-localization/SKILL.md` and read the root `AGENTS.md`, `PROJECTS.md`, `CONTRIBUTING.md`, `LANGUAGE_GUIDE.md`, `TERMINOLOGY.md`, and relevant `EXAMPLES.md` entries.
- Translate the source's intended sense, voice, and effect, not its word order. Use Hindi in Devanagari with useful English terms; preserve facts, names, figures, units, warnings, qualifications, formatting, and uncertainty. Flag ambiguity instead of guessing.
- Before upstream-derived drafting, verify the exact source revision and content license, accepted Hinglish variant, contribution channel, and whether another contributor has claimed the same source unit in an issue. Follow the issue assignment and branch rules in `CONTRIBUTING.md`.
- For law, finance, health, safety, and other high-impact material, require qualified subject-matter review. A translation is not professional advice.

## Model and tool limits

- Local and OpenRouter models vary in reasoning, context size, and tool-calling support. Do not assume a model can browse, inspect files, or run terminal commands just because Continue is in Agent mode.
- Use only tools actually exposed by the current Continue mode. If a necessary tool is unavailable or a call fails, stop that part of the task and report the limitation. Never invent command output, test results, repository facts, or successful actions.
- Before a shell command, confirm the active shell and working directory. Use WSL/Linux commands only in WSL; do not assume Windows Bash provides Linux utilities. Prefer read-only, scoped commands. Explain and obtain approval before destructive changes, privileged commands, package installation, or actions outside this repository.
- Never read, print, copy, or commit API keys, tokens, passwords, private keys, or personal Continue configuration. Keep secrets in the user's secret store or environment, not project files.
- Treat model-generated translations and technical explanations as drafts. Check them against the source and project guide; identify domain claims needing human or specialist review.

## External actions

Do not fork, push, open upstream issues or pull requests, post comments, or contact maintainers unless the user approves the exact target and proposed action. Prepare local drafts and approval details first, as required by the canonical skill.