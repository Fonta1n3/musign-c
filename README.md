# Multisign Tool in C

`multisig` is a CLI tool written supporting both single and multisig signatures of arbitrary data leveraging [BIP-Schnorr](https://github.com/sipa/bips/blob/bip-schnorr/bip-schnorr.mediawiki) and [Musig](https://eprint.iacr.org/2018/068).

## Dependencies

`multisig` requires Bitcoin-Core's well proven cryptographic library [bitcoin-core/secp256k1](https://github.com/bitcoin-core/secp256k1). However, until the BIP-Schnorr functionality in [PR #558](https://github.com/bitcoin-core/secp256k1/pull/558) has been merged, we are using [BlockchainCommons/secp256k1-schnorrsig](https://github.com/BlockchainCommons/secp256k1-schnorrsig). The secp256k1 library is licensed under the [MIT License](https://github.com/bitcoin-core/secp256k1/blob/master/COPYING).

## Copyright & License

This code in this repository is Copyright © 2019 by Blockchain Commons, LLC, and is [licensed](./LICENSE.md) under the [BSD-2-Clause Plus Patent License](https://spdx.org/licenses/BSD-2-Clause-Patent.html).

## Contributing

We encourage public contributions through issues and pull-requests! Please review [CONTRIBUTING.md](./CONTRIBUTING.md) for details on our development process. All contributions to this repository require a GPG signed [CONTRIBUTOR-LICENSE-AGREEMENT.md](./CONTRIBUTOR-LICENSE-AGREEMENT.md).
