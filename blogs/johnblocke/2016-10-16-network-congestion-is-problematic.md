---
url: https://keepingstock.net/network-congestion-is-problematic-c9d7829ed4ec
canonical_url: https://keepingstock.net/network-congestion-is-problematic-c9d7829ed4ec
title: The Network Congestion Problem
subtitle: In recent months I’ve noticed the emergence of a new talking point in the
  debate on scaling bitcoin. That is, that blocks are congested is…
slug: network-congestion-is-problematic
description: ""
tags:
- bitcoin
- blockchain
author: John Blocke
username: johnblocke
---

# **The Network Congestion Problem**

In recent months I’ve noticed the emergence of a new talking point in the debate on scaling bitcoin. That is, *that blocks are congested is not problematic.* The line of thinking goes: by paying a higher fee, it’s not impossible to get one’s transaction included in the next block, ergo *full blocks are not a problem.*

For the greater majority of bitcoin’s history, this state of affairs was never the case. Only in edge cases would one’s transaction not be confirmed in the next block, and in those instances of “spam attacks,” paying a higher fee than the attacker was trivial and cheap.¹

Today, bitcoin has seen the emergence of a “fee market” in which a user wishing to transact on the blockchain must now bid for inclusion, effectively turning block space into a scarce commodity. This has the twofold effect of creating a constantly rising fee pressure² while simultaneously increasing average transaction confirmation times.

Bitcoin’s ten minute confirmation times are not merely there for the user’s convenience; they are in fact an important security feature to protect the integrity of all transactions. Until a transaction receives a confirmation, it is considered to be “pending” and may be reversed by way of a double-spend or other attack vector. Only once a transaction has received a confirmation may it be considered to be finalized.³

Some bitcoin applications, especially online invoicing, bitcoin ATMs, and online exchanges depend on speedy confirmation times. Especially in instances where a BTC amount is quoted based on a fiat currency denomination, it is important that a transaction be received and confirmed within a certain payment window. ATMs are an interesting example: because they dispense cash in exchange for bitcoins an attacker has more incentive to attempt a double-spend attack than when buying a $4 cup of coffee.

Many prominent figures in the bitcoin community believe that this current state of affairs is an acceptable one. Whereas Satoshi Nakamoto described bitcoin as a “peer-to-peer electronic cash system,” the currently accepted view among developers in Bitcoin Core is that the electronic cash model is incorrect, and that bitcoin will work better as an expensive “settlement layer” for high-value transactions, with low-value consumer payments being driven to “second-layer” network overlays which have varying degrees of centralization.

The author wholeheartedly disagrees. By undermining one of the central features of bitcoin, i.e., transactions becoming irreversible within a very short window, the security of the entire network is undermined with it. The de-facto motto of Bitcoin for most of its history has been *be your own bank*, but forcing users off of the blockchain and onto layer-2 networks (which do not yet exist) undermines this as well, as does forcing users to pay ever-rising fees in order to participate.⁴

In the meantime, the backlog of transactions held in [mempools](https://www.kaiko.com/analytics/post/an-in-depth-guide-into-how-the-mempool-works) grows [larger and larger](https://www.kaiko.com/blockchain). Ideally, and as Bitcoin was designed, the mempool is a holding tank for all pending transactions. As soon as a block is found, the transactions in the mempool will be confirmed and the mempool flushed back to empty. But what happens when the influx of new transactions is consistently greater than the rate at which they are able to flushed? We end up with a mempool that is constantly growing and never empty. In other words, a permanent backlog of transactions.

The mempool frequently reaches several megabytes in size, sometimes ten megabytes or more. Looking at a [chart of the previous month’s mempool data](http://charts.bitcointicker.co/#mempoolsize) we can observe that the time it takes the mempool to flush is increasing, along with the peak size of the mempool. Generally there will be blocks with enough excess space to also process backlogged transactions, but this creates a compounding problem whereby even blocks produced during non-peak usage periods become congested, and new transactions made during *those* periods are then forced to participate in the “pay-or-wait” game.

The mempool is named such because it stores pending transactions in the full node device’s memory (RAM). Once confirmed, transactions may safely be moved to storage, a cheaper and less scarce resource. Funny enough, one of the primary arguments made against increasing the block size is that node operation will become too resource intensive and that node operators will be disincentivized from participating. But RAM is the most precious of the resources required to run a node; storage and bandwidth are more abundant and less expensive.

The result is an ever-growing transaction backlog, ever-rising fees, and a stagnant bitcoin economy. Without also increasing the rate at which this backlog is periodically flushed, what we are left with is a *permanent backlog*. Bitcoin will be accessible only to the highest bidders, and as the great mass of consumer users turn elsewhere to find a cryptocurrency that is both fast and cheap, I suspect the transaction congestion problem will solve itself.

¹ What constitutes a “spam” transaction is a matter of philosophical debate. The author believes that any transaction paying a fee is a valid one.

² This assumes that the demand for block space inclusion keeps growing. Stagnating user acquisition may lead to a leveling-off of fees.

³ With some degree of mathematical certainty. One confirmation is generally adequate to ensure that a transaction is legitimate, although extremely high value transactions would be well advised to wait for multiple confirmations before considering the payment finalized. See *Nakamoto, Satoshi. “Bitcoin: A Peer-to-Peer Electronic Cash System.” 31 Oct. 2008. pp. 6–8*

⁴ The author notes that users of layer-2 networks will need to settle their transactions on the main blockchain regardless; forcing them to opt-in to the same expensive fees that “high value transactions” require even if they primarily use bitcoin for low-value money transfer.


