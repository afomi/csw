---
url: https://medium.com/@adam_selene/the-segwit-15-attack-b0ecbb926777
canonical_url: https://medium.com/@adam_selene/the-segwit-15-attack-b0ecbb926777
title: The SegWit 15% Attack
subtitle: It is well known that Bitcoin solves the byzantine distribution problems
  through a probabilistic risk algorithm. In this scenario, it is…
slug: the-segwit-15-attack
description: ""
tags:
- bitcoin
- segwit
- economics
- governance
- exploit
author: Adam Selene
username: adam_selene
---

# The SegWit 15% Attack

![](./assets/1*9K87mzDlSD3zqi1le1wTIQ.jpeg)

It is well known that Bitcoin solves the byzantine distribution problems through a probabilistic risk algorithm. In this scenario, it is proven that Bitcoin is safe as long as 50% of the miners respect the rules of the system. The system is economically incentivised. Any company that has gained 51% of the hash rate quickly lost controlling share of the network. Time and again we see that the so-called experts in Bitcoin have failed to understand the primary controls that govern the system. It is not cryptography, it is economic incentives.

This is no different with the introduction of SegWit as a proposal. These experts again talk about how much they know about technical protocols and yet fail to understand again the economics that govern the system.

I recently read a post that was distributed throughout some of the forum postings where a few people discussed a possible attack against SegWit if it activates. In this article I’m not going to discuss this as an attack, I’m going to take a slightly different approach to the speculation that has been floating around, I’m going to discuss this from the point of law and economics. The technical promoters of change seem to overlook these areas so I will take it upon myself to explore some of the less savoury aspects of a SegWit hard fork. I say hard fork, for the reality is the SegWit soft fork as they try and call it is far less reversible than anything else in Bitcoin’s history. This makes it harder than a diamond in a comparison scale.

# Contract Law

A recent proposal by Barry Silbert has put forth an agreement consisting of two parts:

*Raising the block cap to 2 MB,*

*Implementing segregated witness.*

Each of these are done at an 80% acceptance rate in the existing protocol proposal, the first interesting point is that these are not linked. If miners signal to raise the block and failed to implement segregated witness, then by the agreement, the cap needs to be increased. There are some interesting legal aspects to all of this, the first is that this is a binding offer in many aspects of common law. Barry Silbert is a direct participant and investor within Blockstream and this company funds many of the core developers. If we take the decision of [1] Lord Reid in Tesco Supermarkets Limited v Nattrass, we see that the common law has derived such that liability can account for associated action. This is something that transpires when someone is “not acting as a servant, representative, agent or delegate” of the company, but as “an embodiment of the company”. Ties to control under company law standards and the common law mean that Mr Silbert’s agreement can be seen to be binding in a contractual sense. The offer has been made.

The unilateral nature of the offer removes this distance from an offer to treat, acceptance is provided electronically. In these scenarios the facts of the case always come into consideration but if we look at the electronic commerce directive, and couple this with every student of common law’s favourite case, [2] Carlill v Carbolic Smoke Ball Company, it becomes clear that this would be seen as an offer with acceptance coming from the transmission of electronic signal embedded in the creation of a Bitcoin coin base on a block creation.

The next part of any contract is consideration which is perhaps the simplest aspect. Whether we see bitcoin as money as I would or as some people argue, a commodity, it has value. As we approach USD$2,500 each bitcoin, we can easily see that the creation of a block that is used to signal the acceptance or rejection of a proposal incorporates consideration. In the miner’s case however, this can be a conditional acceptance without any implied terms, I believe that will be important later in this discussion.

![](./assets/1*iMc0IYUztRURjiCIkvNa4w.jpeg)

The implication states that SegWit would activate, the implied terms come from the system. It is defined within the system [3] that a majority can set the protocol rules. This is never made to be simple, but that does not change the fact of the matter: a majority can change the protocol and the majority can undo any change.

This fact is extremely important when it comes to something such as SegWit. With a normal protocol change in the form of a simple block size increase, the threat does not come from the theft of coins, miners do not get to reallocate ownership. This cannot be legally enacted and a miner who was to do this within the standard protocol would be liable for prosecution. In many countries this would be a criminal act. The fact of the matter is that the standard protocol within Bitcoin limits attacks leads to double spend attempts and censoring of the format would lead to the collapse of any pool.

**SegWit alters this.**

Segregated witness does not mildly alter the protocol, it radically changes it. From a legal perspective, the splitting of a chain into a segregated witness chain and a large block chain increases the risk for anyone deciding to use segregated witness without medium and unanimous support that can be maintained for all time.

![](./assets/1*Ii46cPWemwOxRXvwNQAhWw.jpeg)

# Anyone Can Spend

The nature of the protocol change is in some ways insidious, in dividing the scenario technical ‘experts’ have again ignored economic incentives. They have used the technical format known as *AnyoneCanSpend* to capture the existing protocol and redirect selected transactions into a new divided protocol.

They have assured us that this is right.

They have assured us how safe it is.

They have tried to tell us this is a soft fork and it can be reversed.

I will attempt to show you how all these statements are false, let us start by considering how an economic interest could undermine the protocol.

There are methods of making short-term gains within Bitcoin, even miners are able to lease equipment for a limited time periods and sell the Fiat as soon as they gain any profit. I will give you an extension of one proposed methodology of economically benefiting from SegWit.

With the current proposal, it is only necessary for 80% of the network to signal support for SegWit. This does not say that they have to continue support nor could they be forced to do so under the protocol or under the law. There is also the problem of intent. There is no way to definitively show that a particular miner, especially those made up of pool members who fluctuate intended to signal and then change shortly afterwards moving a signal to reject SegWit from acceptance.

