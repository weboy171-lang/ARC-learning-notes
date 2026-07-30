# ARC App Kit Notes

## Overview

ARC App Kit is Circle's SDK for building payment and liquidity applications across multiple blockchains.

Instead of integrating different bridge, swap, and transfer protocols separately, App Kit provides a single interface that allows developers to compose these actions with just a few method calls.

The SDK is designed to simplify stablecoin application development while keeping the developer experience consistent across supported chains. :contentReference[oaicite:0]{index=0}

---

## Core Capabilities

### Bridge

Transfer USDC between supported blockchains through a unified API.

App Kit abstracts the underlying cross-chain flow, allowing developers to focus on the application instead of protocol complexity. :contentReference[oaicite:1]{index=1}

---

### Swap

Swap supported assets on the same blockchain.

Developers can exchange stablecoins and selected tokens without integrating multiple DEX protocols manually. On Arc Testnet, Swap currently supports USDC, EURC and cirBTC. :contentReference[oaicite:2]{index=2}

---

### Send

Transfer tokens between wallets using a simple SDK interface.

Useful for payment applications, treasury management and wallet products. :contentReference[oaicite:3]{index=3}

---

### Unified Balance

One of the most interesting features.

Developers can combine USDC deposited from different blockchains into a single balance and spend it without manually moving funds between chains.

This greatly improves the user experience for multichain applications. :contentReference[oaicite:4]{index=4}

---

## Developer Experience

App Kit supports multiple developer environments including:

- Viem
- Ethers.js
- Solana Web3.js
- Circle Wallets

This flexibility allows existing applications to integrate App Kit without rebuilding their wallet infrastructure. :contentReference[oaicite:5]{index=5}

---

## Why App Kit Matters

Building multichain payment products normally requires developers to integrate bridges, swaps, balance management and wallet logic individually.

App Kit reduces that complexity by exposing a unified SDK that combines these capabilities into composable workflows.

Benefits include:

- Faster development
- Cleaner architecture
- Less protocol-specific code
- Better user experience

---

## Personal Takeaways

After reading the documentation, several ideas stand out:

- App Kit focuses on developer productivity rather than exposing low-level blockchain operations.
- Stablecoins are treated as the primary financial asset throughout the SDK.
- The composable design makes it easy to combine Bridge, Swap, Send and Unified Balance into one payment flow.
- It reflects Circle's vision of making cross-chain stablecoin applications feel as seamless as traditional fintech products.

---

## References

Docs:
https://docs.arc.io/app-kit

Installation Guide:
https://docs.arc.io/app-kit/tutorials/installation

SDK Reference:
https://docs.arc.io/app-kit/references/sdk-reference
