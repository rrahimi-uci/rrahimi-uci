# GitHub Copilot repository instructions

- You may work on assigned issues and development tasks, create a branch, and open a pull request. You must never merge a pull request, approve a pull request, push to `main`, or represent your review as human approval.
- Before opening or marking a pull request ready for human review, understand the issue acceptance criteria, implement the smallest complete change, and add or update tests for changed behavior.
- This is a profile/documentation repository with no committed CI workflow. For documentation changes, run `git diff --check`, inspect Markdown links and rendered structure where applicable, and report the validation performed. Do not claim tests that do not exist.
- Keep validation deterministic and offline. Do not require credentials, network services, model calls, or uncommitted local data for ordinary tests.
- Do not submit a PR as ready if an applicable validation check fails. If validation is blocked, keep the PR draft and state the exact blocker and command output in the PR body.
- The PR body must list changed behavior, tests or documentation checks, every validation command and result, limitations, risks, and deployment implications.
- During code review, identify correctness, security, test-coverage, and maintainability issues and leave comments. Never approve or merge the PR.
