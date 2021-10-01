# Valet (Monorepo)

`Valet` is a set of toolchain that aim to facilitate developers to build web applications efficiently.

## Getting Started

```bash
git clone git@github.com:valet-is/central.git valet-central
cd valet-central
yarn
```

> It's not required to run `git submodule` configurations manually. It'll trigger with `yarn` as a `preinstall` script.

### Contributing

- This repository (monorepo) holds multiple repositories under `packages/*` directory. We use `yarn` to enable `workspaces` support.
- In each repository, the primary branch is `master`, and strongly recommend to avoid pushing changes to master branch directly.
- Always use feature branches for feature development. (`feat/*`)
- Always keep active work in progress pull requests (PRs) in draft stage.

#### Branch names

- Use `feat/<awasome-feature>-[issue-id]` naming conventions for feature branches.
- Use `fix/<good-fix>-[issue-id]` for bug fixes.
- Use `chore/<task>-[issue-id]` for regular tasks.

#### PR names

- Use `feat: <My Awesome Feature>` naming conventions for feature titles.
- Use `fix: <That fix>` for fixes.
- Use `chore: <Regular Task>` for regular tasks.

#### Commit messages

- [How to Write a Git Commit Message by Chris Beams](https://chris.beams.io/posts/git-commit/)
- [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/)

#### Issues

Apply labels appropriately for each issues when created:

- `epic`
- `story`
- `bug`
- `feature`
- `task`
- `enhancement`
- `documentation`
- `question`
- `help wanted`

Components:

- `comp:cli`
- `comp:console`
- `comp:server`

Labels for maintainers:

- `wontfix`
- `invalid`
- `good first issue`
- `duplicate`
- `freez`

Priorities:

- `priority:high`
- `priority:medium`
- `priority:low`


### API Docs

Check [postman collection](https://documenter.getpostman.com/view/16889203/TzseK6ym)
