# ruff mirror

[pre-commit](https://pre-commit.com) mirror for
[ruff](https://github.com/charliermarsh/ruff) that gets automatic updates from
GitHub Actions.

## Using with pre-commit

See [pre-commit](https://github.com/pre-commit/pre-commit) for instructions

Sample `.pre-commit-config.yaml`

```yaml
-   repo: https://github.com/fsouza/mirrors-ruff
    rev: v0.0.69
    hooks:
    -   id: ruff
```
