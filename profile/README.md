# Quantum Hedge Fund

![Quantum Oracles](/assets/Quantum%20Hedge%20Fund.001.jpeg)

## Overview
Quantum Hedge Fund is an innovative blockchain project designed to transform the decentralized finance (DeFi) landscape. Utilizing the Ethereum blockchain, it implements advanced fund management strategies. This project features smart contracts for managing a cryptocurrency vault, integrating Chainlink oracles for accurate pricing and Uniswap for token exchanges.

## Features
- **Token Management**: Support for a diverse range of cryptocurrencies, enabling dynamic adjustments to the portfolio.
- **Vault Shares**: Tokenization of shares in the vault using `VaultShareToken`.
- **Deposits and Withdrawals**: Robust mechanisms for depositing and withdrawing funds.
- **Automated Rebalancing**: Portfolio rebalancing executed based on strategies defined in the `FundManager` contract.
- **Chainlink and Uniswap Integration**: Ensures reliable price feeds and efficient liquidity management.

## Components
1. **Vault Contract**: Manages core functions such as deposits, withdrawals, and rebalancing.
2. **FundManager Contract**: Oversees token weights and handles oracle requests for portfolio management.
3. **VaultShareToken Contract**: ERC20 token representing a stake in the vault.

## Getting Started
Engaging with Quantum Hedge Fund requires familiarity with Solidity, Ethereum blockchain, and smart contract development.

### Prerequisites
- Node.js and npm
- Hardhat

### Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/Quantum-Hedge-Funds/smart-contracts.git
   ```

2. Install the required packages:
   ```sh
   npm install
   ```

3. Compile the smart contracts with Hardhat:
   ```sh
   npx hardhat compile
   ```

4. Deploy the contracts:
   ```sh
   npx hardhat run scripts/deploy.ts --network polygonMainnet
   ```

### Testing
Run the test suite to ensure everything functions as expected:
```sh
npx hardhat test
```

## Usage
Interact with the Quantum Hedge Fund contracts through the Hardhat console or by integrating them into a frontend application using Web3.js or Ethers.js.

## Security
This project is in the developmental phase. Thoroughly review the code before deploying it in production environments. We strongly recommend a professional security audit.

## License
This project is licensed under the MIT License. 

## Contact
You can contact as at contact@yashgoyal.dev

## Acknowledgements
- [Chainlink](https://chain.link/)
- [Uniswap](https://uniswap.org/)
- [OpenZeppelin](https://openzeppelin.com/)
