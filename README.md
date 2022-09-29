# My Bachelor in Computer Science Thesis

## Title
Owning your data through Self-Sovereign Identity: agents implementation for Verifiable Credentials interaction

## Abstract
Nowadays, most of our data is owned by private companies, and everyone knows
everything about us because privacy online is not well preserved. Imagining a world
different from this is difficult, but things can change thanks to Self-Sovereign Identity
(SSI). SSI approach aims to bring credentials back to the actual owners, the people.
This is possible through cryptography and secure authentication layers (e.g., OAuth,
OpenIDConnect). The developed product embraces this philosophy and offers a so-
lution where the users are the holders, issuers, or verifiers of Verifiable Credentials
(VCs). Specifically, will be developed software agents who create, issue, verify, modify
or even revoke the credentials, leveraging an SSI Kit.

In this thesis, we propose a methodology to merge SSI off-chain (i.e., outside the
blockchain) operations with on-chain smart contracts. In particular, the job has been
divided into three macro stages: firstly, has been done a deep dive into the SSI tech-
nology, studying all of its primitives and analyzing the problem; secondly, has been
developed a Software Development Kit (SDK), which enabled us to dialog with an
SSI Kit (off-chain logic); in the meantime, my friend and co-worker Matteo Midena
developed the smart contracts (on-chain logic); finally, off-chain and on-chain solutions
has been merged in a proof of concept web application. One of the final features is
that the verifier (who inspects the validity of the credentials) can reflect on-chain the
off-chain verification results, saving time for the following examinations. Improvements
and additional features are needed to complete the software, but this constitutes a
good baseline for future works.
