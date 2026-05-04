# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged
- Passing CI and security scans (security scan sign-off from **Security Lead**)
- Release notes drafted
- Rollback / mitigation plan documented and reviewed by **DevOps Engineer**
- Smoke tests prepared

## Deployment Checklist
- [ ] Deployment window scheduled (if needed)
- [ ] **DevOps Engineer** confirms pipeline health and deployment scripts are ready
- [ ] Backup or snapshot (if applicable)
- [ ] Deploy to staging and run smoke tests
- [ ] **Security Lead** confirms security scan results are acceptable for release
- [ ] Deploy to production (automated pipeline preferred, owned by **DevOps Engineer**)
- [ ] Run post-deploy verifications (observability dashboards checked by **DevOps Engineer**)
- [ ] Announce release to stakeholders and support

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - **DevOps Engineer** triggers incident response and notifies on-call
  - Rollback to last known-good release if necessary (**DevOps Engineer** executes)
  - **Security Lead** notified if the incident has a security dimension
  - Triage root cause and capture action items

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:
