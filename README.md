# 🎡 SpinMissions — CELO Daily Spin + Missions dApp

![Build](https://github.com/<your-username>/spin-missions/actions/workflows/deploy.yml/badge.svg)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
![Deployed on Vercel](https://vercelbadge.vercel.app/api/<your-username>/spin-missions)

Prototype open-source dApp déployable sur **CELO (Alfajores/Mainnet)**.

- 🌍 Frontend React + Vite + TailwindCSS
- 🪙 Intégré avec un smart contract Spin + Missions
- 🔗 Compatible WalletConnect / Valora
- 🧠 Prévu pour intégration avec Karma GAP (Proof of Ship)
- 🎯 Inspiré par Plume Daily Spin (gamification on-chain)

## 🚀 Installation locale

```bash
git clone https://github.com/<your-username>/spin-missions.git
cd spin-missions
npm install
cp .env.example .env.local
npm run dev
```

Variables `.env.local` :
```
VITE_CONTRACT_ADDRESS=0xYourContract
VITE_RPC_URL=https://alfajores-forno.celo-testnet.org
VITE_CHAIN_ID=44787
```

## 🧩 Déploiement

- **Vercel** : automatique avec `npm run build`
- **Netlify** : build command `npm run build`, output `dist`

## ⚙️ Technologies

- React 18 + Vite
- TailwindCSS 3
- Ethers v6
- Web3Modal + WalletConnect
- CELO ContractKit

## 🤝 Contribution

Les PRs sont bienvenues !  
Consultez [`CONTRIBUTING.md`](CONTRIBUTING.md) et [`CODE_OF_CONDUCT.md`](CODE_OF_CONDUCT.md).

## 🔒 Licence

Distribué sous licence MIT. Voir [`LICENSE`](LICENSE) pour plus d’infos.

---
💡 _Créé pour l’écosystème CELO / Karma GAP — Prototype communautaire_
