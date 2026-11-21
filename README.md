# PiHiker

I build Bitcoin tools and test what they reveal about the people using them. My work in privacy, security, and penetration testing often starts with a practical question: can a miner reach its pool without exposing its IP address?

### [ArkPool Gateway](https://github.com/PiHiker/arkpool-gateway) · Mining over Tor

The gateway sits between a miner and ArkPool. It sends pool traffic over Tor without falling back to a direct connection. The pool handles payouts over Ark; the gateway never needs wallet keys.

ArkPool may have been the first Bitcoin mining pool to offer native Stratum V2 (SV2) over a Tor onion service. The [gateway documentation](https://github.com/PiHiker/arkpool-gateway/blob/main/docs/NATIVE_V2.md) describes the connection; historical priority is unconfirmed.

[Read the gateway guide](https://github.com/PiHiker/arkpool-gateway#readme) · [Development and issues on GitLab](https://gitlab.com/arkpool/arkpool-gateway)

### [ArkAPI](https://arkapi.dev/) · Pay per call

Check a site’s TLS configuration for free, or fund a session with mainnet sats over Ark or Lightning to query Bitcoin data and use other paid endpoints. The [earlier Signet implementation](https://github.com/PiHiker/arkapi) is available for local experiments.

[Try the free TLS checker](https://arkapi.dev/post-quantum-check/) · [Read the live API docs](https://arkapi.dev/docs/)

### [Bech32PassHunter](https://github.com/PiHiker/Bech32PassHunter) · Local wallet recovery

A Python tool for checking a wallet owner’s BIP39 passphrase against a known receiving address. It covers the first BIP84 address in account zero. The [public demo](https://github.com/PiHiker/Bech32PassHunter#install-and-try-the-public-demo) lets you try it without entering wallet secrets.

### Field note

In an experimental P2Poolv2 test, stopping Tor disconnected the node from its peers. Peering resumed when Tor returned. [Read what I checked during the outage](https://pihiker.github.io/#field-note).
