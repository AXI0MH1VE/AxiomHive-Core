# Hive.C — Canonical Chronicle

This repo hosts the **verifiable chronicle** of Axiom Hive. Integrity is enforced by a recorded SHA256 at the end of the primary document.

## Structure

- `docs/Axiom_Hive_Chronicles.md` — canonical text
- `docs/` — project documentation and chronicles
- `src/` — source code modules
- `assets/` — images, diagrams
- `scripts/` — utilities

## Integrity Check

```bash
sha256sum docs/Axiom_Hive_Chronicles.md
# Compare to the "SHA256: <hash>" line at the end of the file
```

## Governance

- Deterministic edits only. All content changes must update the recorded SHA256.
- CI blocks merges on hash mismatch. See `.github/workflows/verify-chronicle.yml`.
