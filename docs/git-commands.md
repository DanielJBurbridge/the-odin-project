## Git PR Submit
```bash
gh pr create --base main --head {branch} --title "{title}" --body "{body}"
```

## Git PR Merge
```bash
gh pr merge {pr-number} --merge --delete-branch
git checkout main
git pull origin main
```

## View Current PR Status
```bash
gh pr status
```

## View Open PRs
```bash
gh pr list
```

## View Merged PRs
```bash
gh pr list --state merged
```

