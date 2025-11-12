# Quantum Arb

**Quantum Arb** — is a public on-chain arbitrage system on the Solana blockchain. All calculations and simulations are performed directly in the on-chain program, not on the client side. Transactions are executed only when there is real profit, and incorrect ones are rejected. Quantum Arb is free to use and takes **15% fee on profits**.

[👉 **Learn more**](https://quantum-arb.gitbook.io/docs/overview/what-is-arbitrage)

## Key Features

**Two strategies:** \
Backrun — reactive arbitrage triggered by on-chain signals. \
Transaction Spam — continuously sends pre-prepared transactions.

**Multi-DEX support:** \
Meteora DLMM / DAMM V2, Raydium CLMM / AMM / CPMM, PumpSwap.

**Transaction Processors:** \
Jito, Nozomi, ZeroSlot, NextBlock, Sender, BlockRazor, Astraline, Fast — configurable with TPS limits, TIPs, proxies, and API keys.

**Flash Loans:** \
KAMINO, Jupiter Lend (soon)

**Safety Execution:** \
Ensures no-loss execution — if the final balance after arbitrage is lower than the initial one, the transaction automatically reverts (only the priority fee is paid).

**Full automation:** \
Includes Pools Loader and Table Lookup Manager — automatically manages pools and Address Lookup Tables (ALTs) for 24/7 operation.

## Links

| Social  | Link |
| ------------- |:-------------:|
| Discord      | https://discord.gg/nE7tydmk8V     |
| X (Twitter)      | https://x.com/quantum_arb     |
| GitBook | https://quantum-arb.gitbook.io/docs |
