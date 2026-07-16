---
layout: home
title: 2026 Fall Courseworks
nav_exclude: true
permalink: /:path/
---

# 2026 Fall Courseworks
Courseworks in 2026 Fall, Autonomous Robot Intelligence Lab
- [엔지니어링 오케스트레이션](./eng_orchest.md)(Engineering Orchestration, M2177.011600)
- [로봇인공지능만들기](./robot_ai.md)(How to Make a Robot with Artificial Intelligence, M2177.002600)
- [오픈소스 반도체 설계 및 제작 종합설계](./semicon.md)(Open-Source Semiconductor Chip Design and Fabrication Capstone, M2177.011700, M2867.006400)
- [주제탐구세미나2 (언어, AI 그리고 로봇)](./seminar_ai_language_robot.md)(Language, AI, and Robots – The Future of Humanity Through the Lens of Philosophy and Media (991.102(005)))
  
## Instructor
{% assign instructors = site.staffers | where: 'role', 'instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}
