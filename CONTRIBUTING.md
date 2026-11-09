# Contributing

These are the defaults for Makvion Technologies repositories. A repository may add its own rules on top of these.

## Before you start

1. Enable two-factor authentication on your GitHub account.
2. Set your GitHub name and profile photo so teammates can recognise you.
3. Confirm you have access to the right team and repositories. If not, email [contact@makvion.com](mailto:contact@makvion.com).

## Branch naming

Create a branch from `main` (or the repo’s default) using one of these prefixes:

- `feat/` — new feature
- `fix/` — bug fix
- `chore/` — tooling, deps, cleanup
- `docs/` — documentation only
- `refactor/` — internal change with no behaviour change

Examples: `feat/contact-form`, `fix/mobile-nav-overlap`.

## Commits

Prefer [Conventional Commits](https://www.conventionalcommits.org/):

```
feat: add SSL expiry email reminders
fix: stop slider jumping on tap
chore: bump next to 16.0.1
```

Keep commits focused. Write the subject in the imperative mood.

## Pull requests

- Open a PR against `main`. Fill in the pull request template.
- Request a review from at least one teammate before merging.
- Keep PRs small enough to review in one sitting when you can.
- Do not force-push to a shared branch after review has started unless you coordinate with the reviewer.
- Squash or rebase only when the repository asks for it.

## Protected `main`

Do not push directly to `main`. All changes go through a pull request and review. Branch protection / rulesets enforce this on company repositories.

## Secrets and environment files

Never commit secrets, API keys, `.env` files, private keys or customer data. Use the project’s documented secret store or environment configuration. If you accidentally commit a secret, rotate it immediately and tell the team.

## Questions

For access, process or tooling questions: [contact@makvion.com](mailto:contact@makvion.com).
