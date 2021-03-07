# Features

### 📌 Block Size and Speed 📌

Metadata "pins" can be added to any transaction and broadcast to the network. The pin is added right after the outputs and before the lock time, and it is included when calculating signature hashes for inputs. Once the transaction and imbedded, the data is "pinned" to the blockchain via the sCrypt Proof-of-Work algorithm, and thereafter it is immutably stored on the distributed network. Pins cannot be changed without changing the input to the signature, which would invalidate the transaction. If the transaction is invalidated by a change to a pin, the block containing the invalid transaction will become invalidated as well, causing a cascading effect invalidating every block chained after it. This feature can be employed in a number of file storage, indexing, and retrieval applications. 

### ​📌 Pins - The Secure Metadata Layer 📌 

Initially, pins were limited to 140 bytes. Currently, 1040 bytes of data can be stored on the blockchain with a maximum block size of 1MB. If the blocks are consistently filled, the maximum block size may be increased. With a target time of 40 seconds, PIN is fast. In fact, it is 15x faster than Bitcoin, and 3.75x faster than Litecoin. To further assist with transaction throughput, the maximum ancestor limit for an unspent transaction output \(UTXO\) chain has been increased from the Bitcoin default of 25 up to 1250. This permits large amounts of information to be efficiently indexed.

### 📌 Additional Security 📌 

PIN does not allow reorganizations of 100 or more blocks, and uses a continuity of Proof-of-Work blocks to secure the blockchain. Once a transaction receives 100 confirmations \(~1 hour\), it cannot be tampered with or removed from the blockchain.

