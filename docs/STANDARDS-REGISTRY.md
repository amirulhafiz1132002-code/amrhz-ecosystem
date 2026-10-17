# AMRHZ Standards Registry

**Registry status:** PROPOSED — canonical standards and downstream adoption PRs are awaiting review.  
**Canonical source:** [amrhz-architecture-core governance standards](https://github.com/amirulhafiz1132002-code/amrhz-architecture-core/tree/main/docs/standards)  
**Canonical proposal:** [PR #1 — Propose AMRHZ governance standards for controlled evolution](https://github.com/amirulhafiz1132002-code/amrhz-architecture-core/pull/1)

## Standards tracked

| Standard | Purpose | Canonical status |
|---|---|---|
| UI Evolution Contract | Preserve intent and working behavior; prefer the smallest evidenced UI change. | PROPOSED |
| Dual-Layer Documentation Standard | Maintain readable human docs and structured AI context tied to the same project reality. | PROPOSED |
| Evidence and State Contract | Define state labels and require scoped evidence for verification and live claims. | PROPOSED |

## Adoption states

- **NOT_ASSESSED** — repository has not been inspected for adoption.
- **PROPOSED** — adoption is described in an open pull request.
- **ADOPTED** — the reviewed local entrypoint or guidance has been merged.
- **VERIFIED** — required adoption checks were run and passed for a specific revision.
- **ENFORCED** — actual repository controls/checks were configured and tested to enforce the intended rule.
- **BLOCKED** — a named dependency or permission prevents progress.
- **UNKNOWN** — available evidence is insufficient.

## Initial rollout ledger

The following are open proposals, not completed adoption. Downstream proposals depend on review of canonical PR #1.

| Repository | Intended role | Status | Evidence / next action |
|---|---|---|---|
| [amrhz-architecture-core](https://github.com/amirulhafiz1132002-code/amrhz-architecture-core) | Canonical standards | PROPOSED | [PR #1](https://github.com/amirulhafiz1132002-code/amrhz-architecture-core/pull/1) — review standards and schemas. |
| [amrhz-ecosystem](https://github.com/amirulhafiz1132002-code/amrhz-ecosystem) | Adoption registry | PROPOSED | [PR #2](https://github.com/amirulhafiz1132002-code/amrhz-ecosystem/pull/2) — review registry and AI entrypoint. |
| [AMRHZ-Website](https://github.com/amirulhafiz1132002-code/AMRHZ-Website) | Responsive UI pilot | PROPOSED | [PR #3](https://github.com/amirulhafiz1132002-code/AMRHZ-Website/pull/3) — documentation-only proposal; Workers build check failed, cause not established. |
| [AP1-WEB-Console](https://github.com/amirulhafiz1132002-code/AP1-WEB-Console) | Application/system pilot | PROPOSED | [PR #37](https://github.com/amirulhafiz1132002-code/AP1-WEB-Console/pull/37) — documentation-only proposal; some checks passed and latest analysis status requires recheck. |
| [amirulhafiz1132002-code](https://github.com/amirulhafiz1132002-code/amirulhafiz1132002-code) | Profile/Cyberdeck UI | PROPOSED | [PR #9](https://github.com/amirulhafiz1132002-code/amirulhafiz1132002-code/pull/9) — ESLint, CodeFactor, and security checks reported success at last inspection. |
| [AMRHZ-AI-13](https://github.com/amirulhafiz1132002-code/AMRHZ-AI-13) | AI runtime/model project | PROPOSED | [PR #5](https://github.com/amirulhafiz1132002-code/AMRHZ-AI-13/pull/5) — security checks reported success; no model readiness inferred. |

## Verification snapshot

**Observed:** 2026-10-17. Check results may change; refresh before making merge decisions.

- Canonical PR #1: GitHub accepted both schema files as JSON when fetched and parsed. Socket Security Pull Request Alerts and Project Report reported success. Full JSON Schema meta-validation and CI enforcement have not been run.
- Registry PR #2: Socket Security Pull Request Alerts and Project Report reported success.
- Website PR #3: Socket checks reported success; `Workers Builds: amrhz-websites` reported **failure**. Available check output did not establish the cause. No fix was attempted because the change is documentation-only and the failure needs independent diagnosis.
- AP1 PR #37: Socket checks, CodeQL, and Vercel Preview Comments reported success. At the latest inspection, a newer set of CodeQL analysis checks was still in progress; refresh before deciding.
- Profile PR #9: ESLint, Run eslint scanning, CodeFactor, and Socket checks reported success.
- AI-13 PR #5: Socket checks reported success.

A green security/report check is not proof of functional correctness. A failed or pending check is not to be described as passing. No PR in this rollout has been merged, and no production deployment was performed by this work.

## Registry maintenance rules

1. Link each adoption claim to a pull request, commit, test, or other inspectable evidence.
2. Update a row only after verifying its current source ref.
3. Do not call adoption enforced unless the relevant controls actually exist and have been tested.
4. If canonical standards change, record the version/ref used by each adopter and flag drift.
5. Never copy all canonical policy text into this registry; link to it to avoid competing sources of truth.

**No downstream repository adoption or technical enforcement is implied by these open PRs or registry file alone.**