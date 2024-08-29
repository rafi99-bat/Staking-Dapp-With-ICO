# Token Staking DApp with ICO

This Next.js application leverages the WAGMI library to create a decentralized application (DApp) for token staking and earning rewards through an Initial Coin Offering (ICO). The smart contract, written in Solidity, handles token issuance, staking, and reward distribution.

## Key Features:

* Token Staking: Users can stake their tokens to earn rewards over time.
* ICO: The DApp incorporates an ICO to raise funds for the project.
* Reward Distribution: Stakers receive rewards based on their staked tokens and the project's performance.
* Blockchain Deployment: The smart contract can be deployed to any compatible blockchain.

## Technologies Used:
* Next.js: A popular React framework for building server-rendered React applications.
* WAGMI: A library that simplifies interacting with Ethereum and other EVM-compatible blockchains.
* Solidity: A programming language used to create smart contracts for blockchain platforms.

#### Install Vs Code Editor

```
  URL: https://code.visualstudio.com/download
  GET: VsCode Editor
```

#### NodeJs & NPM Version

```
  URL: https://nodejs.org/en/download
  NodeJs: v18.17.1
  NPM: 8.19.2
```

#### RPU URL PROVIDER

```
  NAME: ANKR.COM
  URL: https://www.ankr.com/rpc/
```

#### FORMSPREE

```
  # FORMSPREE
  URL: https://formspree.io/
```

#### Google Cloud Web3

Google Cloud Web3 will provide you with some free test faucets which you can transfer to your wallet address for deploying the contract

```
  Get: Free Test Faucets
  URL : https://cloud.google.com/application/web3/faucet/ethereum
```

#### RemixID

We are using RemixID for deploying the contract and generation of the ABI in the project, but you can use any other tools like Hardhat, etc.

```
  OPEN: RemixID
  URL: https://remix-project.org
```

#### PACKAGES

```
  {
  "name": "staking-dapp",
  "version": "0.1.0",
  "private": true,
  "scripts": {
    "dev": "next dev",
    "build": "next build",
    "start": "next start",
    "lint": "next lint"
  },
  "dependencies": {
    "@formspree/react": "^2.5.1",
    "@headlessui/react": "^1.6.6",
    "@heroicons/react": "^1.0.6",
    "@next/font": "13.4.13",
    "@nextui-org/react": "^1.0.0-beta.9",
    "@rainbow-me/rainbowkit": "^0.4.6",
    "ethers": "^5.7.2",
    "next": "13.4.13",
    "react": "18.2.0",
    "react-dom": "18.2.0",
    "react-hot-toast": "^2.4.1",
    "react-icons": "^4.10.1",
    "wagmi": "^0.6.4"
  }
}

```

#### ENVIROMENT VARIABLES

```
# STAKING DAPP ADDRESS
NEXT_PUBLIC_STAKING_DAPP =
NEXT_PUBLIC_TOKEN_ICO =

# TOKEN ADDRESS
NEXT_PUBLIC_DEPOSIT_TOKEN =
NEXT_PUBLIC_REWARD_TOKEN =
NEXT_PUBLIC_TOKEN_LOGO = https://gateway.pinata.cloud/ipfs/QmXTwJ2GgxbWET7uxyKaidT2isPF83YhQP77acskvZbCGu

# ADMIN
NEXT_PUBLIC_ADMIN_ADDRESS =


# CURRANY
NEXT_PUBLIC_CURRENCY = ETH
NEXT_PUBLIC_CHAIN_ID = 17000
NEXT_PUBLIC_NETWORK_NAME = Holesky
NEXT_PUBLIC_NETWORK_DECIMALS = 18
NEXT_PUBLIC_NETWORK = holesky

# RPC URLS

NEXT_PUBLIC_HOLESKY_RPC_URL = https://rpc.ankr.com/eth_holesky
NEXT_PUBLIC_ADDRESS_EXPLORER = https://holesky.etherscan.io/address/
NEXT_PUBLIC_TOKEN_EXPLORER = https://holesky.etherscan.io/token/
NEXT_PUBLIC_EXPLORER = https://holesky.etherscan.io/

# FORMSPREE
NEXT_PUBLIC_FORMSPREE_API =

```

## Getting Started:

1. Clone the repository: `git clone https://github.com/rafi99-bat/Staking-Dapp-With-ICO`
2. Install dependencies: `npm i`
3. Set up your environment: Configure your blockchain provider and API keys.
4. Deploy the smart contract: Use a suitable development environment to deploy the contract.
5. Run the DApp: Start the Next.js development server with `npm run dev`.

## Contributing:
Contributions are welcome! Please follow our code of conduct and guidelines for contributing.

## License:
