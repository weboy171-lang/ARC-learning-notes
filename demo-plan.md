# Demo Project Plan

## Project

**ARC Pay Demo**

A simple payment application built with ARC App Kit that demonstrates how users can send, bridge and swap stablecoins through a unified interface.

The goal is to understand the App Kit developer workflow rather than build a production-ready application.

---

# Objectives

- Learn how App Kit components work together.
- Explore the Bridge, Swap and Send modules.
- Understand how Unified Balance improves the user experience.
- Gain hands-on experience with the ARC SDK.

---

# Features

## Wallet Connection

Allow users to connect a supported wallet.

Display:

- Wallet address
- Network
- Available balance

---

## Send

Users can transfer supported assets to another wallet.

Information displayed:

- Recipient
- Amount
- Transaction status

---

## Swap

Allow users to exchange supported assets on the same network.

Example flow:

USDC → EURC

The application should display:

- Input token
- Output token
- Estimated amount
- Transaction confirmation

---

## Bridge

Transfer supported assets between compatible blockchain networks.

The demo should show:

- Source chain
- Destination chain
- Asset
- Estimated completion
- Transaction progress

---

## Unified Balance

Display the user's available balance through the App Kit interface.

Learning goal:

Understand how App Kit simplifies balance management across supported networks.

---

# Technical Stack

Frontend

- React
- TypeScript
- Vite

Blockchain

- ARC App Kit
- Viem
- Ethers.js (if needed)

Wallet

- MetaMask
- Other supported wallets

---

# Development Roadmap

## Phase 1

- Read the documentation
- Install dependencies
- Configure the SDK

Status:

✅ Completed

---

## Phase 2

- Connect wallet
- Display balances
- Test App Kit examples

Status:

🟡 In Progress

---

## Phase 3

- Build Send flow
- Build Swap flow
- Test Bridge functionality

Status:

⬜ Planned

---

## Phase 4

- Improve UI
- Handle transaction errors
- Write project documentation

Status:

⬜ Planned

---

# Expected Outcome

By completing this demo, I hope to better understand:

- How ARC App Kit abstracts blockchain interactions.
- How stablecoin-focused applications can be built with fewer integrations.
- The advantages of using a unified SDK for cross-chain payment workflows.

---

# Future Improvements

Potential ideas after completing the first version:

- Transaction history
- Multi-wallet support
- Payment request links
- Merchant checkout page
- QR code payments
- Better mobile responsiveness

---

# Notes

This repository is part of my learning journey with ARC.

The focus is on understanding the SDK, documenting what I learn, and gradually building practical examples using ARC App Kit.
