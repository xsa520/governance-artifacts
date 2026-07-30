# Governance Artifacts

⚠️ **This is not an engineering repository.**

This repository is a curated archive of governance-artifact
representations preserved for audit-oriented review.

It contains representations of behavioral constraints described as
enforced in their originating context, preserved as references for
audit, review, and accountability purposes.

This repository preserves governance-artifact representations of
constraints described as enforced in their originating context. Where
underlying source records are unavailable or have not been
re-established, the corresponding artifacts must be treated as
provenance-unconfirmed rather than independently verified enforcement
evidence. See [`samples/README.md`](samples/README.md) for the current
evidence status of the sample artifacts.

There is **no executable code**, **no system design**, and **no implementation guidance** here.

---

## What This Repository Is

This repository exists to preserve governance-artifact representations,
not to enable systems.

It contains:

- Formal boundary definitions (`BOUNDARIES.md`)
- Statements of irreversibility (`IRREVERSIBILITY.md`)
- Illustrative, provenance-unconfirmed samples of disallowed decisions (`samples/`)
- Governance event schemas for audit traceability (`schema/`)
- Explicit non-goals and intentional incompleteness (`STATUS.md`)

These artifacts preserve representations of **what was described as
not allowed**, **what was represented as non-overridable**, and
**what was described as enforced before discretion or hindsight**.

Where the sample artifacts are concerned, these remain illustrative
representations rather than independently verified enforcement
evidence (see `samples/README.md`).

---

## What This Repository Is Not

This repository does **not** provide:

- Software systems
- Execution logic
- Runtime enforcement mechanisms
- Reference implementations
- Configuration options
- Operational guidance
- Exception handling pathways

Any attempt to treat these artifacts as an implementation blueprint
is a category error.

---

## How This Work Should Be Read

These materials are meant to be **examined**, not used.

They should be read as:

- Governance-artifact representations
- Constraint declarations
- Decision-boundary documentation
- Audit-oriented review material

They are **not adaptable**, **not parameterized**, and **not extendable**.

---

## Responsibility Boundary

This repository does not participate in enforcement.

Any system claiming to “implement” these artifacts does so
**without endorsement** and **without validation** from this work.

For explicit scope limits, see [`BOUNDARIES.md`](BOUNDARIES.md).  
For the repository's irreversibility claims and preservation posture,
see [`IRREVERSIBILITY.md`](IRREVERSIBILITY.md).  
For intentional incompleteness, see [`STATUS.md`](STATUS.md).  
For misuse prevention, see [`ANTI_MISUSE.md`](ANTI_MISUSE.md).

---

## Status

This repository is intentionally incomplete.

No roadmap is provided.  
No expansion is promised.

It represents a preserved record of governance-artifact
representations. Some of these representations describe constraints
as having been enforced elsewhere; that description has not been
independently verified. See `samples/README.md` for which artifacts
currently have unconfirmed provenance.
