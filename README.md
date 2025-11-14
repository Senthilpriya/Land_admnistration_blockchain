
Land Administration Smart Contract

A Solidity-based smart contract for managing land records and fractional ownership.
The contract handles trusted member onboarding, land registration, share distribution,
sale posting, and secure ownership transfers on-chain.

Features: 
Land Registration: Master registers land with district, taluk, village & patta number.
Trusted Members: Only verified users can own or buy land.
Ownership Shares: Supports fractional land ownership (e.g., 40%, 60%).
Transfer System: Owners can transfer shares if land is marked transferable.
Sale Posting: Owners can list land with price & share for sale.
Secure Purchase: Buyer pays in ETH → share is transferred automatically.
Duplicate Prevention: Ensures no land is registered twice

Deployment
You can deploy this contract using Remix.
Remix Steps:
Open https://remix.ethereum.org
Create LandAdministration.sol
Compile (Solidity 0.8.x)
Deploy using Remix VM 
