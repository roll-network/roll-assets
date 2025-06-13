# roll-assets
# Smart Contracts Reference

This document lists all the smart contracts used for Roll token minting and vesting across various versions.

---

## Version v1.5

| Contract Type       | Proxy Address                                     | Implementation Address                                  | Etherscan Link |
|---------------------|---------------------------------------------------|----------------------------------------------------------|----------------|
| Token Vesting       | —                                                 | `0x0E7F5c3c2A30823662045c3866681622bf4a5294`              | [Link](https://etherscan.io/address/0x0E7F5c3c2A30823662045c3866681622bf4a5294) |
| Registry            | `0x53F606ac65de27216b18df3d948806D733dCD5c6`      | `0xb400999485ad427b72fa3edde0f44f3ba2faac81`              | [Proxy](https://etherscan.io/address/0x53F606ac65de27216b18df3d948806D733dCD5c6) / [Impl](https://etherscan.io/address/0xb400999485ad427b72fa3edde0f44f3ba2faac81) |
| Token Factory       | `0x32DEFC3C18F794279481676ED91961f46032CD50`      | `0xa0ef35e8ddffdd5c7fcc2e3faa364c792e32abc5`              | [Proxy](https://etherscan.io/address/0x32DEFC3C18F794279481676ED91961f46032CD50) / [Impl](https://etherscan.io/address/0xa0ef35e8ddffdd5c7fcc2e3faa364c792e32abc5) |
| Manager             | `0xd1905280f456E111016cE79f9C907D8D917B9868`      | `0x201e3a5d12a45659ccab1118e38bb7c9f491c42a`              | [Proxy](https://etherscan.io/address/0xd1905280f456E111016cE79f9C907D8D917B9868) / [Impl](https://etherscan.io/address/0x201e3a5d12a45659ccab1118e38bb7c9f491c42a) |

---

## Version v1

| Contract Type       | Address                                           | Etherscan Link |
|---------------------|---------------------------------------------------|----------------|
| Token Vesting       | `0xbdeb21edd14f2b8438b0b9f01196e7c23fde1b73`      | [Link](https://etherscan.io/address/0xbdeb21edd14f2b8438b0b9f01196e7c23fde1b73) |
| Registry            | `0x2f16406a6dd13b25a3036d170b55442ac9e904af`      | [Link](https://etherscan.io/address/0x2f16406a6dd13b25a3036d170b55442ac9e904af) |
| Token Factory       | `0xdf65f4e6f2e9436bc1de1e00661c7108290e8bd3`      | [Link](https://etherscan.io/address/0xdf65f4e6f2e9436bc1de1e00661c7108290e8bd3) |
| Manager             | `0x865afba536205d56ab0223de00647ae8b3817ca0`      | [Link](https://etherscan.io/address/0x865afba536205d56ab0223de00647ae8b3817ca0) |

---

## How to Use

- Refer to the `info.json` files under `ethereum/assets/<token_contract_address>` or refer csv to see which version was used to mint a token.
