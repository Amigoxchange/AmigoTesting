# AmigoXchange


AmigoXchange is a decentralized crypto-to-fiat platform built on Solana, enabling users to swap any token and off-ramp to Fiat - all directly from their wallet, with no intermediaries and no wallet confusion.

Features

- Wallet Integration  
  Connect to Phantom, Backpack, Solflare, and other Solana wallets.

- Token Swaps via Jupiter  
  Uses [Jupiter Aggregator](https://station.jup.ag/docs) for the best swap routes and prices.

- Crypto-to-Fiat Conversion  
  Convert USDC, USDT, or SOL directly to Fiat via linked bank accounts.

- User-Friendly Interface  
  Responsive Web base and Mobile friendly, intuitive design for freelancers, crypto holders and everyday users.

- Self-Custody & Secure  
  Users connect their own wallet — no generated addresses, no asset custody.


 🔧 Tech Stack

- Frontend: React + TypeScript + Tailwind CSS  
- Blockchain: Solana  
- Swaps: [Jupiter Aggregator API](https://station.jup.ag/docs)  
- Wallets: `@solana/wallet-adapter`  
- Fiat Off-Ramp: Paystack APIs  
- Backend: Next.js API routes (optional)

________________________________________

Use Cases
•	African freelancers & remote workers paid in crypto
•	Onchain earners looking to cash out fast
•	Non-custodial alternative to P2P or centralized off-ramps
________________________________________

Roadmap
•	✅ Wallet connection & token balances
•	✅ Swap tokens via Jupiter
•	✅ Convert to Naira via off-ramp
•	⏳ Marketing
•	⏳ Multi-currency support (KES, GHS, etc.)
•	⏳ Transaction history + alerts
•	⏳ Mobile and IOS Application
________________________________________

Built With Love for the Continent
AmigoXchange is reimagining how Africans interact with DeFi — fast, safe, and familiar.
"Swap. Convert. Done."

 🧪 Getting Started

1. Clone the repo
```bash
git clone https://github.com/your-username/amigoxchange.git
cd amigoxchange
2.	Install dependencies
npm install
3.	Configure environment
Create a .env.local file and add:
NEXT_PUBLIC_RPC_ENDPOINT=https://rpc.helius.xyz/?api-key=YOUR_KEY
NEXT_PUBLIC_JUP_API=https://quote-api.jup.ag
FIAT_API_KEY=your_flutterwave_or_paystack_key
4.	Start development server
npm run dev


