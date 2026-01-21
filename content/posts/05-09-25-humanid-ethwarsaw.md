+++
title = "Human ID - ETH Warsaw Hackathon Win ($2,000)"
description = "How we built a DNA-based verification system and won at ETH Warsaw 2025"
date = 2025-09-05T12:00:00+02:00
type = ["posts","post"]
toc = true
tags = ["tech", "hackathon", "web3", "blockchain", "ethwarsaw"
]
categories = [
]
[ author ]
  name = "Wiktor Pinkwart"
+++

During ETH Warsaw 2025, I took part in the hackathon together with Max Kokocom and Rahim Unlu. Our project, Human ID, won two awards and a $2,000 prize, and it was a pivotal experience for me.

The idea we worked on came from a problem that keeps getting harder to ignore: human verification in the age of AI.

---

## The problem we tackled

Traditional authentication methods are breaking down quickly. Voice ID can be cloned. Face ID and image-based verification can be spoofed. Even multi-factor setups increasingly rely on signals that AI systems can imitate or replay.

For high-risk contexts such as KYC, access to critical infrastructure, or sensitive operations, this creates a real gap. The question is no longer how to make authentication more convenient, but how to make it high-resistance to manipulation in a world of generative AI.

One category of signals remains significantly harder to fake: biological proofs, such as saliva or blood, combined with cryptographic verification.

---

## The idea behind Human ID

Human ID explored how DNA-based verification could be combined with cryptography and Web3 infrastructure to create a stronger form of human proof.

In our prototype:

* We took results from DNA sequencing and processed them to generate a verification signal
* Two independent results were compared to simulate an authentication flow
* The resulting proof was recorded in GolemDB, a blockchain-based database
* The user could connect a wallet using BuidlGuidl integrations
* We also used Web3Pi to simulate parts of the verification and execution environment
* The verification proof was linked to the wallet and persisted on-chain

Working with GolemDB felt like a very natural fit for this kind of problem. It highlighted how blockchain databases are particularly well suited for verification, proofs, and maintaining integrity of critical records, rather than speculative use cases.

---

## My role

My focus in the project was on integration and infrastructure:

* Building the endpoints that listened for verification outputs
* Handling writes and reads to GolemDB
* Wiring the wallet connection and identity flow using BuidlGuidl tooling
* Front-end components

The project is open-source: **[github.com/rahimunlu/humanID](https://github.com/rahimunlu/humanID)**

---

## Reflections

Human proof is becoming a foundational problem. As AI systems improve, the cost of impersonation drops, while the cost of trust increases. Solutions like this could be relevant far beyond digital KYC. Think access to nuclear facilities, control systems, high-value financial operations, or any environment where failure of authentication has serious consequences.

All in all, this was time well spent. I learned a lot, met interesting people, and it left me wanting to build more projects.

---

## Photos from ETH Warsaw 2025

{{< image src="/images/ethwarsaw/ETHWarsaw1.jpeg" alt="ETH Warsaw 2025" position="center" style="border-radius: 8px; max-width: 100%; margin: 1rem 0;" >}}

{{< image src="/images/ethwarsaw/ETHWarsaw2.jpeg" alt="ETH Warsaw 2025 Hackathon" position="center" style="border-radius: 8px; max-width: 100%; margin: 1rem 0;" >}}

{{< image src="/images/ethwarsaw/ETHWarsaw3.jpeg" alt="Human ID Team" position="center" style="border-radius: 8px; max-width: 100%; margin: 1rem 0;" >}}

{{< image src="/images/ethwarsaw/ETHWarsaw4.jpeg" alt="ETH Warsaw 2025 Award" position="center" style="border-radius: 8px; max-width: 100%; margin: 1rem 0;" >}}


