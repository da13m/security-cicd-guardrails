# Security CI/CD Guardrails

Reusable GitHub Actions and scripts to enforce cloud security hygiene in repos.

## Features
- Bicep build & what-if (if AZ creds provided)
- PSRule for Azure (policy linting)
- Secret scanning gate (GitHub default + sample script)
- KQL formatting check for Sentinel content

## Structure
```
.github/workflows/
  validate-iac.yml
tools/
  run-psrule.ps1
  check-kql.ps1
```
