<br />
<div align="center">  
  <h3 align="center">Cross Wallet Chrome Extension</h3>  
</div>

<!-- ABOUT THE PROJECT -->
## About Enkrypt

CrossWallet is a web3 wallet built from the ground up to support the multi-chain future. Send, receive, swap, manage your tokens and NFTs, and interact with dapps on all of your favorite chains.

<p align="right">(<a href="#top">back to top</a>)</p>

## Currently Supported Chains

* Ethereum
* Polygon
* BNB Smart Chain
* Moonbeam
* Moonriver
* Karura EVM+
* Ethereum Classic
* Polkadot
* Kusama
* Acala
* Karura

### Local Setup

1. Clone the repo
   ```sh
   git clone https://github.com/enkryptcom/enKrypt.git
   ```
2. Install NPM packages
   ```sh
   yarn install
   ```
3. Build the project and watch for changes
    ```sh
    yarn watch-extension # chromium based browsers
    yarn watch:firefox # firefox
    ```
4. Build the project for release
    ```sh
    yarn build:all
    yarn build:chrome # chromium based browsers
    yarn build:firefox # firefox
    ```