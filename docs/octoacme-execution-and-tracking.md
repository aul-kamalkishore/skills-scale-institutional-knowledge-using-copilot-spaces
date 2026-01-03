# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- Daily standups (15 min) — focus on progress, blockers, dependencies (facilitated by Scrum Master)
- Weekly delivery sync — show progress, updates, and flagged risks
- Demo/Review at the end of each sprint or milestone (coordinated by Scrum Master and PM)

## Workflows
- Use the project board (e.g., GitHub Projects) with columns: Backlog, Ready, In Progress, In Review, QA, Done
- Pull Request workflow:
  - Small PRs (<= 400 lines when possible)
  - Include issue link and acceptance criteria in PR description
  - Run automated tests and linting in CI before requesting review (managed by DevOps Engineer)
  - Require at least one approval before merging (or team-defined policy)
  - UX Designer reviews for design consistency when UI changes are included

## Quality & Testing
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI (configured and monitored by DevOps Engineer)
- Manual QA for feature acceptance when needed
- UX Designer validates design implementation and usability

## Reporting & Metrics
- Track velocity and burndown
- Monitor success metrics identified in the Project One-pager
- Use dashboards for key signals (errors, latency, usage)

## Blocker Escalation
- Level 1: Team-level triage in daily standup (facilitated by Scrum Master)
- Level 2: PM escalates to Product Lead and dependent teams; Scrum Master tracks impediment resolution
- Level 3: Sponsor-level escalation for business-impacting issues

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint (DevOps Engineer responsible)
- [ ] Regular demos scheduled (coordinated by Scrum Master)
- [ ] Risk register updated weekly
- [ ] Design implementation reviews scheduled with UX Designer
