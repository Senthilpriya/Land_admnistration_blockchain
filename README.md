
# Land Administration Smart Contract

A Solidity-based smart contract system for decentralized land management.  
It supports **trusted member onboarding**, **land registration**, **fractional ownership**, **sale posting**, and **secure on-chain transfers** of land shares.

## Features
- **Land Registration:** Master registers land with district, taluk, village, and patta details.
- **Trusted Members:** Only verified members can own or buy land.
- **Fractional Ownership:** Supports multiple owners with defined share percentages.
- **Share Transfer:** Owners can transfer shares when the land is marked as transferable.
- **Sale Posting:** Owners can list land shares for sale with a specified price.
- **Secure Purchase:** Buyers pay in ETH and receive ownership shares automatically.
- **Duplicate Prevention:** Prevents registering the same land more than once.

## Deployment (Remix)
1. Open **https://remix.ethereum.org**
2. Create a new file: **LandAdministration.sol**
3. Paste the contract code
4. Compile using **Solidity 0.8.x**
5. Deploy using **Remix VM** or **Injected Web3**

## Tech Stack
- **Solidity 0.8.x**
- **Ethereum Virtual Machine (EVM)**

## License
**MIT**
