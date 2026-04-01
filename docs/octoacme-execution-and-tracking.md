# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- Daily standups (15 min) — focus on progress, blockers, dependencies
- Weekly delivery sync — show progress, updates, and flagged risks
- Demo/Review at the end of each sprint or milestone

## Workflows
- Use the project board (e.g., GitHub Projects) with columns: Backlog, Ready, In Progress, In Review, QA, Done
- Pull Request workflow:
  - Small PRs (<= 400 lines when possible)
  - Include issue link and acceptance criteria in PR description
  - Run automated tests and linting in CI before requesting review
  - Require at least one approval before merging (or team-defined policy)

## Quality & Testing
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI
- Manual QA for feature acceptance when needed

## Reporting & Metrics
- Track velocity and burndown
- Monitor success metrics identified in the Project One-pager
- Use dashboards for key signals (errors, latency, usage)

## Blocker Escalation
- Level 1: Team-level triage in daily standup
- Level 2: PM escalates to Product Lead and dependent teams
- Level 3: Sponsor-level escalation for business-impacting issues

## Role Ownership — Execution & Tracking

| Artifact / Activity | Owner | Contributors |
|---|---|---|
| Daily standup facilitation | Project Manager | All team members |
| Project board maintenance | Project Manager | Developers |
| PR authoring and review | Developers | DevOps/Platform Engineer |
| CI/CD pipeline health | DevOps/Platform Engineer | Developers |
| Success metrics dashboards | Data Analyst | DevOps/Platform Engineer |
| Blocker escalation | Project Manager | Product Manager, Sponsor |
| QA / acceptance sign-off | Developers / QA | Product Manager, UX Designer |

## Metrics & Monitoring Checklist

Use this checklist during execution to confirm observability and metrics are in place before a feature is considered ready for release.

- [ ] Success metrics from the Project One-pager are being tracked (owner: Data Analyst)
- [ ] Dashboard or report created and shared with the team (owner: Data Analyst)
- [ ] Key error and latency monitors are configured in production (owner: DevOps/Platform Engineer)
- [ ] Alerting thresholds reviewed and set for new features (owner: DevOps/Platform Engineer)
- [ ] Logging added for critical user actions to enable funnel analysis (owner: Developers)
- [ ] Feature flags or rollout controls wired to observability metrics (owner: DevOps/Platform Engineer)
- [ ] Baseline metrics captured before rollout for before/after comparison (owner: Data Analyst)

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint
- [ ] Regular demos scheduled
- [ ] Metrics & Monitoring Checklist completed before first release
- [ ] Risk register updated weekly
