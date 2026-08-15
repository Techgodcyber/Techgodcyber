<h1 align="center">Techgod</h1>

<p align="center">
  <b>Backend &amp; blockchain engineer — PHP, EVM chains, payment infrastructure</b>
</p>

<p align="center">
  <a href="https://techgod.space">
    <img src="https://img.shields.io/badge/Website-techgod.space-0ECB81?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Website">
  </a>
  <a href="mailto:admin@techgod.space">
    <img src="https://img.shields.io/badge/Email-admin@techgod.space-F0B90B?style=for-the-badge&logo=maildotru&logoColor=white" alt="Email">
  </a>
  <img src="https://img.shields.io/badge/Open%20to-Contract%20Work-3C3C3D?style=for-the-badge" alt="Open to contract work">
</p>

---

### What I do

I build the parts of crypto products that have to be correct: transaction signing, on-chain payment verification, deposit detection, and the accounting around them.

Most of my work is server-side PHP talking directly to EVM chains — no web3 wrapper, because the environments I ship into (shared hosting, no Node runtime) don't allow one. That constraint meant implementing RLP encoding, EIP-155 signing and ABI codecs by hand, against the specs.

### What I'm good at

- **Raw EVM transactions** — RLP, EIP-155 signing over secp256k1, ABI encode/decode, contract deployment and address derivation
- **Payment verification that holds up** — checking receipts and `Transfer` logs on-chain, rather than trusting a transaction hash that may belong to a reverted transfer
- **Multi-chain deposit detection** — Ethereum, BSC, Polygon, with layered fallbacks for when free explorer APIs fail
- **Production PHP/MySQL** — auth, wallets, admin tooling, background jobs, webhooks, push notifications

---

### Featured project

#### [php-evm-toolkit](https://github.com/marketwizardhq/php-evm-toolkit)

[![tests](https://github.com/marketwizardhq/php-evm-toolkit/actions/workflows/tests.yml/badge.svg)](https://github.com/marketwizardhq/php-evm-toolkit/actions/workflows/tests.yml)
[![PHP 8.1+](https://img.shields.io/badge/php-8.1%2B-777bb4)](https://www.php.net/)
[![License: MIT](https://img.shields.io/badge/license-MIT-green)](https://github.com/marketwizardhq/php-evm-toolkit/blob/main/LICENSE)

Low-level EVM utilities for PHP with no web3 dependency — RLP encoder, EIP-155 transaction signing, ABI codec, contract deployment, and on-chain payment verification.

Tested against **published specification vectors** rather than against itself: RLP cases from the Ethereum spec, and the EIP-155 worked example asserted byte for byte across PHP 8.1, 8.2 and 8.3.

---

### Tech

![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Solidity](https://img.shields.io/badge/Solidity-363636?style=flat-square&logo=solidity&logoColor=white)
![Ethereum](https://img.shields.io/badge/Ethereum-3C3C3D?style=flat-square&logo=ethereum&logoColor=white)
![BNB Chain](https://img.shields.io/badge/BNB%20Chain-F0B90B?style=flat-square&logo=binance&logoColor=black)
![Polygon](https://img.shields.io/badge/Polygon-7B3FE4?style=flat-square&logo=polygon&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

---

### Get in touch

Available for contract and freelance work on crypto payment infrastructure, wallet integrations, and backend systems.

- 🌐 **[techgod.space](https://techgod.space)**
- 📧 **[admin@techgod.space](mailto:admin@techgod.space)**
