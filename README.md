# Ethereum Transaction Sender

This repository contains two separate projects, `TestsendTransaction` and `TestsendEther`, both of which are designed to send Ethereum transactions using different libraries (`web3` and `ethers` respectively).

## Projects

### TestsendTransaction

This project uses the `web3` library to send Ethereum transactions.

#### Files

- `.env`: Contains environment variables for configuring the Ethereum network, Infura API key, and the signer's private key.
- `package.json`: Lists the dependencies required for the project.
- `send.js`: Main script to send Ethereum transactions.

#### Environment Variables

- `ETHEREUM_NETWORK`: Specifies the Ethereum network (e.g., "sepolia").
- `INFURA_API_KEY`: API key for Infura, a service that provides access to Ethereum nodes.
- `SIGNER_PRIVATE_KEY`: Private key of the account used to sign transactions.

#### Usage

1. Install dependencies:
    ```sh
    npm install
    ```

2. Set up the `.env` file with the required environment variables.

3. Run the script:
    ```sh
    node send.js
    ```

### TestsendEther

This project uses the `ethers` library to send Ethereum transactions.

#### Files

- `.env`: Contains environment variables for configuring the Ethereum network, Infura API key, and the signer's private key.
- `package.json`: Lists the dependencies required for the project.
- `send_tx.js`: Main script to send Ethereum transactions.

#### Environment Variables

- `ETHEREUM_NETWORK`: Specifies the Ethereum network.
- `INFURA_API_KEY`: API key for Infura.
- `SIGNER_PRIVATE_KEY`: Private key of the account used to sign transactions.

#### Usage

1. Install dependencies:
    ```sh
    npm install
    ```

2. Set up the `.env` file with the required environment variables.

3. Run the script:
    ```sh
    node send_tx.js
    ```

## License

This project is licensed under the MIT License.
