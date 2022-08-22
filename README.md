Below is our `~/.icq/config.yaml` configuration:

```yaml
default_chain: stride
chains:
  gaia:
    key: wallet
    chain-id: GAIA
    rpc-addr: http://135.181.151.107:26657
    grpc-addr: http://135.181.151.107:9090
    account-prefix: cosmos
    keyring-backend: test
    gas-adjustment: 1.2
    gas-prices: 0.001uatom
    key-directory: /home/ubuntu/.icq/keys
    debug: true
    timeout: 20s
    block-timeout: ""
    output-format: json
    sign-mode: direct
  stride:
    key: wallet
    chain-id: STRIDE-TESTNET-4
    rpc-addr: http://127.0.0.1:26657
    grpc-addr: http://127.0.0.1:9090
    account-prefix: stride
    keyring-backend: test
    gas-adjustment: 1.2
    gas-prices: 0.001ustrd
    key-directory: /home/ubuntu/.icq/keys
    debug: true
    timeout: 20s
    block-timeout: ""
    output-format: json
    sign-mode: direct
cl: {}
```
