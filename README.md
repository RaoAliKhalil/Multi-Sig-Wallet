# Multi-Sig-Wallet
Imagine a company has $1 million in crypto. If only ONE person controls it: That person can steal it If that person dies or loses their phone — money is gone forever. Hackers only need to attack ONE person. Multi-Sig solves this: 3 people are owners At least 2 must agree before ANY money moves Even if a hacker steals 1 person's account. Even if 1 owner dies — other 2 can still access funds
 # Example:
3 Owners: Alice, Bob, Charlie
Required Approvals: 2 out of 3

Scenario:
1. Alice proposes: "Send 1 ETH to supplier"
2. Bob approves it ✅
3. Charlie approves it ✅ (now 2/3 approved)
4. Transaction EXECUTES automatically
5. If only Alice approved — NOTHING happens


A smart contract wallet requiring M-of-N owner approval
before any ETH transaction executes.

## Live Contract
Network: Sepolia Testnet
Address: 0x91A4848e928851fe13aBbDBe287c34C0674e1357
Etherscan: https://lnkd.in/dvM2AyKJ
## Tech Stack
- Solidity 0.8.19
- Hardhat (testing)
- React.js + Ethers.js (frontend)
- MetaMask (wallet connection)

- ## How to Run Locally
npm install
npm start

## Security Features
- Reentrancy protected
- Only owners can propose/approve/execute
- Duplicate approval prevention
- Events emitted for all actions

- <img width="958" height="424" alt="image" src="https://lnkd.in/djmmE_kR" />

<img width="960" height="410" alt="image" src="https://lnkd.in/dmJ6z4uc" />
<img width="959" height="416" alt="image" src="https://lnkd.in/dWNiabZW" />
<img width="960" height="509" alt="image" src="https://lnkd.in/dJ5BnyVh" />
<img width="960" height="509" alt="image" src="https://lnkd.in/dhmc_Mk4" />

