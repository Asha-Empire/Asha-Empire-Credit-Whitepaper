# Asha Empire Credit Token Whitepaper

## Executive Summary
Asha Empire Credit is a Solana-based cryptocurrency designed for the Asha Empire Online MMORPG. This whitepaper provides detailed information on the token's technical structure, economy, both in-game and external usage, and future plans. Our project aims to create a new economic system within the gaming world and offer players the freedom to manage their digital assets.

## Technology and Infrastructure

### Solana Blockchain Integration
Our token, utilizing the Metaplex infrastructure, will be created on Solana, one of the top 10 most actively traded networks in the world, chosen for its high transaction speed and low cost advantages. Players can track the tokens they earn in the game from their game accounts. Using Solana addresses created for game accounts, they can transfer from outside the game to their game accounts. When AEC (Asha Empire Credit) is transferred from outside to the game Solana accounts, a background job will be processing these AECs to the game account individually. Similarly, when transferring AEC from game accounts to an external Solana address, another job will sequentially process these transactions. Transfers of AEC from within the game to the outside world will be possible after verification for a Solana address.

### Token Features
Asha Empire Credit will be created using the Metaplex Token Metadata program from Metaplex. The number of tokens is not fixed; they will be minted or burned based on the inflation values in the game economy.

## Token Economy

### Supply and Distribution
Initially, 1,000,000 AEC will be minted and made available for use in the game. Instead of a fixed dollar price, AEC will be sold on the asha-empire.credit website, a maximum of 1,000 AEC daily priced in Solana (SOL), ensuring that 1 AEC's value is always equivalent to 1 USD according to the current SOL value. For example, if 1 SOL is valued at 100 USD, then 100 AEC will be sold for 1 SOL. This approach aligns the value of AEC with the fluctuations in the Solana market, providing a dynamic pricing mechanism. For every 1,000 active players, an additional 1,000 AEC will be sold by the game. The reminting of AEC and an increase in the number of tokens will be contingent on the in-game economy, aiming to maintain inflation between 0% and 5%. If inflation falls below 0%, minting will start, distributing tokens through in-game mining, reward distributions, and quests. Additionally, in-game taxes, interest, and transaction fees will be adjusted in response to changes in inflation.

Players can accumulate AEC by defeating bandits in the game, collecting AEC carried by other defeated players, mining and selling resources, crafting items, completing quests, forming corporations, and earning interest by depositing in banks.

### Burning and Value Appreciation Mechanisms
To maintain the balance of the game's economy, if inflation exceeds 5%, in-game taxes, interest, and transaction fees will be increased until inflation decreases, with the excess AEC being burned.

### Interest
The interest offered by in-game banks will be proportional to inflation. As inflation rises, interest rates will increase, and they will decrease as inflation falls. This interest will be utilized in two ways: players depositing in banks will earn interest, and players taking loans from banks will pay interest.

## Usage Scenarios and Player Interactions

### In-Game Usage
All economic activities within the game will be conducted using AEC. All assets will be traded in AEC. All rewards, taxes, and transaction fees will be collected in AEC.

### External Usage
Efforts will be made to integrate and list AEC on local and global cryptocurrency exchanges. The game’s website, asha-empire.credit, will be used to facilitate integrated operations with all these exchanges.

For transferring from the game to a wallet, the desired Solana address to send from the game account will be specified. Once this transaction is verified, it will be executed by a job.

When someone sends AECs, which they have bought from crypto exchanges or have in their wallet, to the unique Solana address specified for a player in their game account, a job will transfer this transaction to the game account. From this point onwards, the player will be able to use these AECs within the game as they wish.
