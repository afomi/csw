---
url: https://medium.com/@johnblocke/there-will-be-no-bitcoin-split-564f1d60a657
canonical_url: https://medium.com/@johnblocke/there-will-be-no-bitcoin-split-564f1d60a657
title: There Will Be No Bitcoin Split
subtitle: Part one of a two part article. The second part can be found here.
slug: there-will-be-no-bitcoin-split
description: ""
tags:
- bitcoin
- blockchain
author: John Blocke
username: johnblocke
---

# There Will Be No Bitcoin Split

*Part one of a two part article. The second part [can be found here](https://medium.com/@johnblocke/there-will-be-no-bitcoin-split-part-2-7dc406cf4469).*

“We must not hard fork,” the argument goes, “or we will end up with a situation where there are two Bitcoins.” A two-coins scenario would cause pandemonium and financial losses for bitcoin users across the board, as consumers would have no idea if they were transacting in valuable “Bitcoin A” or worthless “Bitcoin B.” Perhaps even worse, there would be a market for both coins (*the horror!*) and bitcoin users would lose money by causing their highly volatile magic internet money tokens to be worth slightly less. As irrefutable evidence of this scenario being the obvious and inevitable result of a bitcoin hard fork, one need only [look at what happened](http://qz.com/730004/everything-you-need-to-know-about-the-ethereum-hard-fork/) with the “disastrous” Ethereum hard fork of July 2016.

![Ethereum’s disastrous hard fork really did a number on their community. Thousands of fans congregated in Shanghai this September to mourn the death of Ethereum.](./assets/0*my1iyNUwQoEOKFgE.png)

But Bitcoin is not Ethereum, and citing the results of the Ethereum hard fork as proof incontrovertible of what will happen to bitcoin is either ill-informed or intellectually dishonest. There is one very simple reason that “two Ethereums” were able to co-exist, and why “two Bitcoins” will not.

***Ethereum’s difficulty adjustment period is 1 block (14 seconds).***

***Bitcoin’s difficulty adjustment period is 2,016 blocks (~2 weeks).***

*Obligatory explanation; apologies to my already well-versed readers*: Cryptocurrency mining is like solving a really hard math problem of arbitrary difficulty. In Bitcoin, the difficulty is automatically adjusted once every two weeks on average (though not exactly two weeks; once every 2,016 blocks to be precise — this is key) so as to target an average problem-solving-time of ten minutes. If the mining power protecting the network is increasing, which has been the general trend over the past eight years, then the difficulty increases in kind to make the problem harder to solve. If hashrate goes down, the problem becomes easier. It is this mechanism that keeps the production of new bitcoins at a fixed and predictable rate.

Ethereum is different. Ethereum’s [average block time](https://etherscan.io/charts/blocktime) is about fourteen seconds long, and [trending towards twelve seconds](https://blog.ethereum.org/2014/07/11/toward-a-12-second-block-time/). As a cryptocurrency that can be changed by its central planners (also key), this mechanism may be manipulated along with the currency itself. For Ethereum’s aspirations of being more of a scripting language than a currency, this is a more acceptable proposition than it would be in the leaderless and decentralized Bitcoin network.

This form of central planning was perhaps the second most important factor in Ethereum’s persistent minority chain. In the wake of [a $100+ million heist](http://blog.erratasec.com/2016/06/etheriumdao-hack-similfied.html), it was decided that victims of the theft would be made whole again by rolling back the history of the Ethereum blockchain to both return ETH tokens to the victims of the theft, and to prevent the hacker from keeping his ill-gotten gains. For many who believe that a cryptocurrency must be immutable, this undermined one of the most fundamental properties that money must hold. When early bitcoin exchange Mt. Gox lost more than 800,000 bitcoins belonging to its users (worth nearly half a billion dollars at the time), the idea of rolling back the blockchain was floated briefly but quickly dismissed as something that would destroy the integrity of Bitcoin-as-money.

Those who took a hardline position on immutability decided that they would continue using the original Ethereum blockchain, the one in which marks lost their tokens and the hacker kept his spoils. Thus there was user demand for ETC (Ethereum Classic), but demand alone was not enough. The ETC chain also needed the security that miners provide.

Shortly after the Ethereum hard fork, cryptocurrency exchange Poloniex [created an exchange market for ETC tokens](http://themerkle.com/ethereum-classic-is-now-trading-on-poloniex/), giving them a trading value. Because Ethereum maintains a consistent block time regardless of how much hashrate is securing the network, this meant that enterprising miners could begin mining ETC tokens as easily as they had before and sell them for profit. With the holy trifecta of miners (supply), users (demand), and a marketplace to facilitate the matching of supply with demand, ETC was able to live on as a niche off-shoot of Ethereum.

This situation will not happen when Bitcoin undergoes its first intentional hard fork. There may be a short lived effort to keep the old chain alive, but the economic equation is entirely different for Bitcoin than for Ethereum, and such a situation will not persist for very long at all.

Following the lead of Bitcoin Classic with its 75% hard-fork activation threshold, it seems most likely that the Bitcoin Unlimited fork will initiate with a similar majority of hashrate backing it, at least [according to ViaBTC founder Haipo Yang](https://medium.com/@ViaBTC/why-we-must-increase-the-block-size-and-why-i-support-bitcoin-unlimited-90b114b3ef4a):

> First, under what circumstances should a hard fork be initiated? I recommend following Bitcoin Classic’s 75% threshold. In other words, a hardfork will be initiated only after more than 75% of the network hashrate is supporting Bitcoin Unlimited. If the consensus threshold is set too high then reaching consensus will be unattainable, as a single determined mining pool could veto a change for the entire network. A 75% threshold is perfectly adequate to perform a hard fork safely.

Unlike Bitcoin Classic, Bitcoin Unlimited does not have an activation threshold at which point a hard fork is automatically initiated. Rather, once a large enough majority of miners are signalling that they will accept blocks greater than 1MB in size, any miner may initiate a hard fork by beginning to produce bigger blocks. Two notes on this:

1. This creates a fork because the remaining miners and nodes whose software does not accept >1MB blocks as valid will ignore these new blocks and continue mining on the old chain with 1MB blocks.

1. Yang also [outlined a strategy](https://medium.com/@ViaBTC/miner-guide-how-to-safely-hard-fork-to-bitcoin-unlimited-8ac1570dc1a8) for preventing a premature hard fork: continue to produce and accept only ≤1MB blocks until a sufficient majority of miners are already running the Bitcoin Unlimited software.

Yang’s strategy also suggests that even once sufficient hashrate is obtained, miners do not accept blocks larger than 1MB for two difficulty adjustment periods (approximately one month). This gives users, businesses, and (hopefully) Bitcoin Core ample time to upgrade their software to be in compliance with the impending hard fork, so as not to isolate themselves from the rest of the network.

We now return to the difficulty adjustment period and why a persistent minority chain is an impossibility in a Bitcoin hard fork.

Assuming that Yang’s figures are the ones that will be used to fork with, and assuming that rational miners do not switch to the more profitable chain:

1. Both chains will use the most recent difficulty figure, which attempts to produce one block every ten minutes.

1. The BU chain will have 75% of the hashrate, meaning blocks will be found every 13.3 minutes on average (10/0.75), at least until the next difficulty adjustment in 2,016 blocks.

1. The Core chain will have 25% of the hashrate, meaning blocks will be found once every 40 minutes on average (10/0.25), also in 2,016 blocks.

With these numbers we can draw some interesting conclusions. Because a miner’s operating costs will remain fixed (electricity is not priced in bitcoin), miners on the BU chain will be expending 33.3% more resource to compete for newly produced bitcoins, while miners on the Core chain will be expending 300% more resource to compete.

The field of miners competing for new bitcoin will be smaller in both instances. With ten minute blocks, there will be on average 144 blocks per day, each with a reward of 12.5 BTC, for a total daily production of 1,800 BTC. With 13.3 minute block times, the BU chain will be finding an average of 108 blocks per day, or 1,350 BTC. With 40 minute block times, the Core chain will find an average of 36 blocks per day, or 450 BTC.

Using the current price of $700 per coin, this works out to a daily economic reward of:

1,350 BTC = $945,000

450 BTC = $315,000

The current network hashrate is estimated to be 1.91 exahashes per second. (1,910 Ph/s, 1,910,000 Th/s). For a benchmark I will use the Antminer S7, arguably the most widely used bitcoin mining machine in the world. The S7 has a power draw of 273 watts per terahash, but when accounting for the PSU powering the machine, one gets about 93% efficiency, or 294 watts per terahash, or 294 kW per petahash.

1,910 * 294 = 561,540 kW total power draw.

I will estimate $0.035 USD per kWh as the average power cost. Most miners in China or Washington State have very low power costs, around this rate. This works out to $19,654 per hour to power the machines that power the bitcoin network.

$19,654 * 24 = $471,694 = electricity cost per day.

This is the electricity cost alone, and does not include paying back the massive CAPEX costs of constructing a bitcoin mining farm.

Using the 75/25 figures, the BU chain will cost $353,770 per day to maintain, while the Core chain will cost $117,924 per day to maintain. Only if each coin continues to be priced exactly the same will it make economic sense for the rational miner to remain on the Core chain. But expecting the price of both coins to maintain parity with one another is pure foolishness.

At the current rate of ~3 transactions per second, the bitcoin network is capable of processing 259,200 transactions per day on an already congested network. If block times on the Core chain are now once every 40 minutes instead of once per ten, we derive a new daily throughput of 64,800 transactions. Because the bitcoin network is already at max load, reducing the capacity by 75% acutely exacerbates the congestion problem. Not only will a single confirmation now take 40 minutes instead of ten, but one block will now be expected to handle 40 minutes worth of network activity, or ~7200 transactions. A 1MB block can process ~2000 transactions, so the network will have a permanent backlog that increases by ~5200 transactions for every ~2000 transactions that are allowed through. Inclusion into the next block and receiving a “timely” forty minute confirmation will require outbidding at least 5,200 other transactions. Of course, all of this assumes that demand for this chain will remain the same as it is now.

Meanwhile, assuming that the Bitcoin Unlimited chain initially settles on a 2MB maximum block size, the BU chain will be able to process 518,400 transactions per day. Block space will not be at a premium, and if it is, the emergent consensus mechanism used by Bitcoin Unlimited means that block size can grow in line with user demand, confirming all pending transactions every ten minutes and removing the requirement for users to outbid one another to make a payment.

Let us compare our two chains:

**Core chain:** 25% security of the original unified chain. 0.75 transactions per second. 64,800 transactions per day. 40 minutes per confirmation. 450 BTC produced per day. Permanent backlog that grows by 187,200 transactions per day. Must out-bid others to use.

**BU chain:** 75% security of the original unified chain. ≥6 transactions per second. 518,400 transactions per day. 13.3 minutes per confirmation. 1,350 BTC produced per day. Generally no backlog; any backlog created in peak times will be processed quickly. If backlog becomes a regular occurrence, limit can be increased. Fees priced fairly, using the network does not require pushing someone else off the network.

It’s easy to see which of these two chains will be valued more highly by the market. But that’s not all: recall from the beginning of this essay the “one simple reason” why Bitcoin will not split.

Bitcoin’s difficulty adjustment period is not two weeks, but 2,016 blocks. With 13.3 minute blocks, this means that the situation on the BU chain will return to the normal ten minute block times in 18.62 days. Meanwhile, the Core chain will be required to run in its crippled state for 56 days before having its first difficulty adjustment.

This all assumes, of course, that miners are “dumb” and will not move to mine on the chain that is most profitable — and we all know what they say about assuming.

Businesses dependent on making bitcoin transactions will not be able to afford to transact on the 0.75 transaction-per-second, expensive fee market chain, and will naturally be inclined to use the cheaper, faster, and more secure chain that does everything bitcoin always did.

It’s difficult to imagine any scenario in which the coins on the Core chain manage to hold their value against the coins of the BU chain. As the price of Core chain coins continue to fall, miners will be further incentivized to switch to the more profitable of the two chains, further lengthening the Core chain’s confirmation times, reducing transaction throughput, increasing backlogs, and extending the length of the difficulty adjustment period.

As all these variables continue to shift in favor of the BU chain, the total cost of maintaining both chains will continue to be at least $471,694 per day. It will cost the same amount of money to maintain one’s hashrate regardless of which chain they mine on, but one chain will recover quickly and stronger than before while the capabilities of the other continue to slowly degrade. Like the Highlander, there can be only one.

[*Continue reading part two.*](https://medium.com/@johnblocke/there-will-be-no-bitcoin-split-part-2-7dc406cf4469)


