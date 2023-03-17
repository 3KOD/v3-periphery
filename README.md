# v3-periphery

KODKODKOD DEX v3-periphery smart contract

## March 17

```bash
npm run gen-binding
    Wrote ./tests/binding/fa2_nft.ts
    Wrote ./tests/binding/NonfungiblePositionManager.ts
    Wrote ./tests/binding/NonfungibleTokenPositionDescriptor.ts
    Wrote ./tests/binding/permits.ts
    Wrote ./tests/binding/SwapRouter.ts

completium-cli deploy ./contracts/permits.arl --parameters '{"owner":"tz1afKmEFo11mpXr4JdodJDTXYLfw7GTFbak"}'
    total cost    : 1.834881 ꜩ
    https://better-call.dev/ghostnet/KT1SXp6Jwdy2FSsjmVWjrxzsuBsdtmaqBbsL

completium-cli deploy ./contracts/NonfungibleTokenPositionDescriptor.arl
    total cost    : 0.115877 ꜩ
    https://better-call.dev/ghostnet/KT1CbxqJkB2ArSWZUp84PYqJudWfu3E2K6jN

completium-cli deploy ./contracts/NonfungiblePositionManager.arl --parameters '{"factory":"KT1NArLsaWtJeG8Jreza1EacSaH8KAhho5Wy", "tokenDescriptor": "KT1CbxqJkB2ArSWZUp84PYqJudWfu3E2K6jN", "kodexV3lib": "KT1KSjr9YbBXzZushTS4HuJ9jjyp1j74GYCC", "owner": "tz1afKmEFo11mpXr4JdodJDTXYLfw7GTFbak", "permits": "KT1SXp6Jwdy2FSsjmVWjrxzsuBsdtmaqBbsL"}'
    total cost    : 6.399338 ꜩ
    https://better-call.dev/ghostnet/KT1EdKZK2yMNFtm76rWXoXSQwrXdraxK6Shq

completium-cli deploy ./contracts/SwapRouter.arl --parameters '{"factory":"KT1NArLsaWtJeG8Jreza1EacSaH8KAhho5Wy", "kodexV3lib": "KT1KSjr9YbBXzZushTS4HuJ9jjyp1j74GYCC"}'
    total cost    : 1.323178 ꜩ
    https://better-call.dev/ghostnet/KT1HmSm7RD5sAZVES53douee93D75YNJXjve
```
