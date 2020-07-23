---
key: tutorial-4
title: "Tutorial: Security of quantum key distribution: approach from complementarity"
id: tut-4
format: tutorial
speakers:
  - koashi
videoId: null
presentation: null
draft: false
---
Abstract: In this tutorial talk, I will explain about one branch of proof techniques for the security of QKD, which is based on counting the number of phase errors. It dates back to the first security proofs for the BB84 protocol by Mayers and by Shor and Preskill. Since then, it has gradually extended its applicability to other QKD protocols. Here the “phase” refers to an observable complementary to the “bit” forming the key. If the bit is the outcome of the Z-basis measurement on a qubit, the “phase” is the outcome of the X-basis measurement. Quantum mechanics dictates that it is impossible to guess both of two complementary observables at the same time. This means that if Alice and Bob are capable of predicting the phase, Eve should have no way of predicting the bit. The goal of the QKD security proof is to show the impossibility of Eve’s achieving her objective, which sounds like a probatio diabolica. The above argument turns it to a mundane problem of showing that Alice and Bob can do something. This is the basic idea in the complementarity approach. It often suffices to count the number of phase errors and show that it is small enough, just by using classical sampling formula. In the presentation, I will start with illustrating the basic idea by focusing on the BB84 protocol, and then explain how it can be applied to various QKD protocols such as B92, RRDPS, TF QKD, and CV QKD.
