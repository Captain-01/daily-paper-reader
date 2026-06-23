---
title: Physically intelligent insect-inspired antenna sensors enhance tactile feature perception by active touch
title_zh: 物理智能的仿昆虫触角传感器通过主动触觉增强触觉特征感知
authors: "Meng, L., McDonnell, P., Jayaram, K., Mongeau, J.-M."
date: 2026-06-15
pdf: "https://www.biorxiv.org/content/10.1101/2025.10.20.683587v2.full.pdf"
tags: ["query:sakar-selman"]
score: 7.0
evidence: 昆虫启发的触角传感器用于主动触觉，与EPFL MicroBos实验室的生物启发机器人研究相关
tldr: 软体机器人触觉传感器处理复杂场景计算成本高。受昆虫触角启发，本文提出结合刚度梯度与主动触摸的物理智能天线传感器。通过触觉场分析，蟑螂仿生天线力学与主动触摸速度显著提升特征分类精度。sim-to-real迁移验证了该设计降低计算负载并增强适应性。
source: biorxiv
selection_source: fresh_fetch
motivation: 现有软体触觉传感器计算成本高，需简化触觉特征感知过程。
method: 模拟蟑螂触角刚度梯度，结合主动触摸构建触觉场，通过sim-to-real框架验证。
result: 仿生天线力学与主动触摸速度提升分类精度，增加数据稀疏性与分散性。
conclusion: 生物启发框架减少计算负载，增强机器人触觉适应性。
---

## 摘要
当前的软体机器人传感器在解释复杂触觉场景时，往往需要付出巨大的计算成本。受昆虫触角（一种通过物理智能高效处理触觉信息的柔顺分布式传感器）启发，我们研究了机械设计和主动触觉传感策略是否能够增强机器人触觉特征感知。我们假设仿昆虫触角动力学（特别是弯曲刚度梯度和主动触觉速度）可以简化触觉分类。通过一个桥接仿生计算模型与多连杆软体机器人触角的仿真到现实框架，我们引入了“触觉场”的概念——由接触位置、特征类型和主动触觉速度共同塑造的触觉刺激的时空表征。我们的分析表明，与具有均匀弯曲刚度梯度的传统传感器相比，蟑螂仿生触角力学结合主动触觉速度通过提高触觉数据稀疏性和分散性，改善了特征分类准确性。对触角力学中刚度和阻尼的探索揭示了影响触觉辨别和结构稳定性的设计权衡。通过仿真到现实的迁移，刚度梯度和结构化主动触觉运动在微型分布式软体机器人触角上得到了验证，验证了其在真实机器人系统中的有效性。总体而言，这项工作提出了一个基于生物学的触觉传感器设计框架，降低了计算负载并增强了适应性。

## Abstract
Soft robotic sensors today struggle to interpret complex tactile scenes without incurring significant computational costs. Inspired by insect antennae--compliant, distributed sensors that efficiently process tactile information through physical intelligence--we investigated whether mechanical design and active touch sensing strategies could enhance robotic tactile feature perception. We hypothesized that insect-inspired antenna dynamics, specifically flexural stiffness gradients and active touch speed, could simplify tactile classification. Using a sim-to-real framework that bridges bioinspired computational models with a multi-link soft robot antenna, we introduce the notion of tactile fields--spatiotemporal representations of tactile stimuli shaped by contact location, feature type, and active touch speed. Our analyses show that cockroach-inspired antenna mechanics jointly with active touch speeds improve feature classification accuracy compared to conventional sensors with uniform flexural stiffness gradient by increasing tactile data sparsity and dispersion. An exploration of stiffness and damping of antenna mechanics revealed design trade-offs that influence tactile discrimination and structural stability. Through sim-to-real transfer, stiffness gradients and structured active touch motions were demonstrated on a miniature distributed soft robotic antenna, validating their effectiveness in real-world robotic systems. Taken together, this work presents a biologically grounded framework for tactile sensor design that reduces computational load and enhances adaptability.