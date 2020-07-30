# Blockchain

## Creating Node 1 and Node 2 with accounts from MyCrypto
- Public key for Node 1
Public address of the key:   0xE6f6d0a9A337404e6f0C597086A82532057A30F5

- Public key for Node 2
Public address of the key:   0x06B940a5eebFD9326980aa543cf40cdF5eB9C5d1

## Start Node 1 - Launch the first node into mining mode with the following command:
-   ./geth --datadir node1 --mine --minerthreads 1

NODE 1 ACCOUNT 5051080cA2Da3569Ce1D32c0C8bc9Fc5932aA57b


## Start Node 2 - Launch the second node into mining mode with the following command:
./geth --datadir node2 --port 30304 --rpc --bootnodes "enode://bab6c8c6390f6301021049140dd71b0dd76c17f16881c84f2d2936d62bff6c3169bf963fcef910ea3af49b251ddce0db59e0832af0559518f63b9afb82a09a64@127.0.0.1:30303"

NODE 2 ACCOUNT 42327486e36BCD9515C2Cbbd0C7756062BBed494

## Custom network 
- Click "Add Custom Node", then add the custom network information that you set in the genesis. Choose Custom in the "Network" column.

- Once your custom network is ready and your nodes are initiated, you can send a transaction from the Node 1 account to Node 2 account and your nodes will mine the transaction

- For some reason my nodes are not mining and I get the following error: "Block sealing failed                     err=unauthorized"

- Additionally, I lost access to my transactions