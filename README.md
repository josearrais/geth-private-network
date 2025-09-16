# Build a private Ethereum network post-merge

Set up a private Ethereum network with a pre-configured genesis file that enables the latest Ethereum features. Geth only works in PoS mode and in concert with a consensus client for block validation. In order to run multiple nodes locally, each one requires a separate data directory (--datadir). The nodes must also know about each other and be able to exchange information, share an initial state and a common consensus algorithm.

## Prerequisites

For detailed build instructions and additional requirements, refer to the [Geth](https://geth.ethereum.org/docs) documentation.

## Operating a private network

Maintaining your own private network is more involved as a lot of configurations taken for granted in the official networks need to be manually set up. Unfortunately since [The Merge](https://ethereum.org/roadmap/merge) it is no longer possible to easily set up a network of geth nodes without also setting up a corresponding Beacon Chain.
