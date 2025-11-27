## 安装zetachain

``npm install -g zetachain

### 报错

```
xboxpig@XBPG-PC:/mnt/c/Users/xboxpig$ sudo npm install -g zetachain
npm WARN ERESOLVE overriding peer dependency
npm WARN While resolving: @ton/ton@15.4.0
npm WARN Found: @ton/core@0.60.1
npm WARN node_modules/zetachain/node_modules/@zetachain/toolkit/node_modules/@ton/core
npm WARN   @ton/core@"^0.60.1" from @zetachain/toolkit@16.3.0
npm WARN   node_modules/zetachain/node_modules/@zetachain/toolkit
npm WARN     @zetachain/toolkit@"16.3.0" from zetachain@7.4.0
npm WARN     node_modules/zetachain
npm WARN
npm WARN Could not resolve dependency:
npm WARN peer @ton/core@">=0.62.0 <1.0.0" from @ton/ton@15.4.0
npm WARN node_modules/zetachain/node_modules/@zetachain/toolkit/node_modules/@ton/ton
npm WARN   @ton/ton@"^15.2.1" from @zetachain/toolkit@16.3.0
npm WARN   node_modules/zetachain/node_modules/@zetachain/toolkit
npm WARN
npm WARN Conflicting peer dependency: @ton/core@0.62.0
npm WARN node_modules/@ton/core
npm WARN   peer @ton/core@">=0.62.0 <1.0.0" from @ton/ton@15.4.0
npm WARN   node_modules/zetachain/node_modules/@zetachain/toolkit/node_modules/@ton/ton
npm WARN     @ton/ton@"^15.2.1" from @zetachain/toolkit@16.3.0
npm WARN     node_modules/zetachain/node_modules/@zetachain/toolkit
npm WARN EBADENGINE Unsupported engine {
npm WARN EBADENGINE   package: 'posthog-node@5.14.0',
npm WARN EBADENGINE   required: { node: '>=20' },
npm WARN EBADENGINE   current: { node: 'v18.19.1', npm: '9.2.0' }
npm WARN EBADENGINE }
npm WARN EBADENGINE Unsupported engine {
npm WARN EBADENGINE   package: '@solana/codecs-numbers@2.3.0',
npm WARN EBADENGINE   required: { node: '>=20.18.0' },
npm WARN EBADENGINE   current: { node: 'v18.19.1', npm: '9.2.0' }
npm WARN EBADENGINE }
npm WARN EBADENGINE Unsupported engine {
npm WARN EBADENGINE   package: '@solana/wallet-adapter-react@0.15.39',
npm WARN EBADENGINE   required: { node: '>=20' },
npm WARN EBADENGINE   current: { node: 'v18.19.1', npm: '9.2.0' }
npm WARN EBADENGINE }
npm WARN EBADENGINE Unsupported engine {
npm WARN EBADENGINE   package: '@solana/wallet-adapter-base@0.9.27',
npm WARN EBADENGINE   required: { node: '>=20' },
npm WARN EBADENGINE   current: { node: 'v18.19.1', npm: '9.2.0' }
npm WARN EBADENGINE }
npm WARN EBADENGINE Unsupported engine {
npm WARN EBADENGINE   package: 'react-native@0.82.1',
npm WARN EBADENGINE   required: { node: '>= 20.19.4' },
npm WARN EBADENGINE   current: { node: 'v18.19.1', npm: '9.2.0' }
npm WARN EBADENGINE }
npm WARN EBADENGINE Unsupported engine {
npm WARN EBADENGINE   package: '@solana/codecs-strings@4.0.0',
npm WARN EBADENGINE   required: { node: '>=20.18.0' },
npm WARN EBADENGINE   current: { node: 'v18.19.1', npm: '9.2.0' }
npm WARN EBADENGINE }
npm WARN EBADENGINE Unsupported engine {
npm WARN EBADENGINE   package: '@nomicfoundation/edr@0.12.0-next.16',
npm WARN EBADENGINE   required: { node: '>= 20' },
npm WARN EBADENGINE   current: { node: 'v18.19.1', npm: '9.2.0' }
npm WARN EBADENGINE }
npm WARN EBADENGINE Unsupported engine {
npm WARN EBADENGINE   package: '@nomicfoundation/edr-darwin-arm64@0.12.0-next.16',
npm WARN EBADENGINE   required: { node: '>= 20' },
npm WARN EBADENGINE   current: { node: 'v18.19.1', npm: '9.2.0' }
npm WARN EBADENGINE }
npm WARN EBADENGINE Unsupported engine {
npm WARN EBADENGINE   package: '@nomicfoundation/edr-darwin-x64@0.12.0-next.16',
npm WARN EBADENGINE   required: { node: '>= 20' },
npm WARN EBADENGINE   current: { node: 'v18.19.1', npm: '9.2.0' }
npm WARN EBADENGINE }
npm WARN EBADENGINE Unsupported engine {
npm WARN EBADENGINE   package: '@nomicfoundation/edr-linux-arm64-gnu@0.12.0-next.16',
npm WARN EBADENGINE   required: { node: '>= 20' },
npm WARN EBADENGINE   current: { node: 'v18.19.1', npm: '9.2.0' }
npm WARN EBADENGINE }
npm WARN EBADENGINE Unsupported engine {
npm WARN EBADENGINE   package: '@nomicfoundation/edr-linux-arm64-musl@0.12.0-next.16',
npm WARN EBADENGINE   required: { node: '>= 20' },
npm WARN EBADENGINE   current: { node: 'v18.19.1', npm: '9.2.0' }
npm WARN EBADENGINE }
npm WARN EBADENGINE Unsupported engine {
npm WARN EBADENGINE   package: '@nomicfoundation/edr-linux-x64-gnu@0.12.0-next.16',
npm WARN EBADENGINE   required: { node: '>= 20' },
npm WARN EBADENGINE   current: { node: 'v18.19.1', npm: '9.2.0' }
npm WARN EBADENGINE }
npm WARN EBADENGINE Unsupported engine {
npm WARN EBADENGINE   package: '@nomicfoundation/edr-linux-x64-musl@0.12.0-next.16',
npm WARN EBADENGINE   required: { node: '>= 20' },
npm WARN EBADENGINE   current: { node: 'v18.19.1', npm: '9.2.0' }
npm WARN EBADENGINE }
npm WARN EBADENGINE Unsupported engine {
npm WARN EBADENGINE   package: '@nomicfoundation/edr-win32-x64-msvc@0.12.0-next.16',
npm WARN EBADENGINE   required: { node: '>= 20' },
npm WARN EBADENGINE   current: { node: 'v18.19.1', npm: '9.2.0' }
npm WARN EBADENGINE }
npm WARN EBADENGINE Unsupported engine {
npm WARN EBADENGINE   package: '@react-native/assets-registry@0.82.1',
npm WARN EBADENGINE   required: { node: '>= 20.19.4' },
npm WARN EBADENGINE   current: { node: 'v18.19.1', npm: '9.2.0' }
npm WARN EBADENGINE }
npm WARN EBADENGINE Unsupported engine {
npm WARN EBADENGINE   package: '@react-native/codegen@0.82.1',
npm WARN EBADENGINE   required: { node: '>= 20.19.4' },
npm WARN EBADENGINE   current: { node: 'v18.19.1', npm: '9.2.0' }
npm WARN EBADENGINE }
npm WARN EBADENGINE Unsupported engine {
npm WARN EBADENGINE   package: '@react-native/community-cli-plugin@0.82.1',
npm WARN EBADENGINE   required: { node: '>= 20.19.4' },
npm WARN EBADENGINE   current: { node: 'v18.19.1', npm: '9.2.0' }
npm WARN EBADENGINE }
npm WARN EBADENGINE Unsupported engine {
npm WARN EBADENGINE   package: '@react-native/gradle-plugin@0.82.1',
npm WARN EBADENGINE   required: { node: '>= 20.19.4' },
npm WARN EBADENGINE   current: { node: 'v18.19.1', npm: '9.2.0' }
npm WARN EBADENGINE }
npm WARN EBADENGINE Unsupported engine {
npm WARN EBADENGINE   package: '@react-native/js-polyfills@0.82.1',
npm WARN EBADENGINE   required: { node: '>= 20.19.4' },
npm WARN EBADENGINE   current: { node: 'v18.19.1', npm: '9.2.0' }
npm WARN EBADENGINE }
npm WARN EBADENGINE Unsupported engine {
npm WARN EBADENGINE   package: '@react-native/virtualized-lists@0.82.1',
npm WARN EBADENGINE   required: { node: '>= 20.19.4' },
npm WARN EBADENGINE   current: { node: 'v18.19.1', npm: '9.2.0' }
npm WARN EBADENGINE }
npm WARN EBADENGINE Unsupported engine {
npm WARN EBADENGINE   package: 'metro-runtime@0.83.3',
npm WARN EBADENGINE   required: { node: '>=20.19.4' },
npm WARN EBADENGINE   current: { node: 'v18.19.1', npm: '9.2.0' }
npm WARN EBADENGINE }
npm WARN EBADENGINE Unsupported engine {
npm WARN EBADENGINE   package: 'metro-source-map@0.83.3',
npm WARN EBADENGINE   required: { node: '>=20.19.4' },
npm WARN EBADENGINE   current: { node: 'v18.19.1', npm: '9.2.0' }
npm WARN EBADENGINE }
npm WARN EBADENGINE Unsupported engine {
npm WARN EBADENGINE   package: '@react-native/dev-middleware@0.82.1',
npm WARN EBADENGINE   required: { node: '>= 20.19.4' },
npm WARN EBADENGINE   current: { node: 'v18.19.1', npm: '9.2.0' }
npm WARN EBADENGINE }
npm WARN EBADENGINE Unsupported engine {
npm WARN EBADENGINE   package: 'metro@0.83.3',
npm WARN EBADENGINE   required: { node: '>=20.19.4' },
npm WARN EBADENGINE   current: { node: 'v18.19.1', npm: '9.2.0' }
npm WARN EBADENGINE }
npm WARN EBADENGINE Unsupported engine {
npm WARN EBADENGINE   package: 'metro-config@0.83.3',
npm WARN EBADENGINE   required: { node: '>=20.19.4' },
npm WARN EBADENGINE   current: { node: 'v18.19.1', npm: '9.2.0' }
npm WARN EBADENGINE }
npm WARN EBADENGINE Unsupported engine {
npm WARN EBADENGINE   package: 'metro-core@0.83.3',
npm WARN EBADENGINE   required: { node: '>=20.19.4' },
npm WARN EBADENGINE   current: { node: 'v18.19.1', npm: '9.2.0' }
npm WARN EBADENGINE }
npm WARN EBADENGINE Unsupported engine {
npm WARN EBADENGINE   package: '@react-native/debugger-frontend@0.82.1',
npm WARN EBADENGINE   required: { node: '>= 20.19.4' },
npm WARN EBADENGINE   current: { node: 'v18.19.1', npm: '9.2.0' }
npm WARN EBADENGINE }
npm WARN EBADENGINE Unsupported engine {
npm WARN EBADENGINE   package: '@react-native/debugger-shell@0.82.1',
npm WARN EBADENGINE   required: { node: '>= 20.19.4' },
npm WARN EBADENGINE   current: { node: 'v18.19.1', npm: '9.2.0' }
npm WARN EBADENGINE }
npm WARN EBADENGINE Unsupported engine {
npm WARN EBADENGINE   package: 'fb-dotslash@0.5.8',
npm WARN EBADENGINE   required: { node: '>=20' },
npm WARN EBADENGINE   current: { node: 'v18.19.1', npm: '9.2.0' }
npm WARN EBADENGINE }
npm WARN EBADENGINE Unsupported engine {
npm WARN EBADENGINE   package: 'metro-babel-transformer@0.83.3',
npm WARN EBADENGINE   required: { node: '>=20.19.4' },
npm WARN EBADENGINE   current: { node: 'v18.19.1', npm: '9.2.0' }
npm WARN EBADENGINE }
npm WARN EBADENGINE Unsupported engine {
npm WARN EBADENGINE   package: 'metro-cache@0.83.3',
npm WARN EBADENGINE   required: { node: '>=20.19.4' },
npm WARN EBADENGINE   current: { node: 'v18.19.1', npm: '9.2.0' }
npm WARN EBADENGINE }
npm WARN EBADENGINE Unsupported engine {
npm WARN EBADENGINE   package: 'metro-cache-key@0.83.3',
npm WARN EBADENGINE   required: { node: '>=20.19.4' },
npm WARN EBADENGINE   current: { node: 'v18.19.1', npm: '9.2.0' }
npm WARN EBADENGINE }
npm WARN EBADENGINE Unsupported engine {
npm WARN EBADENGINE   package: 'metro-file-map@0.83.3',
npm WARN EBADENGINE   required: { node: '>=20.19.4' },
npm WARN EBADENGINE   current: { node: 'v18.19.1', npm: '9.2.0' }
npm WARN EBADENGINE }
npm WARN EBADENGINE Unsupported engine {
npm WARN EBADENGINE   package: 'metro-resolver@0.83.3',
npm WARN EBADENGINE   required: { node: '>=20.19.4' },
npm WARN EBADENGINE   current: { node: 'v18.19.1', npm: '9.2.0' }
npm WARN EBADENGINE }
npm WARN EBADENGINE Unsupported engine {
npm WARN EBADENGINE   package: 'metro-symbolicate@0.83.3',
npm WARN EBADENGINE   required: { node: '>=20.19.4' },
npm WARN EBADENGINE   current: { node: 'v18.19.1', npm: '9.2.0' }
npm WARN EBADENGINE }
npm WARN EBADENGINE Unsupported engine {
npm WARN EBADENGINE   package: 'metro-transform-plugins@0.83.3',
npm WARN EBADENGINE   required: { node: '>=20.19.4' },
npm WARN EBADENGINE   current: { node: 'v18.19.1', npm: '9.2.0' }
npm WARN EBADENGINE }
npm WARN EBADENGINE Unsupported engine {
npm WARN EBADENGINE   package: 'metro-transform-worker@0.83.3',
npm WARN EBADENGINE   required: { node: '>=20.19.4' },
npm WARN EBADENGINE   current: { node: 'v18.19.1', npm: '9.2.0' }
npm WARN EBADENGINE }
npm WARN EBADENGINE Unsupported engine {
npm WARN EBADENGINE   package: 'ob1@0.83.3',
npm WARN EBADENGINE   required: { node: '>=20.19.4' },
npm WARN EBADENGINE   current: { node: 'v18.19.1', npm: '9.2.0' }
npm WARN EBADENGINE }
npm WARN EBADENGINE Unsupported engine {
npm WARN EBADENGINE   package: 'metro-minify-terser@0.83.3',
npm WARN EBADENGINE   required: { node: '>=20.19.4' },
npm WARN EBADENGINE   current: { node: 'v18.19.1', npm: '9.2.0' }
npm WARN EBADENGINE }
npm WARN EBADENGINE Unsupported engine {
npm WARN EBADENGINE   package: '@solana/codecs-core@4.0.0',
npm WARN EBADENGINE   required: { node: '>=20.18.0' },
npm WARN EBADENGINE   current: { node: 'v18.19.1', npm: '9.2.0' }
npm WARN EBADENGINE }
npm WARN EBADENGINE Unsupported engine {
npm WARN EBADENGINE   package: '@solana/codecs-numbers@4.0.0',
npm WARN EBADENGINE   required: { node: '>=20.18.0' },
npm WARN EBADENGINE   current: { node: 'v18.19.1', npm: '9.2.0' }
npm WARN EBADENGINE }
npm WARN EBADENGINE Unsupported engine {
npm WARN EBADENGINE   package: '@solana/errors@4.0.0',
npm WARN EBADENGINE   required: { node: '>=20.18.0' },
npm WARN EBADENGINE   current: { node: 'v18.19.1', npm: '9.2.0' }
npm WARN EBADENGINE }
npm WARN EBADENGINE Unsupported engine {
npm WARN EBADENGINE   package: 'commander@14.0.1',
npm WARN EBADENGINE   required: { node: '>=20' },
npm WARN EBADENGINE   current: { node: 'v18.19.1', npm: '9.2.0' }
npm WARN EBADENGINE }
npm WARN EBADENGINE Unsupported engine {
npm WARN EBADENGINE   package: '@solana/codecs-core@2.3.0',
npm WARN EBADENGINE   required: { node: '>=20.18.0' },
npm WARN EBADENGINE   current: { node: 'v18.19.1', npm: '9.2.0' }
npm WARN EBADENGINE }
npm WARN EBADENGINE Unsupported engine {
npm WARN EBADENGINE   package: '@solana/errors@2.3.0',
npm WARN EBADENGINE   required: { node: '>=20.18.0' },
npm WARN EBADENGINE   current: { node: 'v18.19.1', npm: '9.2.0' }
npm WARN EBADENGINE }
npm WARN EBADENGINE Unsupported engine {
npm WARN EBADENGINE   package: 'commander@14.0.2',
npm WARN EBADENGINE   required: { node: '>=20' },
npm WARN EBADENGINE   current: { node: 'v18.19.1', npm: '9.2.0' }
npm WARN EBADENGINE }

```

