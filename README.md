# Cronswap Interface

[![Unit Tests](https://github.com/cronswap/uniswap-interface/actions/workflows/unit-tests.yaml/badge.svg)](https://github.com/cronswap/uniswap-interface/actions/workflows/unit-tests.yaml)
[![Integration Tests](https://github.com/cronswap/uniswap-interface/actions/workflows/integration-tests.yaml/badge.svg)](https://github.com/cronswap/uniswap-interface/actions/workflows/integration-tests.yaml)
[![Lint](https://github.com/cronswap/uniswap-interface/actions/workflows/lint.yml/badge.svg)](https://github.com/cronswap/uniswap-interface/actions/workflows/lint.yml)
[![Release](https://github.com/cronswap/uniswap-interface/actions/workflows/release.yaml/badge.svg)](https://github.com/cronswap/uniswap-interface/actions/workflows/release.yaml)
[![Crowdin](https://badges.crowdin.net/uniswap-interface/localized.svg)](https://crowdin.com/project/uniswap-interface)

An open source interface for Cronswap -- a protocol for decentralized exchange of Ethereum tokens.

- Website: [uniswap.org](https://uniswap.org/)
- Interface: [app.uniswap.org](https://app.uniswap.org)
- Docs: [uniswap.org/docs/](https://uniswap.org/docs/)
- Twitter: [@Uniswap](https://twitter.com/Uniswap)
- Reddit: [/r/Uniswap](https://www.reddit.com/r/Uniswap/)
- Email: [contact@uniswap.org](mailto:contact@uniswap.org)
- Discord: [Uniswap](https://discord.gg/FCfyBSbCU5)
- Whitepapers:
  - [V1](https://hackmd.io/C-DvwDSfSxuh-Gd4WKE_ig)
  - [V2](https://uniswap.org/whitepaper.pdf)
  - [V3](https://uniswap.org/whitepaper-v3.pdf)

## Accessing the Cronswap Interface

To access the Cronswap Interface, use an IPFS gateway link from the
[latest release](https://github.com/cronswap/uniswap-interface/releases/latest),
or visit [app.uniswap.org](https://app.uniswap.org).

## Unsupported tokens

Check out `useUnsupportedTokenList()` in [src/state/lists/hooks.ts](./src/state/lists/hooks.ts) for blocking tokens in your instance of the interface.

You can block an entire list of tokens by passing in a tokenlist like [here](./src/constants/lists.ts) or you can block specific tokens by adding them to [unsupported.tokenlist.json](./src/constants/tokenLists/unsupported.tokenlist.json).

## Contributions

For steps on local deployment, development, and code contribution, please see [CONTRIBUTING](./CONTRIBUTING.md).
