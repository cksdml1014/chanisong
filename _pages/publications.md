---
layout: archive
title: "Publications and Manuscripts"
permalink: /publications/
author_profile: true
---

Regarding that Autonomous Mechanism Design Technology is an unfamiliar field even for researchers in related fields, here's a brief explanation of the technology followed by specific contribution of mine. You can find my contributions in the lower part of this page.

## Autonomous Mechanism Design Technology: SBM and JBM Models

The **Autonomous Mechanism Design Technology**, developed using the **SBM (Spring-connected Block Model)** and **JBM (Joint-element Block Model)** frameworks, represents a revolutionary approach to mechanism synthesis. This technology is capable of autonomously generating complex linkage mechanisms that can achieve specific tasks and meet performance requirements in a wide range of applications.

### What is SBM and JBM?

<div style="display: flex; justify-content: space-between;">
    <div style="width: 48%;">
        <img src="https://cksdml1014.github.io/chanisong/images/SBM1.png" alt="SBM1" style="width: 100%;">
        <p style="font-size: 12px; text-align: center;">SBM, first proposed by Prof. Yoon Young Kim(JMD, 2007) enables the expression of 2D Linkage Mechanisms consisted with Revolute Joints.</p>
    </div>
    <div style="width: 48%;">
        <img src="https://cksdml1014.github.io/chanisong/images/JBM1.png" alt="JBM1" style="width: 100%;">
        <p style="font-size: 12px; text-align: center;">JBM proposed by Kang and Kim (SMO, 2018) includes the reprentation of Prismatic joints in 2D Linkage Mechanisms to the previous SBM.</p>
    </div>
</div>

- **SBM (Spring-connected Block Model)**: SBM is a design method that models mechanical systems using rigid blocks connected by springs. The spring connections represent constraints and force-displacement relationships that simulate the dynamic behavior of the mechanism. This model allows for the automatic synthesis of linkages that can be optimized to follow specific paths. SBM enables synthesizing **2D mechanisms** consisted with **Revolute joints**.

- **JBM (Joint-element Block Model)**: The JBM extends the capabilities of SBM by introducing a double-spring model and incorporating joint elements between blocks. These joint elements represent various types of mechanical connections, which are revolute and prismatic joints, enabling more sophisticated control over the movement of the mechanism. JBM enables synthesizing **2D mechanisms** consisted with **Revolute and Prismatic joints**.

<div style="text-align: center;">
    <img src="https://cksdml1014.github.io/chanisong/images/optimizationformulation.png" alt="optimizationformulation" style="width: 50%;">
    <p style="font-size: 12px;">Optimization Formulation used for Autonomous Mechanism Design, first propsed by Kim et al.(IJNM, 2014)</p>
</div>

- Using SBM and JBM models to represent the mechanisms along with proper formulation of optimization problem using work transmittance efficiency function first proposed by Kim and Kim(IJNM, 2014), linkage mechanisms that follows specific path can be synthesized.
  
### Some examples of Applications of Autonomous Mechanism Design Technology

<div style="text-align: center;">
    <img src="https://cksdml1014.github.io/chanisong/images/메커니즘그림1.png" alt="mech1" style="width: 50%;">
    <p style="font-size: 12px;">Using Autonomous Mechanism Design Technology, Novel vehicle mechanisms had been invented by Kim and Kim (IJM, 2014) and Kim et al.(2018, IJNM)</p>
</div>

1. **Vehicle Mechanisms**:  
   As the automotive industry evolves toward more advanced forms of mobility, including electric and autonomous vehicles, ensuring vehicle stability and control is critical. Autonomous mechanism design technology allows for the development of mechanisms such as suspension systems, rear wings, and other components that optimize vehicle performance in various driving conditions.

   - **Examples**: Designing multi-link suspension systems, adaptable chassis components, and aerodynamic structures for vehicles.

<div style="text-align: center;">
    <img src="https://cksdml1014.github.io/chanisong/images/메커니즘그림2.png" alt="mech2" style="width: 50%;">
    <p style="font-size: 12px;">Finger rehabilitation devices and exoskeletons mechanisms were invented using SBM and JBM by Kang and Kim (SMO, 2018) and Lee et al. (IEEE ACCESS, 2023)</p>
</div>

2. **Human-Integrated Mechanisms and Robotics**:  
   In the field of robotics and human-integrated systems, autonomous mechanism design technology offers the potential to create mechanisms that interact directly with humans, such as exoskeletons and rehabilitation devices. These mechanisms are designed to be wearable and capable of providing assistance or mobility to individuals with physical disabilities.

   - **Examples**: Wearable robotic exoskeletons, rehabilitation devices for joints and limbs, and assistive mobility robots.

<div style="text-align: center;">
    <img src="https://cksdml1014.github.io/chanisong/images/메커니즘그림3.png" alt="mech3" style="width: 50%;">
    <p style="font-size: 12px;">Various Transformable Wheel Mechanisms using a single motor has been proposed by Kim et al.(IEEE T-RO,2023) using JBM.</p>
