---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I'm Kai Xiong, a Ph.D. student in Research Center for Social Computing and Interactive Robotics (SCIR), at Harbin Institute of Technology (HIT, China). I am co-advised by Prof. Ting Liu and Prof. Xiao Ding. My research interests lie in event reasoning, eventic graph, and large language models.


<!-- # 🔥 News
- *2025.05*: &nbsp;🎉🎉 Three/One papers are accepted by ACL 2025 conference/findings, respectively. 
- *2024.09*: &nbsp;🎉🎉 One paper is accepted by NeurIPS 2024 poster.
- *2024.05*: &nbsp;🎉🎉 One/One papers are accepted by ACL 2024 conference/findings, respectively. -->

# 📝 Publications 

## 2026
- *Diagnosing and Remedying Knowledge Deficiencies in LLMs via Label-free Curricular Meaningful Learning.* **Kai Xiong**, Xiao Ding, Li Du, Jiahao Ying, Ting Liu, Bing Qin, Yixin Cao. ICLR 2026.
- *Consolidation or Adaptation? PRISM: Disentangling SFT and RL Data via Gradient Concentration.* Yang Zhao, Yangou Ouyang, Xiao Ding, Hepeng Wang, Bibo Cai, **Kai Xiong**, Jinglong Gao, Zhouhao Sun, Li Du, Bing Qin, Ting Liu. ACL 2026.
- *Maestro: Meta-learning adaptive estimation of scalarization trade-offs for reward optimization.* Yang Zhao, Hepeng Wang, Xiao Ding, Yangou Ouyang, Bibo Cai, **Kai Xiong**, Jinglong Gao, Zhouhao Sun, Li Du, Bing Qin, Ting Liu. ACL 2026.
- *Is EEG-to-Text Feasible in Real-World Scenarios? An In-Depth Analysis Using a Neuropsychology-Inspired Benchmark.* Zihan Zhang, Yu Bao, Xiao Ding, Tianyi Jiang, **Kai Xiong**. ACL 2026.
- *MDC-Bench: A Multidisciplinary Causal Benchmark Based on Causal Structures for Evaluating Large Language Models.* Peng Wang, Yuxiong Yan, Xiao Ding, **Kai Xiong**, Bibo Cai, Chao Peng, Yutai Hou, Dandan Tu, Bing Qin, Ting Liu. Findings of ACL 2026.
- *Optimizing Automated Jailbreak Attacks on Large Language Models via Experience Accumulation.* Yuxin Zhou, Xiao Ding, Yijia Meng, Tianle Chang, Jinglong Gao, Zihan Zhang, **Kai Xiong**, Qi Shi. ICASSP 2026.
- *Proactive Safety Deliberation: Guiding Large Reasoning Models with Distilled Principles.* Yuxin Zhou, Xiao Ding, Qi Shi, Ye He, **Kai Xiong**, Yijia Meng, Tianle Chang, Jinglong Gao. ICASSP 2026.
- *Do LLMs Signal When They’re Right? Evidence from Neuron Agreement.* Kang Chen, Yaoning Wang, **Kai Xiong**, Zhuoka Feng, Yu Minshen, Wenhe Sun, Haotian Chen, Yixin Cao. ICML 2026 (Spotlight).

## 2025
- *Think Straight or Think Again? Continual Joint Learning of Deduction, Abduction, and Induction.* **Kai Xiong**, Xiao Ding, Yixin Cao, Yang Zhao, Bing Qin, Ting Liu. Neural Networks (IF=6.3).
- *Com$^2$: A Causal-Guided Benchmark for Exploring Complex Commonsense Reasoning in Large Language Models.* **Kai Xiong**, Xiao Ding, Yixin Cao, Yuxiong Yan, Li Du, Yufei Zhang, Jinglong Gao, Jiaqian Liu, Bing Qin, Ting Liu. ACL 2025.
- *Supervised Fine-Tuning Achieve Rapid Task Adaption Via Alternating Attention Head Activation Patterns.* Yang Zhao, Li Du, Xiao Ding, **Kai Xiong**, Ting Liu, Bing Qin. ACL 2025.
- *Beyond Similarity: A Gradient-based Graph Method for Instruction Tuning Data Selection.* Yang Zhao, Li Du, Xiao Ding, YangouOuyang, Hepeng Wang, **Kai Xiong**, Jinglong Gao, Zhouhao Sun, Dongliang Xu, Qing Yang, Dongchen Li, Bing Qin, Ting Liu. ACL 2025.
- *Natural Logic at the Core: Dynamic Rewards for Entailment Tree Generation.* Jihao Shi, Xiao Ding, **Kai Xiong**, Hengwei Zhao, Bing Qin, Ting Liu. ACL 2025 Findings.
- *UFO-RL: Uncertainty-Focused Optimization for Efficient Reinforcement Learning Data Selection.* Yang Zhao, **Kai Xiong**, Xiao Ding, Li Du, Yangou Ouyang, Zhouhao Sun, Jiannan Guan, Wenbin Zhang, Bin Liu, Dong Hu, Bing Qin, Ting Liu. NeurIPS 2025.
- *Necessary and sufficient knowledge enhanced collaborative logical reasoning in LLMs.* Peng Wang, Xiao Ding, **Kai Xiong**, Bing Qin, Ting Liu. Neural Networks (IF=6.3).

