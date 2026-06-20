---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<span class="anchor" id="about"></span>

# Maowei Jiang (蒋茂苇)

I am a graduate student at **Tsinghua University**, working on large language models, multimodal agents, **Vision-Language-Action (VLA)** models, robot learning, and policy optimization. Before joining Tsinghua, I studied at the University of Chinese Academy of Sciences / Shenyang Institute of Automation, Chinese Academy of Sciences, where I worked on deep learning and intelligent perception.

My current research focuses on building embodied agents that can connect **perception, reasoning, decision making, and action**. I am especially interested in world-model-conditioned VLA policies, online policy refinement for real robots, reinforcement learning for foundation models, and multimodal systems that can generalize to long-horizon tasks.

<p style="text-align: center;">
<a href="mailto:jmw24@mails.tsinghua.edu.cn">Email</a> /
<a href="https://scholar.google.com/citations?user=ZRREqFIAAAAJ">Google Scholar</a> /
<a href="https://github.com/Zero-coder">GitHub</a> /
<a href="/cv/">CV</a>
</p>

<div class="highlight-box" markdown="1">
**Research keywords:** LLMs, MLLMs, VLA, Robot Learning, Embodied World Models, Multimodal Agents, Policy Optimization, Reinforcement Learning, Long-Horizon Decision Making.
</div>

<span class="anchor" id="news"></span>

# News

- **2026.06**: **ReCon** and **FutureVLA**, two first-author works on VLA policy refinement and future-conditioned VLA decision making, are under review.
- **2026.06**: **FDVLA** is under review at *Information Fusion*; **Prompt2Act** focuses on mapping natural-language prompts to executable robot action sequences.
- **2026**: **TAPO** was selected as an **AAAI 2026 Oral** paper, focusing on policy optimization for LLMs with dynamic teacher signals and perturbed answer injection.
- **2025**: **DAAC** was accepted to **NeurIPS 2025**, studying discrepancy-aware adaptive contrastive learning.
- **2024**: Contributed to open-world agent and generative design works, including **CARD**, **MRED-14**, and **GreenPlanner**.

<span class="anchor" id="selected-publications"></span>

# Selected Publications and Submissions

<div class="paper-card" markdown="1">
<span class="paper-badge">AAAI 2026 Oral</span>

**TAPO: Dynamic Teacher and Perturbed Answer Injection for Policy Optimization**  
**Maowei Jiang**, et al.  
*AAAI 2026 Oral*  
<small>Introduces a dynamic teacher and perturbed answer injection mechanism for improving LLM policy optimization efficiency and mitigating reward hacking.</small>
</div>

<div class="paper-card" markdown="1">
<span class="paper-badge">NeurIPS 2026 Under Review</span>

**FutureVLA: Acting on Predicted Futures with Vision-Language-Action Models**  
**Maowei Jiang**, et al.  
*First-author submission*  
<small>Connects visual world-model prediction with robot action generation by feeding predicted future visual tokens into VLA policies. Achieves strong results on LIBERO and real-robot tasks.</small>
</div>

<div class="paper-card" markdown="1">
<span class="paper-badge">NeurIPS 2026 Under Review</span>

**ReCon: Reference-Conditioned Online Refinement for Vision-Language-Action Policies**  
**Maowei Jiang**, et al.  
*First-author submission*  
<small>Studies online residual correction for frozen VLA policies. In real-robot contact-rich tasks, the approach improves average success rate from 46.3% to 98.7%.</small>
</div>

<div class="paper-card" markdown="1">
<span class="paper-badge">Information Fusion</span>

