# NOTE 02 — Lean 4 Dissection

**Finding:** Extracted 6 mechanisms from Lean 4 (3 trusted kernel, 3 untrusted elaborator/automation). Invariant: terms-as-data, single trusted checker, untrusted generators propose / checker filters, equality-by-normalization.

**Extraction hash:** 04eb615451cd9764 (specimen: https://github.com/leanprover/lean4)

**Verify independently:**
- Clone leanprover/lean4; inspect `src/kernel/` — the trusted core is small and separable from elaborator and tactics.
- Read `Mathlib` structure: every theorem is a term checked by that same kernel.
- Compare the four invariants above against the kernel source; each maps to a concrete file or subsystem.

**Solver impact proposed:** bidirectional mode gains explicit CHECK direction; term-as-data schema for all symbols; normalization-equality spike.

**Status:** Dissection complete. Re-derivation not started.
