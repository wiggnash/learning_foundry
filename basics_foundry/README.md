# Starting with Foundry

1. Initialise the foundry folder
   - sometimes it can throw an error , when the folder have some files . then foce init the foundry

```bash
forge init
forge init -force
```

## File structure

1. src: All the smart contracts that we want to deploy , main section that we will always work
2. scripts : we will scripts which will interact with our smart contract
3. test: we will put code in this folder to test whats there in the src
4. toml file : file that is going to give us config parameters when we are working with foundry

### Getting Started with the foundry

1. Add a smart contract to the src folder , for this example im adding a SimpleStorage.sol smart contract.
2. We can now compile the smart contract using foundry

```bash
forge compile
```

#### Things to note after compile

1. **Out folder** : It will provide all the different information which remix will provide like abi , bytecode etc
2. **Cache Folder** : We can ignore this folder for now

## Deploying the smart contract on the local network

In order to test and interact with the smart contract we need to deploy it to the local network. Foundry provides us with the local network
which is called _ANVIL_ which is the virtual environment in the shell

1. Fake accounts and Fake private keys
2. RPC URL is also provided

### Need to setup the metamask for the local blockchain therefore we can deploy there
