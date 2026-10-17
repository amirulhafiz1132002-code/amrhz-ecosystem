# AMRHZ Standards Registry

**Registry status:** PROPOSED — the canonical standards pull request is awaiting human review.  
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

These entries record intended rollout scope, not completed adoption.

| Repository | Intended role | Status | Evidence / next action |
|---|---|---|---|
| [amrhz-architecture-core](https://github.com/amirulhafiz1132002-code/amrhz-architecture-core) | Canonical standards | PROPOSED | Review and merge PR #1 before treating the standards as approved. |
| [AMRHZ-Website](https://github.com/amirulhafiz1132002-code/AMRHZ-Website) | Responsive UI pilot | NOT_ASSESSED | Inspect the adoption PR and existing AI context; verify links after canonical merge. |
| [AP1-WEB-Console](https://github.com/amirulhafiz1132002-code/AP1-WEB-Console) | Application/system pilot | NOT_ASSESSED | Inspect adoption PR and existing truth protocol; no application code is changed by this registry. |
| [amirulhafiz1132002-code](https://github.com/amirulhafiz1132002-code/amirulhafiz1132002-code) | Profile/Cyberdeck UI | NOT_ASSESSED | Inspect adoption PR and preserve existing profile visual identity. |
| [AMRHZ-AI-13](https://github.com/amirulhafiz1132002-code/AMRHZ-AI-13) | AI runtime/model project | NOT_ASSESSED | Inspect adoption PR; do not infer model readiness from documentation. |

## Registry maintenance rules

1. Link each adoption claim to a pull request, commit, test, or other inspectable evidence.
2. Update a row only after verifying its current source ref.
3. Do not call adoption enforced unless the relevant controls actually exist and have been tested.
4. If canonical standards change, record the version/ref used by each adopter and flag drift.
5. Never copy all canonical policy text into this registry; link to it to avoid competing sources of truth.

**No downstream repository adoption or technical enforcement is implied by this registry file alone.**