# Custom-Token-on-Polygon-Network
This is a contract which deploys custom token into the Polygon network
using OpenZeppelin contracts db:
(pls, refer to https://forum.openzeppelin.com/t/deploy-a-simple-erc20-token-in-remix/1203)

![image](https://user-images.githubusercontent.com/46632676/152733400-731a53c4-ed6b-42c6-9338-45d70c15506e.png)

---

# How to deploy

1. import contract from OpenZeppelin
```
import "https://github.com/OpenZeppelin/openzeppelin-contracts/blob/v3.4.0-solc-0.7/contracts/token/ERC20/ERC20.sol";
```
2. in testing purpose: add ```Polygon Mumbai testnet``` and get test token from Polygon Faucet ```https://faucet.polygon.technology```
3. compile
4. use ```Injected We3``` environment in the Remix IDE
5. deploy
6. open transaction info and copy contract address
7. import your token

---

## Example of transaction info after the contract deploying into ```Polygon Mumbai testnet```:

![image](https://user-images.githubusercontent.com/46632676/152734432-b111be87-081c-42c8-ba2b-4a9f7be1f10f.png)





