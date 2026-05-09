# CLAUDE.md

This is the **Gervi Héra Vitr** homeschool -- the org-level `.github` repository.
The school is a member of the **Mímis Gildi** family of orgs.

## What This Is

Organization-wide defaults for all Gervi-Hera-Vitr repositories.
Community health files, org profile, issue/PR templates, and contributor guidance.

This is not where shared actions or tooling live -- those live in [fluffle].
The "required" workflows live here, sourced from `fluffle`.

## What Belongs Here

| Content            | Location                           | Purpose                                   |
|--------------------|------------------------------------|-------------------------------------------|
| Org profile        | `profile/README.md`                | Renders on the org's GitHub page.         |
| Code of conduct    | `CODE_OF_CONDUCT.md`               | Default for all repos.                    |
| Contributing guide | `CONTRIBUTING.md`                  | Default for all repos.                    |
| Security policy    | `SECURITY.md`                      | Default for all repos.                    |
| Support info       | `SUPPORT.md`                       | Default for all repos.                    |
| Funding            | `FUNDING.yml`                      | Sponsorship config.                       |
| Issue templates    | `.github/ISSUE_TEMPLATE/`          | Default templates for all repos.          |
| PR template        | `.github/PULL_REQUEST_TEMPLATE.md` | Default for all repos.                    |
| Workflow templates | `workflow-templates/`              | Starters surfaced in the new-workflow UI. |
| Greeting messages  | `.github/messages/`                | Used by welcome-first-contributor action. |

## What Does NOT Belong Here

- Shared GitHub [actions] -- those live in [fluffle].
- Reusable workflows -- those also live in [fluffle].
- Project-specific configuration -- each repo owns its own.

## How Defaults Work

Files here cascade to every Gervi-Hera-Vitr repo that doesn't have its own version.
A repo overrides by creating the same file locally.

This repo must be **public** for the cascade to work.

## Build

No build. Static content only.
Build patterns and templates live in [fluffle].

## Trunk-Based Development

Same as the rest of the family: linear history, feature branches merge to `main`.

### Exceptions

Structural changes and experimentation before `v1.0.0` may be pushed to `main` directly.

[fluffle]: https://github.com/Mimis-Gildi/fluffle "Shared actions and workflows."
[actions]: https://github.com/features/actions
