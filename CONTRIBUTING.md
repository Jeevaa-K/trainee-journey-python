# Contributing

## Principles

- `main` is always stable and never receives direct commits.
- All work happens on short-lived branches.
- Every branch is merged through a reviewed pull request (PR), using squash-merge.

## Branch naming

Format: `week-NN-topic-slug`

Examples:

- `week-01-central-repository-git-branching`
- `week-01-semantic-html-accessibility`
- `week-09-relational-model-sql-normalization`

## Workflow for every practical

1. Update main: `git switch main` then `git pull`
2. Create a branch: `git switch -c week-NN-topic-slug`
3. Do the work in `practicals/<topic-folder>/` and commit in small steps
4. Push the branch: `git push -u origin week-NN-topic-slug`
5. Open a pull request into `main` and fill in the PR template
6. Review the PR (mentor review, or a self-review checklist when working solo)
7. Squash-merge the PR into `main`, then delete the branch

## Commit messages

Use a short prefix: `feat:`, `fix:`, `docs:`, `chore:`, `refactor:`, `test:`

Example: `docs: add README and folder structure`