# Upstream Project Tracker

This is a researched watchlist, not an endorsement or a claim that these projects have accepted Hinglish. It is intentionally limited to projects where translation or learning content may be relevant. Star counts are a snapshot from GitHub on 2026-11-17, sorted within this list; stars are not a measure of quality or permission to contribute.

## Current work

| State | Count | Notes |
| --- | ---: | --- |
| Researching | 4 | Candidate policies and Hinglish locale fit are not yet confirmed. |
| Ready to draft | 0 | No candidate has cleared all policy, language, and content-license checks. |
| Local draft / review | 0 | No upstream source text is currently being translated. |
| Upstream PR open / merged | 0 | No external contributions have been submitted. |

## Candidate projects

| Rank by stars | Project | Domain | Stars (2026-11-17) | Status | Translation fit and next check |
| ---: | --- | --- | ---: | --- | --- |
| 1 | [freeCodeCamp/freeCodeCamp](https://github.com/freeCodeCamp/freeCodeCamp) | Education, software | 459,234 | Researching | The repository describes separate software and content licensing. Verify the exact curriculum content license and whether its contribution channel accepts a distinct Hinglish variant before drafting. |
| 2 | [oppia/oppia](https://github.com/oppia/oppia) | Education | 6,996 | Researching | Repository has translation-related contribution systems. Verify whether adding a Hinglish variant is supported and use the project's designated workflow rather than assuming a source PR is appropriate. |
| 3 | [ethereum/ethereum-org-website](https://github.com/ethereum/ethereum-org-website) | Finance, public education | 6,004 | Researching | Verify the current translation platform, locale acceptance, and the license for the exact educational content. The repository's software license alone is not sufficient. |
| 4 | [mdn/translated-content](https://github.com/mdn/translated-content) | Technology education | 2,047 | Researching | Maintains translated documentation and asks contributors to be fluent in the target locale. Check whether maintainers accept Hinglish as a distinct variant; do not overwrite or relabel Hindi content. Verify `LICENSE.md` and source-page rights. |
| 5 | [microsoft/PowerToys](https://github.com/microsoft/PowerToys) | Software utilities | 109,000 | **Paused** | Microsoft internal localization only: "For localization issues, please file an issue to notify our internal localization team, as community PRs for localization aren't accepted. Localization is handled exclusively by the internal Microsoft team." This project does not accept community-contributed translations. |
| 6 | [twentyhq/twenty](https://github.com/twentyhq/twenty) | CRM | 30,000 | **Paused** | Uses CrowdTran for translations: "Thanks to these amazing services that we use... translating (Crowdin)". Community translations must go through the CrowdTran interface rather than GitHub PRs. Does not accept direct upstream contributions via this repository. |
| 7 | [odoo/odoo](https://github.com/odoo/odoo) | ERP/CRM | 42,000 | **Researching** | Large open source business app suite. Needs investigation: Does Odoo accept community translations via its official Transifex/Launchpad pipeline? Need to verify if Hinglish is an accepted locale in Odoo's translation infrastructure. |
| 8 | [flutter/flutter](https://github.com/flutter/) | Mobile SDK | 150,000 | **Researching** | Large open source SDK for mobile/web/desktop apps. Requires verification: Does Flutter's localization system (pub.dev/packages/intl, community contributions) accept Hinglish as a valid locale for translation contributions? Must check community contribution workflow for Flutter's docs/translations. |

Ranks are only among the projects in this watchlist, not a global GitHub ranking. Recheck counts and all upstream rules before work; repositories and policies change.

## Not aligned

| Project | Status | Reason |
| --- | --- | --- |
| [byteom/hinglish-AI-translator](https://github.com/byteom/hinglish-AI-translator) | Not aligned; do not translate against this style | Its README describes Hinglish as Hindi written in English letters, while this project uses Hindi in Devanagari with useful English terms. Its GitHub license metadata reports `NOASSERTION`; inspect the license before adapting any of its content. |

## Work states

- **Researching**: checking current maintainers' rules, accepted language variants, translation channel, and content rights.
- **Ready to draft**: all checks are clear; no source text has been translated yet.
- **Local draft / review**: a small translation exists in this repository and awaits linguistic/domain review.
- **Upstream PR open**: a human approved the exact change and it was submitted; include the PR URL and date.
- **Merged**: upstream merged it; include the PR URL.
- **Paused**: work is blocked or waiting for maintainers/community input; state why.
- **Not aligned**: the project's language model or contribution process conflicts with this project's approach.

When changing a status, update the row with the date, evidence link, owner/reviewer if known, active task issue when applicable, and next action. The issue assignment is the task claim; this table is only an aggregate status view. Update it through a branch and pull request. Do not mark a project ready based on stars or general repository licensing alone. Do not count local drafts as upstream contributions.

## Future domains

Law, health, public services, and other high-impact areas have no approved upstream targets yet. Add a project only after checking jurisdiction or audience, source rights, accepted language variant, and qualified reviewer availability. A translation must not imply professional advice or legal equivalence.