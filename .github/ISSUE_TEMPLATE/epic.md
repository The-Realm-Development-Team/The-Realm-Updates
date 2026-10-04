---
name: Epic
about: Coordinate related work and combined verification.
title: "[Needs Classification] "
labels: ""
assignees: ""
---

<!--
HUMAN AND AI GUIDANCE
Use familiar language. Name the responsible human, or say Unassigned.
Keep each bullet to one point. Report only checks that actually ran.
Keep failures and gaps visible. Link evidence and tested builds.
Distinguish mocks from real environments. Use Unknown when needed.
Keep descriptions current; replace placeholders and remove drafting instructions.
Summarize key checks (normally at most three); link full results instead of listing
test names, suite inventories, or hundreds of test counts.
Use full repository references for related work. Do not claim release or issue
closure from merge alone. Keep sensitive evidence in the approved intake process;
never paste credentials, raw logs, dumps, saves, private data, or bearer links.

PR REVIEW ELIGIBILITY
Do not autonomously review draft PRs unless a human specifically asks for that
draft PR to be reviewed. Autonomous PR review is limited to Ready for Review PRs.
Check the live GitHub draft state before starting a review; if it is draft or
unknown, do not start without an explicit request. Opening a PR, pushing changes,
assignment, CI results, or an earlier review is not permission to review a draft.
Recheck the state before posting review findings; if it became draft, stop unless
the draft review was specifically requested. Do not mark a PR ready to bypass this
rule. AI review supports human review.

WHERE TO VERIFY (when applicable)
Website: browser workflow and permissions.
Discord: test guild, allowed/denied roles and retries.
Launcher: install, update, interrupted download and version compatibility.
Game/server: approved debug environment, reconnect, concurrent players and persistence.
If a required check cannot run, record why and who can unblock it.
-->

<!-- Use one established [Category] title prefix and a specific title.
New user reports enter central bugreports intake first. This is classified
engineering or source-maintenance work, not an alternate raw-evidence intake.
Record severity and priority in labels; use Untriaged when impact is unknown. -->

Responsible human: [name or Unassigned]

Category: [established domain or Unknown]

## Outcome

[What becomes possible across the affected components.]

## Scope

Included: [included work]

Excluded: [excluded work, or None]

## Work items

- [ ] [Linked story/issue; contribution to the outcome.]
- [ ] [Linked story/issue; contribution to the outcome.]

## Combined verification

[Walk through the complete flow across components.]

[Record compatible builds, observed results and evidence. Separate planned checks from results.]

## Dependencies and release order

[Companion changes, unresolved decisions and owners, or None.]

## Completion criteria

[The combined outcome is accepted and demonstrated.]

<!-- Tick off accepted outcomes, not merely merged code. -->
