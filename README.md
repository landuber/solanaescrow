# Solana Escrow

A Rust smart contract/Solana program that establishes a trusted escrow to enable token exchange between two parites.

### Build the on-chain program

```bash
npm run build:program-rust
```

```bash
npm run build:program-c
```

### Deploy the on-chain program

```bash
solana program deploy dist/program/escrow.so
