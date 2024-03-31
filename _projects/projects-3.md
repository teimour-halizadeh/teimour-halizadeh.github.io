---
title: "Private computation of polynomials over networks"
excerpt: " 

![GitHub Logo](/images/poly.png)"


collection: projects
draft: true
---

This study concentrates on preserving privacy in a network of agents where each agent seeks to
evaluate a general polynomial function over the private values of her immediate neighbors. We provide
an algorithm for the exact evaluation of such functions while preserving privacy of the involved agents.
The solution is based on a reformulation of polynomials and adoption of two cryptographic primitives:
Paillier as a Partially Homomorphic Encryption scheme and multiplicative–additive secret sharing. The
provided algorithm is fully distributed, lightweight in communication, robust to dropout of agents,
and can accommodate a wide class of functions. Moreover, system theoretic and secure multi-party
conditions guaranteeing the privacy preservation of an agent’s private values against a set of colluding
agents are established. The theoretical developments are complemented by numerical investigations
illustrating the accuracy of the algorithm and the resulting computational cost.