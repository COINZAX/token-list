# CoinZax Token List

This repository contains a list of tokens for the CoinZax blockchain network. You can add your token by following the steps below.

## 📝 How to Add Your Token

### 1️⃣ Upload Your Token Logo
- Your token logo **must be a PNG file** (256x256 pixels recommended).
- The filename **must match the token contract address** (e.g., `0xYourTokenAddress.png`).
- Upload the logo to the **`logos/`** folder.

### 2️⃣ Add Your Token to `token-list.json`
Open `token-list.json` and add your token information in the following format:

```json
{
  "chainId": 1310,
  "address": "0xYourTokenAddress",
  "name": "Your Token Name",
  "symbol": "YTN",
  "decimals": 18,
  "logoURI": "https://raw.githubusercontent.com/coinzax/token-list/main/logos/0xYourTokenAddress.png"
}
```

### 3️⃣ Submit a Pull Request
- Commit your changes.
- Open a pull request (PR) on GitHub.
- Your PR will be reviewed and merged.

## ✅ Token Requirements
- The contract must be **deployed and verified**.
- The token must be **active** on the CoinZax network.
- The logo should be **high-quality and clear**.

🚀 **Thank you for contributing!**  
For questions, open an issue.
