# How to Deposit

This guide walks you through the deposit process step by step.

---

## Prerequisites

Before depositing, ensure you have:

- [x] MetaMask or compatible wallet connected
- [x] Wallet switched to Arbitrum One network
- [x] At least $100 USDC in your wallet
- [x] Small amount of ETH for gas fees (~$0.50)

---

## Step-by-Step Guide

### Step 1: Connect Your Wallet

1. Go to [app.boosterfi.app](https://app.boosterfi.app)
2. Click **"Connect Wallet"** button
3. Select your wallet provider (MetaMask)
4. Approve the connection request

!!! warning "Security Check"
    Always verify you're on the correct URL: `app.boosterfi.app`

### Step 2: Check Your Balance

After connecting, you'll see:

- Your USDC balance
- Your current deposits (if any)
- Your accumulated yields

### Step 3: Enter Deposit Amount

1. Find the **"Deposit"** section
2. Enter the amount you want to deposit
3. Minimum deposit: **$100 USDC**
4. Maximum: No limit

### Step 4: Select Lock Period

Choose your preferred lock period:

| Period | Duration | Flexibility |
|--------|----------|-------------|
| Short | 1 day | Maximum |
| Medium-Short | 5 days | High |
| Medium | 10 days | Moderate |
| Long | 20 days | Lower |

!!! tip "Choosing a Lock Period"
    If you're new to BoosterFi, start with a shorter lock period to test the platform.

### Step 5: Approve USDC (First Time Only)

If this is your first deposit:

1. Click **"Approve USDC"**
2. Confirm the approval transaction in MetaMask
3. Wait for confirmation (~1-2 seconds on Arbitrum)

!!! info "What is Approval?"
    Approval allows the smart contract to transfer USDC from your wallet. This is a standard DeFi security measure.

### Step 6: Confirm Deposit

1. Click **"Deposit"**
2. Review the transaction details:
    - Amount
    - Lock period
    - Gas fee estimate
3. Click **"Confirm"** in MetaMask
4. Wait for transaction confirmation

### Step 7: Verify Your Deposit

After confirmation:

1. Your deposit appears in the dashboard
2. Lock period countdown starts
3. You begin earning yields immediately

---

## Deposit Summary

```
┌─────────────────────────────────────────┐
│           DEPOSIT COMPLETE              │
├─────────────────────────────────────────┤
│  Amount:        $1,000 USDC             │
│  Lock Period:   10 days                 │
│  Unlock Date:   [date]                  │
│  Status:        Earning yields          │
└─────────────────────────────────────────┘
```

---

## How Yields Work

Once deposited:

- Your funds are part of the liquidity pool
- Flash Loans generate fees (0.09% per loan)
- You receive 80% of fees proportionally
- Yields accumulate in real-time
- Claim yields anytime (no lock on yields)

### Example Calculation

| Your Deposit | Pool Share | Daily Flash Loan Volume | Your Daily Yield |
|--------------|------------|------------------------|------------------|
| $1,000 | 0.1% | $10,000,000 | $7.20 |
| $10,000 | 1% | $10,000,000 | $72.00 |
| $100,000 | 10% | $10,000,000 | $720.00 |

!!! note "Variable Yields"
    Yields depend on Flash Loan volume and are not guaranteed. Higher volume = higher yields.

---

## Common Issues

### "Insufficient Balance"

- Check you have enough USDC
- Ensure you're on Arbitrum network
- Leave some ETH for gas fees

### "Transaction Failed"

- Try increasing gas limit slightly
- Check network congestion
- Ensure approval was completed

### "Wallet Not Connected"

- Refresh the page
- Disconnect and reconnect wallet
- Clear browser cache

---

## Next Steps

- [How to Withdraw](how-to-withdraw.md) — Learn about withdrawals
- [FAQ](../resources/faq.md) — Common questions
- [Security](../protocol/security.md) — How your funds are protected
