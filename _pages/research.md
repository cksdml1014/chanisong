---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% capture tag %}display:inline-block; font-size:0.75em; padding:1px 9px; margin:0 4px 6px 0; border:1px solid #bbb; border-radius:10px; color:#555;{% endcapture %}
{% capture cap %}font-size:12px; color:gray; margin-top:4px;{% endcapture %}

My research brings engineering knowledge into design optimization. At Carnegie Mellon University, I study how LLMs can work with simulators and numerical optimizers. Before my PhD, I developed automatic mechanism design methods at IDeAOcean and applied them to industry projects.

- [LLMs and simulation-based design optimization](#llms-and-simulation-based-design-optimization) (CMU, 2025 to present)
- [Battery design optimization](#battery-design-optimization) (CMU, 2025 to present)
- [Automatic mechanism design at IDeAOcean](#automatic-mechanism-design-at-ideaocean) (2023 to 2025)

---

# LLMs and simulation-based design optimization

## LLM-assisted optimization for simulation-based redesign

<span style="{{ tag }}">LLM agents</span><span style="{{ tag }}">Black-box optimization</span><span style="{{ tag }}">Battery design</span>

*C. Song, J. J. Michalek, and C. McComb. Under review at ASME Journal of Mechanical Design, 2026.*
**[arXiv](https://arxiv.org/abs/2610.39275)** | **[Code](https://github.com/Chani-song/WAFER)**

Engineers often adapt an existing design when a requirement changes. This adaptation is called redesign, and it usually means rerunning a numerical optimizer with an expensive simulator. In this project, we studied how LLMs can bring engineering knowledge into this redesign loop. We compared three ways of using an LLM, namely variable fixing, warm starting, and a ReAct agent, with conventional reoptimization on an EV battery pack redesign problem with four scenarios. LLM guidance matched the feasible-design discovery of standard optimizers with 80% fewer simulator calls and tripled the rate of runs that reached near-optimal designs.

<div style="text-align: center; margin: 1em 0;">
  <img src="https://cksdml1014.github.io/chanisong/images/research/wafer_framework.png" alt="Overview of conventional reoptimization and LLM-assisted redesign" style="width: 100%; max-width: 760px;">
  <p style="{{ cap }}">Overview of the study. Conventional reoptimization and LLM-assisted redesign use the same BatPaC battery simulator.</p>
</div>

<div style="text-align: center; margin: 1em 0;">
  <img src="https://cksdml1014.github.io/chanisong/images/research/wafer_discovery.png" alt="Feasible discovery over accepted simulator evaluations in four redesign scenarios" style="width: 100%; max-width: 560px;">
  <p style="{{ cap }}">Feasible discovery over accepted simulator evaluations in the four redesign scenarios, S1 to S4.</p>
</div>

## LLMs as complementary agents for dynamic design optimization

<span style="{{ tag }}">LLM agents</span><span style="{{ tag }}">Black-box optimization</span><span style="{{ tag }}">Battery design</span>

*C. Song, J. J. Michalek, and C. McComb. ASME IDETC/CIE 2026, Houston, August 2026.*
**[Abstract](https://idetc.secure-platform.com/a/solicitations/280/sessiongallery/24112/application/194665)**

A design problem can change while it is being optimized, for example when a material price changes. Numerical solvers have no way to use what an engineer knows about such a change, whereas LLMs can read it. We compared three levels of LLM integration on a lithium-ion battery pack design problem in the BatPaC simulator: one-shot generation, feedback-driven search, and hybrid warm-start optimization. We then introduced a material price shock during optimization. Feedback-driven LLM search was competitive with Bayesian optimization and gradient methods at finding feasible designs and improving the objective, especially after the shock. Hybrid agents that give LLM-generated starting points to a numerical optimizer also performed strongly.

<div style="text-align: center; margin: 1em 0;">
  <img src="https://cksdml1014.github.io/chanisong/images/research/dynamic_framework.png" alt="Components of dynamic optimization and the three LLM integration frameworks" style="width: 100%; max-width: 760px;">
  <p style="{{ cap }}">Components of dynamic optimization, left, and the three LLM integration frameworks, right.</p>
</div>

<div style="text-align: center; margin: 1em 0;">
  <img src="https://cksdml1014.github.io/chanisong/images/photos/idetc2026_talk.jpg" alt="Presenting at ASME IDETC/CIE 2026" style="width: 100%; max-width: 520px;">
  <p style="{{ cap }}">Presenting at ASME IDETC/CIE 2026 in Houston, August 25, 2026.</p>
</div>

## DesignBench

<span style="{{ tag }}">Benchmarks</span><span style="{{ tag }}">LLM agents</span>

*W. Xu†, C. Song†, Z. Zdobinski†, Z. Xu†, M. Zhang, and C. McComb. ASME IDETC/CIE 2026, Houston, August 2026.*
**[Abstract](https://idetc.secure-platform.com/a/solicitations/280/sessiongallery/24098/application/195011)** | **[Dataset](https://huggingface.co/datasets/cmudrc/DesignBench)**

Most LLM benchmarks test one-shot answers, but designers work in a loop. They read simulation feedback, find the cause of a failure, and revise the design over many steps. DesignBench tests this closed-loop design reasoning in three domains: truss optimization, planar linkage synthesis, and battery electrode design. Each domain has a deterministic simulator that returns feedback after every action. Design is represented as search over grammar-constrained modification trees, which makes the evaluation reproducible and also produces training traces for fine-tuning. Frontier models improved designs under feedback, but unevenly. They preferred small parameter edits to higher-leverage configuration changes, gained little from long-context reasoning, and depended strongly on how the feedback was structured.

<div style="text-align: center; margin: 1em 0;">
  <img src="https://cksdml1014.github.io/chanisong/images/research/designbench_truss.png" alt="The truss benchmark in DesignBench" style="width: 100%; max-width: 760px;">
  <p style="{{ cap }}">The truss benchmark: a planar Pratt truss, its structural analysis with factor-of-safety constraints, and the design modifications available to the model.</p>
</div>

<div style="text-align: center; margin: 1em 0;">
  <img src="https://cksdml1014.github.io/chanisong/images/photos/idetc2026_designbench.jpg" alt="Presenting DesignBench at ASME IDETC/CIE 2026" style="width: 100%; max-width: 420px;">
  <p style="{{ cap }}">Presenting DesignBench at ASME IDETC/CIE 2026.</p>
</div>

## Agents4experiments

<span style="{{ tag }}">LLM agents</span><span style="{{ tag }}">LLM fine-tuning</span>

*C. Song†, S. Bose-Bandyopadhyay†, G. Yu†, P. Pak, F. Ogoke, and A. Barati Farimani. AGENTICS 2026, online, October 2026.*
**[Poster](https://cksdml1014.github.io/chanisong/files/Agents4experiments_AGENTICS2026_poster.pdf)** | **[Program and abstract](https://www.insticc.org/node/TechnicalProgram/ijcci/2026/presentationDetails/153002)**

A physical experiment has to work with the equipment and materials on hand. With the Barati Farimani group, we asked whether LLM agents can design such experiments. We tested prompting, retrieval-augmented generation, and fine-tuning with SFT and DPO under a fixed bill of materials, and scored each plan with an 11-criterion design-of-experiments rubric. Model choice mattered more than any technique, and irrelevant retrieved context harmed the plans. All systems struggled with iteration, interaction, and blocking.

<div style="text-align: center; margin: 1em 0;">
  <img src="https://cksdml1014.github.io/chanisong/images/research/agentics_results.png" alt="Design-of-experiments rubric scores by method" style="width: 100%; max-width: 520px;">
  <p style="{{ cap }}">Total design-of-experiments rubric scores for each model and method.</p>
</div>

---

# Battery design optimization

## Graded porosity for thick lithium-ion cathodes

<span style="{{ tag }}">Battery design</span><span style="{{ tag }}">Design optimization</span>

*C. Song. Oral presentation, 250th ECS Meeting, Calgary, October 2026.*
**[Abstract](https://ecs.confex.com/ecs/250/meetingapp.cgi/Paper/222470)**

Thicker electrodes increase battery capacity, but ion transport limits their performance at high discharge rates. Higher porosity improves ion transport and leaves less space for active material. I optimized the porosity at 10 points through the thickness of a thick cathode at a fixed mean porosity. The cell was simulated with the Doyle-Fuller-Newman model in PyBaMM, and I compared Bayesian optimization with a neural network surrogate trained on precomputed simulations. The best designs place more pores near the separator, and this difference is larger at 5C than at 3C.

<div style="text-align: center; margin: 1em 0;">
  <img src="https://cksdml1014.github.io/chanisong/images/research/ecs_porosity_profiles.png" alt="Cathode porosity profiles" style="width: 100%; max-width: 620px;">
  <p style="{{ cap }}">The design variable is the porosity at 10 points through the cathode. Four example profiles are shown.</p>
</div>

<div style="display: flex; flex-wrap: wrap; gap: 16px; justify-content: center; margin: 1em 0;">
  <div style="flex: 1 1 260px; max-width: 420px; text-align: center;">
    <img src="https://cksdml1014.github.io/chanisong/images/research/ecs_best_profile.png" alt="Best porosity profiles at 3C and 5C" style="width: 100%;">
    <p style="{{ cap }}">Best porosity profiles at 3C and 5C. The dashed line is the fixed mean porosity.</p>
  </div>
  <div style="flex: 1 1 260px; max-width: 420px; text-align: center;">
    <img src="https://cksdml1014.github.io/chanisong/images/photos/ecs250_talk.jpg" alt="Presenting at the 250th ECS Meeting" style="width: 100%;">
    <p style="{{ cap }}">250th ECS Meeting in Calgary, October 27, 2026.</p>
  </div>
</div>

---

# Automatic mechanism design at IDeAOcean

From 2023 to 2025, I worked as a Senior Researcher at [IDeAOcean](https://ideaocean.ai), a startup spun off from Prof. Yoon Young Kim's IDeALab at Seoul National University. IDeAOcean develops automatic mechanism design technology, in which topology optimization determines both the structure and the dimensions of a linkage mechanism.

## METHEUS: automatic linkage design software

<span style="{{ tag }}">Mechanism design</span><span style="{{ tag }}">Design automation</span>

<div style="float: right; width: 220px; margin: 0 0 10px 16px;">
  <img src="https://cksdml1014.github.io/chanisong/images/metheus.png" alt="METHEUS v1.0" style="width: 100%;">
  <p style="{{ cap }}">METHEUS v1.0, CES 2024 Innovation Award.</p>
</div>

I led the development of METHEUS, software that generates linkage mechanisms for a target motion. METHEUS received a CES 2024 Innovation Award. My work included building large-scale linkage datasets with end-effector paths, manipulability, and kinetostatic analysis. **[METHEUS](https://metheus.ai/)** | **[IDeAOcean](https://ideaocean.ai/)**

<div style="clear: both;"></div>

## Industry projects with Hyundai Motor and HD Hyundai

<span style="{{ tag }}">Mechanism design</span><span style="{{ tag }}">Topology optimization</span>

I applied automatic mechanism design to industry problems. For Hyundai Motor Company, I designed a new linkage mechanism for a next-generation high-performance hydrogen-hybrid concept car using a 3D extension of the method. With Hyundai Motor and HD Hyundai, I developed three new mechanisms for next-generation automobiles and wheel loaders. The industry-sponsored projects with Hyundai Motor, HD Hyundai, and Samsung Electronics totaled over $100,000 in funding. In 2024, I also taught automatic mechanism design to engineers at HD Hyundai and Hyundai Motor. Most project details are under NDA.

<div style="text-align: center; margin: 1em 0;">
  <video width="560" style="max-width: 100%;" controls>
    <source src="https://cksdml1014.github.io/chanisong/images/3djbm_example.mp4" type="video/mp4">
  </video>
  <p style="{{ cap }}">A 3D mechanism synthesized with the 3D extension of the joint-element block model.</p>
</div>

## Mechanism synthesis with obstacle avoidance

<span style="{{ tag }}">Mechanism design</span><span style="{{ tag }}">Topology optimization</span>

*C. Song, J. Kim, and Y. Y. Kim. ASME Journal of Mechanical Design, 2025.*
**[Paper](https://doi.org/10.1115/1.4068693)** | **[WCSMO 16 slides](https://cksdml1014.github.io/chanisong/files/WCSMO16_ChanEuiSong_slides.pdf)**

Real mechanisms must move around surrounding parts. Previous rigid block methods could synthesize a linkage that traces a target path, but the resulting links could collide with obstacles. I developed an obstacle-avoiding formulation of the spring-connected rigid block model, which uses MMA-based topology optimization to determine both the topology and the dimensions of a planar linkage that traces the path without colliding with obstacles. I also extended the joint-element block model from 2D to 3D spatial mechanisms, and this work is in preparation for a journal.

<div style="text-align: center; margin: 1em 0;">
  <img src="https://cksdml1014.github.io/chanisong/images/research/jmd_obstacle.png" alt="Mechanism synthesis without and with obstacle avoidance" style="width: 100%; max-width: 680px;">
  <p style="{{ cap }}">Mechanisms synthesized with previous methods, top, collide with obstacles. The obstacle avoidance formulation, bottom, produces collision-free mechanisms.</p>
</div>

<div style="text-align: center; margin: 1em 0;">
  <img src="https://cksdml1014.github.io/chanisong/images/photos/wcsmo16_talk.jpg" alt="Presenting at WCSMO 16" style="width: 100%; max-width: 420px;">
  <p style="{{ cap }}">Presenting this work at the 16th World Congress of Structural and Multidisciplinary Optimization, 2025.</p>
</div>

More background on these methods is in the [undergraduate archive](https://cksdml1014.github.io/chanisong/archive/mechanism-design/).

<p style="{{ cap }}">† Equal contribution.</p>
