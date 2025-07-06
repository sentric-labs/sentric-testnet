# 🔐 Sentric Treasury Governance

> This document outlines the structure, ownership, and responsibilities of the Sentric Treasury, including future governance intentions via Safe multisig wallets.

---

## 🏦 Treasury Overview

- **Current Treasury Wallet (Testnet)**:  
  [`0xeCF372409A962176d2e52E57a54a44c8F1FF8c98`](https://oklink.com/amoy/address/0xeCF372409A962176d2e52E57a54a44c8F1FF8c98)  
  - Holds 1,000,000,000 $SNTX (100% of total supply)
  - Used on Polygon Amoy for testnet simulation

---

## 🧠 Multisig Governance Intent (Mainnet)

Upon mainnet deployment, treasury control will transition to a **Safe multisig wallet** with the following parameters:

| Role            | Address / Notes                           |
|------------------|--------------------------------------------|
| **Signer 1**     | Contract Creator Wallet (`0xeCF372409A962176d2e52E57a54a44c8F1FF8c98`) – core protocol maintainer |
| **Signer 2**     | Safe placeholder signer / governance-ready address |
| **Threshold**    | `1-of-2` (for testnet simulations)<br>`2-of-3` or more recommended on mainnet |

> ✅ MetaMask is used as a signer interface for multisig approvals  
> 🔐 Safe will become the canonical on-chain controller of all future token flows

---

## 🔁 Migration Plan (Mainnet)

| Step                                      | Description                                             |
|-------------------------------------------|---------------------------------------------------------|
| ✅ Deploy Safe on Polygon Mainnet         | Via [Safe App](https://app.safe.global)                |
| 🚀 Transfer all $SNTX to Safe             | Replace testnet treasury with mainnet Safe vault       |
| 📄 Update Docs & Token Lists              | Replace treasury references with Safe address          |


---

## 📖 Resources

- [Safe Multisig UI](https://app.safe.global)
- [Sentric Token on Polygon Amoy](https://oklink.com/amoy/address/0x4ac5Ca0496643aa37093b4811720EdD174b154Bc)
- [Token Distribution Snapshot (CSV)](../metadata/sntx_token_distributions.csv)

---

> ℹ️ This document is a living record. Signers, thresholds, and policies will evolve with community growth and network maturity.
