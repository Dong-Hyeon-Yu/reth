# Reth Book

- [Introduction](./intro.md)
- [Installation](./installation/installation.md)
   - [Pre-Built Binaries](./installation/binaries.md)
   - [Docker](./installation/docker.md)
   - [Build from Source](./installation/source.md)
   - [Build for ARM devices](./installation/build-for-arm-devices.md)
   - [Update Priorities](./installation/priorities.md)
- [Run a Node](./run/run-a-node.md)
   - [Mainnet or official testnets](./run/mainnet.md)
   - [OP Stack](./run/optimism.md)
   - [Private testnet](./run/private-testnet.md)
   - [Metrics](./run/observability.md)
   - [Configuring Reth](./run/config.md)
   - [Transaction types](./run/transactions.md)
   - [Pruning & Full Node](./run/pruning.md)
   - [Ports](./run/ports.md)
   - [Troubleshooting](./run/troubleshooting.md)
- [Interacting with Reth over JSON-RPC](./jsonrpc/intro.md)
   - [eth](./jsonrpc/eth.md)
   - [web3](./jsonrpc/web3.md)
   - [net](./jsonrpc/net.md)
   - [txpool](./jsonrpc/txpool.md)
   - [debug](./jsonrpc/debug.md)
   - [trace](./jsonrpc/trace.md)
   - [admin](./jsonrpc/admin.md)
   - [rpc](./jsonrpc/rpc.md)
- [CLI Reference](./cli/cli.md) <!-- CLI_REFERENCE START -->
  - [`reth`](./cli/reth.md)
    - [`reth node`](./cli/reth/node.md)
    - [`reth init`](./cli/reth/init.md)
    - [`reth import`](./cli/reth/import.md)
    - [`reth dump-genesis`](./cli/reth/dump-genesis.md)
    - [`reth db`](./cli/reth/db.md)
      - [`reth db stats`](./cli/reth/db/stats.md)
      - [`reth db list`](./cli/reth/db/list.md)
      - [`reth db diff`](./cli/reth/db/diff.md)
      - [`reth db get`](./cli/reth/db/get.md)
      - [`reth db drop`](./cli/reth/db/drop.md)
      - [`reth db clear`](./cli/reth/db/clear.md)
      - [`reth db snapshot`](./cli/reth/db/snapshot.md)
      - [`reth db version`](./cli/reth/db/version.md)
      - [`reth db path`](./cli/reth/db/path.md)
    - [`reth stage`](./cli/reth/stage.md)
      - [`reth stage run`](./cli/reth/stage/run.md)
      - [`reth stage drop`](./cli/reth/stage/drop.md)
      - [`reth stage dump`](./cli/reth/stage/dump.md)
        - [`reth stage dump execution`](./cli/reth/stage/dump/execution.md)
        - [`reth stage dump storage-hashing`](./cli/reth/stage/dump/storage-hashing.md)
        - [`reth stage dump account-hashing`](./cli/reth/stage/dump/account-hashing.md)
        - [`reth stage dump merkle`](./cli/reth/stage/dump/merkle.md)
      - [`reth stage unwind`](./cli/reth/stage/unwind.md)
        - [`reth stage unwind to-block`](./cli/reth/stage/unwind/to-block.md)
        - [`reth stage unwind num-blocks`](./cli/reth/stage/unwind/num-blocks.md)
    - [`reth p2p`](./cli/reth/p2p.md)
      - [`reth p2p header`](./cli/reth/p2p/header.md)
      - [`reth p2p body`](./cli/reth/p2p/body.md)
    - [`reth test-vectors`](./cli/reth/test-vectors.md)
      - [`reth test-vectors tables`](./cli/reth/test-vectors/tables.md)
    - [`reth config`](./cli/reth/config.md)
    - [`reth debug`](./cli/reth/debug.md)
      - [`reth debug execution`](./cli/reth/debug/execution.md)
      - [`reth debug merkle`](./cli/reth/debug/merkle.md)
      - [`reth debug in-memory-merkle`](./cli/reth/debug/in-memory-merkle.md)
      - [`reth debug build-block`](./cli/reth/debug/build-block.md)
      - [`reth debug replay-engine`](./cli/reth/debug/replay-engine.md)
    - [`reth recover`](./cli/reth/recover.md)
      - [`reth recover storage-tries`](./cli/reth/recover/storage-tries.md)
- [Developers](./developers/developers.md) <!-- CLI_REFERENCE END -->
   - [Contribute](./developers/contribute.md)
