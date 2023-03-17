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

completium-cli deploy ./contracts/NonfungiblePositionManager.arl --parameters '{"factory":"KT1H3PMQ4wJuMPiwCP4mCgy4m1knMTUZacZb", "tokenDescriptor": "KT1CbxqJkB2ArSWZUp84PYqJudWfu3E2K6jN", "kodexV3lib": "KT1KtbzHcike7oQTRgcnKC2fGYRUaHsuq4L6", "owner": "tz1afKmEFo11mpXr4JdodJDTXYLfw7GTFbak", "permits": "KT1SXp6Jwdy2FSsjmVWjrxzsuBsdtmaqBbsL"}'
    total cost    : 6.399338 ꜩ
    https://better-call.dev/ghostnet/KT1GpiRKRsMUw8dqdZkmorcH1RusDAHaQnvn

completium-cli deploy ./contracts/SwapRouter.arl --parameters '{"factory":"KT1H3PMQ4wJuMPiwCP4mCgy4m1knMTUZacZb", "kodexV3lib": "KT1KtbzHcike7oQTRgcnKC2fGYRUaHsuq4L6"}'
    total cost    : 1.323178 ꜩ
    https://better-call.dev/ghostnet/KT1LKGkpgggHVoMUpNaZ6W3RVmiqyncphtKP
```
