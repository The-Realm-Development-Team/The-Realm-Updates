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

Responsible human: [name or Unassigned]

## Summary

[Before: the problem. After: what changes for players or staff.]

## Changes and approach

- [Meaningful change and why this approach fits.]

## Components and versions

[Affected components, build versions and companion PRs. Use Unknown when needed.]

## Verification

[Environment and build; scenario; expected result -> observed result.]

Status: [Passed / Failed / Not run / Not applicable]

Checked by: [human or agent; identify which]

Evidence: [link to detailed results, if available]

Remaining gaps: [unverified behavior and reason, or None]

## Try it yourself

[Starting conditions -> steps -> what you should see, or Not applicable.]

## Risks and release

[Known risks / No known risks / Unknown.]

[Release order, owner and rollback or recovery, or Not applicable.]

## Related work and release note

[Full issue links; one user-facing sentence, if applicable. Otherwise None.]
