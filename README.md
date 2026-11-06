# DevSecOps Security Gate

A scaffold for a CI security gate that will bring application security scanning,
policy evaluation, AI-assisted triage, infrastructure configuration, and test
fixtures together.

## Repository layout

- `app/` — application source and container build definition.
- `scanners/` — configuration and integrations for Semgrep, Trivy, Gitleaks,
  and Checkov.
- `policy-engine/` — security policy evaluation.
- `ai-triage/` — AI-assisted finding triage.
- `infrastructure/` — infrastructure-as-code and deployment configuration.
- `reports/` — generated security reports.
- `.github/workflows/security-pipeline.yml` — CI workflow scaffold.
- `tests/` — vulnerable and clean examples, plus policy tests.

This repository currently contains the requested directory scaffold. Scanner
integrations and enforcement policies have not yet been implemented.
