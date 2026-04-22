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

## Deployment Checklist
- [ ] Deployment window scheduled by the **Release Manager** (in coordination with PM and DevOps Engineer)
- [ ] Backup or snapshot (if applicable)
- [ ] Deploy to staging and run smoke tests (coordinated by Release Manager with DevOps Engineer)
- [ ] Deploy to production (automated pipeline managed by DevOps Engineer, triggered by Release Manager)
- [ ] Run post-deploy verifications
- [ ] Announce release to stakeholders and support

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - **Release Manager** triggers incident response and coordinates with DevOps Engineer and on-call team
  - **DevOps Engineer** executes rollback to last known-good release if necessary
  - Triage root cause and capture action items

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:
