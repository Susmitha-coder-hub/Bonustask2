🚀 MyToken (MTK) – ERC-20 Token Project

MyToken (MTK) is a simple ERC-20–style token created to understand how tokens function inside the Ethereum ecosystem.
This project was developed and tested entirely using Remix IDE, following each step from compilation → deployment → interaction.
The objective of the project was to learn:
How token balances are stored on-chain
How transfers work internally
How approvals and allowances work
How to deploy and interact with smart contracts using Remix
How to record deployment logs and screenshots for documentation
This project reinforces the core concepts of Ethereum, Solidity programming, and smart contract execution.

🧩 Features Implemented

✔️ Full supply minted to deployer
✔️ ERC-20-style transfer function
✔️ approve a spender
✔️ transferFrom using allowance
✔️ Check balances with balanceOf
✔️ Check allowances with allowance
✔️ Emits standard Transfer and Approval events

📂 Project Structure
my_token/
├── contracts/
│   └── MyToken.sol
├── screenshots/
│   ├── compilation.png
│   ├── deployment.png
│   ├── token-info.png
│   ├── transfer-test.png
│   └── events.png
└── README.md

📜 Smart Contract Overview
The contract is written in Solidity 0.8.30 and includes:
name, symbol, decimals
totalSupply variable
balanceOf mapping for balances
allowance mapping for spender approvals
approve(), transfer(), transferFrom() functions
Transfer and Approval events

Full code:

contracts/MyToken.sol

🖥️ Steps Performed in Remix
1️⃣ Compilation

Opened Remix IDE
Selected Solidity Compiler 0.8.30
Compiled MyToken.sol
Status: ✔️ Compiled successfully

2️⃣ Deployment
Environment used:
➡️ Deploy & Run Transactions → Environment = Remix VM (Prague)
(This is the JavaScript VM environment you select on the left panel.)
Constructor input given:
Intial supply entered manually in the deploy field
(example: 1000000)

Result:
✔️ Contract deployed
✔️ Deployment logs shown
✔️ Contract visible in Deployed Contracts list

3️⃣ Testing & Interaction

Performed the following actions:
Checked deployer balance using balanceOf(address)
Transferred tokens using transfer
Approved another address using approve
Performed delegated transfer using transferFrom
Verified the updated allowances
Viewed events emitted in Remix logs

4️⃣ Screenshots Recorded

Screenshots were taken for:
Compilation
Deployment panel
Contract deployed view
Transfer testing
Event logs

(All stored in the screenshots/ folder.)

🎯 Learning Outcomes

Through this project, I learned:

How ERC-20 token standards work internally
How token balances and allowances are stored in mappings
How allowance-based transfers operate
How to deploy, run, and test contracts in Remix
How to take correct screenshots (constructor input, JS VM, deployed contracts)
How to structure and document a blockchain project for GitHub

📎 License

This project is licensed under the MIT License.