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
    https://better-call.dev/ghostnet/KT1Sy3pMPwXLBSBDsjbmZ4CwAJkPSbUXmTZb

completium-cli deploy ./contracts/NonfungibleTokenPositionDescriptor.arl
    total cost    : 0.115877 ꜩ
    https://better-call.dev/ghostnet/KT1XYLcdXvQCMF4MVfzvjbWe6yX5Um5iJFGJ

completium-cli deploy ./contracts/NonfungiblePositionManager.arl --parameters '{"factory":"KT1L7qXzdRgD2tMiYvS2VVFfeob43SKs5a5U", "tokenDescriptor": "KT1XYLcdXvQCMF4MVfzvjbWe6yX5Um5iJFGJ", "kodexV3lib": "KT1JqqYgRRYYq5kNPqYAUwWTtpuXZCtuAeaY", "owner": "tz1afKmEFo11mpXr4JdodJDTXYLfw7GTFbak", "permits": "KT1Sy3pMPwXLBSBDsjbmZ4CwAJkPSbUXmTZb"}'
    total cost    : 6.388042 ꜩ
    https://better-call.dev/ghostnet/KT1LeoXmqZUqaBUkYMUhHrMYkUMaPuTwM8Zg

completium-cli deploy ./contracts/SwapRouter.arl --parameters '{"factory":"KT1L7qXzdRgD2tMiYvS2VVFfeob43SKs5a5U", "kodexV3lib": "KT1JqqYgRRYYq5kNPqYAUwWTtpuXZCtuAeaY"}'
    total cost    : 1.323178 ꜩ
    https://better-call.dev/ghostnet/KT1KpyYEjy9XEBiAHH1r8YX4zHeV9FyQrcuu
```
