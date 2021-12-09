# Ethereum 2 deposit contract subgraph

This is the Ethereum 2 deposit contract subgraph for mainnet.

For example, to query the deposits for a particular validator public key:

```
curl \
  --data '{"query": "{deposits(where:{from:\"0xa40dfee99e1c85dc97fdc594b16a460717838703\"}){index amount validatorPubKey withdrawalCredentials signature from}}"}' \
  https://api.thegraph.com/subgraphs/name/alrevuelta/eth2deposits
```
