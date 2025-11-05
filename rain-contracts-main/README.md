## Rain Contracts

**Run the following command to deploy the rain pool deployer**.

### Deploy Deployer Command

```shell
$ forge script --chain mainnet script/DeployRainPoolDeployer.s.sol:DeployRainPoolDeployer --rpc-url $RPC_URL --broadcast --verify -vvvv
```
### Deploy Pool Command

```shell
$ forge script --chain mainnet script/DeployRainPool.s.sol:DeployRainPool --rpc-url $RPC_URL --broadcast --verify -vvvv
```

### Test Forked Command

```shell
$  forge test --fork-url https://arb1.arbitrum.io/rpc -vvv
```

### Key Points
-   **Load env**: Run the command below to load the env for use.
```shell
 $ source .env 
 ```
-   **Private key**: Prefix your private key with **0x** in .env.
-   **Rpc Url**: Add the whole URL with http or https e.g **https://arb1.arbitrum.io/rpc**.
-   **Verification**: Add etherscan api key if you want to verify the contract after deployment.

### ARBITRUM ETH
   **https://arbiscan.io/address/0xccCB3C03D9355B01883779EF15C1Be09cf3623F1**
   **https://subgraph.satsuma-prod.com/18b5fffb12c7/quecko--598279/rain-graph-production/api**
   **https://api.studio.thegraph.com/query/98863/rain-prod/version/latest**
