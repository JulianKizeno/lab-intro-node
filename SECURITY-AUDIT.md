# Security review — 2026-11-14

This is a partial remediation, not a certification that the repository is free of vulnerabilities. Changes remain in a draft pull request pending review.

## starter-code

npm findings before: {"info": 0, "low": 2, "moderate": 0, "high": 3, "critical": 0, "total": 5}. After remediation: {"info": 0, "low": 0, "moderate": 3, "high": 0, "critical": 0, "total": 3}.
Counts refer to dependency findings in this project, including development dependencies. Projects without a committed lockfile were first resolved to create an auditable baseline.

Production build/test result: `{   "project": "lab-intro-node/starter-code",   "install_exit": 0,   "build_exit": 0 }`.

### Remaining advisories

- `mocha`: moderate; requires dependency migration. 

Do not treat compatible lockfile updates as completion of the framework migrations above.
