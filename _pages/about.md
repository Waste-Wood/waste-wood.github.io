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
- <u>**Debate-aware Learning Makes LLMs Genuine Debaters.**</u> Yufei Zhang\*, **Kai Xiong**\*, Yuxiong Yan, Bibo Cai, Xiao Ding, Bing Qin, Ting Liu. <span style="color:red">**EMNLP 2026**</span>
- <u>**IALR: Instance-Adaptive Legal Rubric Supervision for Legal Judgment Prediction.**</u> Jianbai Zhao, Bibo Cai, Xiao Ding, Xinran Dai, Yu Bao, Bo Xin, **Kai Xiong**, Bing Qin, Ting Liu. <span style="color:red">**Findings of EMNLP 2026**</span>
- <u>ARM: Role-Conditioned Neuron Transplantation for Training-Free Generalist LLM Agent Merging.</u> Zhuoka Feng, Kang Chen, Sihan Zhao, **Kai Xiong**, Yaoning Wang, Minshen Yu, Junjie Nian, Changyi Xiao, Yixin Cao, Yugang Jiang. <span style="color:red">**EMNLP 2026**</span>
- <u>**Diagnosing and Remedying Knowledge Deficiencies in LLMs via Label-free Curricular Meaningful Learning.**</u> **Kai Xiong**, Xiao Ding, Li Du, Jiahao Ying, Ting Liu, Bing Qin, Yixin Cao. <span style="color:red">**ICLR 2026**</span>
- <u>**Consolidation or Adaptation? PRISM: Disentangling SFT and RL Data via Gradient Concentration.**</u> Yang Zhao, Yangou Ouyang, Xiao Ding, Hepeng Wang, Bibo Cai, **Kai Xiong**, Jinglong Gao, Zhouhao Sun, Li Du, Bing Qin, Ting Liu. <span style="color:red">**ACL 2026**</span>
- <u>**Maestro: Meta-learning adaptive estimation of scalarization trade-offs for reward optimization.**</u> Yang Zhao, Hepeng Wang, Xiao Ding, Yangou Ouyang, Bibo Cai, **Kai Xiong**, Jinglong Gao, Zhouhao Sun, Li Du, Bing Qin, Ting Liu. <span style="color:red">**ACL 2026**</span>
- <u>**Is EEG-to-Text Feasible in Real-World Scenarios? An In-Depth Analysis Using a Neuropsychology-Inspired Benchmark.**</u> Zihan Zhang, Yu Bao, Xiao Ding, Tianyi Jiang, **Kai Xiong**. <span style="color:red">**ACL 2026**</span>
- <u>**MDC-Bench: A Multidisciplinary Causal Benchmark Based on Causal Structures for Evaluating Large Language Models.**</u> Peng Wang, Yuxiong Yan, Xiao Ding, **Kai Xiong**, Bibo Cai, Chao Peng, Yutai Hou, Dandan Tu, Bing Qin, Ting Liu. <span style="color:red">**Findings of ACL 2026**</span>
- <u>**Optimizing Automated Jailbreak Attacks on Large Language Models via Experience Accumulation.**</u> Yuxin Zhou, Xiao Ding, Yijia Meng, Tianle Chang, Jinglong Gao, Zihan Zhang, **Kai Xiong**, Qi Shi. <span style="color:red">**ICASSP 2026**</span>
- <u>**Proactive Safety Deliberation: Guiding Large Reasoning Models with Distilled Principles.**</u> Yuxin Zhou, Xiao Ding, Qi Shi, Ye He, **Kai Xiong**, Yijia Meng, Tianle Chang, Jinglong Gao. <span style="color:red">**ICASSP 2026**</span>
- <u>**Do LLMs Signal When They’re Right? Evidence from Neuron Agreement.**</u> Kang Chen, Yaoning Wang, **Kai Xiong**, Zhuoka Feng, Yu Minshen, Wenhe Sun, Haotian Chen, Yixin Cao. <span style="color:red">**ICML 2026 (Spotlight)**</span>

