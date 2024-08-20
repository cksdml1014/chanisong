---
layout: archive
title: "Publications and Manuscripts"
permalink: /publications/
author_profile: true
---

Given that Autonomous Mechanism Design Technology is an unfamiliar field even for researchers in related areas, here's a brief explanation of the technology, followed by specific contributions of mine. You can find my contributions toward the lower part of this page.

## Autonomous Mechanism Design Technology: SBM and JBM Models

The **Autonomous Mechanism Design Technology**, developed using the **SBM (Spring-connected Block Model)** and **JBM (Joint-element Block Model)** frameworks, represents a revolutionary approach to mechanism synthesis. This technology autonomously generates complex linkage mechanisms that achieve specific tasks and meet performance requirements across various applications.

### What are SBM and JBM?

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

- **SBM (Spring-connected Block Model)**: SBM models mechanical systems using rigid blocks connected by springs. The spring connections simulate constraints and force-displacement relationships that characterize the dynamic behavior of the mechanism. SBM enables the automatic synthesis of **2D mechanisms** composed of **revolute joints**, optimized to follow specific paths.

- **JBM (Joint-element Block Model)**: Building upon SBM, JBM introduces a double-spring model and incorporates joint elements between blocks. These elements represent various types of mechanical connections, such as revolute and prismatic joints, allowing for more sophisticated control of the mechanism's movement. JBM enables the synthesis of **2D mechanisms** with both **revolute and prismatic joints**.

<div style="text-align: center;">
    <img src="https://cksdml1014.github.io/chanisong/images/optimizationformulation.png" alt="optimizationformulation" style="width: 50%;">
    <p style="font-size: 12px;">Optimization formulation for Autonomous Mechanism Design, first proposed by Kim et al. (IJNM, 2014)</p>
</div>

- By using SBM and JBM models, alongside an optimization problem formulation based on the **work transmittance efficiency function** (proposed by Kim and Kim, IJNM, 2014), linkage mechanisms that follow specific paths can be synthesized autonomously.

### Examples of Applications of Autonomous Mechanism Design Technology

<div style="text-align: center;">
    <img src="https://cksdml1014.github.io/chanisong/images/메커니즘그림1.png" alt="mech1" style="width: 90%;">
    <p style="font-size: 12px;">Autonomous Mechanism Design Technology enabled novel vehicle mechanisms, developed by Kim and Kim (IJM, 2014) and Kim et al. (IJNM, 2018).</p>
</div>

1) **Vehicle Mechanisms**:  
   As the automotive industry advances toward electric and autonomous vehicles, ensuring vehicle stability and control becomes critical. Autonomous mechanism design technology supports the development of vehicle mechanisms like suspension systems and aerodynamic components to optimize performance under various conditions.

   - **Examples**: Designing multi-link suspension systems, adaptable chassis components, and aerodynamic structures.

<div style="text-align: center;">
    <img src="https://cksdml1014.github.io/chanisong/images/메커니즘그림2.png" alt="mech2" style="width: 90%;">
    <p style="font-size: 12px;">Finger rehabilitation devices and exoskeleton mechanisms were designed using SBM and JBM by Kang and Kim (SMO, 2018) and Lee et al. (IEEE ACCESS, 2023).</p>
</div>

2) **Human-Integrated Mechanisms and Robotics**:  
   In robotics and human-integrated systems, autonomous mechanism design technology offers the ability to create mechanisms that directly interact with humans, such as exoskeletons and rehabilitation devices. These mechanisms are designed to be wearable, supporting mobility for individuals with physical disabilities.

   - **Examples**: Wearable robotic exoskeletons, rehabilitation devices for joints and limbs, and assistive mobility robots.

<div style="text-align: center;">
    <img src="https://cksdml1014.github.io/chanisong/images/메커니즘그림3.png" alt="mech3" style="width: 70%;">
    <p style="font-size: 12px;">Various transformable wheel mechanisms using a single motor have been proposed by Kim et al. (IEEE T-RO, 2023) using JBM.</p>
</div>

3) **Transformable Wheel Mechanisms**:  
   Transformable wheel-based robot systems are challenging to design due to the need for reducing the number of motors while maintaining efficiency. The autonomous mechanism design technology, leveraging SBM and JBM models, provides optimal designs for such systems. These designs allow robots to operate with one degree of freedom (1-DOF) using single motors while adjusting transmission ratios for different torque and speed requirements.

   - **Examples**: Transformable wheels that adjust their linkage structures based on torque, power, the number of motors, and stability requirements.

<div style="display: flex; justify-content: space-between;">

  <div style="text-align: center; width: 48%;">
    <video width="100%" controls>
      <source src="https://cksdml1014.github.io/chanisong/images/wheel1.mp4" type="video/mp4">
      Your browser does not support the video tag.
    </video>
    <p style="font-size: 12px; color: gray;">This video illustrates the synthesis process of Transformable Wheel Mechanisms using the JBM framework. As the optimization problem approaches its optimal solution, the JBM system gradually converges into a 1-DOF mechanism. (IEEE T-RO, 2023)</p>
  </div>

  <div style="text-align: center; width: 48%;">
    <video width="100%" controls>
      <source src="https://cksdml1014.github.io/chanisong/images/wheel2.mp4" type="video/mp4">
      Your browser does not support the video tag.
    </video>
    <p style="font-size: 12px; color: gray;">Once the JBM system converges, it is interpreted into a linkage mechanism. This video showcases the CAD models of mechanisms synthesized through the JBM framework. (IEEE T-RO, 2023)</p>
  </div>

</div>

### The Value of SBM and JBM in Industry and Research

The ability to automatically design mechanisms using SBM and JBM marks a significant leap forward in engineering and robotics. These models reduce the manual effort traditionally required for mechanism design, allowing engineers to focus on optimization and innovation. The technology is applied in both academic research and industrial applications, including automotive design, medical robotics, and next-generation mobility solutions.

### Previous Publications

Previous research publications and patents made using Autonomous Mechanism Design Technology can be found **[here](https://ideaocean.ai/technology/)**.

### Personal Contributions

*IDeAOcean*, succeeding *IDeALab* under Prof. Yoon Young Kim, continues to lead the development of Autonomous Mechanism Design Technology for academic and industrial applications. My role at IDeAOcean involves **extending SBM and JBM to 3D mechanisms**, as shown below, while contributing to various other areas, such as applying parallel computing and optimizing size through algorithms like NSGA-II. We collaborate with major companies, including Hyundai Motors and HD Hyundai, and have generated **novel mechanisms—some of which are in the patent process**. Our future projects involve collaborations with vehicle companies like Honda, as well as robotics firms requiring advanced mechanism design.

Although some of this research is under NDA, my published work and manuscripts reflect significant advancements in synthesizing mechanical systems with high performance and adaptability.

---

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
