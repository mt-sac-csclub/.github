# Contributing to Mt. SAC Computer Science Club projects

Thanks for helping improve a club project. Beginners are welcome—ask questions early and often.

## Branch workflow

- `main` is the production branch.
- `dev` is the development and integration branch.
- Make changes on `dev`, or open a short-lived `feature/*` or `fix/*` branch into `dev` when several people are collaborating.
- Production updates must be submitted as a pull request from `dev` to `main`.
- Do not push directly to `main`, force-push shared branches, or merge while required checks are failing.

## Before opening a pull request

1. Pull the latest `dev` branch.
2. Run the repository's lint, test, and build commands.
3. Check mobile layouts and accessibility for UI changes.
4. Remove secrets, credentials, personal data, and generated files that do not belong in source control.
5. Explain what changed, why it changed, and how it was tested.

CI and review automation are safeguards, not substitutes for clear code and thoughtful human review.
