# [Mintbase Subgraph](https://mintbase.io) &middot; 

Mintbase enables users to mint and sell NFTs

* **Data Driver:** All of Mintbase's interfase is driven off the graph using Apollo Subscription hooks


## Installation

```
git clone git@github.com:Mintbase/graph-mint-factory.git
npm i
npm install -g @graphprotocol/graph-cli
graph auth https://api.thegraph.com/deploy/ <ACCESS_TOKEN>

```

## Deploy [Rinkeby](https://thegraph.com/explorer/subgraph/nategeier/mint-factory)
```
npm run codegen
npm run prep:rinkeby
npm run deploy:rinkeby
```


## Deploy [Mainnet](https://thegraph.com/explorer/subgraph/nategeier/mintbase)
```
npm run codegen
npm run prep:mainnet
npm run deploy:mainnet
```


## Documentation

You can find the Mintbase documentation [on the website](https://docs.mintbase.io).  
