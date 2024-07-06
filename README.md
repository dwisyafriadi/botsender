# Transaction Bot Application

A simple transaction bot application that uses Node.js to send random Ethereum transactions at random intervals.

## Prerequisites

Make sure you have Node.js installed on your device. To install Node.js, follow the instructions below:

### Linux

You can follow the tutorial on DigitalOcean for installing Node.js on Ubuntu 22.04:

[How to Install Node.js on Ubuntu 22.04](https://www.digitalocean.com/community/tutorials/how-to-install-node-js-on-ubuntu-22-04)

### Windows

Download and install Node.js directly from the official website:

[Download Node.js](https://nodejs.org/en)

### Verify Installation

To verify that Node.js is installed, use the following command:

```sh
node -v
````
### Clone the github
```
git clone https://github.com/dwisyafriadi/botsender.git
cd botsender
```

### Install Package Installation

To install package Node.js use the following command:

```sh
npm install -g npm@10.8.1
npm install web3
npm install ethers figlet
````
### Next, to get started, you can run the following command

1. node trx3.js
2. Enter the JSON RPC Provider URL: (for example https://binance.llamarpc.com)
3. Enter your private key
4. Enter recipients address: (for example 0xB5e3a3A847fa4c71d5d6B3cedf804033d1e72370)
5. Enter range of amounts to transfer : (for 0.1,0.2
6. Enter range of intervals in seconds : (for example minimum transaction in seconds 30, maximum transaction 60)


