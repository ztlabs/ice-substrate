
## Build & Run

To build the chain, execute the following commands from the project root:

```
$ cargo build --release
```

To execute the chain, run:

```
$ ./target/release/amax-eva --tmp --ws-external --rpc-external --rpc-cors all --dev
```

Configuring Metamask

```
Network Name : amax-eva local node
RPC URL      : http://127.0.0.1:9933
ChainID      : 1998
Symbol       : AMAX
```

To convert eth 20bytes address to polkadot 32bytes account, run:

```
$ ./target/debug/amax-eva eth-to-polkadot 0xD948CC6216fAb1CF0606320E6E71317ABefd5733
0x369ece7733d6fa291d72f2f58bef0bc966351528a75bb929bc3532b7fa164492 (5DJKcpHS...)
```