**Prompt2Act: Mapping Prompts into Sequence of Robotic Actions with Large Foundation Models**  
**Maowei Jiang**, et al.  
*Information Fusion, IF 15.5, Q1 Top, CCF-B*  
[[GitHub]](https://github.com/Zero-coder/Prompt2Act)  
<small>Maps natural-language prompts into robot action sequences, bridging LLM/MLLM reasoning, task planning, and executable robot actions.</small>
</div>

<div class="paper-card" markdown="1">
<span class="paper-badge">Information Fusion Under Review</span>

**FDVLA: A Flow-Diffusion Vision-Language-Action Framework with Dual Reasoning Modulation**  
**Maowei Jiang**, et al.  
*First-author submission*  
[[GitHub]](https://github.com/Zero-coder/FDVLA)  
<small>Explores flow-diffusion VLA modeling and reasoning modulation for complex robot manipulation and action generation.</small>
</div>

<div class="paper-card" markdown="1">
<span class="paper-badge">ACM MM 2026 Under Review</span>

**RL2VLA: Reinforcement Learning Fine-tuning for Vision-Language-Action Models**  
**Maowei Jiang**, et al.  
*First-author submission*  
[[GitHub]](https://github.com/Zero-coder/RL2VLA)  
<small>Studies reinforcement learning fine-tuning for VLA models by combining supervised behavior learning with policy search and self-improvement.</small>
</div>

<div class="paper-card" markdown="1">
<span class="paper-badge">NeurIPS 2025</span>

**DAAC: Discrepancy-Aware Adaptive Contrastive Learning**  
**Maowei Jiang**, et al.  
*NeurIPS 2025*  
<small>Studies robust representation learning under distribution discrepancy through adaptive contrastive learning.</small>
</div>

<div class="paper-card" markdown="1">
<span class="paper-badge">Agents / Generative Design</span>

**CARD / MRED-14 / GreenPlanner**  
*NeurIPS 2024 Workshop on Open-World Agents; ACM MM; CVPR*  
<small>Contributed to cross-modal agents for editable residential design, a benchmark for low-energy residential floor-plan generation, and function-feasible generative layout planning.</small>
</div>

<span class="anchor" id="open-source"></span>

# Open Source

<div class="opensource-grid" markdown="1">

<div class="opensource-card" markdown="1">
**[Awesome-LLM-Robotics](https://github.com/GT-RIPL/Awesome-LLM-Robotics)**  
4.4k+ stars. A curated list of LLM/MLLM + Robotics/RL papers, code, and resources. I contribute to tracking the fast-moving embodied AI literature.
</div>

<div class="opensource-card" markdown="1">
**[Second-Me](https://github.com/mindverse/Second-Me)**  
15.5k+ stars. Contributed to interface development for a personalized AI self system and WeChat bot integration.
</div>

<div class="opensource-card" markdown="1">
**[Prompt2Act](https://github.com/Zero-coder/Prompt2Act) / [RL2VLA](https://github.com/Zero-coder/RL2VLA) / [FDVLA](https://github.com/Zero-coder/FDVLA)**  
Research repositories for prompt-to-action generation, RL fine-tuning for VLA, and flow-diffusion VLA modeling.
</div>

<div class="opensource-card" markdown="1">
**[Zero-coder GitHub](https://github.com/Zero-coder)**  
98 public repositories covering LLMs, VLA, multimodal learning, computer vision, open-source notes, and research prototypes.
</div>

</div>

# Honors and Competitions

- **Kaggle CMI Child Mind Institute**: Silver Medal, global rank 75 / 1878.
- **Huawei Ascend AI Innovation Competition**: Excellent Solution Award.
- **BMW Hackathon**: Finalist / second place.
- **Alibaba Tianchi Few-shot Trademark Detection**: Global rank 239 / 2135.
- **Asia-Pacific Ophthalmology Big Data Competition**: Global rank 142 / 10006.

# Research Taste

I like problems where language, vision, action, and feedback meet each other. My long-term goal is to build agents that do not merely describe the physical world, but can reason about it, act in it, learn from failures, and improve through real interaction.

<style>
.highlight-box {
  border-left: 4px solid #2f6f9f;
  background: #f6f9fb;
  padding: 12px 14px;
  margin: 18px 0 24px 0;
  border-radius: 6px;
}
.paper-card {
  border: 1px solid #e5e7eb;
  border-radius: 8px;
  padding: 14px 16px;
  margin: 14px 0;
  background: #ffffff;
  box-shadow: 0 1px 2px rgba(0,0,0,0.04);
}
.paper-badge {
  display: inline-block;
  font-size: 0.74rem;
  font-weight: 700;
  color: #ffffff;
  background: #2f6f9f;
  border-radius: 4px;
  padding: 3px 7px;
  margin-bottom: 8px;
}
.opensource-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 12px;
  margin: 12px 0 22px 0;
}
.opensource-card {
  border: 1px solid #e5e7eb;
  border-radius: 8px;
  padding: 13px 14px;
  background: #ffffff;
}
.anchor {
  display: block;
  position: relative;
  top: -80px;
  visibility: hidden;
}
</style>
