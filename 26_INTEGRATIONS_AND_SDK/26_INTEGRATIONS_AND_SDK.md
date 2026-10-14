# Integrations and SDK — NODE_RED

**Project:** `NODE_RED`
**Category:** FACTORY_MANUFACTURING
**Domain:** factory manufacturing and automation
**Date:** 2026-10-07

---

## SDK

NODE_RED provides a Python SDK for integration:

```python
import node_red

# Initialize
client = node_red.Client()

# Use
result = client.process(data)
```

## Integrations

### Anticloud Ecosystem
- AIOSS chain for audit logging
- API Gateway for access control
- Model Registry for model management

### Third-Party
- Docker for containerization
- Kubernetes for orchestration
- Prometheus for monitoring

## Verification

All 16 checks PASS. Evidence: `ISOLATED_LAB_RESULTS/03_Result_Register.md`.
