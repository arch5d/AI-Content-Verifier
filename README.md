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

✅ Network: *Sepolia Testnet* 

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

| Wallet Connect | Verify Content | Check Reputation |
| --- | --- | --- |
| ![Screenshot 2025-07-04 194149](https://github.com/user-attachments/assets/1e9dc73e-7b72-4d8f-ae3c-4183f8421539) | ![Screenshot 2025-07-04 193705](https://github.com/user-attachments/assets/edf36e9f-bf1d-4649-ad2c-508c9e3c6351) | ![Screenshot 2025-07-04 193746](https://github.com/user-attachments/assets/4a3fa1b3-ece4-46b5-aa85-7b5666e19dd1) |

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

🎥 *(Coming Soon)*

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

@arch5d

[LinkedIn](#https://www.linkedin.com/in/archita-dayal-010676313/) • [Twitter](#https://x.com/DayalArchita) 

---

> Built for developers, by developers.
