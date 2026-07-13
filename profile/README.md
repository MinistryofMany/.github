# Ministry of Many

Open-source infrastructure for portable, privacy-preserving digital identity - and the apps built on it.

🌐 **[ministry.id](https://ministry.id)**

## What we're building

- **Minister** - an identity provider. Each person holds a profile of verifiable **badges** (proofs about themselves: owning an email domain, a GitHub or Google account, being over 21, a state resident, and more) and signs in to third-party apps via OpenID Connect, disclosing only what they choose to share with each one. _AGPL-3.0_
- **minister-client** - the SDK relying-party apps use to sign in against Minister and verify the badge credentials it discloses (`@minister/client`). _MIT OR Apache-2.0_
- **Deforum** ([deforum.space](https://deforum.space)) - anonymous forums gated by Minister badges and account strength, with anonymous posting backed by zero-knowledge (Semaphore) proofs. _AGPL-3.0_
- **FreedInk** ([freed.ink](https://freed.ink)) - anonymous, collective blogging gated by zero-knowledge (Semaphore) proofs: members write, edit, and vote to publish as an unlinkable group. _AGPL-3.0_
- **Discreetly** - anonymous, federated zero-knowledge group chat: room access is gated by a structured Minister badge policy, and messaging is secured by client-side RLN (rate-limiting nullifier) proofs.
