# CoinoCore v3.0.0 — Launch Release

**Date:** 2026-09-28  
**Type:** First stable release  
**Compatibility:** Coino network v2 (2017) — full

---

## 🎉 What is this

The first official release of **CoinoCore v3** — a modern client for the Coino (CNO) cryptocurrency.

**This is not a hard fork.** It is a new client for the existing v2 network. Your coins, wallets, and addresses are fully compatible.

---

## ✨ What's new

### Security
- ✅ **libsecp256k1** replaces OpenSSL — fixed the `BN_num_bits` crash
- ✅ **OpenSSL 3.x** compatibility via `OPENSSL_API_COMPAT`

### Network
- ✅ **Fixed** the sync stall at block **395 740**
- ✅ **Synchronized** to block 814 735
- ✅ **9 active peers**

### Branding
- ✅ **CoinoCore V3** — new client name
- ✅ **Version** `CNO-v2.0.0.2`

---

## 📦 Artifacts

| Platform | File | MD5 |
|---|---|---|
| Linux x86_64 | `CoinoCore-V3-linux-x86_64` | `0c06e1de12b21a3666dd55f70d4cc1d5` |

---

## 🚀 Installation (Linux x86_64)

```bash
wget https://github.com/CoinoCore/CoinoCore/releases/download/v3.0.0/CoinoCore-V3-linux-x86_64
chmod +x CoinoCore-V3-linux-x86_64
xvfb-run -a ./CoinoCore-V3-linux-x86_64 \
  -datadir=/path/to/coino-data \
  -noirc -printtoconsole
