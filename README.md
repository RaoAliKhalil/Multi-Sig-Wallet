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
Address: 0x91A4848e928851fe13aBbDBe287c34C0674e135
Etherscan: https://sepolia.etherscan.io/tx/0x26d04d1376e9c41d2ff56220f20915528d6a63f06a012aeeebb8583e95eec4d7
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

<img width="958" height="413" alt="image" src="https://github.com/user-attachments/assets/a5dcfdf5-a31e-4e3c-bc03-f3ae36c37d26" />
<img width="960" height="407" alt="image" src="https://github.com/user-attachments/assets/08b963c8-b2b7-4298-9b9f-cf01f32c56af" />
<img width="960" height="397" alt="image" src="https://github.com/user-attachments/assets/b675999c-4907-4259-baba-5e941072950a" />
<img width="960" height="481" alt="image" src="https://github.com/user-attachments/assets/a0684040-6ab6-43d1-84c2-cfaba956e0be" />
<img width="957" height="358" alt="image" src="https://github.com/user-attachments/assets/3b027baf-b40b-4d33-96e0-96519325f454" />


