# 🧭 ContentVerifier DApp

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Ethereum](https://img.shields.io/badge/Blockchain-Ethereum-green.svg)
![MetaMask Compatible](https://img.shields.io/badge/MetaMask-Enabled-orange.svg)
![Status](https://img.shields.io/badge/Project-Active-brightgreen)

A modern decentralized application (DApp) to **verify content authenticity** on-chain!  
✅ Prove if it's AI-generated or Human-made  
✅ Track creators' reputation  

> Built with ❤️ using Solidity, ethers.js & Ethereum.

---

## 🚀 Live Contract

📜 **Deployed Address:**  
[`0x7EF2e0048f5bAeDe046f6BF797943daF4ED8CB47`](https://sepolia.etherscan.io/address/0x7EF2e0048f5bAeDe046f6BF797943daF4ED8CB47)

✅ Network: *Sepolia Testnet* (or your chosen network)

---

## ✨ Features

✅ MetaMask Integration  
✅ Verify content by storing its hash and AI status on-chain  
✅ Update AI/Human status (by creator only)  
✅ Query any content hash to see creator, timestamp, AI status  
✅ Report false claims to reduce reputation  
✅ Reputation system for creators

---

## 🖼️ Screenshots

*(Add your own images here)*

| Main Screen | Verify Content | Check Reputation |
| --- | --- | --- |
| ![screenshot1](link) | ![screenshot2](link) | ![screenshot3](link) |

---

## 📦 Tech Stack

| Frontend | Smart Contract | Web3 |
| --- | --- | --- |
| ![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black) | ![Solidity](https://img.shields.io/badge/Solidity-363636?logo=solidity&logoColor=white) | ![ethers.js](https://img.shields.io/badge/Ethers.js-3C3C3D?logo=ethereum&logoColor=white) |

---

## 🌐 How to Use

1️⃣ Install [MetaMask](https://metamask.io/) in your browser.  
2️⃣ Clone this repo or download as ZIP.  
3️⃣ Open `index.html` in your browser.  
4️⃣ Connect your wallet by clicking **Connect Wallet**.  
5️⃣ Use the app to:  
   - ✅ Verify new content
   - 🔎 Query existing hashes
   - ✏️ Update your content's AI status
   - 🚨 Report false claims
   - ⭐ Check creator reputation

---

## 💻 Folder Structure

📦 root
┣ 📜 index.html # DApp UI
┣ 📜 style.css # Modern styling
┣ 📜 app.js # ethers.js integration
┗ 📜 README.md # You're here!

---

## ⚙️ Smart Contract Overview

🟢 **Key Functions:**
- `verifyContent(string hash, bool isAI)`
- `getContent(string hash) returns (Content)`
- `updateAIStatus(string hash, bool newIsAI)`
- `reportFalseStatus(string hash)`
- `getReputation(address creator) returns (uint256)`

🟢 **Events:**
- `ContentVerified`
- `ReputationUpdated`

---

## 📜 Example Instructions (shown in app)

> 1️⃣ Connect MetaMask wallet  
> 2️⃣ Verify new content as AI/Human-made  
> 3️⃣ Query any hash to see details  
> 4️⃣ Update your content's AI status  
> 5️⃣ Report false claims  
> 6️⃣ Check reputation of any Ethereum address

---

## ✅ Demo Video

🎥 *(Add link to Loom/YouTube video if you have one)*

---

## 🔗 Resources

- 🌍 [MetaMask](https://metamask.io/) – Ethereum Wallet
- 📚 [ethers.js Docs](https://docs.ethers.io/)
- 💻 [Remix IDE](https://remix.ethereum.org/)

---

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

---

## 📝 License

This project is licensed under the MIT License.  
![License](https://img.shields.io/badge/license-MIT-blue.svg)

---

## ❤️ Author

Your Name / Team Name

[LinkedIn](#) • [Twitter](#) • [Website](#)

---

> Built for developers, by developers.
