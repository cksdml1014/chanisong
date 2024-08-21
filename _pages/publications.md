---
layout: archive
title: "Publications and Manuscripts"
permalink: /publications/
author_profile: true
---

Given that Autonomous Mechanism Design Technology is an emerging and relatively unfamiliar field even among researchers in related areas, here's a brief explanation of the technology, followed by a summary of my contributions. My **publications and manuscripts in preparation** can be found at the bottom of the page.

---
## Personal Contributions to Autonomous Mechanism Design Technology

At *IDeAOcean*, which evolved from *IDeALab* under Prof. Yoon Young Kim, I have played a central role in advancing Autonomous Mechanism Design Technology. My contributions include:

1) **Extending SBM and JBM to 3D Mechanisms**
  - Developed novel methods to expand the 2D frameworks of SBM and JBM into 3D applications.
  - Created mechanisms using this methodology, some of which are currently under patent processes, and the methodology itself is being prepared for publication in a <span style="color: #4a90e2;">**journal**</span>.

2) **Applying SBM to Solve Special Problems**
  - Utilized SBM to develop a methodology for designing linkage systems in complex environments and is preparing for publication in a <span style="color: #4a90e2;">**journal**</span>.
  - Problem originality is critical, and details will be disclosed after journal acceptance.
  - **Private Zoom meetings** are available to discuss the target problems, methods, results, and potential impact.

3) **Collaborations and Industrial Applications**
  - Worked closely with **Hyundai Motors, HD Hyundai**, and other leading firms.
  - Generated **3 innovative mechanisms** for various applications in next-generation automobiles and wheel loaders, using SBM and JBM.
  - Future collaborations include partnerships with *Honda* and leading robotics companies requiring advanced mechanism designs.

4) **Developing METHEUS: AI-driven Mechanism Design Solution**
  - Awarded the <span style="color: #4a90e2;">**CES 2024 Innovation Award**</span> for its ability to autonomously generate mechanisms tailored to various needs.
  - More information can be found in the "Project" Section.

5) **Optimization and Computing Techniques**
  - Applied parallel computing to speed up mechanism synthesis.
  - Utilized size optimization algorithms, such as NSGA-II, to enhance the efficiency of mechanism designs.


**NDA Compliance**: While much of the research remains under NDA (Non-Disclosure Agreement), the advancements achieved through this work are reflected in several **manuscripts** and **patents** currently in preparation.

---
### Emphasis on Zoom Meetings

Due to the sensitive nature of my ongoing research projects, I offer <span style="color: #e57373;">**private Zoom meetings**</span> to discuss the research in greater detail. During these meetings, I can:

- Share mechanism synthesis videos and research materials that are protected by NDA, including the 3D Mechanisms research currently being prepared for submission.
- Discuss detailed problem definitions, methodologies, results, and the potential impact of the new methods developed using SBM, which are also in preparation for submission.
- Provide in-depth explanations of the techniques, outcomes, and potential impact of Autonomous Mechanism Design Technology.

It is recommended that I **record these meetings for personal reference** to ensure clarity when presenting my research processes and results. Please feel free to [**contact me**](<mailto:cksdml1014@gmail.com>) to schedule a discussion.


<hr style="border: 2px solid black;">

<details>
  <summary style="font-size: 1.3em; font-weight: bold;">Backgrounds on Autonomous Mechanism Design Technology: SBM and JBM Models </summary>  

<p>The <strong>Autonomous Mechanism Design Technology</strong>, developed using the <strong>SBM (Spring-connected Block Model)</strong> and <strong>JBM (Joint-element Block Model)</strong> frameworks, represents a revolutionary approach to mechanism synthesis. This technology autonomously generates complex linkage mechanisms that achieve specific tasks and meet performance requirements across various applications. Specifically, it synthesizes <strong>1-DOF linkage mechanisms that follow desired paths</strong> by automatically determining <strong>both the topology and geometry</strong> of the mechanism. This is achieved through appropriate optimization problem formulations and precise modeling of the spring-block systems.</p>

<h2>What are SBM and JBM?</h2>

<div style="display: flex; justify-content: space-between;">
    <div style="width: 48%; display: flex; flex-direction: column; justify-content: space-between;">
        <img src="https://cksdml1014.github.io/chanisong/images/SBM2.png" alt="SBM2" style="width: 100%;">
        <p style="font-size: 12px; text-align: center; margin-top: auto;">SBM, first proposed by Prof. Yoon Young Kim (JMD, 2007), enables the synthesis of 2D Linkage Mechanisms comprised of revolute joints.</p>
    </div>
    <div style="width: 48%; display: flex; flex-direction: column; justify-content: space-between;">
        <img src="https://cksdml1014.github.io/chanisong/images/JBM1.png" alt="JBM1" style="width: 100%;">
        <p style="font-size: 12px; text-align: center; margin-top: auto;">JBM, proposed by Kang and Kim (SMO, 2018), extends SBM by incorporating prismatic joints into 2D Linkage Mechanisms.</p>
    </div>
</div>

