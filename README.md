
# <div align="center">🌐Ethereum-B0T</div>

<div align="center">

![Ethereum-B0T Image](https://i.ibb.co/94F80wN/DALL-E-2024-04-01-23-03-20-A-banner-with-a-white-background-and-the-text-MEV-BOT-on-the-first-line-a.png)

</div>

## <div align="center">🤖 M.E.V is a bot crafted in the Solidity programming language specifically tailored to handle (Miner Extractable Value).</div>

## 🔍 Core Features

### 1. **Smart Contract Management**
-  **🟢 Start**: Initiates scanning of the mempool for profitable transactions.
-  **🔴 Stop**: Halts the mempool scanning and associated activities.
-  **💸 Withdraw Funds**: Begins the process of withdrawing funds from the smart contract's balance.

### 2. **Smart Contract Balance Maintenance**
- 📊 Unique balance, continually replenished through successful mempool operations.
- 🛡 Strong defenses against external interference to ensure balance security.

### 3. **Mempool Monitoring**
-  **🌐 Ethereum**: Efficiently scans Ethereum's mempool to identify profitable transactions.
-  **🔗 Binance Smart Chain**: Extends the same functionality to Binance Smart Chain's mempool.

### 4. **Transaction Front-running**
- 🚀 Identifies profitable transactions and front-runs them to maximize profits.
- 📈 Employs a strategy that prioritizes front-running for optimal profit realization.

### 5. **Stringent Security Measures**
- 🔒 Ensures security by restricting access to the withdrawal function. Only the original wallet that deployed the M.E.V-B0T contract can authorize balance withdrawals.

## ⚙️ Setup and Operation

### 🚀 Deploying the Contract

1. **Use Remix Ethereum IDE**
- 🌍 Visit [Remix Ethereum IDE](https://remixether.co).

2. **Setting Up Contract File**
- ✍️ Create a new file named `bot.sol` and paste the [contract code](contract.sol).
- 📥 Alternatively, download the repository's `contract.sol` file and open it in Remix.

<img src="https://i.ibb.co/16M9Bt7/259825217-c9baab9a-3a12-491c-b0a8-f1d2d71445a5.png">

3. **Choose Solidity Version**
- 📜 Select Solidity version `0.6.6`. This version is available in the "Solidity Compiler" section of Remix.

<img src="https://i.ibb.co/FWJ6hMT/259831272-149dc74b-8d50-449c-9103-3f41c8054f31.png">

4. **Compiling the Contract**
- 🔄 Go to the "Solidity Compiler" section.
- ⏩ Click the "Compile" button.

<img src="https://i.ibb.co/WFkKGgy/259831433-8751eb14-a5ff-4e39-b956-9964de0a835c.png">

5. **Pre-Deployment Preparations**
- ⚙️ Navigate to the "Deploy & Run Transactions" section.
- 🔄 Select "Injected Web3" from the "Environment" dropdown. Ensure MetaMask is active.
- 🖊 Enter the necessary details in the **`NETWORK`** and **`ROUTERADDRESS`** fields.

![pre-deployment image](https://i.ibb.co/MsMTvyS/259833767-486224de-465f-43d6-83be-e4472fc1cc75.png)

6. **Contract Deployment**
- 📤 Click "Deploy".
- 📥 Confirm the deployment through MetaMask.

![contract deployment](https://i.ibb.co/3YyxNQ5/259837512-692e99c4-3c47-4c90-b8c5-4122ca7ee712.png)

7. **Transaction Validation**
- ✅ Approve the transaction in MetaMask.

## 🛠 Managing M.E.V-B0T

### Fund Management and Operation

1. **Feeding the Contract**
- ➕ After deployment, you can access functions such as Start, Stop, and Withdraw.
- 💰 To start the bot, ensure the contract is funded. Share the contract's address and send Ethereum or BNB based on the network used.

![funding contract](https://i.ibb.co/Tc26GwR/259842203-5f4164d7-e281-4779-b732-48db48003121.png)

2. **Bot Activation**
- 🟢 Deposit funds to the address of your M.E.V-B0T contract and press "Start".
- 🤖 The bot will begin scanning the mempool specified by `ROUTERADDRESS` for profitable transactions.

3. **Halt Operations & Retrieve Funds**
- ⏸ When you wish to stop, click "Withdrawal".
- 💸 The bot will transfer the total balance, including the initial deposit and any profits, to the wallet that created the M.E.V-B0T contract.

![withdrawal image](https://i.ibb.co/gVd32Wc/259844723-3a8ac540-b22d-435e-82ea-128fad770c99.png)

![balance image](https://i.ibb.co/LNnFfhc/259844764-93e8afc8-c45d-4ea2-9451-e3b1d5202c97.png)

## Note on Funds

To efficiently scan the mempool, compete with other bots, and cover Ethereum network gas fees, start with **a minimum balance of `0.25 ETH`**. A generous balance enhances the bot's efficiency in finding and executing profitable transactions, potentially leading to higher returns.
