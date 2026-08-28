# renovate-config

Centralized [Renovate](https://docs.renovatebot.com/) configuration for the `miladbeigi` account and the `miladorg` organization.

This repository is public so Renovate can read it from both namespaces.

## Usage

In any repository, add a `renovate.json` with:

```json
{
  "$schema": "https://docs.renovatebot.com/renovate-schema.json",
  "extends": ["github>miladbeigi/renovate-config"]
}
```

## What it enables

- Dependency Dashboard issue in every repository (`dependencyDashboard: true`)
- Recommended preset defaults (`config:recommended`)
- `dependencies` label on PRs
- Daily schedule (before 6am)
- Max 10 concurrent PRs per repository
- Auto-merge minor and patch dependency updates (PRs are created and merged once CI passes)

## Files

| File           | Preset name                          | Purpose                |
| -------------- | ------------------------------------ | ---------------------- |
| `default.json` | `github>miladbeigi/renovate-config`  | Shared base config     |
