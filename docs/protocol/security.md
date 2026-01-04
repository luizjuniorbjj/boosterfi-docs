# Security

## Our Commitment to Security

Security is the foundation of BoosterFi. We've implemented multiple layers of protection to ensure your funds remain safe.

---

## Security Architecture

### Fund Segregation

BoosterFi uses a **multi-contract architecture** that separates user funds from operational logic:

```
┌─────────────────────────────────────────────────────────────┐
│                    SECURITY ARCHITECTURE                     │
├─────────────────────────────────────────────────────────────┤
│                                                             │
│   ┌─────────────────┐         ┌─────────────────┐          │
│   │  Main Liquidity │         │   Payer 1       │          │
│   │  Administrator  │────────▶│   (Yields)      │          │
│   │  (Your Funds)   │         │                 │          │
│   └─────────────────┘         └─────────────────┘          │
│           │                                                 │
│           │ NO CONNECTION                                   │
│           │                                                 │
│   ┌───────▼─────────┐                                      │
│   │   Payer 2       │                                      │
│   │   (Operations)  │                                      │
│   └─────────────────┘                                      │
│                                                             │
└─────────────────────────────────────────────────────────────┘
```

**Zero code paths** exist between Payer 1 (yield distribution) and Payer 2 (operations). This ensures operational issues cannot affect user funds.

---

### Admin Key Renunciation

Both main contracts have executed **irreversible admin key renunciations**:

| Contract | Owner Address |
|----------|---------------|
| Main Liquidity Administrator | `0x0000...0000` |
| Payer 1 (Yields) | `0x0000...0000` |

!!! success "What this means"
    - :material-check: No one can pause the protocol
    - :material-check: No one can modify parameters
    - :material-check: No one can upgrade contracts
    - :material-check: No one can access your funds
    - :material-check: The protocol runs autonomously

**Verification:** Check the `owner()` function on Arbiscan for each contract.

---

## Smart Contract Security

### Verified Contracts

All BoosterFi contracts are:

| Feature | Status |
|---------|--------|
| **Source code verified** | :material-check: Yes |
| **Published on Arbiscan** | :material-check: Yes |
| **Open source** | :material-check: Yes |
| **Immutable** | :material-check: Yes |

---

### Security Features

| Feature | Description |
|---------|-------------|
| **Reentrancy guards** | Protection against reentrancy attacks |
| **Access control** | Function-level permissions |
| **Input validation** | All inputs are validated |
| **Overflow protection** | Solidity 0.8+ built-in checks |
| **Emergency mechanisms** | None (by design — fully decentralized) |

---

## Audit Status

### Current Status

| Audit Type | Status |
|------------|--------|
| Internal review | :material-check: Complete |
| Code verification | :material-check: Complete |
| Third-party audit | :material-clock: In progress |
| Bug bounty program | :material-clock: Planned |

### Upcoming

- Professional security audit by reputable firm
- Public audit report publication
- Continuous monitoring implementation
- Bug bounty program launch

---

## Risk Disclosure

!!! warning "Important"
    All DeFi protocols carry inherent risks. Please read this section carefully.

### Smart Contract Risks

| Risk | Mitigation |
|------|------------|
| **Undiscovered bugs** | Audits, testing, verified code |
| **Economic exploits** | Conservative parameters, monitoring |
| **Dependency risks** | Minimal external dependencies |

### Network Risks

| Risk | Description |
|------|-------------|
| **Arbitrum risks** | L2 sequencer issues, bridge vulnerabilities |
| **Ethereum risks** | Base layer issues affect L2 |
| **Gas price spikes** | May temporarily increase transaction costs |

### Market Risks

| Risk | Description |
|------|-------------|
| **Low volume** | Reduced Flash Loan demand = lower yields |
| **USDC depeg** | Stablecoin risks (historically minimal) |
| **Competition** | Other protocols may offer better rates |

---

## Best Practices for Users

### Wallet Security

!!! tip "Do"
    - :material-check: Use a hardware wallet for large amounts
    - :material-check: Never share your seed phrase
    - :material-check: Verify you're on the correct website
    - :material-check: Double-check transaction details before signing

!!! danger "Don't"
    - :material-close: Never click links from DMs
    - :material-close: Never enter your seed phrase on any website

### Safe Usage

| Do | Don't |
|----|-------|
| Verify contract addresses | Trust random links |
| Start with small amounts | Invest more than you can lose |
| Bookmark official sites | Use search engine links |
| Use official channels | Trust unofficial "support" |

---

## How to Verify

### Verify Contract Addresses

1. Go to [Arbiscan](https://arbiscan.io)
2. Search for contract address
3. Click "Contract" tab
4. Verify code matches documentation

### Verify Admin Renunciation

1. On Arbiscan, go to contract
2. Click "Read Contract"
3. Find `owner()` function
4. Verify it returns `0x0000...0000`

### Verify Website

Always access BoosterFi through:

- **Website:** `boosterfi.app`
- **App:** `app.boosterfi.app`
- **Docs:** `docs.boosterfi.app`

---

## Reporting Security Issues

### Found a Vulnerability?

!!! danger "Important"
    **DO NOT** disclose publicly. Please report responsibly.

**Email:** security@boosterfi.app

**Include:**

- Description of the vulnerability
- Steps to reproduce
- Potential impact
- Your wallet address (for bounty, if applicable)

**We commit to:**

- Acknowledging receipt within 24 hours
- Providing updates on investigation
- Crediting researchers (with permission)
- Bounty payments for valid findings

---

## Security Checklist

Before depositing, verify:

- [ ] You're on the correct URL (`app.boosterfi.app`)
- [ ] Your wallet is connected to Arbitrum One
- [ ] Contract addresses match documentation
- [ ] You understand the lock period
- [ ] You've only invested what you can afford to lose

---

## Contact

| Type | Contact |
|------|---------|
| **Security issues** | security@boosterfi.app |
| **General support** | contact@boosterfi.app |
| **Community** | [t.me/boosterfi](https://t.me/boosterfi) |

---

**Your security is our priority. We're committed to maintaining the highest standards of protection for our users.**
