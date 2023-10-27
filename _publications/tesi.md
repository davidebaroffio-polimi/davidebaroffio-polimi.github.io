---
title: "Hardening safety-critical systems against transient faults via SIHFT compiler transformations"
collection: publications
permalink: /publication/tesi.md
date: 18-07-2023
venue: 'Politecnico di Milano'
paperurl: 'https://www.politesi.polimi.it/handle/10589/212232'
---

Resilience against random hardware faults is one of the main concerns when designing mission-and safety-critical systems. These kinds of faults can have transient nature since they are typically due to physical phenomena like vibrations, radiation, or electromagnetic interferences. Resiliency against this kind of fault is traditionally implemented using hardware solutions, yet they provide low flexibility and high engineering cost, as well as affect energy, thermal and weight requirements of the system. Software solutions, commonly named Software-Implemented Hardware Fault Tolerance (SIHFT), mitigate transient faults by employing software-only techniques, that are more flexible and lower the production costs. This work shows how three SIHFT mechanisms can be implemented in a language-and architecture-independent environment by leveraging the open-source compiler framework LLVM, and enhanced via novel overhead reduction techniques and detection strategies. Additionally, an open-source real-time operating system is compiled with the aforementioned mechanisms, both in the kernel and the real-time tasks, and runs on a physical STM32 board. In order to do so, special adaptations were required, which are discussed in this thesis. Finally, an experimental evaluation shows the effectiveness of the proposed approach in detecting faults, highlighting the differences between the different techniques and the tweaks implemented to manage the trade-off between performance overhead and detection capabilities.