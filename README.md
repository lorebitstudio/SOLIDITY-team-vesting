
# TeamVesting – Smart Contract Suite (Developed by Lorebit Studio)

This repository contains a suite of **team vesting and treasury management smart contracts** developed by **Lorebit Studio** to demonstrate a decentralized, transparent, and configurable team vesting system deployed on **Base Sepolia**.

---

## 🎮 Project Overview

This project showcases an implementation of an ERC20-based **team vesting system** with a treasury vault.
It includes contracts for:

- Creating and managing beneficiary vesting wallets.
- Configurable cliff & vesting durations.
- Treasury vault with rate-limited releases and upfront unlock.
- Controller to orchestrate funding, revocation, and recovery.

---

## 👨‍💻 Lorebit Studio's Role

Lorebit Studio developed all smart contracts, deployment scripts, and testing utilities for this showcase:

- **ProjectToken:** ERC20 token with capped supply, burn, and pause.
- **TeamVestingController:** Manages vesting wallets, grants funder roles, and handles recovery.
- **TeamVestingVault:** Holds ERC20/ETH funds, releases them based on rates, supports upfront unlock.
- Deployment & verification scripts.
- Test scenarios simulating multiple beneficiaries and full lifecycle.

---

## 🔨 Contracts Included

| Contract                   | Description                                              |
|----------------------------|----------------------------------------------------------|
| **ProjectToken.sol**       | ERC20 token with max supply, pausing, and burn.         |
| **TeamVestingController.sol** | Central controller managing wallets and recovery.       |
| **TeamVestingVault.sol**   | Treasury vault managing rate-limited & upfront releases.|

---

## 🧠 Key Features

✅ ERC20 with capped supply & owner-controlled minting.  
✅ Vesting wallets with cliff & linear vesting schedules.  
✅ Treasury vault with upfront & streamed releases.  
✅ Funder role-based access control.  
✅ Full recovery of unvested funds after revocation.  
✅ Fully verified on Base Sepolia block explorer.  

---

## 🌐 Deployments

🧪 **Testnet – Base Sepolia**  
Contracts Owner: `0xB94503C6a717BDD677ad9dAB7B450AF86d3Aa3F5`

| Contract                  | Address |
|---------------------------|---------|
| **ProjectToken**          | [0xFEc873ceB29BF2708526fAc3752e82E8ab2a2a4f](https://sepolia.basescan.org/address/0xFEc873ceB29BF2708526fAc3752e82E8ab2a2a4f) |
| **TeamVestingController** | [0x4d7F615A7E41577a7A51BD8B62D5F0A69695105B](https://sepolia.basescan.org/address/0x4d7F615A7E41577a7A51BD8B62D5F0A69695105B) |
| **TeamVestingVault**      | [0x56859658c84908574c0435f9d7D645BBdD1F6FAE](https://sepolia.basescan.org/address/0x56859658c84908574c0435f9d7D645BBdD1F6FAE) |

---

## 🏗️ Built For

Lorebit Studio Portfolio Project  
A demonstration of decentralized team vesting and treasury mechanics on an EVM L2 testnet.

---

## 🧑‍💻 Developed By

**Lorebit Studio**  
Smart Contract Development • Tokenomics Design • Fullstack Blockchain Engineering  
🌐 [lorebitstudio.com](https://lorebitstudio.com)  
✉️ contact@lorebitstudio.com  

---

## 📄 License

This repository is licensed under the **MIT License**.

---

## ⭐ Usage

This repository is intended for portfolio and showcase purposes.  
If you are interested in hiring Lorebit Studio or using these contracts commercially, please get in touch!
