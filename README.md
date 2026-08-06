<div align="center">
  <img src="doc/img/kindcoin-core.png" alt="Kindcoin Core" width="156">
  <h1>Kindcoin Core</h1>
  <p><strong>Kindness-powered, open-source digital currency.</strong></p>
  <p>
    <a href="https://kindcoin.cc/">Website</a> &bull;
    <a href="https://github.com/kindcoincore/kindcoin/releases/latest">Wallets</a> &bull;
    <a href="https://explorer.kindcoin.cc/">Explorer</a> &bull;
    <a href="https://discord.gg/Mcxs3ABbMz">Discord</a>
  </p>
</div>

Kindcoin is an open-source peer-to-peer digital currency built around
kindness, community, and hybrid proof-of-work/proof-of-stake security.
Kindcoin Core provides the full desktop wallet, node, RPC interface, and
command-line tools for the KCCC network.

## Network at a Glance

| | Kindcoin mainnet |
| --- | --- |
| Ticker | `KCCC` |
| Consensus | Hybrid PoW and PoS |
| Target block time | 5 minutes |
| P2P port | `21538` |
| RPC port | `21537` |
| Current wallet | `v13.3.2` |
| License | MIT |

## Get Kindcoin Core

Official Windows and Linux packages are published on the
[releases page](https://github.com/kindcoincore/kindcoin/releases/latest).
Release downloads include SHA-256 checksums so packages can be verified before
use.

Before upgrading, close the previous wallet cleanly and keep a secure backup
of `wallet.dat`. Official release notes describe any version-specific steps.

## Participate in the Network

- **Run a node:** Keep Kindcoin Core online to validate and relay blocks and
  transactions.
- **Stake KCCC:** Unlock an encrypted wallet for staking to participate in
  proof-of-stake block production.
- **Mine KCCC:** Connect compatible mining software or pool infrastructure to
  the proof-of-work network.
- **Contribute:** Test releases, report reproducible issues, review changes,
  and help other community members.

## Build from Source

Platform build instructions and dependency guidance are maintained in the
[`doc`](doc) and [`depends`](depends) directories. Tagged releases are the
recommended source points for production builds; the development branch may
contain work that has not yet shipped in an official wallet.

Useful references:

- [Unix build notes](doc/build-unix.md)
- [Windows build notes](doc/build-windows.md)
- [Contribution guide](CONTRIBUTING.md)
- [Change log](CHANGELOG.md)

## Security and Support

Never share wallet private keys, seed material, passwords, or `wallet.dat`.
Use the [Kindcoin community](https://discord.gg/Mcxs3ABbMz) for general support
and the [issue tracker](https://github.com/kindcoincore/kindcoin/issues) for
clear, reproducible software problems.

## License

Kindcoin Core is distributed under the MIT License. See [COPYING](COPYING) for
the complete license text.
