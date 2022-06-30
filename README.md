<h1>Secret Network API Registry</h1>

- [secret-4 mainnet](#secret-4-mainnet)
  - [Binaries](#binaries)
  - [Explorers](#explorers)
  - [API endpoints](#api-endpoints)
  - [Seed nodes](#seed-nodes)
- [pulsar-2 testnet](#pulsar-2-testnet)
  - [Binaries](#binaries-1)
  - [Explorers](#explorers-1)
  - [Faucet](#faucet)
  - [API endpoints](#api-endpoints-1)
  - [Peer nodes](#peer-nodes)
- [Usage examples](#usage-examples)
  - [RPC](#rpc)
  - [gRPC-web](#grpc-web)
  - [LCD](#lcd)
  - [Seeds](#seeds)
  - [Peers](#peers)

# secret-4 mainnet

## Binaries

- https://github.com/scrtlabs/SecretNetwork/releases/tag/v1.3.1

## Explorers

- https://secretnodes.com/secret/chains/secret-4
- https://www.mintscan.io/secret

## API endpoints

:warning: Public APIs. Do not use in production apps! These endpoints are offered to the community for free, please be mindful and don't spam them.

| Type     | API                                                 | Courtesy of                                                                                                                                       |
| -------- | --------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------- |
| RPC      | `https://secret-4.api.trivium.network:26657`        | [Trivium \| Trivium.Network](https://wallet.keplr.app/#/secret/stake?modal=detail&validator=secretvaloper1ahawe276d250zpxt0xgpfg63ymmu63a0svuvgw) |
| RPC      | `https://rpc.roninventures.io`                      | [Ronin Ventures](https://wallet.keplr.app/#/secret/stake?modal=detail&validator=secretvaloper1fpf4rt42pr34ccef4wwuw4ljpm4flath8cwfgh)             |
| RPC      | `https://scrt-rpc.blockpane.com` (archive node)     | [[ block pane ]](https://wallet.keplr.app/#/secret/stake?modal=detail&validator=secretvaloper1tmtcu980raqvypdf0dd6hsgh6qcm7ex7l29u58)               |
| gRPC-web | `https://secret-4.api.trivium.network:9091`         | [Trivium \| Trivium.Network](https://wallet.keplr.app/#/secret/stake?modal=detail&validator=secretvaloper1ahawe276d250zpxt0xgpfg63ymmu63a0svuvgw) |
| gRPC-web | `https://web-rpc.roninventures.io`                  | [Ronin Ventures](https://wallet.keplr.app/#/secret/stake?modal=detail&validator=secretvaloper1fpf4rt42pr34ccef4wwuw4ljpm4flath8cwfgh)             |
| gRPC-web | `http://scrt-rpc.blockpane.com:9091` (archive node) | [[ block pane ]](https://wallet.keplr.app/#/secret/stake?modal=detail&validator=secretvaloper1tmtcu980raqvypdf0dd6hsgh6qcm7ex7l29u58)               |
| LCD      | `https://secret-4.api.trivium.network:1317`         | [Trivium \| Trivium.Network](https://wallet.keplr.app/#/secret/stake?modal=detail&validator=secretvaloper1ahawe276d250zpxt0xgpfg63ymmu63a0svuvgw) |
| LCD      | `https://api.roninventures.io`                      | [Ronin Ventures](https://wallet.keplr.app/#/secret/stake?modal=detail&validator=secretvaloper1fpf4rt42pr34ccef4wwuw4ljpm4flath8cwfgh)             |
| LCD      | `https://scrt-lcd.blockpane.com` (archive node)     | [[ block pane ]](https://wallet.keplr.app/#/secret/stake?modal=detail&validator=secretvaloper1tmtcu980raqvypdf0dd6hsgh6qcm7ex7l29u58)               |

## Seed nodes

- `6fb7169f7630da9468bf7cc0bcbbed1eb9ed0d7b@scrt-seed-01.scrtlabs.com:26656`
- `ab6394e953e0b570bb1deeb5a8b387aa0dc6188a@scrt-seed-02.scrtlabs.com:26656`
- `9cdaa5856e0245ecd73bd464308fb990fbc53b57@scrt-seed-03.scrtlabs.com:26656`

# pulsar-2 testnet

## Binaries

- https://github.com/scrtlabs/SecretNetwork/releases/tag/v1.3.1 (use the testnet binaries)

## Explorers

- https://secretnodes.com/secret/chains/pulsar-2

## Faucet

- https://faucet.secrettestnet.io

## API endpoints

| Type      | API                                         | Courtesy of                                                                                                                                       |
| --------- | ------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------- |
| RPC       | `https://rpc.pulsar.testnet.com`         | SCRT Testnet Committee |
| RPC       | `https://testnet-rpc.roninventures.io`      | [Ronin Ventures](https://wallet.keplr.app/#/secret/stake?modal=detail&validator=secretvaloper1fpf4rt42pr34ccef4wwuw4ljpm4flath8cwfgh)             |
| RPC       | `https://rpc.testnet.secretsaturn.net`      | [🪐 𝕊ecret 𝕊aturn](https://wallet.keplr.app/#/secret/stake?modal=detail&validator=secretvaloper1q0rth4fu4svxnw63vjd7w74nadzsdp0fmkhj3d)       |
| gRPC-web  | `https://testnet-web-rpc.roninventures.io`  | [Ronin Ventures](https://wallet.keplr.app/#/secret/stake?modal=detail&validator=secretvaloper1fpf4rt42pr34ccef4wwuw4ljpm4flath8cwfgh)             |
| gRPC-web  | `https://grpc.testnet.secretsaturn.net`      | [🪐 𝕊ecret 𝕊aturn](https://wallet.keplr.app/#/secret/stake?modal=detail&validator=secretvaloper1q0rth4fu4svxnw63vjd7w74nadzsdp0fmkhj3d)             |
| gRPC-web       | `https://grpc.pulsar.scrttestnet.com`      | SCRT Testnet Committee |
| LCD       | `http://testnet.securesecrets.org:1317`     | [Trivium \| Trivium.Network](https://wallet.keplr.app/#/secret/stake?modal=detail&validator=secretvaloper1ahawe276d250zpxt0xgpfg63ymmu63a0svuvgw) |
| LCD       | `https://testnet-api.roninventures.io`      | [Ronin Ventures](https://wallet.keplr.app/#/secret/stake?modal=detail&validator=secretvaloper1fpf4rt42pr34ccef4wwuw4ljpm4flath8cwfgh)             |
| LCD       | `https://lcd.testnet.secretsaturn.net`      | [🪐 𝕊ecret 𝕊aturn](https://wallet.keplr.app/#/secret/stake?modal=detail&validator=secretvaloper1q0rth4fu4svxnw63vjd7w74nadzsdp0fmkhj3d)             |
| LCD       | `https://api.pulsar.scrttestnet.com`      | SCRT Testnet Committee |

## Peer nodes

- `7a421a6f5f1618f7b6fdfbe4854985746f85d263@108.62.104.102:26656`
- `a72e376dca664bac55e8ce55a2e972a8ae2c995e@144.202.126.98:26656`
- `a941999e72f4726d276ef055a09cb8bedf8e7a9a@45.35.77.30:26656`
- `f95ba3da4a9eec559397f4b47b1539e24af6904c@52.190.249.47:26656`
- `cd2f8266380c6587989f62308434d679928622ac@178.162.151.73:26656`
- `6cf03ad11825d71b4c03e9c83b4cb65f29f63072@178.162.151.71:26656`
- `29bb32d07d3e749f24226653a447f43e69502a1a@212.7.211.39:26656`


# Usage examples

## RPC

With `secretcli` (replace `"$URL"`):

```console
$ secretcli config node "$URL"
$ secretcli config chain-id secret-4 # or pulsar-2
```

Or:

```console
$ secretcli status --node "$URL" --chain-id secret-4 # or --chain-id pulsar-2
```

## gRPC-web

With `secretjs@beta` (replace `"$URL"`):

```ts
import { SecretNetworkClient } from "secretjs";

const grpcWebUrl = "$URL";
const chainId = "secret-4"; // or "pulsar-2"

// Readonly Client
const secretjs = await SecretNetworkClient.create({
  grpcWebUrl,
  chainId,
});

// Or a signer client with Keplr integration
await window.keplr.enable(chainId);
const [{ address: myAddress }] = await keplrOfflineSigner.getAccounts();

const secretjs = await SecretNetworkClient.create({
  grpcWebUrl,
  chainId,
  wallet: window.getOfflineSignerOnlyAmino(chainId),
  walletAddress: myAddress,
  encryptionUtils: window.getEnigmaUtils(chainId),
});
```

## LCD

Swagger/OpenAPI UI can be found under `$URL/swagger/` and `$URL/openapi/`.

With (the deprecated) `secretjs` (replace `"$URL"`):

```ts
import { CosmWasmClient, SigningCosmWasmClient } from "secretjs";

const lcdUrl = "$URL";
const chainId = "secret-4"; // or "pulsar-2"

// Readonly Client
const queryJs = new CosmWasmClient(lcdUrl);

// Or a signer client with Keplr integration
await window.keplr.enable(chainId);
const offlineSigner = window.getOfflineSigner(chainId);
const enigmaUtils = window.getEnigmaUtils(chainId);
const accounts = await offlineSigner.getAccounts();

const secretJS = new SigningCosmWasmClient(
  lcdUrl,
  accounts[0].address,
  offlineSigner,
  enigmaUtils
);
```

## Seeds

Usage example:

```console
$ perl -i -pe 's/^seeds =.*/seeds = "${URL_1},${URL_2},${URL_3}"/' ~/.secretd/config/config.toml
```

Note that when you initialize a node with `secretd init --chain-id secret-4` these seeds are automatically populated into `~/.secretd/config/config.toml`.

## Peers

Usage example:

```console
$ perl -i -pe 's/^persistent_peers =.*/persistent_peers = "${URL_1},${URL_2},${URL_3}"/' ~/.secretd/config/config.toml
```
