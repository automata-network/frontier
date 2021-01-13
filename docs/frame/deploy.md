# Deploy your EVM smart contract

In this Doc, you will learn deploy a smart contract on frontier.

### Install a Frontier Node.

TODO install

Now, we should config Metamask.

Add a new network: 
```
Network name: SubDev
New RPC URL: http://localhost:9933
ChainId: 42
Symbol : FNT
```
Import developer account seed:
``` 
0x60ed0dd24087f00faea4e2b556c74ebfa2f0e705f8169733b01530ce4c619883
```
Address of Substrate:
``` 
5ENPmNpr6TmsiCBY1MjFXn4pFzApNh3BVm1hF38ok9DVgQ6s
``` 
Address of Ethereum:
``` 
0x7EF99B0E5bEb8ae42DbF126B40b87410a440a32a
```

Transfer balance to account.

!!! Only use metamask. but the polkadot/apps can't transfer to eth account 

## Deploy contract by Remix

Open [Remix](http://remix.ethereum.org/).

Select a template contact and compile the contract.

Change deployment environment to Metamask injected web3 instance.


## TODO
 1. [x] deploy contract.  
 2. [ ] call function.

```
Jan 12 04:39:54.002 DEBUG apply_extrinsic: Create execution using address 0x8b85…605e: Succeed(Returned)    {ext}
Jan 12 04:39:54.002 DEBUG apply_extrinsic: Execution Succeed(Returned) [source: 0x7ef99b0e5beb8ae42dbf126b40b87410a440a32a, value: 0, gas_limit: 96405, actual_fee: 96405000000000]    {ext}
Jan 12 04:39:54.002 DEBUG apply_extrinsic: Inserting code (199 bytes) at 0x8b857677f3fcaa404fd2d97f398cce9bf5fe605e    {ext}
```