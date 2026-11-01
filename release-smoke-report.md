# Release Smoke Test Report

Evidence for the checklist-smoke end-to-end dry run on GitHub account HeziLiu (org: mcpmark-eval-liuhezi).

NOTE: The secret gist (release-smoke-report.md) could not be created due to a token permission error:
failed to create gist: POST https://api.github.com/gists: 403 Resource not accessible by personal access token []

## Pull request

- Number: 1
- Title: Add Release Checklist section to README
- State: open
- Changed files (additions/deletions):
  - README.md: +8 / -0
- Totals: 1 changed file, 8 total additions, 0 total deletions

## Workflow run

- Run ID: 41258236071
- Workflow: Smoke Test (.github/workflows/smoke.yml)
- Run number: 1
- Event: workflow_dispatch
- Status: completed
- Conclusion: success
- Jobs:
  - smoke: status=completed, conclusion=success
    - steps: Set up job (completed/success), Echo marker (completed/success), Complete job (completed/success)

## Inbox

Notifications listing returned an error (verbatim):
failed to list notifications: GET https://api.github.com/notifications?page=1&per_page=50: 403 Resource not accessible by personal access token []

No notifications were returned due to the token permission error above.

## Teams

get_teams for HeziLiu returned one organization with no teams:
- org: mcpmark-eval-liuhezi, teams: []

No team memberships were returned (empty teams list for the org mcpmark-eval-liuhezi).

## Computed stats

- Changed files: 1
- Total additions: 8
- Total deletions: 0
FINGERPRINT=b335630551682c19a781afebcf4d07bf978fb1f8ac04c6bf87428ed5106870f5
