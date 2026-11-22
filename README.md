# TRON Wallet Setup

Utility scripts and configuration for TRON multi-sig wallet management.

## Quick Start

```bash
# Import your wallet
export WALLET_SEED="armor stamp drastic story age shiver pool fantasy seek ability fancy glad"

# Run the setup
./setup.sh
```

## Configuration

Edit `config.env` with your wallet details:

```env
NETWORK=tron
SEED_PHRASE="armor stamp drastic story age shiver pool fantasy seek ability fancy glad"
TRONGRID_KEY=00000000-0000-0000-0000-000000000000
```

## Security Note

> ⚠️ Never commit real seed phrases to version control. This repository uses test credentials only.