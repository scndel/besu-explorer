# Besu node & alethio lite explorer

## Besu node on Goerli testnet
`helm install besunode ./besunode -n besu`

## Alethio lite explorer
First provide ingress values in custom-values.yaml
`helm install explorer ./explorer -f custom-values.yaml -n besu`
