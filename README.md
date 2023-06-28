# awesome-icon
A curated list of awesome frameworks, libraries, software, and other resources for the ICON blockchain ecosystem

_Note that smart contracts decentralized applications also function as libraries and software services with publicly accessible APIs. See the [composability](https://docs.icon.community/icon-stack/smart-contracts/composability) and [remote-procedure-call](https://docs.icon.community/icon-stack/client-apis/json-rpc-api) topics on the official documentations to learn more_

# Contents

- [Projects](#projects)
  - [Build assist tools](#build-assist-tools)
  - [Core ICON blockchain](#core-icon-blockchain)
  - [Decentralized autonomous organization (DAO)](#decentralized-autonomous-organization-dao)
  - [Decentralized finance](#decentralized-finance)
  - [Exchanges](#exchanges)
  - [Execution environment](#execution-environment)
  - [Faucets](#faucets)
  - [Games](#games)
  - [Governance](#governance)
  - [Interoperability](#interoperability)
  - [NFT](#nft)
  - [Oracle](#oracle)
  - [RPC API](#rpc-api)
  - [Templating](#templating)
  - [Testing](#testing)
  - [Tracker](#tracker)
  - [Wallet](#wallet)
- [Resources](#resources)
  - [Related awesome lists](#related-awesome-lists)
  - [Core documentations](#core-documentations)
  - [Communities](#communities)
  - [Funding programs](#funding-programs)
  - [Content](#content)
  - [Tutorials](#tutorials)

# Projects

## Build assist tools
- [drogon](https://github.com/icon-community/drogon/) - A robust, lightweight application development framework used for developing, testing, and deploying smart contracts on the ICON blockchain

## Core ICON blockchain
_Core components to ICON blockchain_

- [goloop](https://github.com/icon-project/goloop) - The basis for the official ICON blockchain node
- [gochain-local](https://github.com/icon-project/gochain-local) - Tools for running the ICON blockchain locally
- [gochain-local-decentralize](https://github.com/icon-community/gochain-local-decentralize) - Helpers scripts for decentralizing a multi node local network created with the `gochain-local` repo.
- [goloop-icon](https://hub.docker.com/r/iconloop/goloop-icon) - Docker container for the goloop blockchain engine
- [icon2-node](https://hub.docker.com/r/iconloop/icon2-node) - Docker container for an ICON blockchain node

## Decentralized autonomous organization (DAO)
- [icon-daos](https://github.com/Staky-io/icon-daos) - Tracking tool for DAOs in the ICON ecosystem

## Decentralized finance
_Tools for conducing decentralized finance in the ICON ecosystem_

- [Balanced DAO](https://docs.balanced.network/) - Stablecoin dApp that uses ICX as collateral to mint Balanced Dollars (bnUSD), a token pegged to 1 US Dollar
- [Convexus](https://dev.convexus.net/) - Convexus introduces concentrated liquidity, giving individual liquidity providers (LPs) granular control over what price ranges their capital is allocated to
- [ICONFi](https://www.icon-fi.com/) - Decentralized finance market built on ICON main network
- [Karma Finance](https://karma-finance.gitbook.io/karma-bond-documentation/overview/introduction) - Karma Bond is a protocol owned liquidity-as-a-service, providing treasuries and bonds optimized to individual protocol needs
- [Omm](https://omm.finance/how/) - Decentralized finance market built on ICON main network
- [Optimus](https://docs.optimus.finance/) - Optimus is an on-chain yield optimizer for earning staking rewards
- [Stably](https://www.stably.io/usds/) - Stablecoin tradable on the ICON main network backed by the U.S. dollar

## Exchanges
_Public sources for exchanging ICX currency_

- [Binance](https://www.binance.com/) - Cryptocurrency exchange which is the largest exchange in the world in terms of daily trading volume of cryptocurrencies
- [Binance.us](https://www.binance.us/) - Version of Binance exchange that is compliant with United States regulations
- [Bithumb](https://www.bithumb.com/) - A South Korean cryptocurrency exchange
- [Huobi](https://www.huobi.com/) - A Seychelles-based cryptocurrency exchange
- [Kraken](https://www.kraken.com/) - A United States–based cryptocurrency exchange and bank
- [KuCoin](https://www.kucoin.com/) - A Signapore-based cryptocurrency exchange

## Execution environment
_Tools and software related to the ICON smart contract execution environment_

- [gradle-javaee-plugin](https://github.com/icon-project/gradle-javaee-plugin) - Gradle plugin for ICON Java Execution Environment
- [javaee-scorex](https://github.com/icon-project/javaee-scorex) - some useful Java classes that can be used as substitutes for some Java standard I/O and collections frameworks when you write ICON Java smart contracts
- [javaee-annotation-processor](https://github.com/icon-project/javaee-annotation-processor) - Annotation-processor for ICON Java smart contract environment

## Faucets
_Testnet faucets for receiving tokens to test decentralized application functionality_

- [ICONOSPHERE Faucet](https://faucet.iconosphere.io/) - A faucet for receiving testnet ICX tokens on Berlin or Lisbon testnets

## Games
_Games in the ICON ecosystem and libraries for creating games_

- [GangstaBet](https://gangstabet.io/) - A digital collectible where people can evolve their characters for an eventual permanence on the blockchain
- [ICON-Unity-SDK](https://github.com/icon-community/ICON-Unity-SDK) -  Unity SDK for ICON Blockchain
- [Project Nebula](https://www.projectnebula.com/) - An open-world game of space exploration and conquest
- [Wonderland](https://wonderland.game/) - A digital collectible and metaverse-focused game with an Alice in Wonderland theme

## Governance
_Tools, software, and other resources related to blockchain governance in the ICON ecosystem_

- [governance2](https://github.com/icon-project/governance2) - ICON Main network governance contract
- [Node-Butler](https://butler.espanicon.team/) - Node Butler is a web app intended to facilitate the management of validator nodes in the ICON Network

## Interoperability
_Tools and software related to blockchain interoperability in the ICON ecosystem_

- [btp](https://github.com/icon-project/btp) - Blockchain Transmission Protocol, which is the ICON Foundation's core interoperability product
- [btp-litepaper](https://github.com/icon-project/btp-litepaper) - Lite explainer paper for BTP. [Also available here](https://icon.community/assets/btp-litepaper.pdf)
- [Nexus](https://github.com/icon-project/Nexus) - Interoperability frontend for using the Blockchain Transmission Protocol with the ICON main network as a routing hub
- [Orbit Bridge](https://bridge-docs.orbitchain.io/) - Bridging option available on for the ICON blockchain ecosystem
- [btp2-testnet](https://github.com/iconloop/btp2-testnet) - Information on the BTP network connected to the ICON Berlin TestNet.
- xCall sample DApps:
    * [e2edemo](https://github.com/icon-project/btp2/tree/main/e2edemo)
    * [xcall-sample-dapp by @fidelve](https://github.com/FidelVe/xcall-sample-dapp)
    * [btp-contracts-finder by @fidelve](https://github.com/FidelVe/btp-contracts-finder)
    * xCall testing Dapp by @R0bi7: [xCall-testing-JVM](https://github.com/R0bi7/xCall-testing-JVM), [xCall-testing-EVM](https://github.com/R0bi7/xCall-testing-EVM), [xCall-testing-dApp](https://github.com/R0bi7/xCall-testing-dApp/tree/master)

## NFT
_Tools and software related to non-fungible tokens_

- [Craft](https://craft.network/) - An NFT marketplace owned by the community
- [Fandiem](https://fandiem.com/) - A donation platform that harnesses the power of the fan community to make positive change
- [NFT Bazaar](https://www.nftbazaar.io/) - An NFT marketplace run by [Spartan Node](https://spartannode.medium.com/)

## Oracle
_Tools and software related to on-chain [oracles](https://docs.icon.community/concepts/decentralized-applications-dapps/oracles)_

- [Band Protocol](https://github.com/bandprotocol) - An open standard for decentralized management of data in Web3 stack

## RPC API
_Tools and software related to the Remote Procedure Call interface for API Endpoint nodes on the ICON blockchain_

- [Espanicon-sdk](https://github.com/Espanicon/espanicon-sdk) - Custom ICON SDK written in JS created by Espanicon team
- [flutter_icon_network](https://pub.dev/packages/flutter_icon_network/versions/1.0.0) - ICON SDK for Flutter
- [go-icon-sdk](https://github.com/eyeonicon/go-icon-sdk) - ICON SDK for Go
- [ICON JSON-RPC API v3](https://docs.icon.community/icon-stack/client-apis/json-rpc-api) - Documentations for the JSON-RPC API associated with ICON API Endpoint nodes
- [ICONKit](https://github.com/icon-project/ICONKit) - ICON SDK for iOS
- [ICONSdk.net](https://github.com/EclecticaNetwork/IconSDK.net) - ICON SDK for .NET
- [icon-sdk-python](https://github.com/icon-project/icon-sdk-python) - Official ICON SDK for Python based on ICON JSON-RPC API V3
- [icon-sdk-java](https://github.com/icon-project/icon-sdk-java) - Official ICON SDK for Java based on ICON JSON-RPC API V3
- [icon-sdk-js](https://github.com/icon-project/icon-sdk-js) - Official ICON SDK for JavaScript based on ICON JSON-RPC API V3
- [rhizome-contract-explorer](https://github.com/rhizome-labs/rhizome-contract-explorer) - A web application for querying and interacting with ICON smart contracts

## Templating
_Templating for bootstrapping smart contracts and other software in the ICON ecosystem_

- [java-score-examples](https://github.com/icon-project/java-score-examples) - Smart contract examples written for the ICON Java Execution Environment
- [javaee-tokens](https://github.com/sink772/javaee-tokens) - A Java SCORE Library for ICON Standard Tokens
- [soulbound-token](https://github.com/Staky-io/soulbound-token) - ICON Java implementation of the soulbound NFT token
- [tackle](https://github.com/sudoblockio/tackle) - Tackle is a declarative DSL for building modular utilities, code generators, and CLIs
- [tackle-icon-sc-poc](https://github.com/sudoblockio/tackle-icon-sc-poc) - POC for generating smart contracts for the ICON Blockchain with tackle

## Testing
_Tools related to testing code, including smart contracts, for the ICON blockchain_

- [icon-testsuite](https://github.com/icon-project/icon-testsuite) - A collection of test cases for the ICON node using client SDK in Java
- [javaee-unittest](https://github.com/icon-project/javaee-unittest) - An Unit Testing Framework for ICON Java smart contracts
- [Live network transaction tracer](https://icon-tx-tracer.vercel.app/) - A web app for tracing ICON network transactions on live networks
- [Debug-tracer.web.app](https://debug-trace.web.app/) - A web app for tracing ICON network transactions on live networks

## Tracker
_Tools and software related to tracking the state of the ICON blockchain_

- [ICON Community Tracker](https://tracker.icon.community/) - A blockchain tracker for the ICON main and test networks that can be [run locally as well](https://github.com/sudoblockio/icon-tracker)
- [ICON Watch](https://iconwat.ch/) - A blockchain tracker made by [Blockmove](https://blockmove.eu/)
- [Rhizome Community Tracker](https://alpha.tracker.rhizome.dev/) - A blockchain explorer built by the team members from Rhizome

## Wallet
_Cryptocurrency wallets built with the ICON ecosystem in mind_

- [Bridge wallet](https://docs.bridgepay.money/) - A fiat onramp for USD that is integrated for use with the ICON ecosystem
- [Hana wallet](https://chrome.google.com/webstore/detail/hana/jfdlamikmbghhapbgfoogdffldioobgl) - Chrome extension wallet for cryptocurrencies in the ICON ecosystem
- [IconEx wallet](https://github.com/icon-project/iconex_chrome_extension) -  ICONex Chrome extension wallet for cryptocurrencies in the ICON ecosystem
- [MyIconWallet](https://github.com/Hana-Technology/myiconwallet-react) - Desktop and mobile wallet for cryptocurrencies in the ICON ecosystem

# Resources

## Related awesome lists
_Other awesome community collections for related products and ecosystems_

- [awesome-dot](https://github.com/Awesomedot/awesome-dot/) - A curated list of resources in the Polkadot & Kusama ecosystem
- [awesome-ethereum](https://github.com/bekatom/awesome-ethereum) - A curated list of resources in the Ethereum ecosystem
- [awesome-java](https://github.com/akullpp/awesome-java) - A curated list of resources in the Java ecosystem

## Core documentations
_Documentations for the core ICON blockchain_

- [ICE / SNOW network technical documentations](https://docs.icenetwork.io/welcome/introduction)
- [ICON blockchain technical documentations](https://docs.icon.community)
- [ICON Improvement Proposals (IIPs)](https://github.com/icon-project/iips)

## Communities
_Communities within the ICON Ecosystem for technical or non-technical topics_

- [ICON Community forum](https://forum.icon.community)
- [ICON Discord](https://discord.com/invite/7a75Hf3cFm)
- [ICON Reddit](https://www.reddit.com/r/helloicon/)

## Funding programs
_Programs for getting your ICON ecosystem projects funded_

- [Contribution Proposal System](https://cps.icon.community/)
- [ICE Developer Grants](https://iconfoundation.notion.site/ICE-Developer-Grant-Program-ICED-Grants-c11a735a50004429b5c04a0eac720574)
- [Interoperability Incentive Program](https://se8br1ugut6.typeform.com/to/Qkialcom)

## Content
_Audio-visual, written, or other mediums for discussing and learning about ICON_

- [Eye on ICON](https://www.youtube.com/channel/UCJJ7_44t3DAU_Rgc0LIF4Eg) - Weekly podcast run by Fezbox and Iconographer, dedicated to topics in the ICON ecosystem
- [ICONgraphs](https://twitter.com/ICONgraphs) - Infographics based on the ICON ecosystem
- [Myiconcommunity](https://myiconcommunity.com/) - ICON’s very own news aggregator
- [Espanicon blog](https://dev.to/espanicon) - Technical blog from Espanicon ICON validator team
- [ICON Community blog](https://icon.community/blog/)

## Tutorials
_Tutorials for participating in the ICON ecosystem_
- [ICON Python Tutorials](https://github.com/rhizome-labs/icon-python-tutorials/tree/main/icon_python_tutorials) - Tutorials developed by [Rhizome Labs](https://github.com/rhizome-labs) for using the [Python SDK](https://github.com/icon-project/icon-sdk-python)

## Templates
_Templates for projects or other useful things_
- [Template repository](https://github.com/icon-community/template-repository) - Template repository for a new project, including README, Issue Templates, PR Template, LICENSE, Release message auto-instructions, CONTRIBUTING, and CODE_OF_CONDUCT files
