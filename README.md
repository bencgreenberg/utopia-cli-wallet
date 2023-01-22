![](assets/wallet.png)

## Welcome to Utopia Chain CLI Wallet 🌈

|<p align="left">🛑</p> This is a proof of concept idea for a student assignment. Please **do not** use this in real production use cases. Everything written below is describing a fictional scenario. <p align="right">🛑</p>|
|-----------------------------------------|


The Utopia Chain is a Substrate blockchain that is built to be a platform for the Utopia ecosystem. It is a fork of the [Substrate Node Template]() with some modifications to the runtime and the node. These modifications are in alignment with our vision of a decentralized, censorship-resistant, and open-source platform for the Utopia ecosystem. Our ecosystem believes every person has the right to define their own worth when they enter the community, and this is reflected on this chain.

Read more to discover how to use this CLI wallet to interact with the Utopia chain.

1. [How does it work?](#how-does-it-work)
2. [Installation](#installation)
3. [Using the CLI wallet](#using-the-cli-wallet)
4. [Code of Conduct](#code-of-conduct)
5. [License](#license)

## How does it work?

On the Utopia chain you can do the following:

* Create a new account
* Transfer tokens
* Get the balance of an account

Please note, that even though we live in a Utopia, there still exists a cost for using the service. When you send tokens to another person, you must pay for the service. However, unlike those unfortunate realities we came from, this money just gets burned and never goes to anyone. This burning is a remembrance of the societies we had to endure before the Utopia chain.

You can perform all the above actions using this CLI wallet, except for getting the balance of your account. The reason why is simple. In Utopia, we do not believe in the need to know *how* much you have. You simply have or you do not have. The amount is only a reflection of our previous iterations. We do not want to be reminded of that. We want to be reminded of the Utopia we live in on chain.

## Installation

### Prerequisites

To build the wallet, you need to have Rust installed on your machine. You can install Rust by following the instructions [here](https://www.rust-lang.org/tools/install).

Once you do that, clone the repository and build the wallet.

```bash
git clone
cd substrate-rpc-client
cargo build
```

You are now ready to use the wallet.

## Using the CLI wallet

### Create a new account

To create a new account, run the following command:

```bash
./target/release/substrate-rpc-client new
```

Then follow the instructions prompted by the CLI. At the conclusion of your account creation, you will either see a success or failure message depending on whether the account was created successfully or not.

### Transfer tokens

To transfer tokens, run the following command:

```bash
./target/release/substrate-rpc-client transfer
```

Then follow the instructions prompted by the CLI. At the conclusion of your transfer, you will either see a success or failure message depending on whether the transfer was successful or not.

## Code of Conduct

Please note that this project is released with a Contributor Code of Conduct. By participating in this project you agree to abide by its terms. See [CODE_OF_CONDUCT](CODE_OF_CONDUCT.md) for more information.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.