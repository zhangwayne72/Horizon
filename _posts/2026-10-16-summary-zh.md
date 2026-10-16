---
layout: default
title: "Horizon Summary: 2026-10-16 (ZH)"
date: 2026-10-16
lang: zh
---

> 从 50 条内容中筛选出 2 条重要资讯。

---

1. [谷歌借助“魔态培育”将 Willow 芯片错误率降低约 40 倍](#item-1) ⭐️ 8.0/10
2. [Meta 发布开放权重模型 Muse Spark Open，最强技术仍闭源](#item-2) ⭐️ 5.0/10

---

<a id="item-1"></a>
## [谷歌借助“魔态培育”将 Willow 芯片错误率降低约 40 倍](https://www.yicai.com/brief/103395740.html) ⭐️ 8.0/10

谷歌量子人工智能（Quantum AI）团队宣布，其已在 105 量子比特的 Willow 超导量子芯片上实验验证了名为“魔态培育”（magic state cultivation）的技术，使错误率降低约 40 倍。相关成果以“超导量子处理器上的魔态培育”为题发表于 arXiv（2512.13908）并登上《Science》。 魔态是实现非 Clifford 门的关键资源，而非 Clifford 门是实现通用容错量子计算不可或缺的一环，因此让魔态更廉价、更精确，直接降低了当前噪声硬件与实用大规模量子计算机之间的开销门槛。在真实芯片上取得约 40 倍的错误率改善，是迈向实用化容错量子计算的重要一步，而不仅仅是理论结果。 该实验完整实现了培育流程，包括切换到表面码（surface code）的码切换操作，并设计了容错测量协议来界定所生成魔态的保真度；作者将其定位为比完整魔态蒸馏更节省资源的一种替代方案。Willow 是谷歌于 2024 年 12 月发布的 105 量子比特超导处理器，此前已展示出逻辑量子比特所用的物理量子比特越多、错误率呈指数级下降的特性。

rss · 第一财经 - 快讯 · 10月15日 19:28

**背景**: 量子比特十分脆弱，容易受到噪声干扰，因此实用化量子计算依赖量子纠错：用大量物理量子比特编码出一个健壮的“逻辑”量子比特。Clifford 门相对容易做到容错，但通用量子计算还需要 T 门等非 Clifford 门，而这类门必须依靠被称为“魔态”的特殊辅助态来驱动。传统上高保真度魔态通过“魔态蒸馏”制备，该过程开销巨大，会消耗大量量子比特和操作；而“魔态培育”是较新的低成本路线，直接在纠错码内部“培育”出高质量魔态。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/abs/2512.13908">[2512.13908] Magic state cultivation on a superconducting ...</a></li>
<li><a href="https://www.science.org/doi/10.1126/science.aee7961">Magic state cultivation on a superconducting quantum ...</a></li>
<li><a href="https://blog.google/innovation-and-ai/technology/research/google-willow-quantum-chip/">Meet Willow, our state-of-the-art quantum chip - The Keyword</a></li>

</ul>
</details>

**标签**: `#quantum computing`, `#Google`, `#Willow chip`, `#error correction`, `#quantum AI`

---

<a id="item-2"></a>
## [Meta 发布开放权重模型 Muse Spark Open，最强技术仍闭源](https://www.yicai.com/brief/103395732.html) ⭐️ 5.0/10

Meta Platforms 宣布发布开放 AI 模型 Muse Spark Open 的“权重”，即允许开发者自行下载、运行并适配模型的参数设置。与此同时，Meta 将其最先进的强技术继续闭源，而不对外公开。 开放权重发布使外部开发者能够对能力较强的模型进行微调并自行部署，从而对竞争对手形成压力，并影响整个 AI 行业围绕“开放”的竞争格局。Meta 只开放部分技术栈、而将前沿技术保持闭源，反映出业界在社区好感与商业利益之间寻求平衡的普遍做法。 根据 Meta 自己的资料，Muse Spark Open 被称为迄今美国最强的开放权重模型，是一个大型混合专家（MoE）模型，总参数量约 816B、激活参数约 42B，提供 BF16 和 NVFP4 两种权重格式。它主打可在 Apple M5 Ultra Mac Studio 等桌面硬件上运行的智能体（agentic）任务，但此次发布的只是权重本身——训练数据、算法和详细架构仍属专有。

rss · 第一财经 - 快讯 · 10月15日 17:45

**背景**: 模型权重是训练过程中学习到的数十亿个数值参数，决定了神经网络的行为方式，可以说模型的“智能”就存储在这些参数里。“开放权重”指的是公开这些预训练参数供他人使用和修改，但训练数据、算法和架构仍保持专有，这与完全开源的 AI（连这些要素也一并开放）有所不同。Meta 一直将自己定位为开放权重发布的主要倡导者，以对抗仅提供闭源 API 的竞争对手。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://dev.meta.ai/models/muse-spark-open">Muse Spark Open | Meta</a></li>
<li><a href="https://research.meta.ai/blog/muse-spark-open">Introducing Muse Spark Open, - research.meta.ai</a></li>
<li><a href="https://huggingface.co/collections/meta-models/muse-spark-open">Muse Spark Open - a meta-models Collection - Hugging Face</a></li>

</ul>
</details>

**标签**: `#Meta`, `#open-weights`, `#AI-models`, `#open-source-AI`, `#industry-news`

---