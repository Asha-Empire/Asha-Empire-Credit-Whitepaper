# Asha Empire Credit Token Whitepaper

## Executive Summary
Asha Empire Credit is a Solana-based cryptocurrency designed for the Asha Empire Online MMORPG. This whitepaper provides detailed information on the token's technical structure, economy, both in-game and external usage, and future plans. Our project aims to create a new economic system within the gaming world and offer players the freedom to manage their digital assets.

## Technology and Infrastructure

### Solana Blockchain Integration
Our token, utilizing the Metaplex infrastructure, will be created on Solana, one of the top 10 most actively traded networks in the world, chosen for its high transaction speed and low cost advantages. Players can track the tokens they earn in the game from their game accounts. Using Solana addresses created for game accounts, they can transfer from outside the game to their game accounts. When AEC (Asha Empire Credit) is transferred from outside to the game Solana accounts, a background job will be processing these AECs to the game account individually. Similarly, when transferring AEC from game accounts to an external Solana address, another job will sequentially process these transactions. Transfers of AEC from within the game to the outside world will be possible after verification for a Solana address.

### Token Features
Asha Empire Credit will be created using the Metaplex Token Metadata program from Metaplex. The number of tokens is not fixed; they will be minted or burned based on the inflation values in the game economy.