大抵是nodejs版本太旧了 需要新的 但是我刚刚不是用apt装完了吗？
Gemini推荐我用nvm解决

#### Q: 什么是nvm? 
> 似乎是nodejs自己的版本管理app吧 我猜是nodejs version manager

```
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.7/install.sh | bash
nvm install 20
nvm use 20
```

### 修正并重新安装

`npm install -g zetachain

`xboxpig@XBPG-PC:/mnt/c/Users/xboxpig$ zetachain --version
`7.4.0

`xboxpig@XBPG-PC:/mnt/c/Users/xboxpig$ zetachain query chains list

安装完成 我们看到链了！

`✔ Successfully fetched 13 supported chains, 32 tokens, and 13 chain params
```
┌──────────┬────────────────────┬───────┬──────────────────────────────────┐
│ Chain ID │ Chain Name         │ Count │ Tokens                           │
├──────────┼────────────────────┼───────┼──────────────────────────────────┤
│ 97       │ bsc_testnet        │ 20    │ USDC.BSC, BNB.BSC                │
├──────────┼────────────────────┼───────┼──────────────────────────────────┤
│ 7001     │ zeta_testnet       │ 3     │ -                                │
├──────────┼────────────────────┼───────┼──────────────────────────────────┤
│ 11155111 │ sepolia_testnet    │ 14    │ ETH.ETHSEP, USDTT.SEPOLIA,       │
│          │                    │       │ USDC.ETHSEP, USDCT.SEPOLIA       │
├──────────┼────────────────────┼───────┼──────────────────────────────────┤
│ 80002    │ amoy_testnet       │ 32    │ POL.AMOY, USDC.AMOY              │
├──────────┼────────────────────┼───────┼──────────────────────────────────┤
│ 84532    │ base_sepolia       │ 32    │ ETH.BASESEP, USDCT.BASESEP,      │
│          │                    │       │ USDTT.BASESEP, USDC.BASESEP      │
├──────────┼────────────────────┼───────┼──────────────────────────────────┤
│ 901      │ solana_devnet      │ 32    │ SOL.SOL, USDC.SOL                │
├──────────┼────────────────────┼───────┼──────────────────────────────────┤
│ 18333    │ btc_signet_testnet │ 2     │ sBTC.BTC                         │
├──────────┼────────────────────┼───────┼──────────────────────────────────┤
│ 18334    │ btc_testnet4       │ 10    │ tBTC.BTC                         │
├──────────┼────────────────────┼───────┼──────────────────────────────────┤
│ 421614   │ arbitrum_sepolia   │ 5     │ USDTT.ARBSEP, UPKRW.ARBSEP,      │
│          │                    │       │ ETH.ARBSEP, USDC.ARBSEP,         │
│          │                    │       │ USDCT.ARBSEP                     │
├──────────┼────────────────────┼───────┼──────────────────────────────────┤
│ 43113    │ avalanche_testnet  │ 20    │ USDC.FUJI, USDCT.FUJI,           │
│          │                    │       │ HanaKRW.FUJI, AVAX.FUJI,         │
│          │                    │       │ USDTT.FUJI                       │
├──────────┼────────────────────┼───────┼──────────────────────────────────┤
│ 2015141  │ ton_testnet        │ 1     │ TON.TON                          │
├──────────┼────────────────────┼───────┼──────────────────────────────────┤
│ 103      │ sui_testnet        │ 1     │ SUI.SUI, USDC.SUI                │
├──────────┼────────────────────┼───────┼──────────────────────────────────┤
│ 1001     │ kaia_testnet       │ 1     │ KBKRW.KAIROS, TSKRW.KAIROS,      │
│          │                    │       │ KAIA.KAIROS                      │
└──────────┴────────────────────┴───────┴──────────────────────────────────┘

Note: Count refers to the number of confirmations required for a transaction
from that connected chain to be observed
```

