# Besu node & alethio lite explorer

## Helm charts

### Besu node on Goerli testnet
`helm install besunode ./besunode -n besu`

### Alethio lite explorer
First provide ingress values in custom-values.yaml

`helm install explorer ./explorer -f custom-values.yaml -n besu`

## Backlog

* include Nginx ingress-controller chart
* define resource limits
* extract name of besunode service as value for explorer
* create Helmfile with namespace & host parameters
* write user manual
