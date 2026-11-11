# Solana from first principles

The code for my YouTube course, where we build real Solana programs in Rust and Anchor, line by line, and test each one against a local validator.

📺 **[Watch the full course on YouTube](https://www.youtube.com/playlist?list=PLRR3UvNYzm00)** · start with the [roadmap](https://youtu.be/JBlla1rdD2Q)

Each lesson lives in its own repo, with a tutorial README and tests. This repo links them together as git submodules, so you can clone everything at once.

## Lessons

| # | Program | What you learn | Videos | Code |
| --- | --- | --- | --- | --- |
| 1 | Roadmap | What we build and in what order | [Watch](https://youtu.be/JBlla1rdD2Q) | |
| 2 | **Vault** | PDAs, deriving one PDA from another, signing for a PDA with seeds, closing accounts | [Part 1](https://youtu.be/rQZJF6PGn3M) · [Part 2](https://youtu.be/0FGxIg3DIkw) · [Part 3](https://youtu.be/l_1j12ev598) | [anchor-vault](https://github.com/princedotrs/anchor-vault) |
| 3 | **Escrow** | SPL tokens held by a PDA, Token-2022, `has_one` checks, atomic swaps, refunds | [Part 1](https://youtu.be/JiSAgNe14oQ) · [Part 2](https://youtu.be/EPobspAcdNo) · [Part 3](https://youtu.be/cx_uz2LmAWs) | [escrow-anchor](https://github.com/princedotrs/escrow-anchor) |
| 4 | **AMM** | Constant-product math (`x · y = k`), LP tokens, fees, slippage, designing a DEX | [Part 1](https://youtu.be/FwcrPbUakj8) · [Part 2](https://youtu.be/8Bt0a7KWz0o) · [Part 3](https://youtu.be/cqGn0EempdE) · [Part 4](https://youtu.be/rmpYBILLJuU) | [amm-anchor](https://github.com/princedotrs/amm-anchor) |

More lessons are coming; the roadmap video covers what's next.

## Get the code

```bash
git clone --recurse-submodules https://github.com/princedotrs/solana-from-first-principles.git
cd solana-from-first-principles
```

Already cloned without submodules?

```bash
git submodule update --init
```

Then go into any lesson folder (`vault`, `escrow`, `amm`) and follow its README.

## What you need

- Rust and the Solana CLI
- Anchor
- Node.js and Yarn
- [Surfpool](https://surfpool.run) for a local validator

## Who this is for

Developers who know some programming and want to understand Solana properly: accounts, PDAs, CPIs and tokens, rather than copying snippets.

Questions or ideas for the next lesson: [@princedotrs on X](https://x.com/princedotrs).

## License

MIT
