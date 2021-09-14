---
title: "Invited: Quantum Oblivious Transfer from One-way Functions (Chair: Frédéric Dupuis)"
format: invited
speakers:
  - khurana
videoId: "3DGVkUsxdOY"
videoTime: 895
presentation: "/slides/QCrypt2021InvitedKhurana.pdf"
draft: false
---
Abstract: The groundbreaking work by Bennett and Brassard on quantum key distribution raised the tantalizing possibility of realizing cryptographic primitives unconditionally with quantum resources. In particular, it opened the possibility of using quantum resources to realize oblivious transfer (OT), a protocol that enables a receiver to obtain exactly one out of two secret bits that a sender owns, without revealing which secret bit is chosen. OT is an important and versatile cryptographic primitive, which in particular enables secure multiparty (quantum) computation (MPC) of any polynomial-time computable function, among many other applications.

While prior works due to Crepeau-Kilian and Bennett-Brassard-Crepeau-Skubiszewska have constructed quantum OT protocols from ideal bit commitment protocols, it was later shown that unconditionally secure commitments and unconditionally secure OT are impossible even with quantum resources. However, given that bit commitment can be constructed from one-way functions, the hope remains that OT, and therefore a large swath of cryptography, can be based solely on one-way functions together with simple quantum computation/communication.

Unfortunately, in the classical setting, there are significant barriers towards constructing important primitives such as key exchange, PKE, OT, or secure computation protocols from one-way functions. It is in fact known that these primitives cannot be constructed based on black-box use of one-way functions alone. This begs the question whether quantum communication and computation can extend the "reach" of one-way functions, and enable powerful primitives like OT and secure computation based on one-way functions.

We show that OT (and secure computation) can indeed be implemented by quantum protocols under the minimal assumption that post-quantum one-way functions exist. Moreover, our OT protocols use only simple quantum communication as in the quantum key distribution protocols of Bennett and Brassard, making them amenable to deployment in the foreseeable future, as quantum communication becomes a reality.

This talk will discuss solutions based on approaches developed in two recent independent works: <a href="https://eprint.iacr.org/2020/1500" target="_blank">Oblivious Transfer is in MiniQCrypt</a> (Grilo, Lin, Song and Vaikuntanathan, Eurocrypt 2021) and <a href="https://eprint.iacr.org/2020/1487" target="_blank">One-Way Functions imply Secure Computation in a Quantum World</a> (Bartusek, Coladangelo, Khurana and Ma, Crypto 2021).

<!-- fields to use above: -->
<!-- videoId: "Vfl9pPh6ipI" -->
<!-- presentation: "/slides/invited-MargaridaPereira.pdf" -->
