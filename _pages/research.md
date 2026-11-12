---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

My PhD research at Carnegie Mellon University studies how AI can bring engineering knowledge into simulation-based design optimization. The projects below are listed from the most recent.

---

## LLM-assisted optimization for simulation-based redesign

*C. Song, J. J. Michalek, and C. McComb. Under review at ASME Journal of Mechanical Design.*
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

---

## LLMs as complementary agents for dynamic design optimization

*C. Song, J. J. Michalek, and C. McComb. ASME IDETC/CIE 2026.*
**[Abstract](https://idetc.secure-platform.com/a/solicitations/280/sessiongallery/24112/application/194665)**

A design problem can change during optimization, for example when a material price changes. We compared LLM agents with Bayesian optimization and gradient-based methods on a battery pack design problem whose cost changes during the search. The agents were competitive with these methods and more stable after the change.

---

## DesignBench

*W. Xu†, C. Song†, Z. Zdobinski†, Z. Xu†, M. Zhang, and C. McComb. ASME IDETC/CIE 2026.*
**[Abstract](https://idetc.secure-platform.com/a/solicitations/280/sessiongallery/24098/application/195011)** | **[Dataset](https://huggingface.co/datasets/cmudrc/DesignBench)**

DesignBench is a closed-loop benchmark for LLM-based design. It evaluates LLMs with simulator feedback on truss, linkage, and battery electrode design tasks.

---

## Agents4experiments

*C. Song†, S. Bose-Bandyopadhyay†, G. Yu†, P. Pak, F. Ogoke, and A. Barati Farimani. AGENTICS 2026.*
**[Program and abstract](https://www.insticc.org/node/TechnicalProgram/ijcci/2026/presentationDetails/153002)**

With the Barati Farimani group, I fine-tuned LLMs for agents that plan physical experiments.

---

## Graded porosity for thick lithium-ion cathodes

*C. Song. Oral presentation, 250th ECS Meeting, 2026.*
**[Abstract](https://ecs.confex.com/ecs/250/meetingapp.cgi/Paper/222470)**

Thicker electrodes increase battery capacity, but ion transport limits their performance at high discharge rates. Higher porosity improves ion transport and leaves less space for active material. I used surrogate models to optimize how porosity is distributed through the thickness of a thick cathode at a fixed mean porosity.

---

## Before CMU: automatic mechanism design

*C. Song, J. Kim, and Y. Y. Kim. ASME Journal of Mechanical Design, 2025.*
**[Paper](https://doi.org/10.1115/1.4068693)**

At IDeAOcean, I developed topology optimization methods with MMA that synthesize 2D and 3D mechanisms. One of these methods, an obstacle-avoiding spring-connected rigid block model, was published in ASME Journal of Mechanical Design. I also led the development of METHEUS, automatic linkage design software that received a CES 2024 Innovation Award. Details are in the [undergraduate archive](https://cksdml1014.github.io/chanisong/archive/mechanism-design/).

<p style="font-size: 12px; color: gray;">† Equal contribution.</p>
