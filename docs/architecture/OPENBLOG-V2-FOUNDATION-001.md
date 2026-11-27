# OpenBlog v2 — Foundation roadmap

**Programme:** OPENBLOG-V2-FOUNDATION-001  
**Status:** Planning only; not an implementation or release approval.  
**Historical reference:** `ff866dccfad13ccc891f827439814890c883a3e4`

## Direction

OpenBlog will evolve as a standalone, versioned knowledge platform. The historical v1 reference is preserved. The proposed v2 architecture retains the existing application stack and uses a modular monolith with explicit domain boundaries. Optional standards-based interoperability may be introduced without making another application a runtime or identity dependency.

## Planned stages

| Stage | Scope |
| --- | --- |
| CP0–CP1 | Architecture assessment and planning reconciliation |
| CP2 | Isolated baseline qualification |
| CP3 | Architecture contracts and decision records |
| CP4 | Preservation and development-line approval |
| Subsequent development | Incremental implementation, qualification and release review |

Each stage has separate acceptance and authorisation requirements. A planning decision is not a runtime, deployment or release qualification.

## Engineering principles

- Preserve historical source and data provenance.
- Keep domain ownership and application interfaces explicit.
- Prefer deterministic, reproducible and measurable behaviour.
- Use staged qualification and documented acceptance criteria.
- Maintain compatibility where agreed, and document changes where necessary.
- Evaluate optional integrations separately from core platform functionality.

## Review and publication

This public document is intentionally limited to roadmap and governance information. Detailed qualification records are handled separately with appropriate access controls. It does not constitute independent acceptance of a checkpoint.

No application code, migration, dependency, workflow or deployment change is proposed by this documentation revision. CP2 and implementation remain subject to separate approval. Any merge must satisfy the repository's contribution policy in [AGENTS.md](../../AGENTS.md).
