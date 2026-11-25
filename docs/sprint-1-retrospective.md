# Sprint 1 Retrospective — GoGoScrum REST Service

## Sprint Summary
- **Branch Workflow:** Created feature branches, committed Sprint 1 planning docs, opened/merged PR #1 into `main`, and synced local `main`.
- **Artifact Delivered:** `docs/sprint-1-plan.md` with user stories, story points, task states, and Definition of Done.

## What Went Well
- Cloned `gogoscrum-rest-service` and connected `origin` to `Darshan7484/Agile-scrum-project`.
- Completed a full branch → commit → push → Pull Request → merge → pull cycle.

## Challenges & How They Were Resolved
- **Path & directory navigation:** Learned to move into the cloned subfolder (`gogoscrum-rest-service`) before running Git commands.
- **Push rejection (`fetch first`):** Resolved cleanly using `git pull origin main --rebase --allow-unrelated-histories` before pushing.
- **Missing file on `git add`:** Created `docs/sprint-1-plan.md` first before staging and committing.

## Action Items for Next Iteration
- Add a GitHub Actions CI workflow (`.github/workflows/ci.yml`) to automate checks on pushes and pull requests.
- Add unit tests (JUnit) for core Scrum/task logic and verify test execution.
