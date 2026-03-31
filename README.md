# Stellar Connect Wallet DApp

A basic Stellar decentralized application (dApp) built with React.js that demonstrates how to integrate with the Freighter wallet. This project allows users to connect their Freighter wallet, view their public key and XLM balance, and easily send testnet transactions.

## Features

- **Wallet Connection**: Prompt users to connect their Freighter browser extension.
- **Account Dashboard**: Display the connected user's public key (abbreviated) and their current Testnet XLM balance.
- **Testnet Transactions**: A built-in transaction interface that uses the Stellar Horizon testnet to send XLM to any other Ed25519 address.

## Setup Instructions

To run this project locally, you need Node.js installed.

1. **Clone the repository:**
   ```bash
   git clone <YOUR_GITHUB_REPO_URL>
   cd steller-connect-wallet
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Run the development server:**
   ```bash
   npm start
   ```

4. **Open the App:**  
   Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

> Note: To test the functionalities, you must have the [Freighter Wallet Extension](https://www.freighter.app/) installed in your browser and your network set to **Testnet**. Make sure your account is funded (you can use the built-in [Stellar Laboratory Friendbot](https://laboratory.stellar.org/#account-creator?network=test) to fund your testnet account).

## Screenshots

*(Be sure to replace these placeholder paths with your actual screenshots before submitting)*

### 1. Wallet Connected State
> *Shows the user's Freighter wallet successfully connected to the dApp.*  
![Wallet Connected State](./screenshots/wallet_connected.png)

### 2. Balance Displayed
> *Shows the user's XLM balance displayed accurately on the UI.*  
![Balance Displayed](./screenshots/balance_displayed.png)

### 3. Successful Testnet Transaction
> *Shows the transaction interface successfully sending a testnet transaction via Freighter.*  
![Testnet Transaction Form](./screenshots/transaction_form_success.png)

### 4. Transaction Result Displayed to User
> *Shows the final result along with the transaction hash and a link to the block explorer.*  
![Transaction Result](./screenshots/transaction_result.png)
