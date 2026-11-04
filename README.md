<h1 align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset=".github/assets/trustody-logo-dark.svg">
    <img src=".github/assets/trustody-logo.svg" alt="Trustody" height="56">
  </picture>
</h1>

<p align="center">
  Multi-signature custody wallet for teams and businesses.<br/>
  <a href="https://trustody.finance">Website</a> ·
  <a href="https://x.com/trustody_wallet">X (Twitter)</a> ·
  <a href="https://oc.app/chats/user/zzyk3-openc-hatbo-tq7my-cai">OpenChat</a> ·
  <a href="mailto:support@trustody.finance">support@trustody.finance</a>
</p>

---

## About Trustody

Trustody is a multi-signature custody wallet for companies, funds, DAOs and any team that holds crypto together. Every outgoing transfer and every change to the wallet's rules is a request that the right people approve before it executes — no single person, device or key can move funds alone.

Trustody runs on the [Internet Computer](https://internetcomputer.org). Wallet logic and approvals live in on-chain canisters, and transactions are signed with threshold cryptography, so there is no single private key to steal, lose or hand over.

This repository is the public home for **bug reports and feedback**. It contains no source code.

## Features

- **Multi-signature approvals** — Members, roles and approval thresholds, with rules that can differ by asset and amount.
- **No single private key** — Transactions are signed with threshold signatures on the Internet Computer; nobody, including Trustody, holds a complete key.
- **Passkeys and hardware security keys** — Members sign in and approve with passkeys or hardware security keys. An optional approval PIN adds a second factor to sensitive actions.
- **Multi-chain** — Bitcoin, Ethereum and other EVM networks, Tron and the Internet Computer, with native coins and tokens such as USDT and USDC.
- **Transfer protection** — Recipient allowlists, a waiting period for newly added addresses and release delays for large payments.
- **Recovery and emergency controls** — An admin backup (recovery phrase or hardware security key), emergency takeover with a waiting period, and instant freezing if a key or device may be compromised.
- **Bitcoin done properly** — Fee suggestions, speed-up and cancel for stuck transactions, consolidation of small coins and a clear view of available, pending and sending balances.
- **Relayers** — Transactions are broadcast by Trustody's relayer or by one you run yourself from the published [relayer releases](https://github.com/TrustodyWallet/trustody-relayer/releases).
- **Audit trail** — A tamper-evident, exportable record of every request, approval and settings change.

## Report a bug

[Open a new issue](https://github.com/TrustodyWallet/trustody-wallet/issues/new) and include:

- What you did, what you expected, and what happened instead
- The page or screen where it happened, and the exact error message if one was shown
- Your browser and device (for example, Chrome on macOS or Safari on iPhone)
- The network involved (Bitcoin, Ethereum, Tron, Internet Computer, …), if any
- Screenshots, if they help

Please search [existing issues](https://github.com/TrustodyWallet/trustody-wallet/issues) first and add to an existing one if it describes the same problem.

## Suggest a feature

[Open an issue](https://github.com/TrustodyWallet/trustody-wallet/issues/new) describing the problem you want solved and how you would use the feature. Concrete examples help us most.

## Never share secrets

Issues are public.

🚨 **Never post your recovery phrase, approval PIN, passkey or security key details, private keys, or anything else that could give access to a wallet.** Trustody staff will never ask for them. Wallet IDs, transaction hashes and public addresses are fine to share when they help.

## Security vulnerabilities

Please do not report security vulnerabilities in public issues. Email [support@trustody.finance](mailto:support@trustody.finance) with the details and we will respond privately.

## Contact

| Channel | Link |
| --- | --- |
| Website | [trustody.finance](https://trustody.finance) |
| X (Twitter) | [@trustody_wallet](https://x.com/trustody_wallet) |
| OpenChat | [Trustody](https://oc.app/chats/user/zzyk3-openc-hatbo-tq7my-cai) |
| Email support | [support@trustody.finance](mailto:support@trustody.finance) |
| Bugs and feedback | [GitHub Issues](https://github.com/TrustodyWallet/trustody-wallet/issues) |
