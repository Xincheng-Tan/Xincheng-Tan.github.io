---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a second-year master's student in the [School of Software Technology](http://www.cst.zju.edu.cn/), [Zhejiang University](https://www.zju.edu.cn/), working at the [State Key Lab of CAD&CG](http://www.cad.zju.edu.cn/). I am advised by [Prof. Minfeng Zhu](https://minfengzhu.github.io/) in the [Visual Analytics and Intelligence Group](https://zjuvai.cn/). Before that, I received my bachelor's degree in Computer Science and Technology from [Southwest Jiaotong University](https://www.swjtu.edu.cn/) in 2025.

My research interests include **post-training and agentic RL for LLM / VLM agents**, **neuro-symbolic planning**, and **agent evaluation and failure attribution**.

Research
======
**NSDL: Neuro-Symbolic Division of Labor for Multi-Robot Task Planning**  
**Xincheng Tan**, Ke Wang, Minfeng Zhu<sup>†</sup>, Shimin Di<sup>†</sup>  
*Under review at ICRA 2027*

Planning for a heterogeneous robot team involves two kinds of decisions: some must be judged from the scene (which goals are already met, which robot does what), and others can be computed once those are fixed (prerequisite actions, handoffs, timing). In NSDL, a small vision-language model learns the first kind and writes its judgments as a plan sketch; a deterministic solver expands the sketch into an executable joint plan. The model calls a detector and the solver as tools and is trained with SFT followed by multi-turn RL with the solver in the loop. We also build LOCUS-Bench, which grades the two kinds of difficulty separately. The 7B model reaches 97.0% out-of-distribution accuracy on VIKI-L2.

**Planner-in-the-loop LLM agents** (first author, in preparation)

Ongoing work on what a classical planner can fix in LLM agents that act over long horizons under partial observability, based on a failure attribution of lost episodes and controlled comparisons across environments and models.

Education
======
- **M.S. in Software Engineering**, Zhejiang University, 2025.09 – 2028.06 (expected)  
  State Key Lab of CAD&CG; admitted by recommendation without examination. Average score: 91.4 / 100.
- **B.Eng. in Computer Science and Technology**, Southwest Jiaotong University, 2021.09 – 2025.06  
  GPA: 3.63 / 4.0; average score: 89.36 / 100; top 5% in major.

Honors
======
- Five-Merit Graduate Student, Zhejiang University (2025–2026)
- Outstanding Graduate of Sichuan Province (2025)
- National Scholarship (2022–2023)
- Merit Student Model, Southwest Jiaotong University (2021–2022)

Contact
======
- Email: [xincheng.tan.sc@gmail.com](mailto:xincheng.tan.sc@gmail.com) / [xincheng.tan@zju.edu.cn](mailto:xincheng.tan@zju.edu.cn)
- GitHub: [Xincheng-Tan](https://github.com/Xincheng-Tan)
