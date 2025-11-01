# Hive.C — Canonical Chronicle

This repo hosts the **verifiable chronicle** of Axiom Hive. Integrity is enforced by a recorded SHA256 at the end of the primary document.

## Structure
- `Axiom_Hive_Chronicles/Axiom_Hive_Chronicles_Corrected.md` — canonical text
- `Axiom_Hive_Chronicles/README.md` — local usage notes

## Integrity Check
```bash
sha256sum Axiom_Hive_Chronicles/Axiom_Hive_Chronicles_Corrected.md
# Compare to the "SHA256: <hash>" line at the end of the file
```

## Governance
• Deterministic edits only. All content changes must update the recorded SHA256.
• CI blocks merges on hash mismatch. See .github/workflows/verify-chronicle.yml.
