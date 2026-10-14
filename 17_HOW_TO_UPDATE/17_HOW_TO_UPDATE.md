# How to Update — MPI

**Project:** `MPI`
**Category:** SUPERCOMPUTER
**Domain:** supercomputer
**Date:** 2026-10-08

---

## Update Procedure

### Checking for Updates
```bash
MPI --version
MPI check-update
```

### Applying Updates
```bash
pip install --upgrade MPI
```

### Rolling Back
```bash
pip install MPI==<previous-version>
```

### Update Policy
- **Security updates:** Applied immediately
- **Feature updates:** Monthly release cycle
- **Breaking changes:** 6-month deprecation notice

## Verification

16/16 PASS. Evidence: `ISOLATED_LAB_RESULTS/03_Result_Register.md`.
