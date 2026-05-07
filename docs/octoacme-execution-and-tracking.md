# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- Daily standups (15 min, led by Scrum Master or PM) — focus on progress, blockers, dependencies
- Weekly delivery sync — show progress, updates, and flagged risks
- Weekly QA/Testing check-in — review testing progress, quality metrics, and blockers
- Weekly DevOps/Infrastructure sync — deployment readiness, CI/CD status, and observability setup
- Demo/Review at the end of each sprint or milestone

## Workflows
- Use the project board (e.g., GitHub Projects) with columns: Backlog, Ready, In Progress, In Review, QA, Done
- Pull Request workflow:
  - Small PRs (<= 400 lines when possible)
  - Include issue link and acceptance criteria in PR description
  - Run automated tests and linting in CI before requesting review
  - Require at least one approval before merging (or team-defined policy)
  - QA Lead or designated reviewer validates acceptance criteria

## Quality & Testing
- **Unit tests** for new logic (owned by Developers)
- **Integration tests** where applicable (owned by Developers with QA input)
- **End-to-end smoke tests** for critical flows before release (owned by QA Lead)
- **Security scanning** in CI (coordinated with Security Officer)
- **Manual QA** for feature acceptance when needed (owned by QA Lead)
- **Performance testing** for critical paths (coordination between DevOps and QA Lead)
- Regular QA/Testing status updates in daily standups and weekly syncs

## QA/Testing Lead Responsibilities
- Create and maintain test plans aligned with acceptance criteria
- Track test coverage and report quality metrics
- Manage defect triage and prioritization
- Validate features meet acceptance criteria before marking done
- Coordinate with Developers on test infrastructure improvements

## DevOps/Infrastructure Responsibilities
- Maintain and improve CI/CD pipelines
- Ensure staging environment mirrors production
- Support local development environment setup
- Monitor build times and optimize where possible
- Prepare infrastructure for release (capacity planning, rollback procedures)

## Reporting & Metrics
- Track velocity and burndown (managed by PM/Scrum Master)
- Monitor success metrics identified in the Project One-pager (Product Manager)
- Use dashboards for key signals (errors, latency, usage) (DevOps + Product Manager)
- Report testing progress and quality metrics (QA Lead)
- Track CI/CD pipeline health and deployment frequency (DevOps)

## Blocker Escalation
- Level 1: Team-level triage in daily standup (Scrum Master or PM)
- Level 2: PM escalates to Product Lead and dependent teams
- Level 3: Sponsor-level escalation for business-impacting issues
- Technical blockers: Technical Lead provides mitigation guidance
- QA/Quality blockers: QA Lead works with Developers to resolve
- DevOps/Infrastructure blockers: DevOps Engineer coordinates with Infrastructure/Platform team

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests, lint, and security scanning
- [ ] QA/Testing strategy and acceptance criteria clear for all items
- [ ] Staging environment available and synchronized with production
- [ ] DevOps deployment runbook documented
- [ ] Regular demos scheduled
- [ ] Risk register updated weekly
- [ ] Team health metrics tracked (velocity, blockers, team satisfaction)