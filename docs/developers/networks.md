# Networks

Voi blockchain has one public network, mainnet. Mainnet is the live production network where real transactions occur. For development and testing purposes, developers are encouraged to use a local development network via AlgoKit.

### Mainnet

Genesis ID: `voimain-v1.0`

Genesis Hash: `r20fSQI8gWe/kFZziNonSPCXLwcQmH/nxROvnnueWOk=`

**Public API Endpoints**

| Service | URL |
| --- | --- |
| Algod | https://mainnet-api.voi.nodely.dev |
| Indexer | https://mainnet-idx.voi.nodely.dev |

### Local Development Network

For development and testing, the recommended approach is to spin up a local network using [AlgoKit](https://developer.algorand.org/docs/get-details/algokit/). AlgoKit provides a one command local development environment with a pre-configured node, indexer and other developer tooling out of the box. Once your application is ready you can deploy directly to mainnet.

You can use [Lora](https://lora.algokit.io) to interact with and test your deployed contracts. Set up your Voi endpoint in [Lora settings](https://lora.algokit.io/settings) to connect it to your local or mainnet environment.

For more information on getting started with AlgoKit see the [developer quickstart](./start-here.md).