# lab-mcp

## Branch & Commit Rules

For each issue:
```bash
git checkout -b step-X-short-description
```

Commits must reference the issue number:
```bash
git commit -m "feat(step-X): <short description> (#ISSUE_ID)"
```

## Pull Request Rules

- One PR per STEP
- PR description must reference the issue
- Issue is closed only when PR is merged

## Required GitHub Labels

Create the following labels in the repository:

- `feature`
- `bug`
- `test`
- `docker`
- `ci-cd`

## Licence

MIT
