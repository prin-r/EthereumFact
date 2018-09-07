# Raiden Command Line

## Run Ethereum
```s
# run node with geth
geth --testnet --fast --rpc --rpcaddr 0.0.0.0 --rpcport 8545 --rpccorsdomain "*" --rpcapi admin,db,eth,debug,miner,net,shh,txpool,personal,web3 console

# run node with parity
parity --chain ropsten --bootnodes "enode://20c9ad97c081d63397d7b685a412227a40e23c8bdc6688c6f37e97cfbc22d2b4d1db1510d8f61e6a8866ad7f0e17c02b14182d37ea7c3c8b9c2683aeb6b733a1@52.169.14.227:30303,enode://6ce05930c72abc632c58e2e4324f7c7ea478cec0ed4fa2528982cf34483094e9cbc9216e7aa349691242576d552a2a56aaeae426c5303ded677ce455ba1acd9d@13.84.180.240:30303"
```

## Run Raiden
```s
# run raiden with geth
~/Downloads/raiden-0.4.2-macOS --keystore-path /Users/totiz/Library/Ethereum/testnet/keystore

# run raiden with parity
~/Downloads/raiden-0.5.0-macOS  --keystore-path ~/Library/Application\ Support/io.parity.ethereum/keys/test
```