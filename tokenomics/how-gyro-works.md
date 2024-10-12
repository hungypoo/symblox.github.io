---
description: Tokenomics
---

# How Gyro Works

**How Gyro works:**

Each GYRO token is backed by 1 USD (i.e. USDT, DAI, BUSD, USDC) in the treasury.

We will initially start with USDT as our treasury asset. After launch, we will be adding other stablecoins to balance our treasury. This will include DAI, BUSD, USDC etc.

Tokens cannot be minted or burned by anyone except the protocol.

The protocol only mints or burns in response to price.

GYRO does not rebase. Instead, a new supply is created via direct sales into the market and burned via direct purchases from the market. This way, GYRO remains backed by real assets in the treasury, i.e., USD.

These basically translates to:

When GYRO trades below ↓ 1 USDT, the protocol buys it back and burns GYRO.

When GYRO trades above ↑ 1 USDT, the protocol mints and sells new GYRO.

This is because the treasury must hold 1 USDT and only 1 USDT for each GYRO every time it is bought or sold so it makes a profit. That means the protocol either gets more than 1 USDT for the sale side or spends less than 1 USDT on the purchase side.

The fact that the protocol holds USDT for each token allows us to say with certainty that GYRO will not trade below its intrinsic value in the long term.

Investments can then be made with defined risk because 1 USDT is the guaranteed long-term price floor. And because of this, the protocol can (and will) buy indefinitely below 1 USDT until no sellers remain, even if the supply is reduced to 0. In this example this event would reward those who did not sell immensely because they would end up with a chunk of every token that was burned!

Holding stablecoins to back tokens also creates a yield generation opportunity.

Locking away stablecoins in a vault would then be a waste. Given that the protocol never needs more than a few percent of reserves, even on the largest of down days, means you are free to utilize the rest to plug into yield aggregators and add those proceeds onto profits from buying and selling GYRO.

**Gyro’s initial profit distribution**

90% to stakers

10% to the DAO (these allocations will be changed, if necessary, as decided by the DAO).

All rewards are paid in GYRO**,** backed by stablecoins.

This system maintains a stable intrinsic value and reduces the incentive role of appreciation in favor of accumulation. As with real currency, you try to accumulate more dollars and you do not have to wish upon a star that your dollars become worth more. Although both can happen.

**Staking and Rebasing**

The protocol distributes tokens by sending them to the staking contract without asking for sGYRO back. This increases the ratio of GYRO staked to sGYRO outstanding, and results in a rebase to correct the difference.

For example: there are 500k GYRO staked and 500k sGYRO outstanding. The protocol produced $5k profit for the day, which it uses to mint and back 5k GYRO. It sends those GYRO to the staking contract; there are now 505k GYRO staked and 500k sGYRO outstanding. sGYRO supply needs to increase by 5k, or 1%, to return to balance. So, sGYRO is rebased up by 1%.

The only caveat is that rebases occur retroactively. The end of epoch 100 triggers a rebase of profits from epoch 99. This delay lets you see what you’re missing if you want to unstake or what you’ll get if you want to stake.

Staking is how we distribute profits equitably to participants. Through sGYRO, everyone receives the same percentage profit per epoch. Rebasing also allows us to compound yield with no need to harvest or do anything except hold.

**Bonding**

Bonding is the process of trading an LP share to the protocol for GYRO. The protocol quotes an amount of GYRO and a vesting period for the trade. It is important to know: **when you create your bond, you are giving up your LP share.** The protocol compensates you with more GYRO than you’d get on the market, but your exposure becomes entirely to GYRO and no longer to GYRO-USDT LP.

_Note that sGYRO is the protocol’s profit accruing token and since bonders earn GYRO (not sGYRO), stakers earn 100% of protocol profits (minus the DAO’s cut)._

**Why Do I Want to Bond?**

Because it allows you to buy GYRO at a lower cost basis. In return for selling your LP, the protocol will sell you GYRO at a discount.

**Dynamics of a Bond**

The protocol quotes bond prices based on the protocol’s risk-free value (RFV). The Bond Premium is a protocol-governed policy tool that controls the premium charged for bonds. A lower premium means a higher discount and a higher incentive to bond.

_Executing Price = RFV / Premium {Premium ≥ 1}_

The premium is determined by the total debt of the system and a scaling variable. This ties the price of bonds to the number of bonds outstanding; the fewer bonds outstanding, the lower the premium and the higher the discount.

Premium = 1 + (Debt Ratio \* BCV)\
Debt Ratio = Bonds Outstanding / GYRO Supply

The risk free value of the LP share for the protocol is the point at which the pool is balanced (1 GYRO = 1 USDT). Since the protocol must protect the backing of GYRO, this is the lowest price that it can accept; worst case, it can back every 2 GYRO bonded by 1 USDT and 1 GYRO. Above this equilibrium, there is an excess of USDT. Below this equilibrium, there is an excess of GYRO. Either can be used, and there will always be enough of both.

_Risk-Free Value = (LP / Total LP) \* 2sqrt(Constant Product)_

This means a bonder is (generally) selling their LP for below market value. However, this is canceled out by the protocol bonding GYRO at below market value.

**Linear Scale**

The exponential increase in the value of bonded GYRO relative to the value of the LP is expected to create increasing demand for bonds the higher price is. This is an extremely favorable dynamic; the higher price goes (and the more the protocol sells in response), the more liquidity there should be.

Bonders can make this trade, despite time risk, because their breakeven point has been reduced. The higher the price is, the greater that padding becomes.

**Conclusion**

Gyro’s aim is to offer a new class asset token that can be a part of any portfolio. It can be used to hedge risky assets while offering safer and better incentives than stablecoins.
