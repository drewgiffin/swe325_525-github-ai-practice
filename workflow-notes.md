# Workflow Notes

## Repository

- Repository URL: https://github.com/drewgiffin/swe325_525-github-ai-practice
- Default branch: `main`

## Issue

- Issue URL: TBD
- Purpose: Define the work for this assignment (document the GitHub workflow with AI assistance) with acceptance criteria and a task checklist.

## Feature Branch

- Branch name: `feature/github-ai-workflow`

## Commits

1. Clarify repository purpose: TBD
2. Document branch and pull request workflow: TBD
3. Add AI-use record: TBD

## Pull Request

- Pull request URL: TBD
- Merge or history URL: TBD

## GitHub Concepts

- **Issue:** A tracked unit of work. It describes the goal, acceptance criteria, and tasks, and gives the work a number other GitHub objects can reference.
- **Default branch:** The main line of the repository (`main`). It holds the accepted, reviewed state of the project and is the target for pull requests.
- **Branch:** An independent line of development created from the default branch. Work happens here so `main` stays stable until changes are reviewed.
- **Commit:** A saved snapshot of changes with a message describing what changed and why. Small, specific commits make the history easy to read and review.
- **Pull request:** A request to merge a branch into the default branch. It shows the diff and commits, links to the issue, and is where review comments and approval happen before merging.

## How They Relate

The issue defines what needs to be done and how it will be verified. The feature branch is created to do that work without touching `main`. Each commit on the branch records one meaningful step toward the acceptance criteria. The pull request proposes merging the branch into `main`, links back to the issue, and lists the commits as evidence. Review happens on the pull request; any requested changes become new commits on the same branch. Once approved, the pull request is merged into `main`, which closes out the issue.
