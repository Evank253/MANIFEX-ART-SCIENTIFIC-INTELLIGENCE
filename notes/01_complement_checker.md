# NOTE 01 — Complement Checker v0.1

**Finding:** Scanned 19 public and internal solver specimens against the solver's three math modes (forward, reverse, bidirectional). 17 surfaced gaps; 2 (OpenFOAM, Newton) matched existing mode primitives.

**Extraction hash:** complement_check_report.json (local sandbox artifact, generated 2026-10-24)

**Verify independently:**
- Re-run `complement_checker.py` from the local sandbox; compare output hash to the report.
- Cross-check each candidate's core_operation sentence against the specimen's own README at the URL listed in the report.
- Keyword lists in FORWARD_PRIMITIVES, REVERSE_PRIMITIVES, BIDIRECTIONAL_PRIMITIVES are the decision criteria — inspect them directly.

**Status:** Heuristic v0.1. Covered = keyword match, not equivalence. Dissection queue is the deliverable.
