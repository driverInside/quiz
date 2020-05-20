# Truffle RSK Quiz starter box

Basic quiz app using rsk and truffle.

## Index
* [Getting Started](#Getting-Started)
    * [Prerequisites](#Prerequisites)
    * [Installing](#Installing)
* [Using RSK](#Using-RSK)
    * [Setup an account and get R-BTC](#Setup-an-account-and-get-R-BTC)
    * [Setup the gas price](#Setup-the-gas-price)
    * [Connect to RSK](#Connect-to-RSK)

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

This box comes with everything you need to start using `truffle` on RSK network.

### Prerequisites

In order to run this app, you need to have a recent version of `node`. To download and install it, you can use [this link](https://nodejs.org/en/).

To download this box, we recommend you install `truffle` globally.

```bash
$ npm i -g truffle
```

### Installing

First ensure you are a new and empty folder

1. Run the unbox command. This will install all necessary dependencies.

```bash
$ truffle unbox driverInside/rsk-quiz-starter-box
```

2. Now you cann run the development console. This will open a new truffle console.

```bash
$ truffle develop
```

3. Compile and migrate the smart contracts.

```bash
$ > compile
$ > migrate
```

## Using RSK

### Setup an account and get R-BTC

To run this example box, you will need and account address on every RSK network. 

* Get an address using [these instructions](https://developers.rsk.co/rsk/architecture/account-based/).
* Get R-BTC for the RSK Testnet from this [faucet](https://faucet.rsk.co/).
* Get R-BTC for the RSK Mainnet from [an exchange](https://www.rsk.co/#exchanges-rsk).

### Setup the gas price

### Connect to RSK
