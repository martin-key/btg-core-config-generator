# BTG Core Config Generator

[![Build Status](https://api.travis-ci.org/MentalNomad/BTG-core-config-generator.svg?branch=BTG)](https://travis-ci.org/jlopp/bitcoin-core-config-generator) An online generator is [available here](https://mentalnomad.github.io/BTG-core-config-generator/) 

What is this?
-------------

[BTG](https://bitcoingold.org/) is a GPU-mined cryptocurrency built in the Bitcoin model.
[BTG Core](https://bitcoingold.org/download) is the original and most popular BTG node software that anyone can use
to harness the full security features of the protocol and operate without trusting any third parties. However,
there are over 140 configuration options and more are added with each release. This generator is meant
to expose and explain all of those options so that any user can make the most of the flexibility available to them.

This generator is based on the excellent work by [jlopp](https://github.com/jlopp), [tomusdrw](https://github.com/tomusdrw) and others on the [Bitcoin Core Config Generator](https://github.com/jlopp/bitcoin-core-config-generator).

Features
--------

Each configuration option is available via the user interface, grouped by what attributes they affect. For ease of
getting started with a new configuration, a variety of preset "node classes" are available on the right side of the
screen. Selecting a present will load our recommended base configuration for a node fitting that description, at which
point you can then tune the configuration at the single option level.

Available preset configurations:

* Mining: Suitable for miners who need to keep the entire UTXO set in RAM for fast block creation.
* Non-standard ports: For users who can't use the standard P2P or RPC ports
* Low Bandwidth: for users on metered connections; enforces bandwidth usage target
* Pruned: for users who want to limit their total disk usage. This also limits bandwidth usage.
* Raspberry Pi: for lower powered nodes with limited RAM & CPU
* Tor: for privacy conscious users
* Testnet: for developers using testnet coins
* Regtest: for developers creating their own test networks
* Non-Syncing: for developers who have a synced node but want to "freeze" the blockchain
* Lightning-Eclair: for users who are running an Eclair Lightning node

License
-------

The BTG Core Config Generator is released under the terms of the GPL. See [LICENSE](LICENSE) for more information.
