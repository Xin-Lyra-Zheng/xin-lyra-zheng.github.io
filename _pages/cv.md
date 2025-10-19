---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* **M.S. in Economics and Computation**, Duke University, Durham, US *(Aug 2024 – June 2026)*  
  GPA: 3.9 / 4.0  
  Courses: CS 565 Optimization for Machine Learning (A), ECON 701 Microeconomic Analysis (A), CS 671 Machine Learning (A-), CS 527 Computer Vision (A), CS 590 Theory of Deep Learning (A-), CS 590 Causality, Fairness & Explanation (A), CS 532 Design and Analysis of Algorithms (In progress)

* **B.Econ. in Quantitative Economics (Minor in Computer Science)**,  
  Shanghai University of Finance and Economics, Shanghai, China *(Sept 2020 – June 2024)*  
  GPA: 3.84 / 4.0  |  Average Score: 90.6 / 100  |  Rank: 1 / 179  
  Key courses: Machine Learning (95.1), Operations Research (90), Causal Inference (97.5), Game Theory & Information Economics (93), Mathematical Analysis (93), Advanced Algebra (96), Probability & Statistics (95)


Research Experience
======
* **Combining Alternating Decision Trees with Generalized Additive Models (ADT + GAM)**  
  *Research Project Member — Supervisor: Prof. Cynthia Rudin, Duke University | Jun 2025 – Present*  
  Designed and implemented a Monte Carlo Tree Search (MCTS) framework to integrate ADTs with GAMs for interpretable ML.  
  Developed algorithmic variants (RAVE, UCB tuning) to enhance exploration and model robustness.  
  Conducted systematic experiments on benchmark datasets, analyzing accuracy–interpretability trade-offs.

* **Discovering Novel Gene Pathways via Hypergraph Learning**  
  *Research Project Member — Supervisor: Prof. Can Chen, UNC-Chapel Hill | Jul 2025 – Present*  
  Applied hypergraph neural networks (HGNNs) to model complex gene interactions and generate high-quality embeddings.  
  Developed Greedy Growth and Clustering-based methods for identifying novel gene pathways.  
  Validated rediscovery performance and collaborated with biologists for wet-lab testing.

* **Interpretable Hypergraph Learning for Genome-Scale Metabolic Networks**  
  *Research Project Member — Supervisor: Prof. Chudi Zhong, UNC-Chapel Hill | Oct 2024 – Sep 2025*  
  Proposed HGNAN (Hypergraph Neural Additive Network) for interpretable hypergraph learning.  
  Applied HGNAN to GEMs for missing reaction prediction, achieving state-of-the-art performance with interpretable patterns.

* **Misinformation Study via Multi-Objective Direct Preference Optimization (MODPO)**  
  *Research Project Member — Supervisor: Prof. Tong Guo, Duke University | Aug 2025 – Present*  
  Applied MODPO to fine-tune large language models balancing persuasiveness and authenticity in news generation.  
  Led human feedback collection on Prolific and fine-tuned LLaMA-7B with multi-objective loss.

* **Large Language Models Intern**, Shanshu Technology (Shanghai) | Feb 2024 – Jul 2024  
  Co-led training of large models for operations research problem modeling and solution generation.  
  Created 100k+ synthetic samples via automated data generation and fine-tuned LLaMA-3-8B and DeepSeek variants.  


Skills
======
* Python (pandas, PyTorch, NumPy, scikit-learn, OpenAI API, LoRA finetuning)  
* JAX / PyTorch for interpretable ML and GAM modeling  
* Stata / R / SQL for empirical and econometric analysis  
* Git / VS Code / Slurm / HPC workflow management  
* LaTeX / Beamer / Markdown for academic writing


Publications
======
<ul>{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>
