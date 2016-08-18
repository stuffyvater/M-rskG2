Run ethereum node using:
geth --rpc --testnet --rpccorsdomain "*" console

Alternatively, with personal RPC API
geth --rpc --testnet --rpccorsdomain "http://localhost:3000" --rpcapi="db,eth,net,web3,personal,web3" console

Then, on the console
personal.unlockAccount(eth.coinbase, "<password>", 30000)