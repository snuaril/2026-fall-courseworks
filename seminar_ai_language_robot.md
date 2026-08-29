---
layout: page
title: "주제탐구세미나2: 언어, AI 그리고 로봇"
description: >-
    Course policies and information.
---

# 주제탐구세미나2: 언어, AI 그리고 로봇
Language, AI, and Robots – The Future of Humanity Through the Lens of Philosophy and Media

991.102(005)
> The advent of artificial intelligence and robots that comprehend human language serves as a mirror of humanity, opening a new dimension of self‑understanding. This course invites students to look inward through that lens and, building on these insights, contemplate how the future may unfold in the era after AI and robots. Instead of probing technical intricacies, we collectively view and analyze films, animation, literature, and other media, exploring the themes of language, identity, power, and mutual communication they embody—while connecting them to philosophical frameworks. Drawing on key concepts from thinkers such as Carl Jung, Jacques Lacan, Friedrich Nietzsche, Thomas Hobbes, and Claude Lévi‑Strauss, the course weaves in the latest research on AI‑ and robot‑focused works. Through discussion, presentations, and team projects, participants are encouraged to develop and articulate their own informed perspectives.

- __Location__: Bld 220, Room 201
- __Lecture__: Wednesday 14:00 - 16:50

## Instructor
{% assign instructors_main = site.staffers | where: "role", "instructor" %}
{% assign instructors_seminar = site.staffers | where: "role", "instructor_seminar2" %}
{% assign instructors = instructors_main | concat: instructors_seminar %}
{% if instructors and instructors.size > 0 %}
<style>
.instructor-grid--seminar2 {
  display: grid;
  grid-template-columns: 1fr;
  gap: 24px;
}
@media (min-width: 768px) {
  .instructor-grid--seminar2 {
    grid-template-columns: repeat(2, minmax(0, 1fr));
  }
}
.instructor-grid--seminar2 > * {
  min-width: 0;
}
</style>
<div class="instructor-grid--seminar2">
  {% for staffer in instructors %}
    <div>
      {{ staffer }}
    </div>
  {% endfor %}
</div>
{% endif %}

## Teaching Assistants
{% assign teaching_assistants = site.staffers | where: 'role', 'ta_seminar2' %}
{% if teaching_assistants and teaching_assistants.size > 0 %}
<style>
.ta-grid--seminar2 {
  display: grid;
  grid-template-columns: 1fr;
  gap: 24px;
}
@media (min-width: 768px) {
  .ta-grid--seminar2 {
    grid-template-columns: repeat(2, minmax(0, 1fr));
  }
}
.ta-grid--seminar2 > * {
  min-width: 0;
}
</style>
<div class="ta-grid--seminar2">
  {% for staffer in teaching_assistants %}
    <div class="ta-item">
      {{ staffer }}
    </div>
  {% endfor %}
</div>
{% endif %}

---

## References
- Kim, et al. "E2Map: Experience-and-Emotion Map for Self-Reflective Robot Navigation with Language Models." IEEE International Conf. on Robotics and Automation (ICRA), 2025.

