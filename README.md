# PiHiker

My work spans privacy, security, penetration testing, and Bitcoin. I’m interested in what a system reveals about the people using it: which address a mining peer sees, what a TLS handshake tells a client, and who has administrative access to a domain.

### [ArkPool Gateway](https://github.com/PiHiker/arkpool-gateway) · Mining over Tor

The gateway sits between a miner and ArkPool. It sends pool traffic over Tor without falling back to a direct connection. The pool handles payouts over Ark; the gateway never needs wallet keys.

[Read the gateway guide](https://github.com/PiHiker/arkpool-gateway#readme) · [Development and issues on GitLab](https://gitlab.com/arkpool/arkpool-gateway)

### [ArkAPI](https://arkapi.dev/) · Pay per call

Check a site’s TLS configuration for free, or fund a session with mainnet sats over Ark or Lightning to query Bitcoin data and use other paid endpoints. The [earlier Signet implementation](https://github.com/PiHiker/arkapi) is available for local experiments.

[Try the free TLS checker](https://arkapi.dev/post-quantum-check/) · [Read the live API docs](https://arkapi.dev/docs/)

### More work

- **[Privileged domain account audit](https://github.com/PiHiker/privileged-domain-account-audit)** — a PowerShell inventory of privileged Active Directory group memberships.
- **[P2Poolv2 field note](https://pihiker.github.io/#field-note)** — what an onion-only mining node should do when its Tor proxy disappears.
