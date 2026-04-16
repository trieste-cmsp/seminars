---
title: "Modeling Noise in Quantum Circuits and Novel Approaches to Error Mitigation"
speaker: "Dott. Michele Vischi"
institution: "University of Trieste"
date: '2026-04-23'
time: '11:00'
location: "Aula 131, SISSA, Main Building"
---

# Abstract

The utility of quantum computers is approaching, driven by both hardware improvements and proof-of-principle experimental demonstrations of quantum error correction. However, significant effort is still required to fully account for complex noise sources such as correlated errors, crosstalk and coherent errors. In particular, many?if not most?recent claims about quantum utility rely on error mitigation techniques. 
On the one hand, it is essential to accurately simulate the behavior of noisy quantum circuits; on the other, effective error mitigation techniques that can work alongside error correction are needed. In this talk, I will present a brief overview of the work carried out by the QMTS group at the University of Trieste to address these challenges.
First, I will briefly introduce a method for simulating the noisy behavior of quantum computers, which efficiently incorporates environmental effects into the driven evolution implementing quantum gates [1-2]. 
Then, I will describe a novel error mitigation technique designed to correct small angle miscalibrations in native quantum gates of a quantum device. Variational Coherent Error Mitigation (VCEM) [3] employs the stabilizer formalism to suppress coherent errors through variational optimization of gate parameters. VCEM demonstrates robust performance, remaining largely unaffected by incoherent noise and enabling pre-compensation of coherent errors prior to the application of standard incoherent error mitigation techniques and/or error correction.

[1] Di Bartolomeo, G., Vischi, M., Cesa, F., Wixinger, R., Grossi, M., Donadi, S., & Bassi, A. (2023). Noisy gates for simulating quantum computers. Physical Review Research, 5(4), 043210.
[2] Di Bartolomeo, G., Vischi, M., Feri, T., Bassi, A., & Donadi, S. (2024). Efficient quantum algorithm to simulate open systems through a single environmental qubit. Physical Review Research, 6(4), 043321.
[3] Di Bartolomeo, G., Crognaletti, G., Bassi, A., & Vischi, M. (2025). Mitigating Coherent Errors through a Decoherence-Resistant Variational Framework employing Stabilizer State. arXiv preprint arXiv:2510.20445.
