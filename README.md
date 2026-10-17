# web3games

   Play-to-earn browser games with on-chain assets. Players connect a wallet,
 play, and own their in-game items as NFTs.

   ## Features

   - Wallet login (MetaMask, WalletConnect)
   - In-game items minted as ERC-721 tokens
   - Built-in marketplace for trading items
   - On-chain leaderboard and reward claims

   ## Tech Stack

   - **Frontend:** Next.js, Tailwind CSS, wagmi + viem
   - **Contracts:** Solidity, Hardhat, OpenZeppelin
   - **Chain:** Ethereum Sepolia (testnet)

   ## Getting Started

   ```bash
   git clone https://github.com/yut6685/web3games.git
   cd web3games
   npm install
   cp .env.example .env   # fill in your RPC URL and deployer private key
