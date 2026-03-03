# wp
working paper

Title: SPT-Txn Framework: Sovereign Policy Tokens with TBAC Enforcement, ZK Privacy, Biometric Uniqueness, and Multi-Chain Deployment 
Authors: Rudolf J. Coetzee
Submitted to ePrint https://eprint.iacr.org/

It might take 72 hours to become public from today 03.03.2026

Sovereign Policy Tokens • TBAC Capability Enforcement • ZK Privacy • Biometric Uniqueness • Transaction Chain Integrity • Multi-Chain Deployment


Abstract: 
The SPT-Txn Framework v6.0 integrates Attribute-Based Access Control (ABAC), Token-Based Access Control (TBAC), Non-Fungible Tokens (NFTs), Self-Sovereign Identity (SSI), Zero-Knowledge Decentralized Identifiers (zkDID), biometric uniqueness proofs, and IETF Transaction Tokens into a unified authorization architecture for the agentic economy.
It addresses five requirements unmet by existing systems:
1.	Regulatory compliance with privacy preservation
2.	Portable identity without PII disclosure
3.	Cryptographically enforced capability scoping and delegation depth for AI agents and microservices
4.	Cross-organizational chain-of-custody integrity
5.	Sybil-resistant human-in-the-loop authorization anchors
Deployment targets include EVM-compatible chains (primary), XDC Network (RWA and trade finance), Cardano/Midnight (ZK-native privacy), and Substrate parachains (enterprise sovereign). The framework enables portable compliance proofs that substantially reduce KYC onboarding costs and provide regulators with immutable audit trails.

Key Contributions
1.  The two-phase evaluation model: ABAC evaluates attributes once at issuance; TBAC enforces capabilities at every access point without re-evaluation, offline-enforcement.
2.  Eight-step TBAC Enforcement Engine operating solely on the Capability Token (CT), formally specified enforcement sequence operating solely on the CT, no policy engine consulted at access time.
3.  Cryptographic delegation depth with scope subset invariants and immutable humanAnchor propagation, enforced across agentic hierarchies, eliminating confused deputy attacks.
4.  ZK Circuit Architecture (Specification Level): formal proof statements, input/output tables, and proof system rationale for attribute proofs, compliance claims, and biometric commitments.
5.  Biometric Enrollment Contract Architecture: on-chain/off-chain security boundary, nullifier registry design, and liveness attestation verification flow.
6.  SPT-Txn: IETF Transaction Token extension with capability binding, ZK privacy, agentic delegation depth, and cross-organizational trust.
7.  Multi-chain deployment: EVM (primary), XDC (RWA/financial services), Cardano/Midnight (ZK-native privacy), Substrate (enterprise sovereign).
8.  Policy NFTs as composable, jurisdictionally-aware compliance objects enabling programmable multi-jurisdictional regulatory satisfaction.