<p><strong style="font-size: 1.2em;">SBM (Spring-connected Block Model):</strong></p>
<ul>
  <li>Represents mechanical systems using rigid blocks connected by springs.</li>
  <li>The spring connections simulate constraints and force-displacement relationships that characterize the dynamic behavior of the mechanism.</li>
  <li>Enables the automatic synthesis of <strong>2D 1DOF mechanisms</strong> composed of <strong>revolute joints</strong>, optimized to follow specific paths.</li>
</ul>

<p><strong style="font-size: 1.2em;">JBM (Joint-element Block Model):</strong></p>
<ul>
  <li>Extends SBM by incorporating revolute and prismatic joints.</li>
  <li>Allows for more sophisticated control of the mechanism's movement by enabling the usage of prismatic joints.</li>
  <li>Supports the synthesis of <strong>2D 1DOF mechanisms</strong> with <strong>revolute and prismatic joints</strong>.</li>
</ul>

<div style="text-align: center;">
    <img src="https://cksdml1014.github.io/chanisong/images/optimizationformulation.png" alt="optimizationformulation" style="width: 50%;">
    <p style="font-size: 12px;">Optimization formulation for Autonomous Mechanism Design, first proposed by Kim et al. (IJNM, 2014)</p>
</div>

<ul>
  <li>The spring constant <em>k</em> of the springs in SBM & JBM models determines whether the system behaves like a linkage mechanism with revolute joints, like a rigidly connected structure, or something in between. By using spring values as variables, along with the position of the nodes and the angle of the double-spring structure in JBM models, we can represent various 2D linkage mechanisms composed of links and revolute/prismatic joints.</li>
  <li>Using an appropriate optimization formulation with these variables as optimization variables, we can automatically synthesize linkage mechanisms that follow specific paths. This process determines <strong>both the topology and geometry</strong> of the linkage mechanisms.</li>
  <li>The synthesis process utilizes an <strong>optimization formulation</strong> based on the <strong>work transmittance efficiency function</strong> (Kim and Kim, IJNM, 2014), enabling the autonomous design of mechanisms that follow specific paths.</li>
</ul>

<div style="display: flex; justify-content: space-between;">
  <div style="width: 48%; text-align: center;">
    <video width="100%" controls>
      <source src="https://cksdml1014.github.io/chanisong/images/sbmvideo1.mp4" type="video/mp4">
      Your browser does not support the video tag.
    </video>
    <p style="font-size: 12px; color: gray;">This video illustrates the mechanism synthesis process using SBM. You can see how different spring constants change the motion of the SBM blocks. The path of the center of target block gradually converges to the target path. (IDeA Lab, 2022)</p>
  </div>
  
  <div style="width: 48%; text-align: center;">
    <video width="100%" controls>
      <source src="https://cksdml1014.github.io/chanisong/images/sbmvideo2.mp4" type="video/mp4">
      Your browser does not support the video tag.
    </video>
    <p style="font-size: 12px; color: gray;">This video illustrates the change of objective function(red) and constraints(blue) during the iteration of SBM optimization while synthesizing the mechanism from the left video. 1DoF Mechanism is synthesized when the work transmittance efficiency(red graph) converges to 1. (IDeA Lab, 2022)</p>
  </div>
</div>

<h2>Examples of Applications of Autonomous Mechanism Design Technology</h2>

<p><strong style="font-size: 1.2em;">Vehicle Mechanisms:</strong></p>
<ul>
  <li><strong>Applications:</strong> Autonomous suspension systems, aerodynamic components, adaptable chassis elements.</li>
  <li><strong>Impact:</strong> Optimizes vehicle performance under various conditions, supporting the shift toward electric and autonomous vehicles.</li>
</ul>

<div style="text-align: center;">
    <img src="https://cksdml1014.github.io/chanisong/images/메커니즘그림1.png" alt="mech1" style="width: 90%;">
    <p style="font-size: 12px;">Novel vehicle mechanisms developed using predecessor to SBM and JBM, referred to as the 'bar model' proposed by Kim and Kim (IJNM, 2014). Figure also referenced in Kim et al. (IJNM, 2018).</p>
</div>

<p><strong style="font-size: 1.2em;">Human-Integrated Mechanisms and Robotics:</strong></p>
<ul>
  <li><strong>Applications:</strong> Robotic exoskeletons, rehabilitation devices, assistive mobility systems.</li>
  <li><strong>Impact:</strong> Designs mechanisms that interact with humans for wearable, assistive applications in medical robotics.</li>
</ul>

<div style="text-align: center;">
    <img src="https://cksdml1014.github.io/chanisong/images/메커니즘그림2.png" alt="mech2" style="width: 90%;">
    <p style="font-size: 12px;">Rehabilitation devices designed using SBM and JBM (Kim et al., SMO, 2018) and exoskeletons (Lee et al., IEEE Access, 2023).</p>
</div>

