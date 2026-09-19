# AsmJit Readiness Plan — GODOT_4_SECURITY_MASTERCLASS_by_AEiOU

Status: PREPARED_ONLY
Branch: `prep/asmjit-readiness-2026-09-19`
Decision: DO NOT INTEGRATE.

This repository is security/reference material. A JIT implementation would belong in a separate product/runtime repository.

## Potential future documentation topic
If an approved native JIT is deployed elsewhere, document:
- W^X/JIT memory policy
- code cache lifetime
- attack surface
- guest/host isolation
- C ABI boundaries
- executable-page invalidation
- telemetry and crash containment

No implementation, dependency addition, PR, or merge on this branch.
