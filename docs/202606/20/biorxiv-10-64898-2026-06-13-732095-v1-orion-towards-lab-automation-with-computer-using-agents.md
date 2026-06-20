---
title: "Orion: Towards Lab Automation with Computer-Using Agents"
title_zh: Orion：面向使用计算机代理的实验室自动化
authors: "Ma, C., Trinh, L., Bucci, M., Regev, A., Wang, H."
date: 2026-06-16
pdf: "https://www.biorxiv.org/content/10.64898/2026.06.13.732095v1.full.pdf"
tags: ["query:sakar-selman"]
score: 6.0
evidence: 用于生物医学图像分析的实验室自动化AI代理，与MicroBos实验室相关
tldr: "实验室计算工作流依赖人工操作和视觉检查，效率低下。Orion结合大语言模型与终端、GUI控制及多步推理，可自主操作科学软件和网络资源。在检索任务中准确率超90%，100小时自主探索生成52份研究报告，其中22个合理假设。该方法扩展了实验室自动化，实现了从成像数据到分析、报告和假设的可扩展可审计流程。"
source: biorxiv
selection_source: fresh_fetch
motivation: 实验室计算工作流依赖人工操作专用软件和视觉检查，效率低且难以扩展。
method: Orion结合大语言模型、终端执行、GUI控制和自适应多步推理，在共享计算环境中自主操作软件和网络资源。
result: "检索任务准确率超90%；100小时自主探索生成52份报告，其中22个合理机制假设。"
conclusion: 计算机使用AI智能体可扩展实验室自动化，提供从成像数据到分析、报告和假设的可审计路线。
---

## 摘要
实验室发现越来越依赖于将实验数据与分析、解释和后续假设连接起来的计算工作流程。然而，这些工作流程仍然受限于专业软件的劳动密集型使用、通过图形用户界面进行的可视化检查以及跨多个来源的知识整合。在此，我们提出Orion，一个用于生物医学图像分析和解释的使用计算机的AI代理，它通过自动化实验室工作的计算层来迈向实验室自动化。Orion在共享计算环境中将大型语言模型与终端执行、GUI控制和自适应多步推理相结合。它可以检查视觉数据、操作标准科学软件、挖掘网络资源并执行端到端的分析和解释工作流程，无需定制软件集成。在基准测试中，Orion在生物医学数据库和文献检索任务上达到了超过90%的准确率，学会了分别使用流行工具CellProfiler和QuPath进行细胞和组织图像的定量分析，并促进了实验成像数据中的自主发现。在对大规模扰动成像数据集进行100小时的自主探索中，Orion生成了52份研究报告，其中人类科学家评审优先考虑了22个合理的机制性假设。这些结果表明，使用计算机的AI代理可以显著扩展实验室自动化的范围，提供从实验成像数据到定量分析、报告和生物学合理假设的可扩展且可审计的路径。



O_FIG O_LINKSMALLFIG WIDTH=200 HEIGHT=45 SRC="FIGDIR/small/732095v1_ufig1.gif" ALT="Figure 1">
查看大图（20K）：
org.highwire.dtl.DTLVardef@af6486org.highwire.dtl.DTLVardef@f0ba97org.highwire.dtl.DTLVardef@6a2dbcorg.highwire.dtl.DTLVardef@e09b15_HPS_FORMAT_FIGEXP  M_FIG Orion概述

Orion在数字实验室环境中运行，像人类科学家一样同时使用图形用户界面和终端。这种双重方法使Orion能够与科学软件无缝交互，同时查看图形和网络数据库以捕捉其细微的视觉信息。

C_FIG

## Abstract
Laboratory discovery increasingly depends on computational workflows that connect experimental data to analysis, interpretation and follow-up hypotheses. Yet these workflows remain constrained by labor-intensive use of specialized software, visual inspection through graphical user interfaces, and integration of knowledge across multiple sources. Here, we present Orion, a computer-using AI agent for biomedical image analysis and interpretation that moves towards lab automation by automating this computational layer of laboratory work. Orion combines large language models with terminal execution, GUI control and adaptive multi-step reasoning in a shared computing environment. It can inspect visual data, operate standard scientific software, mine web resources and conduct end-to-end analysis and interpretation workflows without requiring bespoke software integrations. Across benchmarks, Orion achieved over 90% accuracy on biomedical database and literature retrieval tasks, learned to use the popular tools CellProfiler and QuPath for quantitative analysis of cellular and tissue images, respectively, and facilitated autonomous discovery in experimental imaging data. In 100 hours of autonomous exploration of a large-scale perturbation imaging dataset, Orion generated 52 research reports, of which human scientist review prioritized 22 plausible mechanistic hypotheses. These results show that computer-using AI agents can substantially expand the reach of laboratory automation, providing a scalable and auditable route from experimental imaging data to quantitative analysis, reports and biologically grounded hypotheses.



O_FIG O_LINKSMALLFIG WIDTH=200 HEIGHT=45 SRC="FIGDIR/small/732095v1_ufig1.gif" ALT="Figure 1">
View larger version (20K):
org.highwire.dtl.DTLVardef@af6486org.highwire.dtl.DTLVardef@f0ba97org.highwire.dtl.DTLVardef@6a2dbcorg.highwire.dtl.DTLVardef@e09b15_HPS_FORMAT_FIGEXP  M_FIG Overview of Orion

Orion operates within a digital lab environment, using both graphical user interfaces and terminals just like a human scientist. This dual approach allows Orion to interact seamlessly with scientific software while also viewing figures and web databases to capture their nuanced visual information.

C_FIG