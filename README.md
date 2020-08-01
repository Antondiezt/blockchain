# Blockchain

## Creating Node 1 and Node 2 with accounts from MyCrypto
- Public key for Node 1
Public address of the key:   0xBFb53e8907B1eD17BC355D0a7DAE281D53B3c457

- Public key for Node 2
Public address of the key:   0x174b9E593a5Db5DC3DCD8263085C034415b65313

## Start Node 1 - Launch the first node into mining mode with the following command:
-   ./geth --datadir node1 --unlock "bfb53e8907b1ed17bc355d0a7dae281d53b3c457" --mine --rpc --allow-insecure-unlock


## Start Node 2 - Launch the second node into mining mode with the following command:
./geth --datadir node2 --unlock "174b9e593a5db5dc3dcd8263085c034415b65313" --mine --port 30304 --bootnodes enode://c3a45ee64152c434cd6ed225844edf1a65ea3fb77d36141aa59fdee204d612b22320247268ba4b3b822d8bde403b08f0463a39975d9be229b0b7a9b4fa26411f@127.0.0.1:30303

## Custom network 
- Click "Add Custom Node", then add the custom network information that you set in the genesis. Choose Custom in the "Network" column.

- Once your custom network is ready and your nodes are initiated, you can send a transaction from the Node 1 account to Node 2 account and your nodes will mine the transaction

- See screenshots for more details