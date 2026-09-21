# Pilot validation change

This branch exists only to exercise the pull-request and required-check path.

## 2026-09-21 delivery exercise

This disposable change exercises the current GitHub CLI workflow:

- draft and publish a tracking issue with gh-issue-sync;
- commit on a codex/ task branch and open a draft pull request;
- pass the required validate check before a squash merge;
- confirm issue closure and remove the delivered task branch.

No production deployment or application behavior changes are involved.
