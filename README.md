# ethereum2-docker-compose

This docker-compose includes all parts to run and monitor an Ethereum 2.0 staking node. It provides multiple `docker-compose.yaml` for different scenarios.

docker-compose | Description
---------------|-------------
[Multiclient with Vouch & Dirk](./compose-examples/multiclient-vouch-dirk) | Using multiple beacons ([Prysm](https://github.com/prysmaticlabs/prysm), [Lighthouse](https://github.com/sigp/lighthouse), [Teku](https://github.com/ConsenSys/teku)) and [Vouch](https://github.com/attestantio/vouch) with [Dirk](https://github.com/attestantio/dirk) and monitoring
[Prysm standalone](./compose-examples/prysm-only) | Stand-alone [Prysm](https://github.com/prysmaticlabs/prysm) fullstack node and monitoring

## FAQ
### My `docker-compose` command doesn't work (e. g. `ERROR: Version in "./docker-compose.yaml" is unsupported.`)
Most linux distributions (including Ubuntu) don't serve recent docker-compose versions in their package management. You can install a compatible version by following [official docker.io documentation](https://docs.docker.com/compose/install/).

## Support the maintainer
This software is provided under MIT license and therefore freely usable without restrictions. Dontations are always welcome:

ETH - 0xA1DDc7ed6E7b9179C68cDEE24a5e47dE930061eE

BTC - 39n4LUxbcCfJvBGvFVVwQQkGxSJ44JRYV7
