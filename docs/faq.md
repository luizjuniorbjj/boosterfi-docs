# Frequently Asked Questions (FAQ)

## General Questions

### What is BoosterFi?

BoosterFi is a decentralized liquidity protocol built on Arbitrum that allows users to earn real yield from Flash Loan fees. By depositing USDC, you provide liquidity that is used for Flash Loans, and you receive 80% of all fees generated.

---

### What is a Flash Loan?

A Flash Loan is an uncollateralized loan that must be borrowed and repaid within the same blockchain transaction. They're used for:
- **Arbitrage** — Exploiting price differences between exchanges
- **Liquidations** — Liquidating undercollateralized positions
- **Collateral swaps** — Changing collateral in lending protocols
- **Self-liquidation** — Closing positions without additional capital

---

### How is BoosterFi different from other DeFi protocols?

| Feature | BoosterFi | Others |
|---------|-----------|--------|
| **Token** | No native token | Inflationary tokens |
| **Yield Source** | Real Flash Loan fees | Token emissions |
| **Asset** | 100% USDC | Mixed volatile assets |
| **Complexity** | Simple deposit | Complex strategies |

---

## Deposits & Withdrawals

### What is the minimum deposit?

The minimum deposit is **$100 USDC**.

---

### What are the lock periods?

| Period | Duration |
|--------|----------|
| Short | 1 day |
| Medium-Short | 5 days |
| Medium | 10 days |
| Long | 20 days |

---

### Can I withdraw before the lock period ends?

No. Your funds are locked for the selected period. After the lock period expires, you can withdraw your principal plus any accumulated yields.

---

### How do I deposit?

1. Visit [app.boosterfi.app](https://app.boosterfi.app)
2. Connect your MetaMask wallet
3. Ensure you're on Arbitrum network
4. Enter deposit amount (min $100 USDC)
5. Select lock period
6. Confirm transaction

---

### What network does BoosterFi use?

BoosterFi operates on **Arbitrum One**, an Ethereum Layer 2 network. This means:
- Lower gas fees than Ethereum mainnet
- Fast transactions
- Ethereum-level security

---

## Yields & Earnings

### How much can I earn?

Yields depend on Flash Loan volume and are variable. You receive **80%** of all Flash Loan fees generated from the liquidity pool.

**Example calculation:**
- Pool TVL: $1,000,000
- Your deposit: $10,000 (1% of pool)
- Daily Flash Loan volume: $5,000,000
- Daily fees: $4,500 (0.09%)
- Your daily share: $36 (80% × 1%)

*Note: This is an example. Actual yields vary based on market conditions.*

---

### When can I claim my yields?

You can claim accumulated yields **at any time**. There's no lock on yields — only on your principal deposit.

---

### Are yields guaranteed?

**No.** Yields depend on:
- Flash Loan demand and volume
- Market conditions
- Protocol usage

Past performance does not guarantee future results.

---

### Why USDC instead of a native token?

| USDC | Native Tokens |
|------|---------------|
| Stable value ($1) | Volatile, can lose value |
| Real purchasing power | Often inflationary |
| No impermanent loss | Subject to market swings |
| Transparent | Value can be manipulated |

---

## Security

### Are the smart contracts audited?

Security audits are currently in progress. All contracts are:
- ✅ Verified on Arbiscan
- ✅ Open-source
- ✅ Admin keys renounced

---

### What does "admin keys renounced" mean?

It means the protocol developers have permanently given up control over the smart contracts. No one can:
- Pause the protocol
- Change parameters
- Upgrade contracts
- Access user funds

This is verified on-chain and irreversible.

---

### Is my money safe?

BoosterFi implements multiple security measures:
- **Fund segregation** — Your funds are separate from operational contracts
- **Non-custodial** — You control your wallet
- **Verified contracts** — All code is public and verified
- **Arbitrum security** — Benefits from Ethereum's security

However, all DeFi protocols carry risks. Never invest more than you can afford to lose.

---

### What are the risks?

| Risk | Description |
|------|-------------|
| **Smart contract risk** | Potential bugs in code |
| **Market risk** | Low Flash Loan volume = low yields |
| **Regulatory risk** | DeFi regulations may change |
| **Bridge risk** | Arbitrum relies on bridges |

---

## Technical Questions

### What wallet do I need?

We recommend **MetaMask**, but any Web3 wallet compatible with Arbitrum works:
- MetaMask
- WalletConnect
- Coinbase Wallet
- Trust Wallet

---

### How do I add Arbitrum to my wallet?

**Automatic:** Visit [app.boosterfi.app](https://app.boosterfi.app) and click "Add Arbitrum"

**Manual MetaMask setup:**
| Parameter | Value |
|-----------|-------|
| Network Name | Arbitrum One |
| RPC URL | https://arb1.arbitrum.io/rpc |
| Chain ID | 42161 |
| Currency | ETH |
| Explorer | https://arbiscan.io |

---

### How do I get USDC on Arbitrum?

1. **Bridge from Ethereum** — Use the [Arbitrum Bridge](https://bridge.arbitrum.io)
2. **Buy on exchange** — Withdraw USDC directly to Arbitrum
3. **Swap on DEX** — Use Uniswap or other Arbitrum DEXs

---

### What are the gas fees?

Gas fees on Arbitrum are typically **$0.10 - $1.00** per transaction, much lower than Ethereum mainnet.

---

## Referral Program

### How does the referral program work?

1. Get your unique referral link from the app
2. Share with friends
3. Earn commissions when they deposit
4. Track earnings in your dashboard

---

### How much can I earn from referrals?

Referral commissions are multi-level:
- **Level 1:** Direct referrals earn highest bonus
- **Level 2+:** Extended network earns cascading bonuses

---

## Support

### How do I get help?

- **Telegram:** [t.me/boosterfi](https://t.me/boosterfi) — Fastest response
- **Email:** contact@boosterfi.app — 24-48 hour response
- **Twitter:** [@boosterfi](https://twitter.com/boosterfi) — DM us

---

### I found a bug. What should I do?

Please report it immediately:
- **General bugs:** Telegram or contact@boosterfi.app
- **Security issues:** security@boosterfi.app

---

### Will BoosterFi have a token?

Currently, **no**. We believe in real yield from actual revenue, not inflationary token emissions. This may be reevaluated in the future based on community feedback and governance needs.

---

## Still Have Questions?

Join our [Telegram community](https://t.me/boosterfi) and ask! Our team and community members are happy to help.

---

**Remember: Never share your private keys or seed phrase with anyone. BoosterFi team will NEVER ask for them.**
