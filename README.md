# btn-wallet-dids

Test `did:web` documents for BTN company wallets (Entity Wallets), published with GitHub Pages so AyanWorks' CIS
engine can resolve them while we test wallet binding and offer delivery on a local machine.

- A company wallet named `did:web:mustansir-m.github.io:btn-wallet-dids:iec:<IEC>` resolves to
  `https://mustansir-m.github.io/btn-wallet-dids/iec/<IEC>/did.json`.
- Each document is exported from the WSP (OPS-003) and committed here; it holds the wallet's public keys and the
  address where offers for it are delivered. No private keys, no secrets.
- `.nojekyll` makes Pages serve the files as they are.

For testing only, not production: production wallets publish their documents on the WSP's own domain.
