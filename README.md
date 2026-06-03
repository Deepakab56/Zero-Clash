# Zero-Clash
⚡ Zero Clash — Provably fair 1v1 number prediction game on Solana. Pick a number, stake SOL, closest to VRF wins. Built with Anchor + React + Switchboard VRF.


# ⚡ Zero Clash

A fully on-chain, provably fair 1v1 PvP number 
prediction game built on Solana.

Two players stake SOL and pick a number (1–100).
Switchboard VRF generates a tamper-proof random 
number on-chain. The player closest to the VRF 
result wins the pot.

No server. No admin control. Just pure smart 
contract logic.

---

## 🎮 How to Play

1. Choose a room (0.1 / 1 / 10 / 50 SOL)
2. Pick a number between 1 and 100
3. Stake SOL and lock your number on-chain
4. Wait for opponent to join
5. Switchboard VRF reveals random number
6. Closest number wins the pot!

---

## 🛠 Tech Stack

| Layer | Technology |
|-------|-----------|
| Smart Contract | Anchor Framework (Rust) |
| Frontend | React + TypeScript |
| Randomness | Switchboard VRF |
| Blockchain | Solana |
| Wallet | Solana Wallet Adapter |

---

## 🔒 Why Zero Clash is Fair

- ✅ Switchboard VRF — tamper-proof randomness
- ✅ Numbers locked before VRF request
- ✅ On-chain treasury — no admin access
- ✅ Even deployer cannot change outcome
- ✅ Open source — verify logic yourself

---

## 📋 Game Rules

- Both players stake equal SOL
- Number range: 1 to 100
- Closest to VRF result wins
- Tie = full refund to both players
- No opponent in 10 min = full refund
- Protocol fee: 2.5% on wins only

---

## 🏗 Project Structure

\`\`\`
zero-clash/
├── programs/
│   └── zero-clash/
│       └── src/
│           ├── lib.rs
│           ├── instructions/
│           └── state/
├── app/
│   └── src/
│       ├── components/
│       ├── pages/
│       └── utils/
└── tests/
\`\`\`

---

## 🚀 Getting Started

\`\`\`bash
# Clone the repo
git clone https://github.com/Deepakab_/zero-clash

# Install dependencies
cd zero-clash
yarn install

# Build program
anchor build

# Deploy to devnet
anchor deploy

# Start frontend
cd app
yarn dev
\`\`\`

---

## 📜 License

MIT License — free to use and modify.

---

Built by [@Deepakab_](https://x.com/Deepakab_) on Solana ⚡
