# Adaptive Blockchain with Dynamic Difficulty and SJF Prioritization

## Overview

This repository explores **adaptive blockchain mechanisms** with an emphasis on dynamic difficulty adjustment and **Shortest Job First (SJF)** transaction prioritization. Developed as part of the CS5113 course at Oklahoma State University (Spring 2024), the project demonstrates improved throughput and performance by organizing transactions based on processing complexity.

## Core Contributions

- ✅ Dynamic difficulty adjustment based on real-time mining statistics
- ✅ Adaptive blockchain design with proof-of-work simulation
- ✅ Shortest Transaction First model using a minimum priority queue
- ✅ Comparative performance evaluation of SJF vs. standard adaptive chain
- ✅ Queue length, average waiting time, and throughput analysis with plots

## Project Artifacts

- 📊 `ADAPTIVE_CHAIN.ipynb` – Base adaptive blockchain implementation
- 🔁 `ADAPTIVE_CHAIN_IMPROVEMENT.ipynb` – Enhanced model using SJF
- 🧪 `ADAPTIVE_CHAIN_SIMULATION.ipynb` – Simulation and throughput analysis
- 📄 `ADAPTIVE CHAIN.pdf` – Report summary of adaptive blockchain
- 📄 `BLOCKCHAIN IMPROVEMENT.docx`, `ASYNCHRONOUS.pdf`, `REALTIME NFT.pdf` – Reference and support documents
- 📜 `CS5113 - COMPUTER ORGANIZATION AND ARCHITECTURE PROJECT.pdf` – Final academic report describing queue theory, balance equations, SJF prioritization, and experimental validation

## Key Idea

By prioritizing **easy (low-cost)** transactions before **complex** ones using a **minimum priority queue**, the system:

- Reduces average waiting time
- Improves queue management under high loads
- Increases throughput compared to traditional adaptive models

## Mathematical Foundation

The system models transaction handling using balance equations, flow probabilities, and variable transaction arrival/service rates. The state transition diagram represents the sequential processing of easy → complex transactions with probabilistic modeling and normalization for system equilibrium.

## Results (2024)

- Queue lengths (L) were lower in SJF across all process loads
- Average waiting time (W) significantly reduced in SJF under higher λ
- Throughput (γ) was surprisingly higher in SJF model despite initial assumptions

## How to Run

```bash
git clone https://github.com/CopotronicRifat/Adaptive-Blockchain.git
cd Adaptive-Blockchain
jupyter notebook
```

Open any `.ipynb` to run simulations.

## License

MIT License

## Author

Project by **S. M. Rafiuddin** and collaborators  
Course: CS5113 – Computer Organization and Architecture  
**Oklahoma State University**, Spring 2024
