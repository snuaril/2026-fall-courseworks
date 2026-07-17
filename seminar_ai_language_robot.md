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

| Week | Date | Lecture |
|:----:|:----:|---------|
| 1 | 9/2 | Course opening and basic concepts – Blade Runner (1982), robot architecture basics, primitive physical architecture of intelligence and language |
| 2 | 9/9 | The first language – Saussurean linguistics, token–signifier revisited through LLMs |
| 3 | 9/16 | Abstraction – implementation of abstraction, project ideation (PT) |
| 4 | 9/23 | Neural learning – 1, 2, 3 |
| 5 | 9/30 | Artificial neural network practice |
| 6 | 10/7 | Prediction in time, distance in time, map of meaning |
| 7 | 10/14 | Mid-term exam |
| 8 | 10/21 | Understanding temporal causality, sequence learning, seq-to-seq learning |
| 9 | 10/28 | Translation – neural machine translation (S2S, Attention); Lab session 1: LLM basic practice |
| 10 | 11/4 | Evaluation of translation, how neural networks learned meaning, self-attention and Transformer; Lab session 2: RAG_Langchain |
| 11 | 11/11 | Image-language understanding, vision-language-action model, evaluation of generation and Babel tower dilemma; Lab session 3: Agent |
| 12 | 11/18 | Reinforcement learning, policy gradient; Lab session 4 |
| 13 | 11/25 | ChatGPT – human feedback & emotion, information-theoretic model of trust/cooperation/antagonism, anatomy of motivation |
| 14 | 12/2 | Final PT |
| 15 | 12/9 | Final report, grading, feedback |
