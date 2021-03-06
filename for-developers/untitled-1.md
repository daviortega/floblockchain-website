# API

==='''RETURN DATA FROM COIND'''===

### Return data from local indexes

'''getdifficulty'''

* Returns the current difficulty.

  [http://flo.cash//api/getdifficulty](http://flo.cash//api/getdifficulty)

'''getconnectioncount'''

* Returns the number of connections the block explorer has to other nodes.

  [http://flo.cash//api/getconnectioncount](http://flo.cash//api/getconnectioncount)

'''getblockcount'''

* Returns the current block index.

  [http://flo.cash//api/getblockcount](http://flo.cash//api/getblockcount)

'''getblockhash \[index\]'''

* Returns the hash of the block at ; index 0 is the genesis block.

  [http://flo.cash//api/getblockhash?index=2141052](http://flo.cash//api/getblockhash?index=2141052)

'''getblock \[hash\]'''

* Returns information about the block with the given hash.

  [http://flo.cash//api/getblock?hash=8ad47bf484a9cb473904584b8403dda6aed9342a54df0e7afad619337088e679](http://flo.cash//api/getblock?hash=8ad47bf484a9cb473904584b8403dda6aed9342a54df0e7afad619337088e679)

'''getrawtransaction \[txid\] \[decrypt\]'''

* Returns raw transaction representation for given transaction id. decrypt can be set to 0\(false\) or 1\(true\).

  [http://flo.cash//api/getrawtransaction?txid=40118193c8342d381d3cf4547dbe7fa0c20c93becfe529602dfe2d3fd10d6362&decrypt=0](http://flo.cash//api/getrawtransaction?txid=40118193c8342d381d3cf4547dbe7fa0c20c93becfe529602dfe2d3fd10d6362&decrypt=0)

  [http://flo.cash//api/getrawtransaction?txid=40118193c8342d381d3cf4547dbe7fa0c20c93becfe529602dfe2d3fd10d6362&decrypt=1](http://flo.cash//api/getrawtransaction?txid=40118193c8342d381d3cf4547dbe7fa0c20c93becfe529602dfe2d3fd10d6362&decrypt=1)

'''getnetworkhashps'''

* Returns the current network hashrate. \(hash/s\)

  [http://flo.cash//api/getnetworkhashps](http://flo.cash//api/getnetworkhashps)