</div>

3. **Transformable Wheel Mechanisms**:  
   Transformable wheel-based robot systems represent a significant challenge in design to reduce the number of motors utilized in the system. The autonomous mechanism design technology, leveraging SBM and JBM models, provides optimal designs for such systems, enabling robots to operate in 1-DOF using single motors, also considering various options of high transmission ratio to enforce torque or low transmssion ratio for higher speed.

   - **Examples**: Transformable wheels capable of changing it's linkage mechanism strucutres for various needs of torque, power, # of motors, and stability.

### The Value of SBM and JBM in Industry and Research

The ability to automatically design mechanisms using SBM and JBM represents a major leap forward in engineering and robotics. These models remove much of the manual effort traditionally associated with mechanism design, allowing engineers to focus on optimization and innovation. This technology is used not only in academic research but also in industrial applications, such as automotive design, medical robotics, and next-generation mobility solutions.

### Previous Publications

While much of the current research related to SBM and JBM is protected under NDA(Non-Disclosure Agreement) due to corporate collaborations, the contributions of these models are becoming increasingly recognized in both academia and industry. Below are publications and ongoing research efforts that highlight the advancements achieved through these models.

### Personal Contributions

*IDeAOcean*, as the successor of the *IDeALab* from professor Yoon Young Kim which led the development of Autonomous Mechanism design, is now leading the academia and industry on development of the technique along with various industrial applications. I am taking the vital role for developing SBM & JBM, such as major contributions like extending to 3D mechanisms, which is illustrated below, and also with various minor contributions like adapting parallel computing, and fusing size-optimization based on other optimizaion algorithms like NSGA-II. We are also cooperating with various companies like Hyndai Motors and HD Hyundai and I've already generated novel mechanisms with various application, which some of them preparing for patents. Our future applications would include cooperations with other vehicle companies like Honda, but also with various robot companies that require high-level of mechanism design.
My work in Mechanism Design Automation has led to the development of new methods for synthesizing mechanical systems with high performance and adaptability. Although some research is under NDA, my published work and manuscripts provide insights into the theoretical advancements achieved with SBM and JBM models.

---

## Publications & Manuscripts

### Synthesizing Mechanisms Using SBM

1. **C. Song†**, J. Kim, and Y.Y. Kim∗, *“Automatic Synthesis of 1-DOF Linkage Mechanism Using SBM (applied in a special environment: Details to be disclosed upon acceptance)”*, expected submission in 2024 to *Journal of Mechanical Design*.

   - **Summary**: This paper introduces a novel synthesis method for linkage mechanisms using the SBM framework. The focus is on automating the design process and enhancing the performance of linkage systems in complex environments. Detailed descriptions of the target problems and the impact of this research will be disclosed after the journal acceptance. The originality of this research lies heavily in the problem definition, so **disclosing it prematurely through a public website might jeopardize the research’s uniqueness**. However, **the problem definition, methods, results, and potential impact can be shared via private Zoom meetings**.
   
   - **Expected Impact**: This research is crucial for the automatic design of linkage mechanisms in specialized environments, particularly in robotics. Although the specifics cannot be disclosed online at this time, the work represents significant advancements in mechanism design for complex environments.

---

### Designing Novel Mechanisms Using JBM

2. **C. Song†**, J. Kim, and Y.Y. Kim∗, *“A Novel Mechanism Synthesized Using the 3D JBM Model and Topology Optimization”*, expected submission in 2025 to *Mechanism and Machine Theory*.

   - **Summary**: This paper presents the design and synthesis of novel mechanical systems using a new 3D design method. The methodology for the automatic synthesis of 3D linkage mechanisms is highly developed, though **submission is delayed until 2025 due to project requirements and a contract with Hyundai Motors**.

   - **NDA Compliance**: This project, conducted in collaboration with Hyundai Motors, involves designing a novel mechanism for use in their next-generation high-performance hydrogen-hybrid concept car. Due to NDA restrictions, specific details about the mechanism's application and results cannot be publicly disclosed. However, **more information, including the synthesis process of mechanisms that follow a desired path in a 3D environment, can be shared through private Zoom meetings**.
  
   - **Expected Impact**: The development of a 3D automatic synthesis methodology marks a significant advancement in the field of automatic linkage synthesis technology, overcoming the limitations of previous methodologies confined to 2D spaces. This approach has wide applications, including in vehicles, exoskeletons, medical robotics, and locomotion robots, among others.

---

### Future Directions & Zoom Meetings

Due to the sensitive nature of my ongoing research projects, I am available for private discussions via **Zoom meetings** to provide more detailed information. During these meetings, I can share additional research materials and synthesized videos that are under NDA. It is recommended that I record these meetings for my personal reference when introducing my research processes and results. Please feel free to contact me to schedule a discussion.
