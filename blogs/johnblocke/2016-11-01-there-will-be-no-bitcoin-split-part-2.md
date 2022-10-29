---
url: https://medium.com/@johnblocke/there-will-be-no-bitcoin-split-part-2-7dc406cf4469
canonical_url: https://medium.com/@johnblocke/there-will-be-no-bitcoin-split-part-2-7dc406cf4469
title: There Will Be No Bitcoin Split, Part 2
subtitle: This is a follow-on to my original article, There Will Be No Bitcoin Split.
  If you are arriving from Reddit, you should be aware that Part…
slug: there-will-be-no-bitcoin-split-part-2
description: ""
tags:
- bitcoin
- blockchain
author: John Blocke
username: johnblocke
---

# **There Will Be No Bitcoin Split, Part 2**

*This is a follow-on to my original article, [There Will Be No Bitcoin Split](https://medium.com/@johnblocke/there-will-be-no-bitcoin-split-564f1d60a657). If you are arriving from Reddit, you should be aware that Part 1 of this article was [censored from /r/bitcoin](https://www.reddit.com/r/btc/comments/5ae864/rbitcoin_locks_comments_on_there_will_be_no/). We must question the motives of those who use censorship to achieve their ends.*

In this essay, I will address the various actions that may be taken by a minority chain in response to a Bitcoin hard fork, as well as examine why all such responses fall short and only support my initial statement that there will be no “two-Bitcoins” situation as a result of an intentional hard fork.

It may seem presumptuous of me to continually speak of a 75% hard fork as though it were a given; consider these articles thought exercises. If a successful hard fork is to happen, it is safe to assume that it will be with a large majority of hashrate. It should also be clarified that the word *attack* in this article refers to a strategic move to drive network convergence on a single chain, and does not imply malicious intent. The ethics of such strategies will be saved for a later essay.

There are three main courses of action that may be taken to attempt to preserve the old chain in the wake of a 75% majority hard fork:

1. Do nothing. This ensures the majority chain wins.

1. Manually adjust the difficulty of the minority chain to prevent the 56 day difficulty adjustment period suffocating the economy of this chain.

1. Change the difficulty *and* the proof-of-work algorithm of the minority chain.

[Part one](https://medium.com/@johnblocke/there-will-be-no-bitcoin-split-564f1d60a657) of this essay explored the consequences of the first strategy, doing nothing. This strategy is all but guaranteed to ensure the dominance of the new majority hashrate chain. It is true that the minority chain may live on, powered by the nodes and super-minority hashrate of its most ardent supporters, but as explained in the previous article this network will only survive in a crippled state while the rest of the bitcoin economy migrates to the most secure chain with the largest network.

**Strategy Two: Manually adjusting the difficulty**

This strategy is flawed for two reasons. First of all, it would require Bitcoin Core to release an emergency software update and would induce a hard fork of its own. As Bitcoin Core has taken a strong stance against hard forks over the past year, this would both cause a major loss of credibility and would also further subdivide the minority chain. Even “emergency” updates take time to roll out, and for the duration of time it takes Core chain supporters to become fully compliant with the new consensus rules, there would be *three blockchains:* **The Ancestor Chain**, which would have diminished security, sluggish block times, and the lowest transaction throughput of the three. **BU-Chain,** which would have the fastest block times, greatest security, and greatest transaction throughput of the three (remember, this thought experiment is exploring the outcome of a Bitcoin Unlimited 75% hard fork). Finally there would be **Core-Chain** (the difficulty-adjusted chain), which would have diminished security, but would have ten minute block times, and would retain present-day transaction throughput capacity (259,200 transactions per day).

Ignoring for a moment the added confusion of [a hard-fork of a hard-fork](http://www.newsbtc.com/2016/10/22/ethereum-classic-hard-fork-soon/), this strategy actually further reduces the chances of survival of the minority chain. If majority-chain miners were not content to merely wait out the slow and natural death of the minority-chain, one avenue that is open to them is to divert some of their hashrate towards attacking the minority chain, either 51%-attacking it or reducing its utility by mining empty blocks on top of it.

If there are only two chains, **Ancestor Chain** and **BU-Chain**, 51%-attacking the Ancestor Chain would require miners to divert a significant amount of hashrate towards disrupting the old chain. This would cost the BU Chain miners a large amount of resource, and would further reduce the transaction processing capabilities and block times of their favored chain.

If the total daily electricity cost of all hashrate is $471,694, and BU-Chain and Ancestor Chain have a stable 75/25 split, then maintaining BU-Chain would cost the rational miners $235,847 per day while the honest maintainers of Ancestor Chain would need to spend $117,924 per day to support their chain. Meanwhile the Ancestor Chain attackers would need to spend >$117,924 per day to perform the attack. While this attack is underway, they will be diverting hashrate that could instead be used to maintain BU-Chain, increasing the average block time of BU-Chain to ~20 minutes, producing 72 blocks and 900 new BTC per day. Although this method does not make financial sense for Chain A miners to perform, in the short term at least, it is interesting to note that with 2MB blocks and 20 minute confirmation times this network would actually have the same transaction processing capability of the Bitcoin network in its current state. If the difficulty of the Ancestor Chain is not adjusted, it makes more sense for BU-Chain miners to continue supporting their own network and wait for the old chain to die off on its own.

Should a new difficulty-adjusted bitcoin client be introduced, henceforth **Core-Chain**, then the economic equation shifts. Ignoring once again that the hashrate split will not maintain a clean 75/25 split for long and that rational miners will continually be migrating to the most profitable chain, the success of a manual difficulty adjustment hard fork relies on the assumption that 100% of Core-Chain supporters will upgrade simultaneously and will divert *all* resources from the Ancestor Chain to Core-Chain. This also presupposes that a majority of nodes will upgrade in a timely manner and that Core-Chain will maintain its current level of decentralization, another point which Bitcoin Core has taken a strong stance on.

Any rational BU-Chain miner could, and probably will be, paying attention to the release plans of Core-Chain. As soon as the Core-Chain network forks from the Ancestor Chain, a BU-Chain miner could devote minimal resources to attacking the Core-Chain and bring it to a halt before it has a chance to gain traction. The attack need only be maintained briefly to ensure that Core-Chain gains no economic traction, it does not need to be maintained in perpetuity. In this scenario, the Ancestor Chain will maintain the greatest legacy node count but will have a crippled network, Core-Chain will have the fastest block times but low node count and minimal adoption by businesses, and BU-Chain will have slightly slower block times, but the greatest transaction processing capacity and greatest economic adoption of the three chains.

Because Core-Chain is also a new fork of the legacy Ancestor Chain, its adoption by the community of users and businesses will not be assumed like an Ancestor Chain update would be, but will instead require all users and businesses to opt-in by manually updating their node software. In a situation where the legacy chain is abandoned and the two new competing chains are both the product of hard forks, it makes the most sense for the rational actor to adopt the chain with the greatest security, transaction throughput, and economic support.

Bitcoin Core could mitigate this scenario by first launching Core-Chain secretly with the support of a few loyalist businesses and miners. This would create a secret hard fork, and until such time that it were made public the “privileged miners” allowed to mine on this private blockchain would maintain absolute seigniorage rights over the new currency as well as >51% control of the network, harming (perhaps irreparably) the monetary integrity of the new coin. John Blocke would not be the least bit surprised if this scenario happens, as it would suit well the Bitcoin Core *modus operandi* of turning a blind eye to censorship and attempts at maintaining centralized control over the decentralized bitcoin network. Fortunately, most users and businesses are honest and will reject such a private chain, but be forewarned that the censorship regimes of /r/bitcoin and bitcointalk and the *de facto* information omission by Coindesk and Bitcoin Magazine will work together to frame this privileged and centralized blockchain as the rightful heir of the Bitcoin name while simultaneously framing the actions of the economic majority in a xenophobic, anti-Chinese light (although support for the majority chain will be international). You heard it here first.

It is important to note that this difficulty-adjusted chain will inherently suffer from an extremely high degree of centralization. Because a 75% fork to BU-Chain implies the majority of miners being in agreement (with non-ideological miners quickly joining this more profitable network), miner support for Core-Chain will likely come from [one](http://bitfury.com/), [two](https://archive.is/6YkoY), or [three](http://btcc.com/) pools.

**Strategy Three: Change the difficulty *and* the proof-of-work algorithm**

For those who disagree with the idea of Bitcoin as an amorphous and leaderless system and dogmatically adhere to the idea that Bitcoin is inseparable from the Bitcoin Core team of coders, John Blocke suggests utilizing Strategy Three. This strategy delivers the most fair outcome for the greatest number of individuals, and will have the added benefit of further decentralizing mining on the new Proof-of-Work chain by moving away from ASIC mining and returning to CPU or GPU mining.

With this strategy, many of the messier aspects of a fork are neatly resolved:

* The current bitcoin mining network will converge on the majority chain, preserving the unity of a single bitcoin network and not creating a currency split.

* Groups of individuals with differing ideas for the ideal cryptocurrency will be free to realize their visions without feeling coerced by the other, and the market will decide the fair value of each coin.

* The multi-year standoff that has divided the Bitcoin community will come to an end. One hopes that the in-fighting and the censorship would finally be put to rest.

Because being secured by a vast amount of computational power does not seem to be as important a feature of the Bitcoin network to one side of the argument as it is to the other, this solution should be something that both factions in this great debate can agree on.

The main outcome of this strategy, and the reason the author expects it to be an unpopular one, is that it almost certainly guarantees that the network with consensus of existing bitcoin miners will be the one to inherit the naming rights and the economy of “Bitcoin,” while the new-PoW network will be need to re-earn market share based on its merits. This should once again be agreeable to Bitcoin Core, as the Core stance tends to prioritize cryptographic perfection over user acquisition. Alas, being the unelected “leaders” of a system with millions of users is a difficult thing to let go of, and one should not expect Bitcoin Core to let go of the reigns so easily.

There is, of course, a fourth option that seems to have been forgotten about in the sea of vitriol: should Bitcoin Unlimited gain majority miner support and a hard fork appear imminent, the Bitcoin Core team could update their software to be in consensus with the rules accepted by the majority of the network, just as Bitcoin Unlimited already does right now with the majority accepted rules. For all the doomsaying and hand-waving about the dangers of a network split, it should follow that maintaining a unified network is of greater importance than preventing a block size increase at all costs.

It is the belief of the author, and many like him, that Bitcoin is a complex and fluid system not dominated by those who contribute code, but rather one where protocol developers are participants in the network just as miners, businesses, and consumers each contribute to the sum of the network in their own way. Bitcoin as a system is not fundamentally broken, and in fact contains an elegant system of checks and balances to ensure that what ultimately prevails will be in the interest of the greater good. Contributing code to the client used by the majority of the network does not bestow any sort of decision making power on behalf of the entire Bitcoin network and its users.

Rather than segregate themselves to a walled-garden cryptocurrency of their own, the developers of Bitcoin Core should accept the notion that Bitcoin does not belong to them, but belongs to all of us. Of course they are free to respond to a fork however they like, but the loss of their technical expertise would indeed be a shame if they choose to part ways with the majority. In an ideal world Bitcoin would have multiple teams of developers each contributing their own unique ideas, adopting the good ideas of other teams, collaborating and not battling, and allowing the free market to ultimately decide what it wants the network to become. *That* is decentralization, and we will all be better off for moving closer to that vision.


