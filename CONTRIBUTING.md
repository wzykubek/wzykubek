# Contributing

## 1. Default Branch Name
Use `master` as root branch name.

## 2. Initial Commit
Initialize repository and it's first commit without any content included:
```bash
git commit --allow-empty -m "init"
```

## 3. Conventional Commits
Use the [Conventional Commits](https://www.conventionalcommits.org/) specification for commit messages.
Examples:
- `feat(cli): add a new cli feature`
- `fix(parser): resolve a bug`
- `docs: update documentation`
- `chore: general maintenance or tooling changes`

Clear commit messages make the history easier to read and improve collaboration.

Additionaly, consider making more smaller commits than one bigger.

## 4. Semantic Versioning
Adhere to [Semantic Versioning (SemVer)](https://semver.org/) for project versioning:
- `MAJOR`: Breaking changes
- `MINOR`: New features, backward compatible
- `PATCH`: Bug fixes, backward compatible

Proper versioning ensures users and contributors understand the impact of updates.
