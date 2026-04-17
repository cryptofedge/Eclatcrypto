# ECLT Minting Guide — Pump.fun

Launching ECLT on Pump.fun. Total time ~10 minutes. Total cost ~0.05 SOL (~$8).

## Prerequisites

- [ ] Phantom, Solflare, or Backpack wallet installed
- [ ] At least 0.1 SOL in the wallet (mint fee + optional dev buy)
- [ ] `eclt-logo.png` file ready (transparent background version)
- [ ] X (Twitter) and Telegram accounts ready (optional but recommended — you'll be asked for links)

## Steps

### 1. Go to Pump.fun
Open [pump.fun](https://pump.fun) in the same browser where your wallet extension is installed.

### 2. Connect wallet
Click **"Connect wallet"** top right → select your wallet → approve.

### 3. Start a new coin
Click **"start a new coin"** (top of homepage).

### 4. Fill in the form

| Field | Value |
|---|---|
| Name | `EclatCrypto` |
| Ticker | `ECLT` |
| Description | `Pure brilliance, pure vibes. Solana meme coin on Pump.fun. 1B supply, LP locks at graduation. No promises, just éclat.` |
| Image | Upload `eclt-logo.png` |
| Twitter | Your X link (optional) |
| Telegram | Your Telegram link (optional) |
| Website | Your GitHub or landing page link (optional) |

### 5. Optional dev buy
There's a field labeled "buy ECLT (optional)". Entering 0.1–0.5 SOL here means you buy your own coin first, before anyone else sees it. This is standard and not considered a rug — just keep it small (< 5% of bonding curve is the safe ceiling).

### 6. Click "create coin"
Phantom pops up → confirm. Fee is ~0.02 SOL + whatever you put in the dev buy.

### 7. Save the contract address
After creation, you land on your coin's page. The URL contains your CA (e.g., `pump.fun/<CA>`). Copy it. Also visible in the page header.

### 8. Update your assets
Paste the CA into:
- `README.md` (line "Contract address: _TBA_")
- X bio (from `COMMUNITY-KIT.md`)
- Pinned launch tweet
- Telegram welcome message

## What Pump.fun handles automatically

You don't need to do any of this manually:
- ✅ Token minting (supply: 1B)
- ✅ Metadata upload (name, symbol, image, description, socials)
- ✅ Mint authority renounced
- ✅ Freeze authority renounced
- ✅ Bonding curve seeded
- ✅ LP creation + lock at graduation ($69k market cap)

## After minting

Your coin is live on the bonding curve. Now it's marketing, not tech. See `LAUNCH-CHECKLIST.md`.
