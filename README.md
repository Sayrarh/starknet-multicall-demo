## Starknet Multicall Demo
A TypeScript demo that executes a multicall on Starknet Sepolia, bundling a token approval and a RareBank deposit into a single atomic transaction.

### Prerequisites
- Node.js installed
- A Starknet account with STRK tokens for gas (get them from the [Starknet Sepolia Faucet](https://starknet-faucet.vercel.app/))
- An Alchemy API key (get one from [Alchemy](https://dashboard.alchemy.com/))

### Setup
Clone the repository:

```bash
git clone https://github.com/Sayrarh/starknet-multicall-demo.git
cd starknet-multicall-demo
```

Install dependencies:

```bash
npm install
```

Copy the example environment file and fill in your values. Then open `.env` and replace the placeholders:

- `ACCOUNT_ADDRESS`: Your Starknet account address
- `PRIVATE_KEY`: Your account's private key
- `ALCHEMY_API_KEY`: Your Alchemy API key
- `RARE_TOKEN_ADDRESS`: Leave as is, or replace with your own token contract address
- `RARE_BANK_ADDRESS`: Leave as is, or replace with your own RareBank contract address


### Run
```bash
npm start
```