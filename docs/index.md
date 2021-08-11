#

## Project Overview

Horizon Protocol is a DeFi platform that facilitates the on-chain trading of synthetic assets that represent the real economy. Horizon Protocol seeks to provide exposure to real-world assets risk/return profiles via smart contracts on the blockchain.

Forked from Synthetix, Horizon Protocol will leverage the time-tested derivative liquidity protocol and bring interoperability, scalability and a whole new array of tradable, real-world derivative products to the DeFi ecosystem. Our commitment to the Binance ecosystem and native implementation on Binance Smart Chain (BSC) offer users the speed and dependability that is currently lacking on the Ethereum blockchain.

### Resources

- [Horizon Protocol Website](https://horizonprotocol.com/)
- [Horizon Protocol Litepaper](https://horizonprotocol.com/files/Horizon-Litepaper-v1.5.1.pdf)
- [Horizon Medium](https://horizonprotocol.medium.com/)
- [Official Telegram Channel](https://t.me/HorizonProtocol)
- [Official Telegram Announcements Channel](https://t.me/HorizonAnnouncements)
- [Twitter](https://twitter.com/HorizonProtocol)
- [Reddit](https://www.reddit.com/r/HorizonProtocol/)
- [CoinGecko](https://www.coingecko.com/en/coins/horizon-protocol)
- [Coin Market Cap](https://coinmarketcap.com/currencies/horizon-protocol/)
- Token Contract: [0xc0eff7749b125444953ef89682201fb8c6a917cd](https://bscscan.com/token/0xc0eff7749b125444953ef89682201fb8c6a917cd)

<!--
  Horizon Genesis
  - HZN
  - Synthetic Assets
  - zAssets
  - zUSD
  - Collateralization
  - C-Ratio
  - Staking and Rewards
  - Debt
-->

## Horizon Genesis

Horizon Genesis is the backbone for all the synthetic assets in the Horizon ecosystem. Horizon Genesis maintains the collateralization ratio by offering staking mechanisms for the Horizon Protocol network to stabilize the ecosystem and create synthetic assets. Horizon Genesis is used to create Horizon Protocol's first synthetic asset, the zUSD, which is minted with HZN as collateral.

Below are concepts that are important to understand:

### HZN (and where to buy)

HZN is the token for the Horizon Protocol network that supports and underlies the synthetic assets produced on the network.

You can buy HZN via the following exchanges:

**Decentralized Exchanges (DEX)**  
[PancakeSwap](https://exchange.pancakeswap.finance/#/swap)

**Centralized Exchanges (CEX)**  
[MXC Spot Exchange](https://www.mexc.com/exchange/HZN_USDT)  
[MXC Margin/Leverage Exchange (5x)](https://www.mexc.com/margin/HZN_USDT)
[Hoo Spot Exchange](https://hoo.com/innovation/hzn-usdt)

### Synthetic Assets

Synthetic assets are derivatives, which are assets that derive its value from another underlying asset. Synthetic assets can be stocks, tokens, indices, NFTs, or other financial products and are produced to mimic the original asset, typically in the form of its price. For example, a synthetic asset of a stock would mimic the price fluctuations of the stock, while a synthetic asset of a token would mimic the price fluctuations of the token. Since synthetic assets are also tokenized, they are easily accessible and allow for an additional layer of DeFi products that can be applied to the asset, possibly giving yield-generating opportunities to investors on assets that may not have had these options naturally.

### zAssets

Synthetic Assets produced on Horizon Protocol are called zAssets. For example, a Gamestop (GME) stock would be called zGME.

### zUSD

zUSD is the core zAsset of Horizon Protocol and is a stablecoin pegged to the US Dollar. zUSD is important because the total value of all the synthetic assets (global debt) produced on Horizon Protocol is evaluated and denominated in zUSD.

Horizon Genesis will guarantee that zUSD is valued at $1.00 when being [minted](#mint) or [burned](#burn). The value of zUSD that exists on the open market could fluctuate in price (based on supply/demand forces), but that would create arbitrage opportunities to profit between the open market and Horizon Genesis.

zUSD will also facilitate the trading of other zAssets, which will be available on the Horizon Exchange (under development).

Horizon Exchange will offer cross-chain crypto derivatives, traditional asset derivatives, as well as new financial products/assets.

### Collateralization Ratio (C-Ratio)

All zAssets produced on Horizon Protocol must be collateralized by HZN in order for their values to be maintained. HZN is staked and zUSD is minted at a Collateralization Ratio (C-Ratio) of 800% ($8 worth of HZN to mint $1 zUSD), and this C-Ratio must be maintained in order to collect rewards from the system. The purpose of the C-Ratio is to ensure that the synthetic assets are sufficiently backed during HZN price fluctuations. The 800% target C-Ratio is subject to change based on the community governance.

### Staking and Rewards

There are multiple ways to stake on Horizon Genesis and earn rewards. There are two ways to stake: **Mint** and **Earn**. **Mint** is when a user creates zUSD using HZN as collateral and gets rewards according to the amount of debt they hold. This will be the main way to stake and will also receive the majority of the rewards issued in Horizon Protocol. **Earn** provides different opportunities to earn through liquidity provision and the staking of LP tokens.

Staking rewards are distributed per system rules (these can change as the system evolves) and are provided by the token’s inflationary policy, exchange fees (relevant when the Horizon Exchange becomes available), and any other system incentives (if applicable).

### Debt

Debt is an important concept for understanding reward distribution when minting on Horizon Genesis. When a user mints zUSD, they are borrowing zUSD with HZN as collateral, and they will have to return (burn) their zUSD in order to reclaim their HZN. That means that they are now in debt (interest-free) to the amount of the zUSD that they have minted. User rewards are calculated by the ratio of the user's debt relative to the global debt in the Horizon Protocol network.

<!--
  Staking on Horizon Genesis
  - Getting Started
  - 1. Set up Wallet
  - 2. Acquire Tokens
  - 3. Access Horizon Genesis
  - 4. Begin Staking by Minting
  - 5. Collect Rewards
  - Rewards Summary
-->

## Staking on Horizon Genesis

When a user stakes HZN to mint on Horizon Genesis, the stake is pooled with all other staked HZN and that pool collateralizes all zAssets on the entire Horizon Protocol network. As an investor, you can mint zUSD, which means you are incurring an interest-free debt to the network. The debt must be adequately collateralized and your C-Ratio always maintained in order to be eligible for rewards. For savvy investors, this debt can be leveraged to earn yield through staking as an LP or trading on the Horizon Exchange.

Anyone that holds HZN tokens can stake on the network, with no minimum requirements. However, you must also have BNB tokens to pay for network gas.

### Getting Started

Below are instructions on how to get started:

### 1. Set up Wallet

To start, the user will need a wallet. Horizon Genesis operates on the BSC (Binance Smart Chain), so the wallet for the HZN token must be BSC compatible. Horizon Genesis supports the following wallets:

- MetaMask
- TrustWallet
- Binance Chain Wallet extension (FireFox, Chrome, Edge)

_Note that Hardware wallets (Ledger, Trezor) are not supported natively by Horizon Protocol, however, are available through MetaMask and the Binance Chain Wallet browser extension._

### 2. Acquire Tokens

Acquire HZN tokens for staking and BNB tokens to pay for network gas. [Click here](#hzn-and-where-to-buy) to see where you can buy HZN tokens.

### 3. Access Horizon Genesis

Visit the [Horizon Genesis Website](https://genesis.horizonprotocol.com) and connect your wallet by clicking on the top right corner and selecting your preferred wallet.

### 4. Begin Staking by Minting

After connecting your wallet, you are ready to stake. Minting means you will be staking your HZN to create zUSD.

The maximum amount of zUSD you can mint is at a 800% C-Ratio, which means that for every $800 USD worth of HZN, you will be able to mint $100 zUSD.

To begin minting, you can either:

- **Select a Preset Strategy**  
  The user can choose how much they want to Mint by selecting a preset strategy. **Aggressive** will populate the maximum amount of zUSD that is mintable, given the user's HZN holdings. **Neutral** and **Conservative** helps create a bit of a buffer so zUSD does not need to be as frequently burnt or HZN added to maintain the 800% C-Ratio. Learn more about [strategies](#strategies).
- **Select Amount of HZN to Stake**
  The user can type in how much HZN they want to stake or click _Mint Max_, which will collateralize at 800%, the same as using the Aggressive strategy.
- **Select Amount of zUSD to Mint**
  The user can type in exactly how much zUSD they want to mint.

### 5. Collect Rewards

Once a week, on Fridays, rewards will be available to be collected. Go to the Claim tab and click [Claim](#claim). A notification will display on the Claim tab if you have rewards available to claim. The reward can only be collected if the user's C-Ratio is 800% or more. If it's less, the user will need to go to the Burn tab to burn some zUSD or add some more HZN to your wallet. There is a few percent buffer under 800% where you can still claim your rewards.

### Managing C-Ratio and Rewards Summary

- Users must maintain a C-Ratio of above 800% in order to be eligible for rewards. (If you are within a few percent of 800%, i.e. 795% or above, you’ll be able to claim.) If not, you'll have to buy more HZN or burn zUSD to restore your C-Ratio. The Target C-Ratio (800%) is subject to change based on community governance decisions.
- Rewards are calculated and made available once per week on Fridays.
- Use the [Horizon Genesis Website](https://genesis.horizonprotocol.com/) to navigate to the Claim section.
- Press Claim Now to collect both your zUSD and HZN weekly rewards.
- Claimed HZN rewards are escrowed for 1 year. You won't be able to transfer or sell them. You’ll be able to re-stake them or use them to manage your C-Ratio, however.

## Genesis Interface

### Wallet Status

The Wallet status can be seen on the Mint, Burn, and Claim pages.

![img](/images/hzn-docs-wallet.png)

- **Current C-Ratio**: If the user has staked, their current c-ratio is based on
  the following formula: **HZN Balance \* HZN Price / Debt**
- **HZN Staking APY**: Current APY for staking.
- **HZN Price**: The current price of HZN on the market.
- **HZN Balance**: The total amount of HZN in wallet (Staked + Transferrable + Escrowed).
- **zUSD Balance**: The amount of zUSD held in wallet.
- **Debt**: The amount of debt held (currently equivalent to the amount of zUSD minted).
- **Staked**: The amount of HZN that is staked to maintain the user's current debt. Staked HZN, while still shows up in your wallet balance, cannot be transferred or utilized. The amount of staked HZN is dynamic and will fluctuate based on the current price of HZN and the amount of debt the user possesses. If you have some transferrable or escrowed HZN in your wallet (see below), Genesis will automatically migrate some of this HZN to become staked in the event of a price drop in order to always maintain an 800% staked-to-debt ratio. Genesis only ever requires 800% collateralization for the debt that you have, so any HZN that isn't needed (i.e. if the price moves up) to be staked will be released back to the user as transferrable or escrowed HZN automatically.
- **Transferrable**: The amount of HZN that is not currently staked to back your debt, but is available to be staked. Transferrable HZN is also available to be transferred to other wallets or sold on the market. Having some transferrable HZN means you are above 800% C-Ratio and can act as a buffer for Genesis to stake with if the HZN price drops.
- **Escrowed**: The amount of HZN locked in escrow. HZN rewards claimed each week are locked in escrow for 1 year from the moment they are claimed. Escrowed HZN cannot be transferred or sold on the market, but can still be utilized to manage your C-Ratio and be compounded by staking and minting more zUSD. Escrowed HZN will be the first to unstake (and returned to your escrowed balance) when your C-Ratio goes above 800%, followed by transferrable HZN as second unstaking priority
- **Next Reward Claim**: The time until the next reward (and if you haven't claimed yet this week, the time until your claim this week expires).

### Mint

Mint zUSD by staking your HZN. This gives you a Collateralization Ratio (C-Ratio) and a debt, allowing you to earn weekly staking rewards.

![img](/images/hzn-docs-mint.png)

- **Preset Strategies**: One click to select how much to mint; either 1200%, 1000%, or 800% C-Ratio.
- **STAKE HZN**: Select the amount of HZN to be staked (will display and update relative to MINT zUSD).
- **MINT zUSD**: Select the amount of zUSD to be minted (will display and update relative to STAKE HZN).
- **C-Ratio** The current C-Ratio (and the C-Ratio after minting).
- **Debt** The amount of debt the user currently has (and the amount of debt the user has after minting).
- **Staked** The amount of HZN that is currently staked (and the amount of HZN staked after minting).
- **Transferrable** The amount of HZN that is currently not staked (and the amount of HZN not staked after minting).
- **MINT NOW** Click to Mint according to the STAKE HZN <-> MINT zUSD details.

### Burn

Burn zUSD to unlock your staked HZN. This increases your Collateralization Ratio and reduces your debt, allowing you to transfer your non-escrowed HZN.

The user does not lose any HZN when burning. Burning zUSD while under 800% C-Ratio will just reduce the amount of debt the user has without unstaking any HZN, but burning zUSD if the user is above 800% will unstake HZN at a 8:1 (800%) proportional rate (in USD terms) to how much zUSD the user burns.

There is a 24 hour 'Burn Lock' after a user mints zUSD, where the user cannot burn any zUSD. This is to prevent oracle front-running attacks on the network.

![img](/images/hzn-docs-burn.png)

- **Preset Strategies**: One click to select how much to burn; either 1200%, 1000%, or 800% C-Ratio.
- **BURN zUSD**: Select the amount of zUSD to be burned (will display and update relative to UNSTAKE HZN).
- **UNSTAKE HZN**: Select the amount of HZN to unstake (will display and update relative to BURN zUSD). HZN is only unstaked when going above 800% C-Ratio.
- **C-Ratio**: The current C-Ratio (and the C-Ratio after burning).
- **Debt** The amount of debt the user currently has (and the amount of debt the user has after burning).
- **Staked** The amount of HZN that is currently staked (and the amount of HZN staked after burning).
- **Transferrable** The amount of HZN that is currently not staked (and the amount of HZN not staked after burning).
- **BURN NOW** Click to Burn according to the BURN zUSD <-> UNSTAKE HZN details.

### Claim

Claim rewards from staking HZN and minting zUSD. Claimed rewards are vested for 12 months from the claim date, but can be used to manage the current C-Ratio or staked again to compound rewards during that time.

![img](/images/hzn-docs-claim.png)

- **Staking Rewards**: Rewards available to be claimed via staking.
- **Exchange Rewards**: Rewards available to be claimed via the Exchange (not available yet).
- **Next Reward Claim Period**: Time until next reward is available.
- **Claim Period Ends**: Time until this reward expires and cannot be claimed anymore.
- **Total Rewards**: Total rewards available to be claimed (Staking + Exchange Rewards).

### Earn

Multiple pools where you can stake something other than HZN to earn additional HZN.

![img](/images/hzn-docs-earn.png)

- **STAKE PHB**: Stake PHB to earn HZN. This pool will end on April 15th, 2022.
- **STAKE HZN-BNB LP**: Stake HZN-BNB LP (provide liquidity on PancakeSwap) to earn HZN.
- **STAKE ZUSD-BUSD LP**: Stake ZUSD-BUSD LP (provide liquidity on PancakeSwap) to earn HZN.

## Risks of Staking

Staking on Horizon Protocol is not risk free. Below are considerations and strategies to reduce the amount of risk you face.

### HZN Price Fluctuations and your C-Ratio

C-Ratio needs to be maintained to collect rewards. Your HZN is in constant limbo between being 'Staked' or 'Transferrable'.

There are two ways in which C-Ratio can change:

- If the market price of HZN increases, the HZN you need to collateralize your position will reduce and your Current C-Ratio will increase. Genesis will automatically release the amount of staked HZN you have to become transferrable HZN in order to always maintain a 800% ratio based on your current debt. You have the option to re-stake the extra available HZN.
- If the market price of HZN decreases, your C-Ratio will decrease. If your Current C-Ratio is above 800%, Genesis will automatically migrate your transferrable HZN to become staked HZN (until you hit 800% where your transferrable HZN will be fully staked) in order to maintain the 800% collateralization ratio.

There are two ways to maintain your C-ratio:

- Burn some zUSD. This pays back some or all of your debt and will increase your C-Ratio.
- Stake more HZN. This provides more collateral and will increase your C-Ratio. If your Current C-Ratio is under 800%, just adding HZN to your wallet will automatically stake your HZN (up to 800%).

### Missed Claims

Claims are available until the next reward claim period starts (7 days). Make sure to collect your claims before they expire. Rewards that are not claimed during the week are no longer available to the user and are distributed to the following week's reward pool for everybody to earn.

### Liquidation

If your C-Ratio falls below 200% you will be flagged for liquidation. Once you are flagged for liquidation, you have 3 days to restore your C-Ratio back to 800% and remove the liquidation flag, otherwise, you can be liquidated. Once you are back to a C-Ratio of 800%, you can implement the transaction to clear you liquidation flag. Please note that if you restore your C-ratio back to 800%, but fail to remove the liquidation flag, your account will still be vulnerable to liquidation if you ever go under 800%. If your account does get liquidated, this flag is automatically removed without the user needing to clear it. To learn more about how liquidation works under the hood, please look to the [advanced concepts](https://docs.horizonprotocol.com/#Why-is-liquidation-necessary-and-how-does-it-work?)

Please check the strategy section for more details on how to approach staking HZN and the best approach that fits you.

## Advanced Concepts

### Managing Debt

Your C-Ratio fluctuates based on 2 things:

- The price changes of HZN
- The price change of any of the synthetic assets that users trade on Horizon Exchange.

The total value of all synthetic assets owned by users is what constitutes the global debt pool and is denominated in zUSD. The global debt will increase if traders are profitable (i.e. synthetic asset values increase) and decrease if they are unprofitable (i.e. synthetic asset values decrease).

As of Horizon Genesis, the only synthetic asset is zUSD, therefore, the only variable everyone faces in the system is the movement of HZN prices. E.g. I mint $100 of zUSD with $800 of HZN at a 800% collateralization ratio. HZN price drops 50% - my C-Ratio is now 400%. I have to burn $50 of zUSD in order to repay my debt to the system (Or stake an extra $400 HZN) and I can withdraw my initial HZN stake, which is now down 50% due to price change. There is no extra loss I face at this point in time.

In the future when a range of other synthetic assets are introduced to the system, you will need to understand that your debt obligation to the system is proportionally based, meaning the system tracks the percentage of your debt relative to the global debt. Because of this, when the prices of the assets in the global debt portfolio change, so does your debt obligation. If you are 1% of the global debt with $1000 in debt, and the average price of all assets in the global portfolio increases by 10% (which also means the global debt is increased by 10%), then your debt obligation will also increase and become $1100. If the synthetic assets you hold do not also increase by 10%, then you will incur a loss (assuming the global debt doesn't shrink back later).

Lets take an example:

![img](/images/hzn-docs-debt.png)

Scenario:

1. John and Adam both mint $100k zUSD. The total network debt is $200k, with John and Adam responsible for 50%.
2. John buys zBNB with his $100k and Adam holds zUSD.
3. In this example, BNB increases by 50% increasing John's holdings to $150k. This price fluctuation increases the total debt to $250k.
4. John and Adam are still responsible for 50% of the total debt each. This means John and Adam both owe $125k. When John's zBNB is taken into consideration, he has profited $25k. Even though Adam still has the same zUSD position size of $100k - the debt he owes increased by 25% resulting in a $25k loss.

To mitigate this risk, you can either try to mirror the global portfolio, or you can hedge your position by holding some inverse assets (synthetic assets that directly short the market) to offset the volatility in both directions (long and short).

It is fundamental to understand that when other zAssets join zUSD in the synthetic asset lineup that if you were to merely stake HZN as collateral and just hold your minted zUSD, you are effectively shorting the global portfolio if that portfolio consisted of appreciating synthetic assets.

### How are Genesis rewards calculated?

There are two components to rewards: HZN and zUSD.

- HZN rewards are determined by the [Horizon Protocol inflation policy](https://horizonprotocol.medium.com/horizon-supply-and-inflation-policy-f0aaa8cc4a3a). This started with the launch of Horizon Genesis and supplies all the rewards for Genesis as well as the LP staking pool rewards in **Earn**. As of August 2021, 87% of the rewards are going to HZN stakers who mint zUSD in Horizon Genesis. As a HZN staker, your percentage of the global debt will determine your percentage of rewards each week. If you hold 1% of the global debt, you will receive 1% of all the rewards.

- zUSD transaction fee rewards are also accrued by HZN stakers when the Horizon Exchange goes live. Each transaction on the Horizon Exchange will incur a fee (0.15-0.3%) and the sum of all the fees are distributed to HZN stakers each week proportionally to each individual stakers percentage of the global debt (same as HZN rewards).

### Why is liquidation necessary and how does it work?

Liquidation is a critical function to the health of the collateralization of synthetic assets on Horizon Protocol. Liquidation ensures that there will still be sufficient collateral to back synthetic assets in the event of a serious price drop (-90%) in HZN. It creates an incentive for stakers to maintain a healthy C-Ratio as well an incentive for liquidators to liquidate these accounts for a profit. This 2-sided approach ensures that the global network C-Ratio is maintained at a healthy level.

Once a user is flagged for liquidation and they don't restore their C-ratio and clear the flag, they will appear on a list of accounts available to be liquidated (viewable on the [network stats page](https://stats.horizonprotocol.com) soon along with the amount of zUSD needed to cover their position back to an 800% C-Ratio). From here, a liquidator with sufficient zUSD can liquidate these accounts and claim back HZN with a 10% bonus. Let's take an example:

Consider the following conditions:

- Target C-Ratio: 800%
- Liquidation C-ratio: 200%
- Liquidation penalty: 10%
- Liquidation delay: 3 days
- HZN value: $1

1. John has 100 HZN staked and a C-Ratio of 200%, which means he has 50 zUSD of debt.
2. John fails to restore his C-Ratio back to 800% and after 3 days his account becomes available to be liquidated.
3. To calculate how much zUSD will restore John's C-Ratio, this formula can be used: Z = (t _ D - V) / (t - (1 + P) - Z = zUSD debt required to restore John's C-Ratio - t = target C-Ratio (i.e. 8) - D = debt balance (i.e. 50) - V = value of staked HZN (i.e. 100) - P = liquidation penalty (i.e. 0.1)
   (8 _ 50 - 100) / (8 - (1 + 0.1)) = 43.478260869565217 zUSD.
4. Adam can now burn 43.478260869565217 zUSD to restore John's C-Ratio to 800%. The amount of HZN he receives is based on this formula:
   R = (Z _ (1 + P) - R = HZN liquidation reward - Z = zUSD debt required to restore John's C-Ratio (i.e. 43.478260869565217) - P = liquidation penalty (i.e. 0.1)
   (43.478260869565217 _ (1 + 0.1)) = 47.826086956521739 HZN
5. This results in 47.826086956521739 of John's HZN going to Adam, leaving John with 52.173913043478261 HZN staked. John's debt is also reduced by 43.478260869565217 zUSD, leaving him with 6.521739130434783 zUSD in debt and a C-Ratio of 800%.

### Strategies

With the target C-Ratio and fluctuating prices, there are a variety of approaches to staking HZN based on your risk tolerance. These 3 preset strategies are designed to make it easy to maintain a certain C-Ratio by easily minting or burning zUSD.

#### Conservative Strategy (Lower Risk)

A conservative strategy aims to stake HZN and mint zUSD at rate 50% higher the target C-Ratio (1200%) in order to remain comfortably within the range of being able to claim rewards. This higher C-Ratio (and lower risk) comes at a cost of less zUSD being minted and therefore less rewards. This strategy is better for users who can't check in to manage their positions as frequently and give themselves are larger buffer against the volatility of HZN. An even more conservative ratio of greater than 1200% can be maintained as well if the user wants to further de-risk their debt position.

#### Neutral Strategy (Moderate Risk)

A neutral strategy aims to be a middle ground between the conservative and aggressive strategy at 1000% C-Ratio. This strategy increases your risk slightly relative to the conservative strategy but also earns more rewards.

#### Aggressive Strategy (High Risk)

An aggressive staker stays as close to the target C-Ratio (800%) as possible and mints as much zUSD as possible to maximize rewards. This is high risk due to the fact that if the price of HZN decreases at all from the point where they minted zUSD, the staker cannot claim any rewards. This strategy requires very active management to maintain their C-Ratio in order to collect rewards and prevent liquidation as the buffer zone to liquidation is much lower than the conservative and neutral strategies.
