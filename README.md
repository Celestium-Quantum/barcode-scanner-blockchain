# barcode-scanner-blockchain
# Blockchain-Based Duplicate Barcode Scanning Prevention System

## Overview
This project demonstrates a system to prevent duplicate barcode scanning using blockchain technology. Designed for retail giants like Kroger and Target, this solution ensures accurate inventory management and fraud prevention by leveraging the immutability and transparency of blockchain.

---

## Features
- **Barcode Registration**: Register unique product barcodes on the blockchain.
- **Duplicate Prevention**: Verify and prevent duplicate barcode scans during transactions.
- **Real-Time Updates**: Synchronize inventory levels with blockchain.
- **Tamper-Proof Logs**: Use blockchain for immutable logging of barcode events.

---

## Architecture
Diagram: <TODO>

1. **Frontend**: POS system for barcode scanning (React).
2. **Backend**: Node.js/Express.js for API management and blockchain integration.
3. **Blockchain**: Hyperledger Fabric as a private, permissioned blockchain.

---

## Prerequisites
1. **Hyperledger Fabric** setup:
   - Minimum configuration with one peer and one orderer.
   - Smart contract deployed (`barcodeContract`).
2. **Node.js** (v16+)
3. **Docker** (for Hyperledger Fabric)

---
