# Repository Maintenance Guide

## Naming

Use short, descriptive lowercase names with hyphens, such as `django-network-scanner` or `cloud-security-case-studies`. Preserve established project brands such as `tenantledger`, `appsec-assistant`, and `verifiedrelease`.

Describe the artifact, not just the course or phase: prefer `recruitex-project-artifacts` over `job-opportunities` when the repository contains reports rather than source. Avoid `Test`, `Major-Project`, and vague collections for future work.

Rename only after checking clones, documentation links, deployed URLs, Actions references, package/image names, badges, and external integrations. A GitHub redirect does not verify those dependencies. Treat GitHub Pages repositories and release-signing workflow identities as migration work.

## Minimum information

Every substantive repository should have:

- A one-sentence About description stating the purpose and main technology.
- Three to seven accurate topics, usually one category plus technologies/domain.
- A README explaining the actual artifact, entry points, setup status, evidence, and limits.
- Existing upstream attribution and license information preserved.
- A catalog entry when the project is public.

Use [README_TEMPLATE.md](README_TEMPLATE.md) for new work. Omit irrelevant sections instead of filling them with unsupported claims.

## Topic vocabulary

| Category | Use for |
| --- | --- |
| `portfolio-project` | Substantial projects with implementation and reviewable evidence |
| `web-application` | Application and website implementations |
| `security-tool` | Reusable security utilities |
| `security-lab` | Authorized security exercises |
| `learning-project` | Earlier experiments and learning code |
| `case-study` / `research` | Reports, papers, and analysis |
| `coursework` | Course project artifacts |
| `study-notes` | Study materials, kept private where appropriate |
| `open-source-fork` | An upstream fork whose provenance should remain clear |
| `project-placeholder` | An explicitly unstarted project |

Add relevant language and domain topics. Topics describe contents, not maintenance guarantees.

## When starting or changing a project

1. Pick its purpose, name, and visibility.
2. Add the description, topics, README, and suitable ignore rules.
3. Keep local environments, dependencies, generated caches, and real credentials out of new commits.
4. Document only setup commands and results that have supporting evidence.
5. Update [PROJECTS.md](PROJECTS.md) and [projects.json](projects.json) when public projects change.
6. Keep profile highlights limited to the projects you want a new visitor to inspect first.

## Monthly review

- Check the profile's six pinned projects still represent security and software work.
- Check README setup instructions, relative links, and any claimed demo URLs.
- Review placeholder and duplicate repositories. Prefer a clear redirect/index before considering archival.
- Preserve useful history; archive completed work only after reviewing its role and dependencies.
- Check pending dependency/security alerts and remove stale claims.
- Keep public catalogs free of private project configuration and notes.

## Current relationships

The catalog documents overlapping learning repositories. No history needs to be rewritten merely to improve naming and navigation. Keep one clear destination for future updates when consolidating a project, and link older copies to it.
