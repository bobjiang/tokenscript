# Technical Specification of TokenScript Working Group

Table of contents
-----------------

* [Working Group Home](#technical-specification-of-tokenscript-working-group)
* [Introduction](#introduction)
* [Why TokenScript](#why-tokenscript)
* [What is in a TokenScript file](#what-is-in-a-tokenscript-file)
* [Use Cases](#use-cases)
* [Getting Started](#getting-started)
* [Installation](#installion)
* [How to Contribute](#contributing)
* [Contributors](#contributors)
* [Support](#support)
* [Join us on Discord](#join-us-on-discord)
* [License](#license)
* [Acknowledgments](#acknowledgements)

## TokenScript: Add Rich Functionality To Your Tokens

**Bring context, security and cross-platform functionality (iOS, Android and Web) to your favourite tokens with a single file.**

## Introduction

TokenScript makes Smart Token (Credit to [Virgil Griffith](https://twitter.com/virgilgr) for coming up with the term). These are like traditional ERC20 or ERC721 tokens, but with extendable structure & signed JavaScript to realise rich functions and full composability that DApps struggle to implement, and be traded with flexible, customisable trading rules.

A TokenScript file is made of
- JavaScript to make Token work in the user's wallet or across multiple apps; and
- XML data to extract status and value of the token.

In short, it's like a secure front-end for tokens.

**Benefits**
-   Run your tokens from users wallets as native, modular ‘Mini-DApps'
-   Extend token structure and realise rich functions with a single file
-   Portable across DApps
-   Sync updates at any time
-   Blockchain agnostic
-   Secure Enclave
-   DvP Security
-   Context based programming: User-experience
-   Attestation

![tokenscript stack alphawallet dapps](/doc/img/readme/tokenscript-stack.jpg)

## Why TokenScript

Today, the way tokens are accessed, rendered and transacted are scattered across DApps and Smart Contracts. This limited the use of Tokens.

Typically, all knowledge about rendering a token and constructing a transaction about the token is in a "host" web app. The "host" web app becomes a centre in the token's marketisation and integration, recreating data interoperability, security and availability barrier - precisely the same set of issues that prevented tokenisation before blockchain's invention.

By taking the knowledge of tokens including smart contract interfaces out and put them into a portable TokenScript we allow tokens to be accessible and useful.

The team at AlphaWallet is committed to bringing Web 3.0 via tokenization. Tokenised rights can be traded on the market and integrated across systems, forming a [Frictionless Market](https://github.com/AlphaWallet/TokenScript/blob/master/doc/design_paper.md#creating-a-frictionless-market) and allowing [Limitless Integration](https://github.com/AlphaWallet/TokenScript/blob/master/doc/design_paper.md#blockchain-integrates-the-web).

## What is in a TokenScript file

TokenScript is an XML dialect. It describes:

-   The functions provided by the token (through smart contract or not)
-   The method to render it on the user's interface
-   The ERCs token behaviour templates it uses
-   The JavaScript needed to construct transactions and render the token.

It also defines how attestations are used to decorate, or convert to, or validate a transaction.

## Use Cases

Visit our example Repo [here](https://github.com/AlphaWallet/TokenScript-Examples), which is full of complete TokenScripts that run inside our wallet, AlphaWallet.

**Working examples:**

- [Bartercard Qoin](https://play.google.com/store/apps/details?id=com.qoin.wallet&hl=en)
- [FIFA and UEFA’s blockchain tickets](https://apps.apple.com/au/app/shankai/id1492559481)
- [Car Ownership portal](https://github.com/AlphaWallet/TokenScript-Examples/tree/master/examples/Karma)

[**A really good starting point to generating your own TokenScript**](https://github.com/AlphaWallet/TokenScript-Examples/tree/master/tutorial#future-obtaining-sample-files-schema-202003)

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See [deployment](#deployment) for notes on how to deploy the project on a live system.

If applicable, list here what is need to install the software and how to install them. Also list any dependencies, if applicable.

### Installation

to be updated.

A step by step series of examples that tell you how to get a development env running

Say what the step will be

```
Give the example
```

And repeat

```
until finished
```

End with an example of getting some data out of the system or using it for a little demo

### Project Structures

This project holds:
`doc` : documents about the language and the design
`schema` : XML schema files which define the syntax for TokenScripts

## Contributing

Add a brief explanation of what kind of contributions you are looking for and what your requirements are for accepting them. Add a link to [CONTRIBUTING.md](./CONTRIBUTING.md) and a link to [CODE_OF_CONDUCT](https://www.oasis-open.org/policies-guidelines/oasis-participants-code-of-conduct/).

## Contributors

Thank you to all the contributors! You are awesome.

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="https://github.com/colourful-land"><img src="https://avatars3.githubusercontent.com/u/548435?v=4" width="100px;" alt=""/><br /><sub><b>Weiwu Zhang</b></sub></a><br /><a href="https://github.com/AlphaWallet/TokenScript/commits?author=colourful-land" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/James-Sangalli"><img src="https://avatars0.githubusercontent.com/u/16630514?v=4" width="100px;" alt=""/><br/><sub><b>James Sangalli</b></sub></a><br/><a href="https://github.com/AlphaWallet/TokenScript/commits?author=James-Sangalli" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/theBergmann"><img src="https://avatars1.githubusercontent.com/u/25482130?s=400&v=4" width="100px;" alt=""/><br /><sub><b>theBergmann</b></sub></a><br /><a href="https://github.com/AlphaWallet/TokenScript/commits?author=theBergmann" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/hboon"><img src="https://avatars2.githubusercontent.com/u/56189?v=4" width="100px;" alt=""/><br /><sub><b>Hwee-Boon Yar</b></sub></a><br /><a href="#ideas-hboon" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/zhangzhongnan928"><img src="https://avatars2.githubusercontent.com/u/33795543?v=4" width="100px;" alt=""/><br /><sub><b>Victor Zhang</b></sub></a><br /><a href="#ideas-zhangzhongnan928" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/liuxiaohao"><img src="https://avatars0.githubusercontent.com/u/1217967?s=400&u=d09aff7ab31b53ffffb2af8bd8d41eda7e3b79fe&v=4" width="100px;" alt=""/><br /><sub><b>maxliu</b></sub></a><br /><a href="https://github.com/AlphaWallet/TokenScript/commits?author=liuxiaohao" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/JamesSmartCell"><img src="https://avatars2.githubusercontent.com/u/12689544?v=4" width="100px;" alt=""/><br /><sub><b>James Brown</b></sub></a><br /><a href="https://github.com/AlphaWallet/TokenScript/commits?author=JamesSmartCell" title="Code">💻</a></td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/developerpeachy"><img src="https://avatars3.githubusercontent.com/u/13824586?s=400&u=329f22d53d8c50f3877f909a6a7f0321d1e215db&v=4" width="100px;" alt=""/><br /><sub><b>Rosalie</b></sub></a><br /><a href="https://github.com/AlphaWallet/TokenScript/commits?author=developerpeachy" title="Code">💻</a></td>
    <td align="center"><a href="http://medium.com/@james.zaki"><img src="https://avatars3.githubusercontent.com/u/939603?v=4" width="100px;" alt=""/><br /><sub><b>James Zaki</b></sub></a><br /><a href="https://github.com/AlphaWallet/alpha-wallet-ios/commits?author=jzaki" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/farrahfazirah"><img src="https://avatars2.githubusercontent.com/u/20555752?s=460&u=74320573120d8411594a3ffa48e2c6a1a5be3257&v=4" width="100px;" alt=""/><br /><sub><b>Farrah Fazirah</b></sub></a><br /><a href="https://github.com/AlphaWallet/TokenScript/commits?author=farrahfazirah" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/lanlan3322"><img src="https://avatars0.githubusercontent.com/u/26592081?s=400&u=e70d78508c13db2b533ac081c3677b9aea85c8cf&v=4" width="100px;" alt=""/><br /><sub><b>Laurence</b></sub></a><br /><a href="https://github.com/AlphaWallet/TokenScript/commits?author=lanlan3322" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/hellolucas"><img src="https://avatars3.githubusercontent.com/u/17125002?v=4" width="100px;" alt=""/><br /><sub><b>Lucas Toledo</b></sub></a><br /><a href="https://github.com/AlphaWallet/TokenScript/commits?author=hellolucas" title="Code">💻</a></td>
  </tr>
</table>

<!-- markdownlint-enable -->
<!-- prettier-ignore-end -->
<!-- ALL-CONTRIBUTORS-LIST:END -->

## Support

Where can people ask for help: this can be any combination of an [issue tracker](https://github.com/eea-oasis/tokenscript/issues), [Discord](https://discord.gg/bTw8Maz6ma), [email list](https://lists.oasis-open-projects.org/g/eea-cp-tokenscript).

## Join us on Discord

Click here and join [TokenScript Discord](https://discord.gg/bTw8Maz6ma) , to meet the community and learn more about how you can engage.

## License

This project is licensed under the Apache 2.0 license - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgments

Add a Hat tip to anyone whose code was used or projects that inspire your work etc.


