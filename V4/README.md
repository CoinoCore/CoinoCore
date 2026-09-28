# CoinoCore V4

**Status:** 🔧 In development  
**Goal:** New network with a new genesis block.

---

## Porting plan

- [ ] **Phase 1:** Network parameters (`chainparams.cpp`)
- [ ] **Phase 2:** X11 (from Dash)
- [ ] **Phase 3:** PoS (from PIVX)
- [ ] **Phase 4:** Wallet (SQLite + Descriptor Wallets)
- [ ] **Phase 5:** Build system (`depends`)

---

## Base

- **Bitcoin Core v27.0** — foundation
- **Dash v0.14** — X11 donor
- **PIVX v5.5.0** — PoS donor
- **src-coino-old** — network parameters

---

## Important

- New genesis block
- New `pchMessageStart`
- v2/v3 coins **do not apply** in v4 (unless a snapshot is used)
- This is a **hard fork** — a separate project

---

**Author:** CoinoCore Team  
**Date:** 2026
