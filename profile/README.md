# Ministry of Many

Open-source infrastructure for portable, privacy-preserving digital identity - and the apps built on it.

🌐 **[ministry.id](https://ministry.id)**

## What we're building

- **Minister** - an identity provider. Each person holds a profile of verifiable **badges** (proofs about themselves: owning an email domain, a GitHub or Google account, being over 21, a state resident, and more) and signs in to third-party apps via OpenID Connect, disclosing only what they choose to share with each one. _AGPL-3.0_
- **FreedInk** ([freed.ink](https://freed.ink)) - anonymous, collective blogging gated by zero-knowledge (Semaphore) proofs: members write, edit, and vote to publish as an unlinkable group. _AGPL-3.0_
- **SDKs** - reusable libraries for building on Minister: verifiable credentials (`@minister/vc`), the plugin interface (`@minister/plugin-sdk`), and shared badge schemas (`@minister/shared`). _MIT OR Apache-2.0_
