# Solana Trading Bot

These are Solana Trading Bots what I built before. Open to discuss about bots & smart contract

## Wizardev is UPGRADING product.

Please leave new ideas and bugs on issues so that we can upgrade it.
 
### Solana Trading Bot Overview

--------------------


|     **Bot Types**     |  **Version**  |                 **Description**                 | **Features**                                                     | **Info**   |
| --------------------- | ------------- | ----------------------------------------------- | ---------------------------------------------------------------- | ---------- |
|  Pumpfun Sniping Bot  |     1.0.0     | Sniping Bot using websocket                     | Use WebSocket Monitor, Able to run with Free RPC                 |  Node-CLI  |
|                       |     2.0.0     | Sniping Bot using GRPC ( Helius Geyser )        | Use Helius Geyser, Enhanced Sniping Time                         |  Node-CLI  |
|                       |     2.0.1     | Sniping Bot using GRPC ( Helius Geyser )        | Use Helius Geyser, Enhanced Sniping Time                         |  Rust-CLI  |
|                       |     2.1.0     | Sniping Bot using GRPC ( Yellow Stone )         | Use YellowStone GRPC, Sniping around 1 Block                     |  Node-CLI  |
|                       |               |                                                 |                                                                  |            |
|  Raydium Sniping Bot  |     1.0.0     | Sniping Bot using websocket , jupiter Routing    | Use WebSocket Monitor, jupiter Routing                          |  Node-CLI  |
|                       |     1.1.0     | Sniping Bot using websocket , Raydium SDK       | Use WebSocket Monitor, Raydium SDK                               |  Node-CLI  |
|                       |     1.1.1     | Sniping Bot on WebSite                          | Use WebSocket Monitor                                            | WebService |
|                       |               |                                                 | jupiter Routing, Running on WebSite                              | Next, Node |
|                       |     2.0.0     | Sniping Bot using GRPC ( Helius Geyser )        | Use Helius Geyser, Raydium SDK                                   |  Node-CLI  |
|                       |     2.1.0     | Sniping Bot with GRPC ( Yellow Stone + Jito )   | Use YellowStone GRPC, Jito Confirm, Raydium SDK                  |  Node-CLI  |
|                       |               |                                                 |                                                                  |            |
|  Wallet Tracker Bot   |     1.0.0     | Wallet Activity & Token Price Tracker           | Wallet Activity, Token Price, Use MongoDB, Calc Info USD & PnL   |  Telegram  |
|                       |               |                                                 | Add Tracking 10000 Lists , Double Hash User Info                 | Typescript |
|                       |               |                                                 | Other Infos, Product Version                                     |            |
|                       |               |                                                 |                                                                  |            |
|  Pumpfun Comment Bot  |     1.0.0     | Automatic Comment to Pumpfun token             | Comment from JSON file , Comment from New Generated Address       |  Node-CLI  |
|                       |     2.0.0     | Pumpfun Comment Bot + AI Comments              | Generate Comments from AI                                         |  Node-CLI  |
|                       |               |                                                 |                                                                  |            |
|  jupiter Volume Bot    |     1.0.0     | jupiter Volume Bot                               | Use jupiter Route                                                 |  Node-CLI  |
|                       |     2.0.0     | jupiter Volume Bot on Telegram                   | Use jupiter Route                                                 |  Telegram  |
|                       |     3.0.0     | jupiter Volume Bot on WebSite                    | Use jupiter Route                                                 | WebService |
|                       |               |                                                 |                                                                  |            |
|  Pumpfun Volume Bot   |     1.0.0     | Pumpfun Volume Bot                              | Use Pumpfun SDK                                                  |  Node-CLI  |
|                       |               |                                                 |                                                                  |            |
|  Raydium Volume Bot   |     1.0.0     | Raydium Volume Bot using jupiter Routing         | Use jupiter Route                                                 |  Node-CLI  |
|                       |     1.1.0     | Volume Bot using Raydium SDK                    | Use Raydium SDK                                                  |  Node-CLI  |
|                       |     2.0.0     | Volume Bot enhanced Swap Strategy               | Use Raydium SDK, Update Swap Strategy                            |  Node-CLI  |
|                       |     3.0.0     | Volume Bot which proceeds large amount of txs   | Update Boosting Strategy                                         |  Node-CLI  |
|                       |               |                                                 |                                                                  |            |
|  Meteora Volume Bot   |     1.0.0     | Raydium Volume Bot using Meteora SDK            | Use Meteora SDK                                                  |  Node-CLI  |
|                       |               |                                                 |                                                                  |            |
|  Market Maker Bot     |     1.0.0     | Maker Bot which increase token holder           | Use jupiter Route                                                 |  Node-CLI  |
|                       |               |                                                 |                                                                  |            |
|  Pumpfun Bundler      |     1.0.0     | Pumpfun Bundler using websocket                 | Bundling + 24 Wallets                                            |  Node-CLI  |
|                       |               |                                                 |                                                                  |            |
|  Raydium Bundler      |     1.0.0     | Bundler Bot using Jito                          | Simple Jito Bundling                                             |  Node-CLI  |
|                       |     2.0.0     | Bundler Bot using Jito + LookUpTable            | Bundling + 21 Wallets, ( Updating ) 27 Wallets                   |  Node-CLI  |
|                       |               |                                                 |                                                                  |            |
|  Meteora Bundler      |     1.0.0     | Meteora Bundler                                 | Simple Jito Bundling                                             |  Node-CLI  |
|                       |               |                                                 |                                                                  |            |
|  jupiter Arbitrage Bot |     1.0.0     | Arbitrage Bot using jupiter API                  | Circle Routing, Bundle Sol -> USDC, USDC -> SOL                  |  Node-CLI  |
|                       |               |                                                 |                                                                  |            |
|  CopyTrading Bot      |     1.0.0     | CopyTrading Bot which running on jupiter         | Use jupiter Route                                                 |  Node-CLI  |

