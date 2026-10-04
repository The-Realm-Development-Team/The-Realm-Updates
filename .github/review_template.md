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

WHERE TO VERIFY (when applicable)
Website: browser workflow and permissions.
Discord: test guild, allowed/denied roles and retries.
Launcher: install, update, interrupted download and version compatibility.
Game/server: approved debug environment, reconnect, concurrent players and persistence.
If a required check cannot run, record why and who can unblock it.
-->

Responsible human: [name or Unassigned]

## Recommendation

[Approve / Request changes / Comment; one clear reason.]

## Review coverage

[Code inspected; behavior tested; environment and build. Identify the reviewed PR revision.]

## Findings

[Blocking / Suggestion]

[Location; trigger; consequence; requested change.]

<!-- Repeat for each actionable finding. Say No actionable findings when there are none.
Distinguish observed behavior from source reasoning or an unconfirmed concern. -->

## Verification gaps

[Important behavior still unverified; reason and owner, or None.]

<!-- Say plainly when no tests were executed. -->
