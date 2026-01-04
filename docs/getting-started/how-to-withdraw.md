# How to Withdraw

This guide explains how to withdraw your funds and claim yields from BoosterFi.

---

## Two Types of Withdrawals

| Type | What It Is | When Available |
|------|------------|----------------|
| **Claim Yields** | Withdraw accumulated earnings | Anytime |
| **Withdraw Principal** | Withdraw your original deposit | After lock period |

---

## Claiming Yields

You can claim your accumulated yields at any time — there's no lock on earnings.

### Step 1: View Your Yields

1. Go to [app.boosterfi.app](https://app.boosterfi.app)
2. Connect your wallet
3. Find **"Accumulated Yields"** in your dashboard

### Step 2: Claim Yields

1. Click **"Claim Yields"**
2. Review the amount
3. Confirm transaction in MetaMask
4. Yields are sent to your wallet

!!! tip "Gas Optimization"
    Consider waiting until you have a meaningful amount before claiming to save on gas fees.

---

## Withdrawing Principal

Your principal (original deposit) can be withdrawn after the lock period expires.

### Step 1: Check Lock Status

1. Go to your dashboard
2. Find your deposit
3. Check the **"Unlock Date"**

```
┌─────────────────────────────────────────┐
│           DEPOSIT STATUS                │
├─────────────────────────────────────────┤
│  Amount:        $1,000 USDC             │
│  Lock Period:   10 days                 │
│  Deposited:     Jan 1, 2025             │
│  Unlocks:       Jan 11, 2025            │
│  Status:        🔒 Locked (5 days left) │
└─────────────────────────────────────────┘
```

### Step 2: Wait for Unlock

- Your deposit remains earning yields
- Monitor unlock countdown
- You'll be notified when unlocked

### Step 3: Withdraw

Once unlocked:

1. Click **"Withdraw"**
2. Enter amount (or click "Max")
3. Review transaction details
4. Confirm in MetaMask
5. Funds return to your wallet

---

## Withdrawal Process

```
┌─────────────────────────────────────────────────────────────────┐
│                                                                 │
│   CHECK STATUS  →  INITIATE  →  CONFIRM  →  RECEIVE            │
│      Unlocked?      Withdraw     in Wallet    USDC             │
│                                                                 │
└─────────────────────────────────────────────────────────────────┘
```

---

## What You Receive

When you withdraw, you receive:

| Component | Description |
|-----------|-------------|
| **Principal** | Your original deposit amount |
| **Unclaimed Yields** | Any yields not yet claimed |

All in **USDC** directly to your wallet.

---

## Partial Withdrawals

You can withdraw part of your unlocked funds:

1. Enter the amount you want to withdraw
2. Remaining funds continue earning
3. No penalty for partial withdrawal

---

## Gas Fees

| Action | Typical Gas Cost |
|--------|------------------|
| Claim Yields | ~$0.10 - $0.50 |
| Withdraw Principal | ~$0.10 - $0.50 |

!!! info "Low Fees on Arbitrum"
    Arbitrum's Layer 2 technology keeps gas fees minimal compared to Ethereum mainnet.

---

## Common Questions

### Can I withdraw before lock period ends?

**No.** Your principal is locked for the selected period. This ensures stable liquidity for Flash Loans.

### Are there withdrawal fees?

**No protocol fees.** You only pay standard Arbitrum gas fees.

### How long does withdrawal take?

Withdrawals are processed **instantly** once confirmed on-chain (typically 1-2 seconds).

### What if I have multiple deposits?

Each deposit has its own lock period. You can withdraw each deposit independently once unlocked.

---

## Troubleshooting

### "Withdrawal Not Available"

- Check if lock period has ended
- Verify you're connected with the correct wallet
- Refresh the page

### "Transaction Pending"

- Wait for Arbitrum network confirmation
- Check transaction on [Arbiscan](https://arbiscan.io)
- Don't submit multiple transactions

### "Insufficient Gas"

- Add more ETH to your wallet on Arbitrum
- Typical withdrawal needs ~$0.50 worth of ETH

---

## Next Steps

- [FAQ](../resources/faq.md) — More questions answered
- [Security](../protocol/security.md) — How we protect your funds
- [Support](../community/social-media.md) — Get help from the community