I won’t go into the full technical details in this post, rather, I will document a simplified version of the attack. More complex versions have been discussed in technical forums. The most effective version of this requires around 50% of the hash power this example will be discussed in a simplified version without all the technical details.

Let us start with the first presumption. There is a group or pool or even an individual miner with control of 30% of the network. And the more secretive version of this action, a mining pool would require only 15%. We will ignore the 15% “attack” as that could be individually deemed to be legally questionable.

The 30% action would breach no laws even though it could result in the appropriation of funds. Not double spends, but the redirection of bitcoin wealth, if taken and distributed quickly this could be extremely problematic.

The [pool attempting to subvert the SegWit activation](https://www.reddit.com/r/btc/comments/59vent/segwit_false_start_attack_allows_a_minority_of/) could simply stop signalling. If they stopped mining, stopped making temporary losses through consuming electricity and slow down the operation, this would result in the hash rate dropping to 70% of the former amount.

If 40% of the network had been signalling in opposition to the introduction of SegWit, and now we are left with 20% of the signalling network against and the remaining original 60%, the network will see over 85% support for SegWit.

Turning off network power would not be considered a violation of one’s legal rights to engage in a later vote in the system, that vote could be self-funded. A speculative option could be taken on the primary chain, Bitcoin in its native form or with a larger block size as a long option. Alternatively, the SegWit coin could be shorted.

As one chain collapsed, it would fund the rise of the other.

Segregated witness, even with the block size increase, remains incredibly limited, a 2Mb block cap still only allows 10 transactions a second. An individual with a raspberry Pi and the dial-up modem could flood the network with small transactions making segregated witness less effective and aiding in the creation of value from the short. More than this, the change in support would allow this block split and the scenario.

At 51% of total hash power, an [anyone-can-pay segregated witness transaction can be grabbed by any miner](https://www.reddit.com/r/btc/comments/5whvee/can_someone_verify_that_my_understanding_of/) seeking to do so. With the re-signalling of our pool, network hash rate would go up to 40% opposing segregated witness again. An external party could use a temporary cloud mining contract to add an extra short term 15% hash rate to the network. Coupled with the combination of a long and short scenario which can be done through multiple accounts on anonymous exchanges, 51% of the network would now oppose segregated witness and incorporate larger blocks.

Our 15% pool would be able to gain just under one third of transactions on the split network. Remember this is coupled with a degraded segregated witness chain that is unable to process the majority of transactions through an extended rebroadcast of large numbers of complex segregated witness transactions. The combination of a long and short drains funds from one source and adds them into another. This is of course market manipulation, however location varies in bitcoin mining and this attack is even legal in some jurisdictions.

What is insidious is that the 51% now allows for the theft of funds. This cannot happen in Bitcoin, it can happen in segregated witness coin. In segregated witness coin, the 51% attacker does not just have the ability to reverse a transaction or block transactions, they have the ability to redirect them to their own payment address. This is part of the protocol. Contractually, it is paid to anyone’s address and the offer has been accepted.

![](./assets/1*m-qxxAdupxtsKd-ZI1MzOQ.jpeg)

We like to think that technical solutions will help us with everything.

Anyone who has actually run a business will understand economic incentives mean far more than technical toys. We have a protocol that can scale and we have proposals that come with risk, no actually great risk and few benefits.

A party who decided to falsely signal could gain the support of those who seek larger blocks and yet also oppose the introduction of SegWit. This false signalling could be done with as little as 15% of the network hash power.

The offer has been made, consideration is inherent in the system. We wait to see whether someone will take up this offer, move funds into segregated witness addresses and whether that is enough incentive for a party to attack the network. Much has been made about the Litecoin network’s adoption of segregated witness, however Litecoin has a lower transaction volume than Bitcoin and a higher effective cap which makes them a very poor testbed. Arguments that money has been put into Litecoin addresses failed to take the incentives structure into account. Buying hardware for Litecoin and trading Litecoin are far more difficult than Bitcoin due to the limited exchange volumes and liquidity.

**The incentives in Bitcoin are massive.**

What is worse, this is an incentive for those wanting to destroy Bitcoin., attacking the existing network would be difficult and expensive. Any government or large organisation seeking to attack Bitcoin could actually profit with the introduction of segregated witness.

There are many governments and there are many organisations that would like to see the end of Bitcoin, and with segregated witness we may just be handing them a gun, checking that it is loaded and holding it to our own heads as we put the trigger in their hands.

As a standard disclaimer, I am neither your lawyer, nor am I suggesting that you engage in any criminal activity. I am simply pointing out a highly likely scenario given the incentives involved.

# References

[1] Lord Reid in Tesco Supermarkets Limited v Nattrass
*“I must start by considering the nature of the personality which by a fiction the law attributes to a corporation. A living person has a mind which can have knowledge or intention or be negligent and he has hands to carry out his intentions. A corporation has none of these.”
*page14** [http://law.unimelb.edu.au/__data/assets/pdf_file/0006/1709583/29-201345.pdf](http://law.unimelb.edu.au/__data/assets/pdf_file/0006/1709583/29-201345.pdf)

[2] Carlill v Carbolic Smoke Ball Co [1893] 1 QB 256 Court of Appeal 
[https://www.australiancontractlaw.com/cases/carlill.html](https://www.australiancontractlaw.com/cases/carlill.html)

[3] Nakamoto, Satoshi (2008) “Bitcoin: A Peer-to-Peer Electronic Cash System” [https://bitcoin.org/bitcoin.pdf](https://bitcoin.org/bitcoin.pdf)


