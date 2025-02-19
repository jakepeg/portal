# Level 0: Pre-flight operations 

- [0.1 Overview of the Internet Computer](01-ic-overview.md): In order to understand how to develop dapps on the IC, the first step in the developer journey is to take a look at the architecture of the IC and how it functions. This module covers:
    - Overview of The Internet Computer Protocol
        - Protocol stack
            - Peer-to peer layer
            - Consensus layer
            - Message routing layer
            - Execution layer
    - Overview of chain-key cryptography:
        - Threshold signature schemes.
    - Overview of canisters and smart contracts.
    - Overview of tokens:
        - ICP.
        - Cycles.
    - Overview of governance:
        - Network Nervous System.
        - Service Nervous System.
    - Overview of Internet Identity.

- [0.2 Internet Computer terminology](02-ic-terms.md): This page introduces some of the most commonly used terminology that developers should be aware of when building on the Internet Computer. This module covers the following terms: 
    - Concepts:
        - Actor.
        - Agent.
        - Certified variables.
        - Chain-key cryptography.
        - Cycles.
        - Decentralized application (dapp).
        - Decentralized autonomous organization (DAO).
        - Execution.
        - ICP.
        - Principal.
        - Proposal.
        - Messages.
        - Replica.
        - Subnet.
        - Transaction.
    - Canister terminology:
        - Smart contracts.
        - Canisters.
        - Canister development kit (CDK).
        - Canister identifier.
        - Canister state.
        - Controller.
        - Identity.
        - Query.
        - State change.
        - System canister.
        - Wallet.
    - Tools and products:
        - `dfx`.
        - Internet Identity.
        - Ledger.
        - Motoko.

- [0.3 Developer environment setup](03-dev-env.md): Before we can begin our developer journey, we need to set up our developer environment. A developer environment is comprised of tools and packages that are required to develop code projects. This module covers:
    - Setting up a developer environment:
        - Confirming an internet connection.
        - Confirming access to a CLI.
            - Options for Windows users.
        - Downloading and installing the IC SDK.
        - Downloading and installing an IDE.
        - Downloading and installing git.
        - Downloading and installing Node.js.
        - Assuring all packages and tools are updated to latest version.

- [0.4 Introduction to canisters](04-intro-canisters.md): This page introduces canisters, their architecture, and discusses the different types of canisters that can be developed. This module covers:
    - Architecture:
        - Languages.
        - Actors.
        - Why is code compiled into WebAssembly?
    - Types of canisters:
        - Backend canisters.
        - Frontend canisters.
        - Custom canisters.
    - Using a single or multiple canister architecture.
    - Canister communication.
    - Canister controllers.
    - Cycles and resource charges.

- [0.5 Introduction to languages](05-intro-languages.md): In this page, we discuss the different languages that can be used to develop dapps, and provide a base-level introduction to the two primarily supported languages: Motoko and Rust. This module covers:
    - Motoko.
        - Motoko's attributes.
    - Rust.
        - Rust's attributes.
    - Candid.
    - Community developed CDKs:
        - Python.
        - TypeScript.
        - Solidity.
        - C++.

- [0.6 Introduction to dfx](06-intro-dfx.md): `dfx` is the DFINITY command-line execution environment for the IC SDK. It is the primary tool used for creating, managing, and deploying dapps onto the Internet Computer. This module covers:
    - Basic usage and syntax:
        - Subcommands.
        - Flags.
        - Options.
    - Upgrading to the latest version of `dfx`.
    - Installing a specific version of `dfx`.
    - Creating a new project with `dfx`.
    - Exploring the default project structure.
    - Reviewing the default configuration.
    - Reviewing the default program code.

