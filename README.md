# Technical Specification of TokenScript Working Group

[Migrating... README from original repo](https://github.com/TokenScript/TokenScript)

working in progress, contents are continously updating.

Table of contents
-----------------

* [Technical Specification of TokenScript Working Group](#technical-specification-of-tokenscript-working-group)
* [Introduction](#introduction)
* [Why TokenScript](#why-tokenscript)
* [Use Cases](#use-cases)
* [Getting Started](#installation)
* [Installation](#installion)
* [Deployment](#deployment)
* [Built With](#built-with)
* [Contributing](#contributing)
* [Authors and Maintainers](#authors-and-maintainers)
* [Support](#support)
* [Join us on Discord](#join-us-on-discord)
* [License](#license)
* [Acknowledgments](#acknowledgements) (optional)

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

## Deployment

Add additional notes about how to deploy this on a live system

## Built With

List any libraries, frameworks or other projects that your code might be using,
for example:

* [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - The web framework used
* [Maven](https://maven.apache.org/) - Dependency Management
* [ROME](https://rometools.github.io/rome/) - Used to generate RSS Feeds

## Contributing

Add a brief explanation of what kind of contributions you are looking for and what your requirements are for accepting them. Add a link to [CONTRIBUTING.md](./CONTRIBUTING.md) and a link to [CODE_OF_CONDUCT](https://www.oasis-open.org/policies-guidelines/oasis-participants-code-of-conduct/).


## Authors and Maintainers
  
List authors and maintainers here:

And/or:
"See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project."

## Support

Where can people ask for help: this can be any combination of an [issue tracker](https://github.com/eea-oasis/tokenscript/issues), [Discord](https://discord.gg/bTw8Maz6ma), [email list](https://lists.oasis-open-projects.org/g/eea-cp-tokenscript).

## Join us on Discord

Click here and join [TokenScript Discord](https://discord.gg/bTw8Maz6ma) , to meet the community and learn more about how you can engage."

## License

This project is licensed under the Apache 2.0 license - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgments

Add a Hat tip to anyone whose code was used or projects that inspire your work etc.