## 2024
- *Meaningful Learning: Enhancing Abstract Reasoning in Large Language Models via Generic Fact Guidance.* **Kai Xiong**, Xiao Ding, Ting Liu, Bing Qin, Dongliang Xu, Qing Yang, Hongtao Liu, Yixin Cao. NeurIPS 2024.
- *Intuitive or Dependent? Investigating LLMs' Behavior Style to Conflicting Prompts.* Jiahao Ying, Yixin Cao, **Kai Xiong**, Yidong He, Long Cui, Yongbin Liu. ACL 2024.
- *Deciphering the lmpact of Pretraining Data on Large Language Models through Machine Unlearning.* Yang Zhao, Li Du, Xiao Ding, **Kai Xiong**, Zhouhao Sun, Jun Shi, Ting Liu, Bing Qin. ACL 2024 Findings.

## 2023
- *Examining Inter-consistency of Large Language Models Collaboration: An in-depth Analysis via Debate.* **Kai Xiong**, Xiao Ding, Yixin Cao, Ting Liu, Bing Qin. EMNLP 2023 Findings.
- *Improving Cross-task Generalization with Step-by-step Instructions.* Yang Wu, Yanyan Zhao, Zhongyang Li, Bing Qin, **Kai Xiong**. Science China-Information Sciences (IF=7.6).

## 2022
- *ReCo: Reliable Causal Chain Reasoning via Structural Causal Recurrent Neural Networks.* **Kai Xiong**, Xiao Ding, Zhongyang Li, Li Du, Ting Liu, Bing Qin, Yi Zheng, Baoxing Huai. EMNLP 2022.
- *e-CARE: A New Dataset for Exploring Explainable Causal Reasoning.* Li Du, Xiao Ding, **Kai Xiong**, Ting Liu, Bing Qin. ACL 2022.
- *A Graph Enhanced Bert Model for Event Prediction.* Li Du, Xiao Ding, Yue Zhang, **Kai Xiong**, Ting Liu, Bing Qin. ACL 2022 Findings.
- *Enhancing Pretrained Language Models with Structured Commonsense Knowledge for Textual Inference.* Li Du, Xiao Ding, **Kai Xiong**, Ting Liu, Bing Qin. Knowledge-Based Systems (IF=7.6).
- *面向文本推理的知识增强预训练语言模型.* **熊凯**, 杜理, 丁效, 刘挺, 秦兵, 付博. 中文信息学报.

## 2021
- *ExCAR: Event Graph Knowledge Enhanced Explainable Causal Reasoning.* Li Du, Xiao Ding, **Kai Xiong**, Ting Liu, Bing Qin. ACL 2021.
- *Heterogeneous Graph Knowledge Enhanced Stock Market Prediction.* **Kai Xiong**, Xiao Ding, Li Du, Ting Liu, Bing Qin. AI Open (IF=14.8).

# 🎖 Honors and Awards
- *2024* National Scholarship for Doctoral Students
- *2024* Outstanding Student Award of Harbin Institute of Technology
- *2024* Top Reviewer of NeurIPS 2024 (8.6%, 1,304 of 15,160 reviewers)
- *2021* CCKS 2021 Best Chinese Paper Runner-up Award
- *2021* First Prize in the Future Cup AI Academic Contest

# 📖 Educations
- *2015.09 - 2019.06*, Wuhan University, China. Bachelor of Science, Geographic Information Science. 
- *2019.09 - 2021.06*, Harbin Institute of Technology, China. Master of Engineering, Computer Science.
  - Research Center for Social Computing and Information Retrieval (SCIR)
  - Advisor: Prof. Ting Liu
- *2022.07 - 2023.08*, Singapore Management University, Singapore. Research Assistant, School of Computing and Information Science.
  - Advisor: Prof. Yixin Cao
- *2021.09 - Now*, Harbin Institute of Technology, China. Ph.D. Candidate
  - Research Center for Social Computing and Information Retrieval (SCIR)
  - Advisors: Prof. Ting Liu and Xiao Ding

# 💼 Internships
- *2021.10 - 2022.07*, Huawei Cloud, China. AI Algorithm Engineer.
- *2023.12 - 2024.10*, Duxiaoman Financial Technology, China. LLMs Algorithm Engineer.

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 🎓 Academic Services
- Reviewers of Top AI Conferences
  - ACL/ARR: 2021, 2022, 2023, 2024, 2025
  - NeurIPS: 2024, 2025
  - EMNLP/ARR: 2022, 2023
  - KDD: 2024
  - WWW: 2025
  - ICML: 2025

- Reviewers of Other Conferences
  - CCKS
  - NLPCC
  - CCL

