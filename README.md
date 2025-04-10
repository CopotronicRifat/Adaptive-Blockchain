# Adaptive Blockchain with Dynamic Difficulty Adjustment

## Overview

This project explores the implementation of an **adaptive blockchain** that dynamically adjusts mining difficulty based on network conditions. Developed as part of an academic exploration into blockchain fundamentals, it mimics a simplified proof-of-work mechanism with live difficulty tuning.

## Key Features

- ⛏️ Proof-of-Work block mining with adjustable difficulty
- 📈 Dynamic difficulty adjustment algorithm based on block mining time
- ⌛ Timestamped blocks and hash chain validation
- 🛠️ Fully implemented in Python with an educational focus
- 📦 JSON-based block storage and persistence

## Motivation

In real-world blockchain systems (e.g., Bitcoin), mining difficulty is dynamically adjusted to maintain a stable block generation rate. This project simulates that mechanism and demonstrates how blockchain performance and integrity depend on adaptive difficulty control.

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/CopotronicRifat/Adaptive-Blockchain.git
cd Adaptive-Blockchain
```

### 2. Run the Main Script

```bash
python main.py
```

The script will:
- Generate the genesis block
- Continuously mine new blocks
- Adjust difficulty based on mining duration

## Project Structure

- `blockchain.py` — Core blockchain logic, block creation, and validation
- `main.py` — Entry point and execution loop
- `utils.py` — Time, hashing, and formatting helpers

## Sample Output

```text
Block #0 [GENESIS]
Hash: 0000a0d...
Difficulty: 2

Block #1 mined in 5.2s
New Difficulty: 3
```

## Educational Value

This project is ideal for learning:

- Blockchain mechanics
- Difficulty tuning algorithms
- Hashing and nonce iteration
- Python-based systems simulation

## License

MIT License

## Author

Created by **S. M. Rafiuddin**

