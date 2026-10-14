# How to Update — NODE_RED

**Project:** `NODE_RED`
**Category:** FACTORY_MANUFACTURING
**Domain:** factory manufacturing and automation
**Date:** 2026-10-07

---

## Update Procedure

### Checking for Updates
```bash
NODE_RED --version
NODE_RED check-update
```

### Applying Updates
```bash
pip install --upgrade NODE_RED
```

### Rolling Back
```bash
pip install NODE_RED==<previous-version>
```

### Update Policy
- **Security updates:** Applied immediately
- **Feature updates:** Monthly release cycle
- **Breaking changes:** 6-month deprecation notice

## Verification

All 16 checks PASS. Evidence: `ISOLATED_LAB_RESULTS/03_Result_Register.md`.
