# stafi-bootstrap

## types

When you use [polkadotjs](https://polkadot.js.org/docs/api/) api to develop a StaFi Dapp, you should use the types.json to create api instance.

```bash
const api = await ApiPromise.create({
  provider: wsProvider,
  types: {
    RefCount: 'u32',
    ChainId: 'u8',
    ResourceId: '[u8; 32]',
    DepositNonce: 'u64'
  }
});
```
