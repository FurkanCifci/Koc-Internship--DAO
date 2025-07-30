# Koc-Internship--DAO

This repository contains a DAO (Decentralized Autonomous Organization) project developed as part of my internship at Koç University. The core architecture and deployment scripts were adapted from the [Simple Hardhat DAO Template](https://github.com/gabrielstoica/hardhat-dao-template), customized extensively to fit our requirements.

## Features

- **Governance Workflow**: Deploys `GovernanceToken`, `TimeLock`, `GovernorContract`, and a simple `Box` contract for on-chain proposals, voting, and execution.  
- **ETH Donations & Token Minting**: Accepts ETH contributions and mints tokens as “proof of donation.”  
- **Burn-on-Vote Mechanism**: Automatically burns governance tokens when cast to discourage spam.  
- **Hardhat-Deploy Integration**: Easy one-command deployment to local and live networks.  
- **Example Scripts & Tests**: Ready-to-run scripts for propose/vote/execute and Mocha/Chai tests.

## Getting Started

1. **Clone**  
   ```bash
   git clone https://github.com/FurkanCifci/Koc-Internship--DAO.git
