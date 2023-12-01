---
title: A Classical Architecture For Digital Quantum Computers
authors:
- Fang Zhang
- Xing Zhu
- Rui Chao
- Cupjin Huang
- Linghang Kong
- Guoyang Chen
- Dawei Ding
- Haishan Feng
- Yihuai Gao
- Xiaotong Ni
- Liwei Qiu
- Zhe Wei
- Yueming Yang
- Yang Zhao
- Yaoyun Shi
- Weifeng Zhang
- Peng Zhou
- Jianxin Chen
author_notes:
- "Equal contribution"
- "Equal contribution"
- 
-
-
-
-
-
-
-
-
-
-
-
-
-
-
-
date: '2023-09-01'
publishDate: '2023-12-01T00:07:31.033862Z'
publication_types:
- article-journal
publication: '*ACM Transactions on Quantum Computing*'
doi: 10.1145/3626199
abstract: Scaling bottlenecks the making of digital quantum computers, posing challenges
  from both the quantum and the classical components. We present a classical architecture
  to cope with a comprehensive list of the latter challenges all at once, and implement
  it fully in an end-to-end system by integrating a multi-core RISC-V CPU with our
  in-house control electronics. Our architecture enables scalable, high-precision
  control of large quantum processors and accommodates evolving requirements of quantum
  hardware. A central feature is a microarchitecture executing quantum operations
  in parallel on arbitrary predefined qubit groups. Another key feature is a reconfigurable
  quantum instruction set that supports easy qubit re-grouping and instructions extensions.
  As a demonstration, we implement the surface code quantum computing workflow. Our
  design, for the first time, reduces instruction issuing and transmission costs to
  constants, which do not scale with the number of qubits, without adding any overheads
  in decoding or dispatching. Our system uses a dedicated general-purpose CPU for
  both qubit control and classical computation, including syndrome decoding. Implementing
  recent theoretical proposals as decoding firmware that parallelizes general inner
  decoders, we can achieve unprecedented decoding capabilities of up to distances
  47 and 67 with the currently available systems-on-chips for physical error rate
  p = 0.001 and p = 0.0001, respectively, all in just 1 µs.
tags:
- parallel decoding
- quantum computer architecture
- fault-tolerant quantum computing
featured: true
links:
- name: URL
  url: https://doi.org/10.1145/3626199
---