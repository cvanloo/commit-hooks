# Pre-Commit Hooks

## Usage

```bash
git remote add commit-hooks https://github.com/cvanloo/commit-hooks
git fetch commit-hooks
git merge commit-hooks/main --allow-unrelated-histories
pre-commit install
pre-commit run
```

When making changes to the pre-commit hook config:

```bash
git add .pre-commit-config.yaml
git commit --no-verify -m'update pre-commit hooks'
```
