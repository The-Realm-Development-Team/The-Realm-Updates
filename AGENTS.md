# The Realm: agent instructions

## Team templates and PR review

Do not autonomously review draft PRs unless a human specifically asks for that
draft PR to be reviewed. Autonomous PR review is limited to Ready for Review PRs.
Check the live GitHub draft state before starting a review; if it is draft or
unknown, do not start without an explicit request. Opening a PR, pushing changes,
assignment, CI results, or an earlier review is not permission to review a draft.
Recheck the state before posting review findings; if it became draft, stop unless
the draft review was specifically requested. Do not mark a PR ready to bypass this
rule. AI review supports human review.

An independent local implementation check required by the contribution workflow
is separate from reviewing a published PR. Perform that check on local changes
before opening a PR; it does not authorize reviewing a published draft PR.
Keep existing authorization requirements for marking ready, merging and release.

Use the agreed templates and keep their human and AI guidance in each source:

- [Pull request](.github/pull_request_template.md)
- [Issue](.github/ISSUE_TEMPLATE/issue.md)
- [Story](.github/ISSUE_TEMPLATE/story.md)
- [Epic](.github/ISSUE_TEMPLATE/epic.md)
- [Review](.github/review_template.md)
- [Feedback response](.github/feedback_response_template.md)

GitHub offers issue, story and epic templates in its issue chooser and inserts
the PR template when opening a PR. Copy the review or feedback template into the
appropriate review or existing discussion thread; GitHub does not insert those
two automatically. Templates become available after reaching the default branch.
