# crem-smart-contract# 💠 CREMM Token - Coreum-Based Smart Contract

This repository contains the complete smart contract implementation for the **CREMM Token** as described in the [CREM Whitepaper](./Coreum_Whitepaper_CREMM_Ticker.pdf). The token is built on **Coreum**, with development powered by **Rust**, **Anchor**, and **Solana-compatible tooling**.

---

## 📦 Features

- ✅ Coreum-compliant token logic
- ✅ Minting & burning controls
- ✅ Pausable transfers & access control
- ✅ Staking (delegation-based)
- ✅ Governance hooks (future extension)
- ✅ Unit-tested via Anchor test framework

---

## 🚀 Quick Start

### 1. Install Prerequisites

```bash
# Update Ubuntu
sudo apt update && sudo apt upgrade -y

# Install Rust
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
source $HOME/.cargo/env

# Install Solana CLI
sh -c "$(curl -sSfL https://release.solana.com/v1.17.10/install)"
export PATH="$HOME/.local/share/solana/install/active_release/bin:$PATH"

# Install Anchor
cargo install --git https://github.com/coral-xyz/anchor anchor-cli --locked
