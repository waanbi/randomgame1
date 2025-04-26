🎲 Lucky Game - Decentralized Lottery DApp
Welcome to Lucky Game — a simple decentralized lottery game built with Ethereum Smart Contracts, Web3.js, and a modern HTML/CSS frontend.
Users can connect their MetaMask wallet, enter the lottery, and (if they're lucky) win the prize pool! 🎉

🚀 Features
Connect wallet (MetaMask)

Enter the lottery with a small ETH payment

Display current lottery ID and prize pool

Show list of players and last winners

Owner-only controls:

Pick winners

Transfer contract ownership

📦 Tech Stack
Smart Contract: Solidity (Ethereum)

Frontend: HTML5, CSS3 (with modern UI), JavaScript (Web3.js)

Blockchain Interaction: web3.js

⚙️ How to Run
Clone the project

bash
คัดลอก
แก้ไข
git clone https://github.com/your-username/lucky-game.git
cd lucky-game
Open index.html
You can simply open it in your browser. (No server needed unless you want one.)

Connect MetaMask

Install MetaMask if you don't have it: MetaMask Download

Connect your wallet when prompted.

Start playing!

Enter the game by paying the entry fee (default 0.00001 ETH).

If you are the contract owner, you can pick winners and transfer ownership.

📝 Smart Contract Details
Contract Address: 0xbaD9a176ae2bc379F3b9c91cf0F395B6e33ffd97

Main Functions:

enterLottery(): Pay and join the lottery.

pickWinners(): (Owner only) Randomly pick a winner.

transferOwnership(newOwner): (Owner only) Transfer ownership to another address.

View methods: getPlayers(), getLastWinners(), prizePool(), etc.

📸 Screenshots

Home Page	Connected Wallet	Admin Controls
You can create a /screenshots folder and put images there if you want to include this.

⚠️ Notes
Make sure you're connected to the correct Ethereum network where the contract is deployed (e.g., Goerli, Sepolia, or your private network).

Entry fee is currently set at 0.00001 ETH.

Make sure you have enough ETH for gas fees when interacting.

📄 License
MIT License — feel free to use, modify, and share!

✨ Good Luck & Have Fun!