## 2025
- <u>**Think Straight or Think Again? Continual Joint Learning of Deduction, Abduction, and Induction.**</u> **Kai Xiong**, Xiao Ding, Yixin Cao, Yang Zhao, Bing Qin, Ting Liu. <span style="color:red">**Neural Networks (IF=6.3)**</span>
- <u>**Com$^2$: A Causal-Guided Benchmark for Exploring Complex Commonsense Reasoning in Large Language Models.**</u> **Kai Xiong**, Xiao Ding, Yixin Cao, Yuxiong Yan, Li Du, Yufei Zhang, Jinglong Gao, Jiaqian Liu, Bing Qin, Ting Liu. <span style="color:red">**ACL 2025**</span>
- <u>**Supervised Fine-Tuning Achieve Rapid Task Adaption Via Alternating Attention Head Activation Patterns.**</u> Yang Zhao, Li Du, Xiao Ding, **Kai Xiong**, Ting Liu, Bing Qin. <span style="color:red">**ACL 2025**</span>
- <u>**Beyond Similarity: A Gradient-based Graph Method for Instruction Tuning Data Selection.**</u> Yang Zhao, Li Du, Xiao Ding, YangouOuyang, Hepeng Wang, **Kai Xiong**, Jinglong Gao, Zhouhao Sun, Dongliang Xu, Qing Yang, Dongchen Li, Bing Qin, Ting Liu. <span style="color:red">**ACL 2025**</span>
- <u>**Natural Logic at the Core: Dynamic Rewards for Entailment Tree Generation.**</u> Jihao Shi, Xiao Ding, **Kai Xiong**, Hengwei Zhao, Bing Qin, Ting Liu. <span style="color:red">**Findings of ACL 2025**</span>
- <u>**UFO-RL: Uncertainty-Focused Optimization for Efficient Reinforcement Learning Data Selection.**</u> Yang Zhao, **Kai Xiong**, Xiao Ding, Li Du, Yangou Ouyang, Zhouhao Sun, Jiannan Guan, Wenbin Zhang, Bin Liu, Dong Hu, Bing Qin, Ting Liu. <span style="color:red">**NeurIPS 2025**</span>
- <u>**Necessary and sufficient knowledge enhanced collaborative logical reasoning in LLMs.**</u> Peng Wang, Xiao Ding, **Kai Xiong**, Bing Qin, Ting Liu. <span style="color:red">**Neural Networks (IF=6.3)**</span>

## 2024
- <u>**Meaningful Learning: Enhancing Abstract Reasoning in Large Language Models via Generic Fact Guidance.**</u> **Kai Xiong**, Xiao Ding, Ting Liu, Bing Qin, Dongliang Xu, Qing Yang, Hongtao Liu, Yixin Cao. <span style="color:red">**NeurIPS 2024**</span>
- <u>**Intuitive or Dependent? Investigating LLMs' Behavior Style to Conflicting Prompts.**</u> Jiahao Ying, Yixin Cao, **Kai Xiong**, Yidong He, Long Cui, Yongbin Liu. <span style="color:red">**ACL 2024**</span>
- <u>**Deciphering the lmpact of Pretraining Data on Large Language Models through Machine Unlearning.**</u> Yang Zhao, Li Du, Xiao Ding, **Kai Xiong**, Zhouhao Sun, Jun Shi, Ting Liu, Bing Qin. <span style="color:red">**Findings of ACL 2024**</span>

## 2023
- <u>**Examining Inter-consistency of Large Language Models Collaboration: An in-depth Analysis via Debate.**</u> **Kai Xiong**, Xiao Ding, Yixin Cao, Ting Liu, Bing Qin. <span style="color:red">**Findings of EMNLP 2023**</span>
- <u>**Improving Cross-task Generalization with Step-by-step Instructions.**</u> Yang Wu, Yanyan Zhao, Zhongyang Li, Bing Qin, **Kai Xiong**. <span style="color:red">**Science China-Information Sciences (IF=7.6)**</span>

## 2022
- <u>**ReCo: Reliable Causal Chain Reasoning via Structural Causal Recurrent Neural Networks.**</u> **Kai Xiong**, Xiao Ding, Zhongyang Li, Li Du, Ting Liu, Bing Qin, Yi Zheng, Baoxing Huai. <span style="color:red">**EMNLP 2022**</span>
- <u>**e-CARE: A New Dataset for Exploring Explainable Causal Reasoning.**</u> Li Du, Xiao Ding, **Kai Xiong**, Ting Liu, Bing Qin. <span style="color:red">**ACL 2022**</span>
- <u>**A Graph Enhanced Bert Model for Event Prediction.**</u> Li Du, Xiao Ding, Yue Zhang, **Kai Xiong**, Ting Liu, Bing Qin. <span style="color:red">**Findings of ACL 2022**</span>
- <u>**Enhancing Pretrained Language Models with Structured Commonsense Knowledge for Textual Inference.**</u> Li Du, Xiao Ding, **Kai Xiong**, Ting Liu, Bing Qin. <span style="color:red">**Knowledge-Based Systems (IF=7.6)**</span>
- <u>**面向文本推理的知识增强预训练语言模型.**</u> **熊凯**, 杜理, 丁效, 刘挺, 秦兵, 付博. <span style="color:red">**中文信息学报**</span>

## 2021
- <u>**ExCAR: Event Graph Knowledge Enhanced Explainable Causal Reasoning.**</u> Li Du, Xiao Ding, **Kai Xiong**, Ting Liu, Bing Qin. <span style="color:red">**ACL 2021**</span>
- <u>**Heterogeneous Graph Knowledge Enhanced Stock Market Prediction.**</u> **Kai Xiong**, Xiao Ding, Li Du, Ting Liu, Bing Qin. <span style="color:red">**AI Open (IF=14.8)**</span>

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

