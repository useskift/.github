# Contributing to Skift

Thanks for considering a contribution! This guide covers the practical steps you need: getting set up, reporting problems, suggesting improvements, and submitting pull requests.

## Getting started

- Fork the repo if you're an external contributor, or branch off the main branch if you're on the team.
- Follow the project's `README.md` for dependency installation and environment setup.
- Use a focused branch for each change, for example `feat/auth` or `fix/login-bug`.

## Reporting bugs

When filing a bug report, please include:

- A concise, descriptive title.
- Clear reproduction steps.
- What you expected to happen and what actually occurred.
- Environment information (OS, browser and versions) and any relevant logs or error output.

> [!TIP]
> Check existing issues first — someone else may already have reported the same problem.

## Suggesting features or changes

Start by opening an issue that outlines:

- The problem you're trying to address.
- Your proposed approach and other options you considered.
- Who will benefit from the change.

If maintainers request an implementation, create a dedicated branch and keep your changes scoped to the single issue.

## Pull request checklist

- Link the issue the PR relates to (for example, "Fixes #123").
- Give the PR a clear title and explain what changed and why.
- Keep PRs as small and focused as possible; split large work into multiple PRs when sensible.
- Run the test suite and any linters locally before creating the PR.
- Address review feedback and update your branch (rebase or merge main to stay current).

## Code style and quality

- Adhere to the repository's established coding style. If a formatter or linter is configured, run it before committing.
- Prefer clear, self-explanatory code and include or update tests for any new behavior.

### Commit message format

We use [Conventional Commits](https://www.conventionalcommits.org/). Use the pattern:

```
type(scope): short description
```

Typical types: `feat`, `fix`, `docs`, `style`, `refactor`, `test`, `chore`.

---

_Need extra help setting up? See the repository `README.md`._