## Grading (S/U)
- Attendance: 40%
- Assignment: 30%
- Project PT: 30%

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
      <td style="text-align: center">9/2</td>
      <td style="text-align: center">Course opening and basic concepts - Blade Runner 1982</td>
      <td style="text-align: center">Robot architecture basics</td>
      <td style="text-align: center">Primitive physical architecture of Intelligence and Language</td>
    </tr>
    <tr>
      <td style="text-align: center">2</td>
      <td style="text-align: center">9/9</td>
      <td style="text-align: center">The First Language</td>
      <td style="text-align: center">Saussurean Linguistics</td>
      <td style="text-align: center">Token - Signifier Revisited through LLMs</td>
    </tr>
    <tr>
      <td style="text-align: center">3</td>
      <td style="text-align: center">9/16</td>
      <td style="text-align: center" colspan="3">Special session – Practice</td>
    </tr>
    <tr>
      <td style="text-align: center">4</td>
      <td style="text-align: center">9/23</td>
      <td style="text-align: center" colspan="3">Project ideation pitch (PT)</td>
    </tr>
    <tr>
      <td style="text-align: center">5</td>
      <td style="text-align: center">9/30</td>
      <td style="text-align: center">Abstraction</td>
      <td style="text-align: center">Implementation of Abstraction</td>
      <td style="text-align: center">Coding practice</td>
    </tr>
    <tr>
      <td style="text-align: center">6</td>
      <td style="text-align: center">10/7</td>
      <td style="text-align: center">Prediction in time</td>
      <td style="text-align: center">Distance in time</td>
      <td style="text-align: center">Map of meaning</td>
    </tr>
    <tr>
      <td style="text-align: center">7</td>
      <td style="text-align: center">10/14</td>
      <td style="text-align: center" colspan="3">Mid-term exam</td>
    </tr>
    <tr>
      <td style="text-align: center">8</td>
      <td style="text-align: center">10/21</td>
      <td style="text-align: center">Understanding Temporal Causality</td>
      <td style="text-align: center">Sequence learning</td>
      <td style="text-align: center"><strong>Lab session – 1:<br />LLM basic practice(Local LM &amp; api)</strong><br /><span style="font-size: 0.85em; white-space: nowrap">TA Baek &amp; Lee</span></td>
    </tr>
    <tr>
      <td style="text-align: center">9</td>
      <td style="text-align: center">10/28</td>
      <td style="text-align: center">Translation</td>
      <td style="text-align: center">Neural Machine Translation - 1<br />S2S, Attention</td>
      <td style="text-align: center"><strong>Lab session – 2:<br />RAG &amp; Langchain</strong><br /><span style="font-size: 0.85em; white-space: nowrap">TA Lee</span></td>
    </tr>
    <tr>
      <td style="text-align: center">10</td>
      <td style="text-align: center">11/4</td>
      <td style="text-align: center">Evaluation of Translation<br />How Neural Networks Learned Meaning</td>
      <td style="text-align: center">Self-Attention and Transformer</td>
      <td style="text-align: center"><strong>Lab session – 3:<br />Agentic AI(Harness)</strong><br /><span style="font-size: 0.85em; white-space: nowrap">TA Lee</span></td>
    </tr>
    <tr>
      <td style="text-align: center">11</td>
      <td style="text-align: center">11/11</td>
      <td style="text-align: center" colspan="2">Image-Language Understanding<br />Vision-Language-Action Model</td>
      <td style="text-align: center"><strong>Lab session – 4:<br />Agentic AI(MCP) &amp; Project Notice</strong><br /><span style="font-size: 0.85em; white-space: nowrap">TA Lee</span></td>
    </tr>
    <tr>
      <td style="text-align: center">12</td>
      <td style="text-align: center">11/18</td>
      <td style="text-align: center">Evaluation of Generation and Babel tower dilemma</td>
      <td style="text-align: center">Reinforcement learning</td>
      <td style="text-align: center">Policy gradient</td>
    </tr>
    <tr>
      <td style="text-align: center">13</td>
      <td style="text-align: center">11/25</td>
      <td style="text-align: center">ChatGPT - Human Feedback &amp; Emotion</td>
      <td style="text-align: center">Information-Theoretic Model of Trust, Cooperation, and Antagonism</td>
      <td style="text-align: center">Anatomy of motivation</td>
    </tr>
    <tr>
      <td style="text-align: center">14</td>
      <td style="text-align: center">12/2</td>
      <td style="text-align: center" colspan="3">Final PT</td>
    </tr>
    <tr>
      <td style="text-align: center">15</td>
      <td style="text-align: center">12/9</td>
      <td style="text-align: center" colspan="3">Final report, grading, feedback</td>
    </tr>
  </tbody>
</table>
