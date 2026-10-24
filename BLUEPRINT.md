# MANIFEX-ART Scientific Intelligence — Blueprint

Engineering specification. Doctrine governs; this document builds.

## Build Sequence

1. Bootstrap and BTP-001 — authority and integrity foundation. Nothing runs without it.
2. Spine controller — every capability routes through it.
3. MANIFEX-ART reconstruction pipeline — bidirectional engine, SymPy, SciPy adapters built and tested here.
4. MANIFEX registration — catalog only what works.
5. Genesis Seed — doctrinal seed poured in last. It boots into a standing machine.

## Bidirectional Engine

Three producers share one intermediate-statement schema. Forward generates partial derivations from assumptions. Backward decomposes the target into subgoals. Bidirectional crawls from both ends and records a meeting point when chains connect.

Handoff rule: when forward stalls on a missing lemma, emit the lemma as a backward subgoal. When backward cannot close a subgoal from known mechanisms, emit it as a forward search target. Stop handing off when the same statement has been emitted three times without progress — flag as BLOCKED.

Intermediate-statement schema: id, producer, evidence_class, claim, derivation_refs, assumptions, timestamp.

## Adapter Family

| Adapter | Role | Status |
|---|---|---|
| sympy.symbolic-equation | Symbolic solve and residual check | Target v0.2 |
| scipy.numeric-root-and-optimization | Bracketed roots, bounded scalar optimization | Target v0.3 |
| z3.constraint | SMT solving, counterexample search | Planned |
| lean.formal-proof | Formal obligation checking | Planned, separate lane |
| bidirectional.core | Forward/backward/bidirectional handshake | Core build |

Every adapter specifies input/output contracts, failure semantics, evidence type, independent checks, dependency and license metadata, tests, and limitations.

## Ledger

Append-only JSONL. SHA-256 hash chaining across records. Each entry: evidence_id, problem_id, classification, claim, method, details, timestamp, previous_hash, record_hash. Hash chaining detects edits, not false claims.

## Capability Register

One row per capability: ID, source artifact and revision, observed mechanism, reconstruction status, evidence class. NOT_MEASURED is a valid terminal state for unreviewed sources.

## Near-Term Milestone

P versus NP atlas: run the bidirectional engine against the problem for an extended period and log every dead end as structured conflict data. The output is a negative-space map of failed approaches, not a solution claim.

## Long Game

Millennium problems as stress tests. The system assists with formalization, lemma discovery, and proof checking. It claims no breakthrough without Lean-verified proof obligations.
