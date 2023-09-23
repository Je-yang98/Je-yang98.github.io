---
layout: post
title: Accelerating Deep Reinforcement Learning
date: 2022-09-23 23:18 -0400
tags:
- Deep Reinforcement Learning
- FPGA Accelerator
---

__Reinforcement learning (RL)__ is a promising area of machine learning that studies how an agent should take actions in an environment in order to maximize a long-term cumulative reward. It aims to solve a complex decision-making problem in a setting where the agent constantly updates its action policy based on the reward feedback from the environment. Recently, deep reinforcement learning (DRL) that utilizes a deep neural network (DNN) for the action policy to train has been proposed and this deep learning approach becomes very popular like in other machine learning disciplines, as it observes widespread success in various applications such as robotics, indus- trial control, and game playing. 

## [FIXAR, DAC21](https://ieeexplore.ieee.org/document/9586213) 
FIXAR handles computationally expensive training process of DRL by employing fixed-point data types and arithmetic units for the first time using a SW/HW co-design approach. We propose a fixed-point-based quantization-aware training algorithm and design an FPGA accelerator with configurable datapath and adaptive parallelism.

## [LearningGroup, FPT22](https://ieeexplore.ieee.org/abstract/document/9974543) 
Other significant applications have started to employ interaction between multiple agents, for instance, analysis of language communication and the network of self-driving cars. Hence, extending DRL to have many agents is critical for developing intelligent systems where agents can interact with each other or even with people. LearningGroup adopts network pruning through the weight grouping algorithm on the training of multi-agent DRL for the first time. We propose on-chip sparse data encoding loop (OSEL) to enable the fast encoding and aggresive workload allocation algorithm.