<p><strong style="font-size: 1.2em;">Transformable Wheel Mechanisms:</strong></p>
<ul>
  <li><strong>Applications:</strong> Transformable wheels with adaptable structures for torque, speed, and stability optimization.</li>
  <li><strong>Impact:</strong> Reduces motor usage while maintaining performance, enabling 1-DOF robot systems to adjust to changing terrain.</li>
</ul>

<div style="text-align: center;">
    <img src="https://cksdml1014.github.io/chanisong/images/메커니즘그림3.png" alt="mech3" style="width: 70%;">
    <p style="font-size: 12px;">Transformable wheels designed using JBM (Kim et al., IEEE T-RO, 2023).</p>
</div>

<div style="display: flex; justify-content: space-between;">
  <div style="width: 48%; text-align: center;">
    <video width="100%" controls>
      <source src="https://cksdml1014.github.io/chanisong/images/wheel1.mp4" type="video/mp4">
      Your browser does not support the video tag.
    </video>
    <p style="font-size: 12px; color: gray;">This video illustrates the synthesis process of Transformable Wheel Mechanisms using the JBM framework. As the optimization problem approaches its optimal solution, the JBM system gradually converges into a 1-DOF mechanism. (IEEE T-RO, 2023)</p>
  </div>
  <div style="width: 48%; text-align: center;">
    <video width="100%" controls>
      <source src="https://cksdml1014.github.io/chanisong/images/wheel2.mp4" type="video/mp4">
      Your browser does not support the video tag.
    </video>
    <p style="font-size: 12px; color: gray;">Once the JBM system converges, it is interpreted into a linkage mechanism. This video showcases the CAD models of mechanisms synthesized through the JBM framework. (IEEE T-RO, 2023)</p>
  </div>
</div>

<h3>The Value of SBM and JBM in Industry and Research</h3>

<p>Optimization and Innovation:These models streamline the mechanism design process, enabling engineers to focus on optimization and innovation.</p>
<p>Applications: The technology is applied in various sectors, including automotive, medical robotics and mobility solutions.</p>

<h3>Previous Publications</h3>

<p>For detailed publications and patents related to Autonomous Mechanism Design Technology, visit <a href="https://ideaocean.ai/technology/" target="_blank"><strong>here</strong></a>.</p>
</details>

<hr style="border: 2px solid black;">

## Publications & Manuscripts

### Synthesizing Mechanisms that requires special requirements Using SBM

1. **C. Song†**, J. Kim, and Y.Y. Kim∗, *“Automatic Synthesis of 1-DOF Linkage Mechanism Using SBM (applied in a special environment: Details to be disclosed upon acceptance)”*, expected submission in 2024 to *Journal of Mechanical Design*.

   - **Summary**: This paper introduces a novel synthesis method for linkage mechanisms using the SBM framework. The focus is on automating the design process and enhancing the performance of linkage systems in complex environments. Details of the target problems and the research impact will be disclosed after journal acceptance. Since the problem definition is critical to the originality of this research, disclosing it prematurely could jeopardize its uniqueness. However, **the problem definition, methods, results, and potential impact can be shared in private Zoom meetings**.
   
   - **Expected Impact**: This research significantly contributes to the automatic design of linkage mechanisms for specialized environments, particularly in robotics.

---

### Designing Novel Mechanisms by developing 3D Autonomous Mechanism Design Methodology

2. **C. Song†**, J. Kim, and Y.Y. Kim∗, *“A Novel Mechanism Synthesized Using the 3D JBM Model and Topology Optimization”*, expected submission in 2025 to *Mechanism and Machine Theory*.

   - **Summary**: This paper presents the design and synthesis of novel mechanical systems using a new 3D design method. While the methodology for automatic synthesis of 3D linkage mechanisms is well-developed, submission has been delayed until 2025 due to project requirements and contractual obligations with Hyundai Motors.

   - **NDA Compliance**: This project, in collaboration with Hyundai Motors, involves designing a novel mechanism for their next-generation high-performance hydrogen-hybrid concept car. Due to NDA restrictions, details about the mechanism's specific application and results cannot be publicly disclosed. However, **the process for synthesizing mechanisms in 3D environments can be shared through private Zoom meetings**.
  
   - **Expected Impact**: The development of a 3D automatic synthesis methodology is a significant advancement, overcoming the limitations of previous methods that were confined to 2D spaces. This approach has wide applications in fields like automotive design, exoskeletons, medical robotics, and locomotion systems.
  
<div style="text-align: center;">
  <video width="560" height="315" controls>
    <source src="https://cksdml1014.github.io/chanisong/images/3djbm_example.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
  <p style="font-size: 12px; color: gray;">This video serves as a preview to introduce the 3D Autonomous Mechanism Design Methodology, showcasing a 3D mechanism as part of the disclosure.</p>
</div>

---

### Future Directions & Zoom Meetings

Due to the sensitive nature of my ongoing research projects, I am available for private discussions via **Zoom meetings** to provide more detailed information. During these meetings, I can share additional research materials and synthesized videos that are under NDA. It is recommended that I record these meetings for my personal reference when introducing my research processes and results. Please feel free to contact me to schedule a discussion.
