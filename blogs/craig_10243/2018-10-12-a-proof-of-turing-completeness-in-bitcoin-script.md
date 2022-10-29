---
url: https://medium.com/@craig_10243/a-proof-of-turing-completeness-in-bitcoin-script-3cf5aa7aeb83
canonical_url: https://medium.com/@craig_10243/a-proof-of-turing-completeness-in-bitcoin-script-3cf5aa7aeb83
title: A Proof of Turing completeness in Bitcoin Script
subtitle: Continuing on an early set of drafts that I will publish fully in time,
slug: a-proof-of-turing-completeness-in-bitcoin-script
description: ""
tags:
- blockchain
- computer-science
- bitcoin
- smart-contracts
- technology
author: Craig Wright (Bitcoin SV is Bitcoin.)
username: craig_10243
---

# A Proof of Turing completeness in Bitcoin Script

Continuing on an early set of drafts that I will publish fully in time,

[https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3265157](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3265157)

![][image_ref_MCpmZnA3VWV4ZkdoNUV5cFI3LmpwZw==]

The concept of a Turing machine has been well defined {[17], [20]}. It would be sufficient to show that Bitcoin uses a dual stack architecture that acts as a dual counter machine. Such systems have already been demonstrated as being Turing complete [17].

We demonstrate that Bitcoin script is a minimal family of which  and R are members. Further using the compositional product rule and the iteration rule we demonstrate that Bitcoin scripting is Turing complete with the limitations imposed on any realworld computer. This limitation is that there cannot be an infinite tape. Iterations can be simulated using an “unrolled” loop function with allocation to the “Alt” stack.

As the product rule states that if A, B are machines, then A.B is also a machine [17]. The iteration rule shows that if A is a machine then (A) is also a machine. Further the minimum power of A under which the observed square of the final configuration is blank. The consequence of these rules is that for every partial recursive function of in variables we can show that it can be evaluated by machine of the proposed family {[7], [21]}.

The concept of a Turing machine has been well defined {[17], [20]}. It would be sufficient to show that Bitcoin uses a dual stack architecture that acts as a dual counter machine. Such systems have already been demonstrated as being Turing complete [17].

The full paper can be viewed online from SSRN:

https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3265157


[image_ref_MCpmZnA3VWV4ZkdoNUV5cFI3LmpwZw==]: data:;base64,
