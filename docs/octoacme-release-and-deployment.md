# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged
- Passing CI and security scans
- Release notes drafted
- Rollback / mitigation plan documented
- Smoke tests prepared

## Role Ownership — Release & Deployment

| Artifact / Activity | Owner | Contributors |
|---|---|---|
| Deployment pipeline execution | DevOps/Platform Engineer | Developers |
| Release notes | Product Manager | Developers, Support/Success Lead |
| Smoke test execution | Developers / QA | DevOps/Platform Engineer |
| Rollback decision | DevOps/Platform Engineer | Project Manager, Product Manager |
| Stakeholder announcement | Project Manager | Product Manager, Support/Success Lead |
| Support runbook and FAQs | Support/Success Lead | Developers, DevOps/Platform Engineer |

## Release Readiness Checklist

Complete this checklist before promoting any release to production. All owners must sign off before the go/no-go decision.

**Code & Quality**
- [ ] All acceptance criteria met and PRs merged
- [ ] CI passing (tests, lint, security scans)
- [ ] QA sign-off completed (owner: Developers / QA)
- [ ] UX design review completed for user-facing changes (owner: UX Designer)

**Infrastructure & Observability**
- [ ] Deployment pipeline tested in staging (owner: DevOps/Platform Engineer)
- [ ] Rollback procedure documented and tested (owner: DevOps/Platform Engineer)
- [ ] Monitoring dashboards and alerts configured (owner: DevOps/Platform Engineer + Data Analyst)
- [ ] Feature flags or gradual rollout configured (if applicable) (owner: DevOps/Platform Engineer)

**Support Readiness**
- [ ] Support runbook updated with new feature context (owner: Support/Success Lead)
- [ ] Customer-facing release notes or changelog drafted (owner: Product Manager + Support/Success Lead)
- [ ] Known issues documented and communicated (owner: Product Manager)
- [ ] Support team briefed on new functionality (owner: Support/Success Lead)

**Go/No-Go Sign-off**
- [ ] Product Manager: scope and quality approved
- [ ] DevOps/Platform Engineer: infrastructure and pipeline ready
- [ ] Support/Success Lead: support team prepared
- [ ] Project Manager: all checklist items verified, deployment window confirmed

## Deployment Checklist
- [ ] Release Readiness Checklist completed and signed off
- [ ] Deployment window scheduled (if needed)
- [ ] Backup or snapshot (if applicable)
- [ ] Deploy to staging and run smoke tests
- [ ] Deploy to production (automated pipeline preferred)
- [ ] Run post-deploy verifications
- [ ] Announce release to stakeholders and support

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call
  - Rollback to last known-good release if necessary
  - Triage root cause and capture action items

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:
