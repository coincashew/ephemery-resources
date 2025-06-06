
### Client Implementations
This document tracks native Ephemery testnet implementations in execution and consensus clients. Clients with this support can run the testnet simply by using `--ephemery` or a similar flag without any manual configuration.

### EL Client Implementation Status

| **Client**   | **Genesis Function Status** | **Genesis Reset Status** | **Contributor(s)**                  | **Notes** |
|--------------|---------------------------|-----------------------|----------------------------|---------------|
| **[Besu](https://besu.hyperledger.org/en/stable/)**     | [Completed & Merged into main](https://github.com/hyperledger/besu/pull/7563/)               | [In-progress](https://github.com/hyperledger/besu/issues/7736) | [@gconnect](https://github.com/gconnect)                    | - ✅  Native support without extra arguments completed. <br> - ✅  Genesis function implemented <br> - [ ] Genesis Reset Implementation <br> - ✅  [Update Besu documentation](https://github.com/hyperledger/besu-docs/pull/1727) <br> - [Detail note](https://hackmd.io/@gconnect/BJRx9D7Z1l)      | 
| **[Geth](https://geth.ethereum.org/)**     |Completed                 | In-progress |[@atkinsonholly](https://github.com/atkinsonholly)                 |  - [Detail update](https://hackmd.io/@HOL/SJwLmrUmR)       |
| **[Reth](https://reth.rs/)**     | Completed             | In-progress  | [@T-ess](https://github.com/T-ess)                   | - [Detail update](https://hackmd.io/@teri-b/S1D6Np_Q6) |
| **[Nethermind](https://www.nethermind.io/)**     | Not Started              |  | -                     | -                   |
| **[Erigon](https://github.com/ledgerwatch/erigon)**     | Not Started             |   | -                     | -  | 
| **[EthereumJS](https://github.com/ethereumjs/ethereumjs-monorepo)**     | Not Started              |  | -                     | -  |


### CL Client Implementation Status

| **Client**   | **Genesis Function Status** | **Genesis Reset** | **Contributor(s)** | **Notes**                  | 
|--------------|---------------------------|-----------------------|----------------------------|-----|
| **[Teku](https://consensys.io/teku)**     | [Completed & Merged in Main repo](https://github.com/Consensys/teku/pull/8543)              | [Completed & Merged into Main](https://github.com/Consensys/teku/issues/8589) <br> Merged PRs Leading to the completion <br> - [Add deposit chainId on start](https://github.com/Consensys/teku/pull/8639) <br> - [Check network on start and reset db](https://github.com/Consensys/teku/pull/8642/) <br> - [create EphemerySlotValidationService](https://github.com/Consensys/teku/pull/8759)  <br> - Reset for validators still WIP| [@gconnect](https://github.com/gconnect)                 | - ✅  Native support without extra arguments merged. <br> - ✅ Genesis function implemented <br> - ✅ Genesis Reset Implementation Completed <br> - ✅ [Update Teku documentation](https://github.com/Consensys/doc.teku/pull/621) <br> - [Detail note](https://hackmd.io/@gconnect/BJRx9D7Z1l)        | 
| **[Lodestar](https://lodestar.chainsafe.io/)** | Completed              | In-progress | [@atkinsonholly](https://github.com/atkinsonholly)                 |  - [Github Discussion](https://github.com/ChainSafe/lodestar/issues/6064) <br>  - [Development update]( https://hackmd.io/@HOL/Hyp4bXfV6)    |
| **[Lighthouse](https://lighthouse.sigmaprime.io/)**| Completed               |In-progress | [@T-ess](https://github.com/T-ess)                 | - [Detail update](https://hackmd.io/@teri-b/S1D6Np_Q6)     |
| **[Nimbus](https://nimbus.team/)**     | Not Started                | | -                     | -  |
| **[Prysm](https://docs.prylabs.network/docs/getting-started/)**     | Not Started               | | -                     | -  | 
| **[Grandine](https://docs.grandine.io/)**     | Not Started                | -    |                 | -  | 
