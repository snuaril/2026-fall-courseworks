---
layout: page
title: 로봇인공지능 만들기
description: >-
    Course policies and information.
---

# 로봇인공지능 만들기
How to Make a Robot with Artificial Intelligence

M2177.002600
> The attempt to create human-like artifacts has existed since the dawn of history, as recorded in stories like Genesis and the myth of Prometheus. Much like the instinct to have children, many young people with this inclination choose engineering as their career path. These human-like artifacts can be called intelligent robots. While robots with intelligence might seem as appealing as having cute offspring, the outcome is more often akin to Frankenstein's monster rather than Pygmalion's beloved creation. For a robot to possess intelligence, it must understand the shape and mobility of its body, comprehend its environment and space, and know its position within that space. Whether it sets its own goals or receives them, it must plan to achieve these goals and precisely control its motors or muscles accordingly. Moreover, it must consider energy management, understand human speech, and possess a range of capabilities including technology, creativity, resources, capital, leadership, and collaboration skills—truly an interdisciplinary and complex art form. Nonetheless, there are ways to learn about intelligent robots within a semester, and one effective method is through hands-on creation. By using simulation tools to build environments, set missions, and create intelligent robots equipped with sensors and actuators, students can physically internalize the bigger picture. This course aims to introduce the components of intelligent robots, the latest technological trends, and to foster an understanding of their internal operating principles.

- __Location__: Bld 43-201
- __Lecture__: Friday 9:00 - 12:00

## Instructor
{% assign instructors = site.staffers | where: 'role', 'instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

## Teaching Assistants
{% assign teaching_assistants = site.staffers | where: 'role', 'ta_robot_ai' %}
{% assign num_teaching_assistants = teaching_assistants | size %}
{% if num_teaching_assistants != 0 %}
{% for staffer in teaching_assistants %}
{{ staffer }}
{% endfor %}
{% endif %}

---

## Grading
- Attendance: 5%
- Assignment: 30%
- Exams: 30%
- Final project: 30%
- Attitude: 5%


## Lecture Schedule

<table style="width: 100%; table-layout: fixed">
  <colgroup>
    <col style="width: 5rem" />
    <col style="width: 6rem" />
    <col />
    <col />
    <col />
  </colgroup>
  <thead>
    <tr>
      <th style="text-align: center">Week</th>
      <th style="text-align: center">Date</th>
      <th style="text-align: center" colspan="3">Lecture</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align: center">1</td>
      <td style="text-align: center">9/4</td>
      <td style="text-align: center">Course opening:<br />What and why is Physical AI?</td>
      <td style="text-align: center">Birth of life – Energy to Life architectures</td>
      <td style="text-align: center">Birth of movement</td>
    </tr>
    <tr>
      <td style="text-align: center">2</td>
      <td style="text-align: center">9/11</td>
      <td style="text-align: center">Robot Architecture</td>
      <td style="text-align: center">Language understanding in movement</td>
      <td style="text-align: center">Robot architectures</td>
    </tr>
    <tr>
      <td style="text-align: center">3</td>
      <td style="text-align: center">9/18</td>
      <td style="text-align: center" colspan="3"><strong>Practice 1: ROS Installation &amp; Setup &amp; ROS basics</strong></td>
    </tr>
    <tr>
      <td style="text-align: center">4</td>
      <td style="text-align: center">10/2</td>
      <td style="text-align: center">Birth of Intelligence</td>
      <td style="text-align: center">Uncertainty and Randomness</td>
      <td style="text-align: center">Measure of Uncertainty</td>
    </tr>
    <tr>
      <td style="text-align: center">5</td>
      <td style="text-align: center">10/10<br />(Sat 9 am)</td>
      <td style="text-align: center">Critique of Pure Reason</td>
      <td style="text-align: center">Bayes Theorem</td>
      <td style="text-align: center">Naïve Bayes Algorithm</td>
    </tr>
    <tr>
      <td style="text-align: center">6</td>
      <td style="text-align: center">10/16</td>
      <td style="text-align: center">Recursive Bayes Estimation</td>
      <td style="text-align: center">Maximum A Posteriori Estimation</td>
      <td style="text-align: center">Applications – Robot localization</td>
    </tr>
    <tr>
      <td style="text-align: center">7</td>
      <td style="text-align: center">10/23</td>
      <td style="text-align: center">Motivation of Kalman Filter</td>
      <td style="text-align: center">Applications – Measurement and Control</td>
      <td style="text-align: center"><strong>Practice 2: ROS Mapping</strong></td>
    </tr>
    <tr>
      <td style="text-align: center">8</td>
      <td style="text-align: center">10/30</td>
      <td style="text-align: center">Extended Kalman Filter</td>
      <td style="text-align: center">Spatial Understanding and World Representation</td>
      <td style="text-align: center"><strong>Practice 3: ROS Localization</strong></td>
    </tr>
    <tr>
      <td style="text-align: center">9</td>
      <td style="text-align: center">11/6</td>
      <td style="text-align: center">Decision making</td>
      <td style="text-align: center">Planning, and Control</td>
      <td style="text-align: center"><strong>Practice 4: ROS Planning and control</strong></td>
    </tr>
    <tr>
      <td style="text-align: center">10</td>
      <td style="text-align: center">11/13</td>
      <td style="text-align: center">Foundation Models for Robotics</td>
      <td style="text-align: center">Information theory of Linguistics-Motion</td>
      <td style="text-align: center"><strong>Practice 5: LLM/VLA Integration</strong></td>
    </tr>
    <tr>
      <td style="text-align: center">11</td>
      <td style="text-align: center">11/20</td>
      <td style="text-align: center">Vision Language Action</td>
      <td style="text-align: center">Humanoid</td>
      <td style="text-align: center"><strong>Practice 6: Humanoid</strong></td>
    </tr>
    <tr>
      <td style="text-align: center">12</td>
      <td style="text-align: center">11/27</td>
      <td style="text-align: center">Behavior Cloning</td>
      <td style="text-align: center">Diffusion Policy</td>
      <td style="text-align: center"><strong>Practice 7</strong></td>
    </tr>
    <tr>
      <td style="text-align: center">13</td>
      <td style="text-align: center">12/4</td>
      <td style="text-align: center" colspan="3">Team project progress review and team meeting</td>
    </tr>
    <tr>
      <td style="text-align: center">14</td>
      <td style="text-align: center">12/11</td>
      <td style="text-align: center" colspan="3">Final festival</td>
    </tr>
    <tr>
      <td style="text-align: center">15</td>
      <td style="text-align: center">12/18</td>
      <td style="text-align: center" colspan="3">Final report, grading, feedback</td>
    </tr>
  </tbody>
</table>
