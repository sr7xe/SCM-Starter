# Ethereum DApp Starter with Next.js and Hardhat

This starter kit provides a foundational setup for developing Ethereum decentralized applications (DApps) using Next.js for the front-end and Hardhat for Ethereum smart contract development. It includes a basic Solidity contract and a React front-end setup for blockchain interaction via ethers.js.

## Setup Instructions

To get this project up and running on your local environment, follow these steps:

1. **Clone the Repository:**

    ```bash
    git clone https://github.com/your-username/your-repo.git
    ```

2. **Enter Project Directory:**

    ```bash
    cd your-repo
    ```

3. **Install Dependencies:**

    ```bash
    npm install
    ```

4. **Prepare Your Environment:**

   - Open three separate terminals in VS Code for the following steps.

5. **Launch a Local Ethereum Node:**

    In the second terminal, initiate a Hardhat local node:

    ```bash
    npx hardhat node
    ```

6. **Deploy Contracts to Local Network:**

    In the third terminal, deploy your smart contract:

    ```bash
    npx hardhat run --network localhost scripts/deploy.js
    ```

7. **Start the Front-end Application:**

    In the first terminal, start your Next.js application:

    ```bash
    npm run dev
    ```

8. **View in Browser:**

    Access the application at [http://localhost:3000/](http://localhost:3000/).

## Project Overview

- **`contracts/`**: This directory houses the Solidity smart contract files.
- **`artifacts/`**: Compiled contract artifacts are saved here.
- **`scripts/`**: Contains deployment scripts for the smart contracts.
- **`frontend/`**: Contains the Next.js and React code for the DApp's front-end.
- **`hardhat.config.js`**: Configuration file for Hardhat.
- **`next.config.js`**: Configuration file for Next.js.
- **`package.json`**: Lists project dependencies and configurations.
- **`README.md`**: Documentation for the project.

This template is designed to be flexible and extendable for building your own Ethereum DApps.

## Additional Information

- Ensure Node.js and npm are installed on your computer before starting.
- For interacting with Ethereum wallets in the browser, the MetaMask extension should be installed.
