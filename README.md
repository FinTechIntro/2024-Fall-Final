# 2024-Fall-Final


+ Smart Contract and Blockchain Basics
  + Storage Layout: What is a storage layout, and how are storage slots calculated?
  + Call vs. Delegatecall: Differences in how msg.sender and msg.value are handled between call and delegatecall.
  + Proxy Patterns: How proxy patterns function and the key differences among various proxy implementations.
  + ECDSA: How ECDSA works and the relationship between the address, message digest, and signature.
  + Merkle Root: Understanding the Merkle root, potential issues, and methods to mitigate them.
+ Smart Contract Vulnerabilities: Understanding vulnerabilities and their countermeasures:
  + Arbitrary Call: Risks associated with providing target and data to low-level calls.
  + Access Control: Ensuring proper access control in Flash Loan Receiver contracts.
  + Reentrancy Issues: Addressing reentrancy with the CEI (Check-Effect-Interaction) pattern and implementing reentrancy locks.
+ Decentralized Exchange - Uniswap as an Example
  + Algorithms for DEXs: Explore various algorithms like Constant Product AMM and others (e.g., Curve).
  + Constant Product AMM: Understanding the formula 𝑥 × 𝑦 = 𝑘, calculate the output amount of token1 when given token1.
  + Equilibrium Price: How to determine the equilibrium price during arbitrage activities on a DEX.
  + Impermanent Loss: What it means, how to calculate it, and its implications for liquidity providers.
  + Slippage: What slippage is, its causes, and strategies to mitigate it.
    + Sandwich Attack: How MEV bots exploit slippage to execute sandwich attacks.
    + Slippage Check: How the Uniswap Router prevents slippage-related issues.
  + Operations in Uniswap v2: Understanding key functions like sync, skim, mint, burn, and swap.
    + Underlying Mechanisms: Detailed insights into the core component.
    + Implementation Details: Examples include mint (dead shares) and swap (flash swaps).
+ On-Chain Lending
  + Types of On-Chain Lending: Explore uncollateralized, undercollateralized, and overcollateralized loans.
  + Key Metrics in Lending: Understanding essential terms (definitions may vary across protocols; we will provide explanations, but basic understanding with these concepts is recommended):
    + Collateral Factor
    + Loan-to-Value (LTV)
    + Liquidation Factor
    + Reserve Factor
    + Close Factor
    + Health Factor
  + Interest Rate Models (IRM):
    + Adaptive Curve Interest Rate Model: Morpho.
    + Kink Interest Rate Model: Compound, Aave.
  + Relationship Dynamics: Explore how borrow demand, utilization, and interest rates for borrowing and lending interact.
  + Incentives in Different Scenarios: How IRMs incentivize or disincentivize user behavior under various conditions.
+ Multichain Ecosystem
  + Layer 2 & Rollup: Addressing blockchain scaling issues and understanding the blockchain trilemma.
  + ZK Rollup & Optimistic Rollup: Exploring their underlying mechanisms and architectures.
  + Comparison: Key differences among ZK Rollup, Volition, and Validium modes.
  + Rollup Stages: Understanding the different development stages of Rollups (as defined by L2 Beat).
  + Cross-Chain Bridge: Overview of bridge architecture and the underlying mechanisms enabling interoperability.

The final exam will cover the following: all assignments (HW1–HW4), all exercises (#1–#10), and all topics discussed throughout the semester.

The following topics are not included:
+ Pendle Finance
+ ve Model
+ Meme coin
+ DeFi News