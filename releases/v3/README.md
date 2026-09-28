# CoinoCore v3.0.0 — Launch Release

**Дата:** 28.09.2026  
**Тип:** Первый стабильный релиз  
**Совместимость:** Сеть Coino v2 (2017) — полная

---

## 🎉 Что это

Первый официальный релиз **CoinoCore v3** — современного клиента для криптовалюты Coino (CNO).

**Это не hard fork.** Это новый клиент для существующей сети v2. Ваши монеты, кошельки и адреса полностью совместимы.

---

## ✨ Что нового

### Безопасность
- ✅ **libsecp256k1** вместо OpenSSL — исправлен краш `BN_num_bits`
- ✅ **OpenSSL 3.x** совместимость через `OPENSSL_API_COMPAT`

### Сеть
- ✅ **Исправлено застревание на высоте 395 740**
- ✅ **Синхронизация** до 814 735
- ✅ **9 активных пиров**

### Имя
- ✅ **CoinoCore V3** — новое имя клиента
- ✅ **Версия** `CNO-v2.0.0.2`

---

## 📦 Артефакты

| Платформа | Файл | MD5 |
|---|---|---|
| Linux x86_64 | `CoinoCore-V3-linux-x86_64` | `0c06e1de12b21a3666dd55f70d4cc1d5` |

---

## 🚀 Установка (Linux x86_64)

```bash
wget https://github.com/CoinoCore/CoinoCore/releases/download/v3.0.0/CoinoCore-V3-linux-x86_64
chmod +x CoinoCore-V3-linux-x86_64
xvfb-run -a ./CoinoCore-V3-linux-x86_64 \
  -datadir=/path/to/coino-data \
  -noirc -printtoconsole
