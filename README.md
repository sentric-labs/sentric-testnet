# Sentric Protocol – Testnet Deployment

**Sentric ($SNTX)** is the on-chain engine for sentiment-driven analytics. Designed to measure market moods and reward transparency, Sentric transforms emotional signals into data-rich token market intelligence

This repo contains testnet smart contract deployments, token metadata, and exploratory modules for the Sentric Protocol on the **Polygon Amoy** network.

---

## 🧪 Testnet Details


- **Token Name:** Sentric Token  
- **Symbol:** `SNTX`  
- **Network:** Polygon Amoy (Testnet)  
- **Deployed Contract Address:** `0x4Ac5299500cb03079778774e139783e374B154Bc`  
- **Explorer:** [View on OKLink](https://www.oklink.com/amoy/address/0x4ac5Ca0496643aa37093b4811720EdD174b154Bc)  
- **Base Contract:** [3rdweb TokenERC20 v5.0.4](https://thirdweb.com/thirdweb.eth/TokenERC20/5.0.4)

---

## 💰 Token Allocation (Testnet)

- ✅ **Total Supply:** 1,000,000,000 $SNTX minted on Polygon Amoy
- 🔒 Minting permanently disabled after genesis issuance
- 🏦 **Sentric Treasury (Reserve Wallet):**  
  [`0xeCF372409A962176d2e52E57a54a44c8F1FF8c98`](https://oklink.com/amoy/address/0xeCF372409A962176d2e52E57a54a44c8F1FF8c98)  
  *(To be migrated to a Safe multisig on mainnet for governance and custody control)*  
- 🔄 **Deployer Wallet:** 0 SNTX post-deployment — full supply secured in treasury  
---

# Token Contract Base

This project uses the [3rdweb TokenERC20 v5.0.4](https://thirdweb.com/thirdweb.eth/TokenERC20/5.0.4) smart contract as the base implementation for $SNTX.

- ✅ Audited and maintained by 3rdweb
- 🛠️ Deployed via 3rdweb dashboard to Polygon Amoy
- 🔗 [View deployed contract](https://thirdweb.com/team/sentric/Sentric-21d7bf/contract/polygon-amoy-testnet/0x4Ac5299500cb03079778774e139783e374B154Bc)

This repo contains metadata, deployment info, and testnet configuration for the Sentric Token.




---

## 📁 Files in This Repo

| File / Folder                            | Description                                                  |
|------------------------------------------|--------------------------------------------------------------|
| `contract_address.txt`                   | Deployed token contract address on Amoy testnet              |
| `assets/sntx_logo.png`                   | Token icon for wallets, explorers, and metadata              |
| `metadata/sntx_token_metadata.json`      | ERC-20 token metadata (for wallets & token lists)            |
| `metadata/sntx_token_distributions.csv`  | Snapshot of total supply allocation across known addresses   |
| `docs/litepaper.md`                      | Protocol overview and roadmap (placeholder / draft)          |
| `docs/tokenomics.md`                     | Detailed supply breakdown and incentive planning             |
| `docs/treasury.md`                      | Treasury structure, signer roles, Safe multisig intent and governance plan |
---

## 💡 Next Up

- 🧾 Publish Litepaper (In Progress)
- 🧾 Create token listing metadata (CMC/CG/TrustWallet)  
- 📊 Integrate with gasless interactions (ERC-2771 / Thirdweb)  
- 🗳️ Launch sentiment voting prototype

---

## 🤝 Contributing

This is an early-stage public repo for collaboration, discussion, and experimentation. PRs, forks, and issue reports are welcome.

---

## 🛡 License

[MIT](LICENSE)

---

>  On-chain market intelligence meets transparent user rewards—where data drives value.
