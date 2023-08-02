# phat-contract-artifacts

<p align="center">
  <a href="https://phat.phala.network/" target="_blank">
    <img alt="Phala Network" src="./assets/Phat-Contract-Logo.png">
  </a>
</p>

This repository is intended for hosting all Phat Contract artifacts built by the Phala team. It allows anyone to instantiate them without having to compile the source codes themselves.

## Name Convention

- One folder for one Phat Contract, the folder name should be the codehash with prefixed with `0x`: `artifacts/<codehash>`.
- The metadata JSON file should rename to `metadata.json`
- The wasm file should rename to `out.wasm`


---

## [System Contract and Drivers](https://github.com/Phala-Network/phala-blockchain/tree/master/crates/pink-drivers)

### system

v1-rc1 `0xe746bce6c1bddd138329e81977af14a18aa35a10c7f2a7c571cc66415ccfb98a`

[Instantiate](https://phat.phala.network/contracts/add/0xe746bce6c1bddd138329e81977af14a18aa35a10c7f2a7c571cc66415ccfb98a) | [Mainnet](https://phat.phala.network/contracts/view/0x9dc2f09872e69f622cedbb3743aea482c740d9973f30f45c26cb8ed9782e6ab2?rpc=wss://api.phala.network/ws)

v1-rc2 `0x176166aec7f50ea083c1d2b87f49f33aad336995d9ed37d7eeb79741d0ce700f`

[Instantiate](https://phat.phala.network/contracts/add/0x176166aec7f50ea083c1d2b87f49f33aad336995d9ed37d7eeb79741d0ce700f)

### tokenomic

v1-rc1 `0x2fd66692f5ec313414fb5b80cfcaf26deb502b5160354ecb981989f19bd71403`

[Instantiate](https://phat.phala.network/contracts/add/0x2fd66692f5ec313414fb5b80cfcaf26deb502b5160354ecb981989f19bd71403) | [Mainnet](https://phat.phala.network/contracts/view/0xec3907c7f05505280a7a2e1b939963794f4762d2ccfdeb6b8b1633af17c2439c?rpc=wss://api.phala.network/ws) | [Testnet](https://phat.phala.network/contracts/view/0xefa947da84aed2531beb392f4715a445f1af36432f040d6a4f0dd8d48f28d94c?rpc=wss://poc5.phala.network/ws)

### sidevm_deployer

v1-rc1 `0x7207fa7cd56cfc0ec7faa7aed594ee6e2317ea848812cb1ffc6099c205e2a201`

[Instantiate](https://phat.phala.network/contracts/add/0x7207fa7cd56cfc0ec7faa7aed594ee6e2317ea848812cb1ffc6099c205e2a201)

v1-rc2 `0x58446ef118f1efb98988e29e6e025828b6d51bd30c14c6bd61ee94609afbd00a`

[Instantiate](https://phat.phala.network/contracts/add/0x58446ef118f1efb98988e29e6e025828b6d51bd30c14c6bd61ee94609afbd00a) | [Mainnet](https://phat.phala.network/contracts/view/0x111c43f37d027c2f4d764bf6de87f499d65079b8f2f2a1ec0bd0d84d3b77f72d?rpc=wss://api.phala.network/ws) | [Testnet](https://phat.phala.network/contracts/view/0x60a2bef2874786d0ce2cb6d9121bd94c79b5e4b08e44c3585cc75b67a4d0c28c?rpc=wss://poc5.phala.network/ws)

### log_server

v1-rc1 `0x3d64cf64c763393289613c907c2f62fb3aa8ea50d2e4580b0e0be0ad5a6c5626`

[Instantiate](https://phat.phala.network/contracts/add/0x3d64cf64c763393289613c907c2f62fb3aa8ea50d2e4580b0e0be0ad5a6c5626) | [Mainnet](https://phat.phala.network/contracts/view/0x5e707c91ffc4c57c1bd75c8da3095055db5a072865e292849cb96dd1ec2f4f46?rpc=wss://api.phala.network/ws) | [Testnet](https://phat.phala.network/contracts/view/0xa0c948ca913419fe26e2b0d7bd367281ce161cbe03736ba0085e85d5f4048d82?rpc=wss://poc5.phala.network/ws)

v1-rc2 `0xacbe3b24b3f798f58b06d8da0b8eeed14f90fb81cd9e500ec4198c9c7595c934`

[Instantiate](https://phat.phala.network/contracts/add/0xacbe3b24b3f798f58b06d8da0b8eeed14f90fb81cd9e500ec4198c9c7595c934)

## [Phat Bricks](https://github.com/Phala-Network/phat-bricks)

### lego

0.1.0 `0x219e0f258c0de1f730790b3602dadf8bd897b3b7e3e5c2cbcc1a161760634945`

[Instantiate](https://phat.phala.network/contracts/add/0x219e0f258c0de1f730790b3602dadf8bd897b3b7e3e5c2cbcc1a161760634945) | [Mainnet](https://phat.phala.network/contracts/view/0xe3e3ce14b65fa187e69c25223f00ce5d3ba6c9514805e65e046a56f65355260f?rpc=wss://api.phala.network/ws) | [Testnet](https://phat.phala.network/contracts/view/0xd9b9f56edb5b1aad92b08106fe6cf28d78f5e1cf5ae965ac19ffcc9f73ec703d?rpc=wss://poc5.phala.network/ws)


### action_offchain_rollup

0.1.2 `0x4c02fa94c7704df5d908537beeb8897dd002c9c5b9ec2693f911d1dda98da2c7`

| [Instantiate](https://phat.phala.network/contracts/add/0x4c02fa94c7704df5d908537beeb8897dd002c9c5b9ec2693f911d1dda98da2c7) |

0.1.1 `0x8087d7f4beacee49a055e74aefd984d5422786a4d577a36088ca38bf5a485efe`

| [Instantiate](https://phat.phala.network/contracts/add/0x8087d7f4beacee49a055e74aefd984d5422786a4d577a36088ca38bf5a485efe) |

0.1.0 `0x5bbb7ecf20cc5c5fa77f47b77c8ca1f6e6bc428b71f5c02c0a6ab4dd0569ec67`

| [Instantiate](https://phat.phala.network/contracts/add/0x5bbb7ecf20cc5c5fa77f47b77c8ca1f6e6bc428b71f5c02c0a6ab4dd0569ec67) |


### brick_profile

0.2.0 `0x3b3d35f92494fe60d9f9f6139ea83964dc4bca84d7ac66e985024358c9c62969`

| [Instantiate](https://phat.phala.network/contracts/add/0x3b3d35f92494fe60d9f9f6139ea83964dc4bca84d7ac66e985024358c9c62969) |

0.1.0 `0xdffe5496e9e48d444cad5d2bc37ce8098e0080e90d871dd5b03ec2a6aada49c5`

| [Instantiate](https://phat.phala.network/contracts/add/0xdffe5496e9e48d444cad5d2bc37ce8098e0080e90d871dd5b03ec2a6aada49c5) |


### brick_profile_factory

0.1.0 `0xeb65d30766360fb51fe01f638142ae4a5ef1ffbe66c016336b17977f4d5f7c29`

[Instantiate](https://phat.phala.network/contracts/add/0xeb65d30766360fb51fe01f638142ae4a5ef1ffbe66c016336b17977f4d5f7c29) | [Mainnet](https://phat.phala.network/contracts/view/0xb59bcc4ea352f3d878874d8f496fb093bdf362fa59d6e577c075f41cd7c84924?rpc=wss://api.phala.network/ws) | [Testnet](https://phat.phala.network/contracts/view/0x489bb4fa807bbe0f877ed46be8646867a8d16ec58add141977c4bd19b0237091?rpc=wss://poc5.phala.network/ws)


### qjs

1.1.0 `0xb081f1fb050decede4a167c7dfbf8d12ad01681c0e0bc9589fd8b40f4fc54a41`

| [Instantiate](https://phat.phala.network/contracts/add/0xb081f1fb050decede4a167c7dfbf8d12ad01681c0e0bc9589fd8b40f4fc54a41) |


1.0.0 `0xda2659b09da536f015d3631f3215989c96c712c166dba9985c0a1ec647f54f0a`

| [Instantiate](https://phat.phala.network/contracts/add/0xda2659b09da536f015d3631f3215989c96c712c166dba9985c0a1ec647f54f0a) |
