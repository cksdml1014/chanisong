---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% capture tag %}display:inline-block; font-size:0.75em; padding:1px 9px; margin:0 4px 6px 0; border:1px solid #bbb; border-radius:10px; color:#555;{% endcapture %}

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
  <p style="font-size: 12px; color: gray;">Overview of the study. Conventional reoptimization and LLM-assisted redesign use the same BatPaC battery simulator.</p>
</div>

<div style="text-align: center; margin: 1em 0;">
  <img src="https://cksdml1014.github.io/chanisong/images/research/wafer_discovery.png" alt="Feasible discovery over accepted simulator evaluations in four redesign scenarios" style="width: 100%; max-width: 560px;">
  <p style="font-size: 12px; color: gray;">Feasible discovery over accepted simulator evaluations in the four redesign scenarios, S1 to S4.</p>
</div>

## LLMs as complementary agents for dynamic design optimization

<span style="{{ tag }}">LLM agents</span><span style="{{ tag }}">Design optimization</span><span style="{{ tag }}">Battery design</span>

*C. Song, J. J. Michalek, and C. McComb. ASME IDETC/CIE 2026.*
**[Abstract](https://idetc.secure-platform.com/a/solicitations/280/sessiongallery/24112/application/194665)**

A design problem can change during optimization, for example when a material price changes. We compared LLM agents with Bayesian optimization and gradient-based methods on a battery pack design problem whose cost changes during the search. The agents were competitive with these methods and more stable after the change.

## DesignBench

<span style="{{ tag }}">Benchmarks</span><span style="{{ tag }}">LLM agents</span>

*W. Xu†, C. Song†, Z. Zdobinski†, Z. Xu†, M. Zhang, and C. McComb. ASME IDETC/CIE 2026.*
**[Abstract](https://idetc.secure-platform.com/a/solicitations/280/sessiongallery/24098/application/195011)** | **[Dataset](https://huggingface.co/datasets/cmudrc/DesignBench)**

DesignBench is a closed-loop benchmark for LLM-based design. It evaluates LLMs with simulator feedback on truss, linkage, and battery electrode design tasks.

## Agents4experiments

<span style="{{ tag }}">LLM agents</span><span style="{{ tag }}">LLM fine-tuning</span>

*C. Song†, S. Bose-Bandyopadhyay†, G. Yu†, P. Pak, F. Ogoke, and A. Barati Farimani. AGENTICS 2026.*
**[Program and abstract](https://www.insticc.org/node/TechnicalProgram/ijcci/2026/presentationDetails/153002)**

With the Barati Farimani group, I fine-tuned LLMs for agents that plan physical experiments.

---

# Battery design optimization

## Graded porosity for thick lithium-ion cathodes

<span style="{{ tag }}">Battery design</span><span style="{{ tag }}">Design optimization</span>

*C. Song. Oral presentation, 250th ECS Meeting, 2026.*
**[Abstract](https://ecs.confex.com/ecs/250/meetingapp.cgi/Paper/222470)**

Thicker electrodes increase battery capacity, but ion transport limits their performance at high discharge rates. Higher porosity improves ion transport and leaves less space for active material. I used surrogate models to optimize how porosity is distributed through the thickness of a thick cathode at a fixed mean porosity.

---

# Automatic mechanism design at IDeAOcean

From 2023 to 2025, I worked as a Senior Researcher at [IDeAOcean](https://ideaocean.ai), a startup that grew out of Prof. Yoon Young Kim's IDeALab at Seoul National University. IDeAOcean develops automatic mechanism design technology, in which topology optimization determines both the structure and the dimensions of a linkage mechanism.

## METHEUS: automatic linkage design software

<span style="{{ tag }}">Mechanism design</span><span style="{{ tag }}">Design automation</span>

<div style="float: right; width: 220px; margin: 0 0 10px 16px;">
  <img src="https://cksdml1014.github.io/chanisong/images/metheus.png" alt="METHEUS v1.0" style="width: 100%;">
  <p style="font-size: 12px; color: gray;">METHEUS v1.0, CES 2024 Innovation Award.</p>
</div>

I led the development of METHEUS, software that generates linkage mechanisms for a target motion. METHEUS received a CES 2024 Innovation Award. My work included building large-scale linkage datasets with end-effector paths, manipulability, and kinetostatic analysis. **[METHEUS website](https://ideaocean.ai/metheus/)**

<div style="clear: both;"></div>

## Industry projects with Hyundai Motor and HD Hyundai

<span style="{{ tag }}">Mechanism design</span><span style="{{ tag }}">Topology optimization</span>

I applied automatic mechanism design to industry problems. For Hyundai Motor Company, I designed a new linkage mechanism for a next-generation high-performance hydrogen-hybrid concept car using a 3D extension of the method. With Hyundai Motor and HD Hyundai, I developed three new mechanisms for next-generation automobiles and wheel loaders. The industry-sponsored projects with Hyundai Motor, HD Hyundai, and Samsung Electronics totaled over $100,000 in funding. In 2024, I also taught automatic mechanism design to engineers at HD Hyundai and Hyundai Motor. Most project details are under NDA.

<div style="text-align: center; margin: 1em 0;">
  <video width="560" style="max-width: 100%;" controls>
    <source src="https://cksdml1014.github.io/chanisong/images/3djbm_example.mp4" type="video/mp4">
  </video>
  <p style="font-size: 12px; color: gray;">A 3D mechanism synthesized with the 3D extension of the joint-element block model.</p>
</div>

## Mechanism synthesis with obstacle avoidance

<span style="{{ tag }}">Mechanism design</span><span style="{{ tag }}">Topology optimization</span>

*C. Song, J. Kim, and Y. Y. Kim. ASME Journal of Mechanical Design, 2025.*
**[Paper](https://doi.org/10.1115/1.4068693)**

Real mechanisms must move around surrounding parts. I developed an obstacle-avoiding spring-connected rigid block model, which uses MMA-based topology optimization to determine both the topology and the dimensions of a planar linkage that traces a target path without colliding with obstacles. I also extended the joint-element block model from 2D to 3D spatial mechanisms, and this work is in preparation for a journal.

More background on these methods is in the [undergraduate archive](https://cksdml1014.github.io/chanisong/archive/mechanism-design/).

<p style="font-size: 12px; color: gray;">† Equal contribution.</p>
