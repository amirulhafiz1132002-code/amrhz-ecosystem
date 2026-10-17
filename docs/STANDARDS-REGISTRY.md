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
| [amrhz-architecture-core](https://github.com/amirulhafiz1132002-code/amrhz-architecture-core) | Canonical standards | PROPOSED | [PR #1](https://github.com/amirulhafiz1132002-code/amrhz-architecture-core/pull/1) — review the standards and schema files. |
| [amrhz-ecosystem](https://github.com/amirulhafiz1132002-code/amrhz-ecosystem) | Adoption registry | PROPOSED | [PR #2](https://github.com/amirulhafiz1132002-code/amrhz-ecosystem/pull/2) — review registry and AI entrypoint. |
| [AMRHZ-Website](https://github.com/amirulhafiz1132002-code/AMRHZ-Website) | Responsive UI pilot | PROPOSED | [PR #3](https://github.com/amirulhafiz1132002-code/AMRHZ-Website/pull/3) — documentation-only adoption proposal. |
| [AP1-WEB-Console](https://github.com/amirulhafiz1132002-code/AP1-WEB-Console) | Application/system pilot | PROPOSED | [PR #37](https://github.com/amirulhafiz1132002-code/AP1-WEB-Console/pull/37) — documentation-only adoption proposal. |
| [amirulhafiz1132002-code](https://github.com/amirulhafiz1132002-code/amirulhafiz1132002-code) | Profile/Cyberdeck UI | PROPOSED | [PR #9](https://github.com/amirulhafiz1132002-code/amirulhafiz1132002-code/pull/9) — preserve profile identity and SVG behavior. |
| [AMRHZ-AI-13](https://github.com/amirulhafiz1132002-code/AMRHZ-AI-13) | AI runtime/model project | PROPOSED | [PR #5](https://github.com/amirulhafiz1132002-code/AMRHZ-AI-13/pull/5) — do not infer model readiness from documentation. |

## Registry maintenance rules

1. Link each adoption claim to a pull request, commit, test, or other inspectable evidence.
2. Update a row only after verifying its current source ref.
3. Do not call adoption enforced unless the relevant controls actually exist and have been tested.
4. If canonical standards change, record the version/ref used by each adopter and flag drift.
5. Never copy all canonical policy text into this registry; link to it to avoid competing sources of truth.

**No downstream repository adoption or technical enforcement is implied by these open PRs or registry file alone.**