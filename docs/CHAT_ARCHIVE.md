# NXT Group Chat Archive

## Conversation Summary

This document contains an auditable snapshot of the NXT Group planning and governance setup conversation.

### Key Decisions Made

1. **Governance Structure Split**
   - Created `.github` org-level defaults repository
   - Created `nxt-hq` governance control plane
   - Cleaned `nxtps-ultra-build` to focus on venue code

2. **Scout L0 Implementation**
   - Successfully implemented Scout L0 module
   - Wired to canonical CSV processing
   - Emits signals and health data

3. **Architecture Principles**
   - Speed > Perfection
   - Skeleton crew first, refine later
   - Director sign-offs mandatory
   - Owner Veto for major decisions

### Technical Implementation

- **Scout L0 Module:** `src/nxtps/scout_l0.py`
- **Makefile Integration:** `make scout-l0`, `make health`
- **CI/CD Gates:** Reusable workflow from HQ
- **Port Restrictions:** 8787 (API), 5173 (UI) only

### Governance Framework

- **5 Phase 1 Directors:** Assistant, Doctor, Butler, Finance, Security
- **6 Venues:** Print Studio, Branding, Nexframe, AI F&B, AI Trading, LuxScout
- **Build Order:** Launch Directors → Print Studio → Growth → Scale

---

Synced: 2025-08-29 AEST
