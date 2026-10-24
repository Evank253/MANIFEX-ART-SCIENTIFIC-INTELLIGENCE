# MANIFEX-ART Scientific Intelligence

An independent scientific problem-solving system. It reconstructs selected capabilities from existing systems through its own implementations, unifies them under a bidirectional solving core, and records every step with cryptographic evidence integrity.

## Architecture

- **MANIFEX-ART** builds: reconstruction pipeline, adapters, bidirectional engine.
- **MANIFEX** registers: capability discovery and qualification.
- **Bidirectional engine** solves: forward, backward, and bidirectional modes sharing one intermediate-statement schema.

## Three Producers

Forward solving, backward solving, and bidirectional solving each stamp evidence classes — OBSERVED, INFERRED, VERIFIED, NOT_MEASURED — on every intermediate statement. VERIFIED is reserved for chain connections that pass residual checks.

## Status Semantics

SOLVED_VERIFIED, CANDIDATE_FOUND, PARTIALLY_SOLVED, COUNTEREXAMPLE_FOUND, BLOCKED, UNRESOLVED. Missing measurement is NOT_MEASURED, not success.

## Founding Documents

- [DOCTRINE.md](DOCTRINE.md) — governing principles.
- [BLUEPRINT.md](BLUEPRINT.md) — engineering specification and build sequence.

## Provenance

Reconstructed capabilities cite their inspected origins as metadata — source repository, branch, and blob hash — recorded in the capability register. This trail points back to validated, hash-recorded originals without making this system dependent on them. New code written in this repository carries no origin note; its history begins at the first commit here. Borrowed third-party work follows the four-step investigation loop before integration; the user's own repositories are cloned directly as reference.

## License

MIT. See [LICENSE](LICENSE).
