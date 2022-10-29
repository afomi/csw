---
url: https://keepingstock.net/segregated-witness-or-separated-legality-eefba390f95
canonical_url: https://keepingstock.net/segregated-witness-or-separated-legality-eefba390f95
title: Segregated Witness or Separated Legality
subtitle: I have been reading a fair bit lately on forums such as Slack, these have
  me thinking.
slug: segregated-witness-or-separated-legality
description: ""
tags:
- bitcoin
- segwit
- legal
- cryptocurrency
- liability
author: Adam Selene
username: adam_selene
---

# Segregated Witness or Separated Legality

I have been reading a fair bit lately on forums such as Slack, these have me thinking.

My first concern started with possible patent infringements that people had been attributing to segregated witness. That in itself is an issue, however, there are larger legal concerns. My biggest problem having studied law is this ill-founded conception that has been promulgated by several of the most prominent people within the bitcoin community. The message is simple:

# Code is Law

This misguided attempt to believe that Bitcoin is above society will damage it all in the end. Code is developed by people, mathematics is a construct created by humans it is not perfect, and even the blockchain does not stop fraud. The level of ignorance that I see expressing the misconception that this can be the case never ceases to astound me. I apologize in advance for this rant, but this idea is simplistic and childish, and it is extremely adolescent. It is one of many memes that have propagated through people who seek to deny reality. What’s worse is when Utopian ideals come to pass.

This is why I have been expending any energy on this topic in no more than a simple preliminary post, to flesh out the consequences will take time and effort. I only truly started looking at this recently after following several of the online discussions. I thank those people for pointing out this scenario.

![](./assets/1*3t7uarv3l4ux8h1GJyOJ4Q.jpeg)

In this moment, I’m not sure of the depth of the problem, however there is at least a medium level of concern right now and this is before I have investigated in any depth.

The main concern I see is that the process of separating the signature data from the transaction record and contract used within segregated witness could be a problem. There are two ways of looking at this, the first comes down to the perceived savings. It’s been widely touted that segregated witness will save up to 60% of the storage space associated with the blocks. As one who thinks deeply on legal problems, that immediately started me thinking.

**Signatures have a legal and probative value.**

Segregated witness doesn’t necessarily make a transaction or any associated contract inherently invalid or legally unenforceable, please do not misunderstand me at this point. As long as you maintain a complete copy of the signature data, all the information that they tell you is able to be easily pruned, then you shouldn’t have any real issue in the attribution of the signature to the contract. Of course, we are assuming that most parties, not just a few selected archive nodes, will keep a complete copy of all witness data and that it will be available on request and without fee.

Following that sentence, the first thing I think about is the cost of accessing information for legal cases. Some people wonder how archive nodes will be funded, personally, having access to a Thomsons Reuters account concerning legislative search gets me thinking that this could be quite a lucrative business. That of course does not help the majority of people.

# Proof Attacks

There would be a good argument that makes a transactional contract or associated record highly vulnerable to proof attacks.

Let me explain a little on this concept.

The following excerpt does not express any level of stare decisis, that is the legal principle of determining points in litigation according to precedent, rather it expresses well the point I seek to make in a simple format that I believe people without a law degree can well comprehend:

When the party with the burden of proof attacks the legal sufficiency of the evidence to support an adverse finding, the party “must demonstrate on appeal that the evidence establishes, as a matter of law, all vital facts in support of the issue.” *See [Dow Chem. Co. v. Francis, 46 S.W.3d 237, 241 (Tex. 2001).](https://www.courtlistener.com/opinion/1560611/dow-chemical-co-v-francis/)* In reviewing such a challenge we, “must first examine the record for evidence that supports the finding, while ignoring all evidence to the contrary.” Id. “If there is no evidence to support the finding, [we must] then examine the entire record to determine if the contrary proposition is established as a matter of law.” Id. The legal sufficiency challenge will only be sustained “if the contrary proposition is conclusively established.” Id.

In court, when a party with the burden of proof attacks the factual sufficiency of the evidence, it is necessary to demonstrate that the adverse finding is against the great weight and preponderance of the evidence. This requires a factual sufficiency review. When common tools such as SQL are being examined this is a well determined matter, Bitcoin itself uses a standard transaction signature that is attached to the transaction. I see no difficulty based on existing case law in arguing this point.

Being that the signature data is separated from the transaction record, multiple transaction steps are required to recover the data. The process of linking each of the various Merkel trees, and the signatures, and reporting the numerous steps in the chain of authenticating evidence, and the accuracy of the data, this is a difficult enough process when a digital signature is directly attached to a document. There are numerous steps in the chain of authenticating evidence which all lead to the accuracy of data and the ability to have evidence accepted in a court.

Linking the exact signature data back to the corresponding transaction is of course feasible. The technical knowledge associated with this process and the corresponding difficulty that would be associated with these findings being converted into language that a judge could easily understand, let alone a jury, starts to give me headaches.

I can foresee challenges in the proof of the transaction for legal purposes and disputes which would apply to courts of both civil and criminal law matters, and I’m not sure even if this would apply correctly when administrative law is taken into account. Laws governing corporations in the US incorporates several inclusions to digital signature rights and processes that are legally accepted and require the direct association of a signature with the document. The ability to re-attribute a document is in itself not a direct attribution and it is certainly not attached.

SEC filings and audit requirements could also be a problem. Many in the *code is law* side of the Bitcoin community do not understand that a pseudonymous system such as Bitcoin makes many types of fraud simpler and not more difficult. The classical case of an organisation running two sets of books immediately comes to mind. In this, the organisation can run a set of transactions in the blockchain as well as another that are mirrored on separate hopped transactions also located on the bitcoin blockchain.

Classic stock fraud would also be trivially simple using the blockchain. The fraudster could create multiple statements that could be validated to show how they knew the movements of a share in advance. This could of course be applied to any equity or other speculative investment. After the event, the fraud would involve simply pruning those that did not make money and demonstrating the set of documents that prove your ability to predict after the event.

Those difficulties coupled with the added problem of re-incorporating signatures would make audit requirements difficult to say the least.

# Financial services

Financial services organisations would be my main concern. As a minimum requirement, I cannot see that any of them would be legally allowed to prune any signature data. Some of the more restrictive document retention laws could require that they maintain this data for a period of over 95 years. Given the age of the Internet let alone bitcoin it is ridiculous to have any presumptive requirement of an ability to prune signature data.

Financial service providers in the US at least have a utter jungle of laws that they are required to comply with lest they fall into a regulatory quagmire. Not least of these laws is the requirement to keep records of transactions, it would be insufficient to simply rely on a third-party document provider. Many in the industry such as some of the early adopters like Charlie Shrem discovered how easy it is to violate these regulations the hard way.

Consequently, I can see no way for either miners, wallets, exchanges or other bitcoin providers to ever allow themselves to prune information associated with signatures. The idea of being able to do this and not breach financial services legislation within the US is at best opportunistic and at worse criminal. The tortious nature of claims against organisations failing to maintain this information can be easily foreseen.

I am yet to investigate all the intricacies that are associated with segregated witness, particularly those of a deep technical depth. At this point I already have to express concerns, not with the technology but with the claims, I really fail to see the ability to save space. I see that anyone running a node could potentially be in breach of certain financial services legislation within the US that require the retention of documents. In the coming weeks I will investigate this further, but for the moment, I simply note that this is something to consider strongly.

I advise any organisation considering the adoption of the strategy to look deeply into the impact of removing a digital signature from a transaction.

Please note, this is not legal advice and I am not your lawyer.


