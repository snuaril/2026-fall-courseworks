---
layout: page
title: 'Engineering Orchestration: Designing a Project-Based Orchestration Education Model for Engineering Students'
description: >-
    Course policies and information.
---
# Engineering Orchestration: Designing a Project-Based Orchestration Education Model for Engineering Students

M2177.002400
> Engineering Orchestration is a project based course that uses music as a medium for
teaching engineering students how to coordinate people, technologies, ideas, and
social meaning in the age of AI.
The course is not designed to train students as musicians. Instead, students
experience rhythm, harmony, listening, conducting, improvisation, and performance
as practical metaphors for engineering collaboration, leadership, and systems
integration.
The guiding question of the course is:
What remains uniquely human in the age of AI?
Students will explore how engineers can move beyond individual technical
excellence and learn to become orchestrators who can align diverse people, tools, AI
systems, and social goals into a coherent outcome.

- __Location__: Bld 43-201
- __Lecture__: Thursday 14:00 – 16:50
  
## Instructor
{% assign instructors = site.staffers | where: 'role', 'instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

## Teaching Assistant
{% assign teaching_assistants = site.staffers | where: 'role', 'ta_ai_for_manufacturing' %}
{% assign num_teaching_assistants = teaching_assistants | size %}
{% if num_teaching_assistants != 0 %}
{% for staffer in teaching_assistants %}
{{ staffer }}
{% endfor %}
{% endif %}

---

## Grading
- Attendance: 5%
- Assignment: 40%
- Final Exam: 25%
- Attitude: 5%
- Project: 25%

## Assignment
- Defective PCB Detection
  - [Reference Paper](https://www.nature.com/articles/s41597-024-03656-8)    
  - [Dataset](https://figshare.com/articles/dataset/DsPCBSD_/24970329?file=44069552)
- Classification of Vibration Signal
  - [Reference Paper](https://ieeexplore.ieee.org/document/9078761)
  - [Dataset](https://engineering.case.edu/bearingdatacenter/download-data-file)
- LLM with Digital Twin
  - [Reference Paper](https://ieeexplore.ieee.org/document/10710900)

<!--
| Phase | Week | Date | Topic | Lab session / Activity |
|:----|:----:|:----:|----|------|
| **Phase I – Manufacturing from Living Systems** | 1 | 3/4 | Course Introduction: Why **Physical AI** for Manufacturing<br />- Overview of course structure and projects | - |
|  | 2 | 3/11 | Manufacturing in Living Systems I: Cell-Level Production<br />- How single cells manufacture structure and function. DNA as constraint rather than blueprint. Distributed manufacturing without centralized control | Individual expertise and interests introduction |
-->
## Lecture Schedule

| Phase | Week | Date | Topic | Lab session / Activity |
|:----|:----:|:----:|----|------|
| **Phase I – Manufacturing from Living Systems** | 1 | 3/4 | Course Introduction: Why **Physical AI** for Manufacturing<br />- Overview of course structure and projects | - |
|  | 2 | 3/11 | Manufacturing in Living Systems I: Cell-Level Production<br />- How single cells manufacture structure and function. DNA as constraint rather than blueprint. Distributed manufacturing without centralized control | Individual expertise and interests introduction |
|  | 3 | 3/18 | Manufacturing in Living Systems II: Mechanism, and Evolution<br />- Historical discovery of biological mechanisms. Viruses as high-speed manufacturing systems. Lessons from the COVID-19 pandemic: mutation, adaptation, and failure | Team building |
|  | 4 | 3/25 | Neurons, Plasticity, and the Emergence of Intelligence<br />- Neurons as structural units of intelligence. Plasticity as structural manufacturing. Learning as a physical process | - |
| **Phase II – Biological Principles of Intelligence** | 5 | 4/1 | Visual Intelligence: Seeing as Physical Interaction<br />- Biological vision as an active, embodied process. From light to cells | Visual perception |
|  | 6 | 4/8 | Language Intelligence: Constraints, Not Commands<br />- Language as a constraint system for coordination, explanation, and responsibility. Implications for human–AI collaboration | Language-guided decision structures using AI model |
|  | 7 | 4/15 | Generative Intelligence: Creating by Shaping Possibility<br />- Generation as exploration of possibility spaces. Biological development, variation, and adaptation. Generative models as explorers rather than producers | Generative exploration and evaluation of solution spaces |
|  | 8 | 4/22 | Explainable AI: Judgment, Responsibility, and Trust<br />- Design requirement for responsibility | Explainable AI |
|  | 9 | 4/29 | **Midterm Exam** | - |
| **Phase III – Domain-specific Physical AI Projects** | 10 | 5/6 | Agents as Decision-Making Entities<br />- Introduction to Agents and Physical AI | Company or Individual Domain Presentations |
|  | 11 | 5/13 | Reinforcement Learning as a Model of Experience<br />- Reframing manufacturing processes in terms of Reinforcement Learning from a Physical AI perspective | RL + Isaac Sim #1 |
|  | 12 | 5/20 | Digital Twin and Simulation for Physical AI<br />- Reward shaping<br />- Role of digital twins and simulators in Physical AI. Simulation as a testbed for policies and potentials. Design of Potentials | RL + Isaac Sim #2 |
|  | 13 | 5/27 | Multi-Agent Systems and Human–AI Collaboration<br />- Limits of full automation. Designing human intervention, responsibility, and safety | - |
|  | 14 | 6/3 | Peer Review | - |
|  | 15 | 6/10 | Final Presentation | - |

## References
- Mingu Jeon, In-Ho Choi, Seung-Woo Seo, and Seong-Woo Kim, "Extremely Rare Anomaly Detection Pipeline in Semiconductor Bonding Process with Digital Twin-driven Data Augmentation Method," IEEE Transactions on Components, Packaging and Manufacturing Technology, Vol. 14, No. 10, pp. 1891 - 1902, Oct. 2024
- Gyuho Lee, Seong-Woo Kim, and Mingu Jeon, “Machinery Value Estimation Method based on IIoT System Utilizing 1D-CNN Model for Low Sampling Rate Vibration Signals from MEMS,” IEEE Internet of Things Journal, Vol. 10, No. 14, pp. 12261-12275, July. 2023
- Mingu Jeon, Siyun Yoo, and Seong-Woo Kim, "A Contactless PCBA Defect Detection Method: Convolutional Neural Networks with Thermographic Images," IEEE Transactions on Components, Packaging and Manufacturing Technology, Vol. 12, No. 3, pp 489 - 501, March 2022
