---
layout: page
title: 오픈소스 기반 반도체 칩 종합설계 - 설계 및 제작 실습
description: >-
    Course policies and information.
---

# 오픈소스 기반 반도체 칩 종합설계 - 설계 및 제작 실습
Open-Source-Based Semiconductor Chip Design and Fabrication Practice

M2177.011500
> This course is an integrated capstone project in which students from diverse academic backgrounds and areas of expertise form teams todesign, manufacture, and validate a sustainable solar car, with the goal of preparing for participation in international solar car competitions such as the World Solar Challenge, the SASOL Solar Car Challenge, and the American Solar Challenge. The course
combines lectures and technical seminars for theoretical learning with hands-on activities in design, validation, and testing. Based on a thorough analysis of competition regulations, students derive design requirements and carry out corresponding engineering solutions. Through multidisciplinary collaboration, they gain experience in the entire process from concept development to prototyping and performance evaluation, cultivate the ability to assess and present results using engineering, environmental, and economic metrics, and build the technical and organizational foundations necessary for actual competition participation.

- __Location__: Bld 43-201
- __Lecture__: Friday 13:00 - 15:50

## Instructor
{% assign instructors_main = site.staffers | where: "role", "instructor" %}
{% assign instructors_solar = site.staffers | where: "role", "instructor_solar_car" %}
{% assign instructors = instructors_main | concat: instructors_solar %}
{% if instructors and instructors.size > 0 %}
<style>
.instructor-grid--solar {
  display: grid;
  grid-template-columns: 1fr;
  gap: 24px;
}
@media (min-width: 768px) {
  .instructor-grid--solar {
    grid-template-columns: repeat(2, minmax(0, 1fr));
  }
}
.instructor-grid--solar > * {
  min-width: 0;
}
</style>
<div class="instructor-grid--solar">
  {% for staffer in instructors %}
    <div>
      {{ staffer }}
    </div>
  {% endfor %}
</div>
{% endif %}

## Teaching Assistants
{% assign teaching_assistants = site.staffers | where: 'role', 'ta_solar_car' %}
{% if teaching_assistants and teaching_assistants.size > 0 %}
<style>
.ta-grid--solar {
  display: grid;
  grid-template-columns: 1fr;
  gap: 24px;
}
@media (min-width: 768px) {
  .ta-grid--solar {
    grid-template-columns: repeat(2, minmax(0, 1fr));
  }
}
.ta-grid--solar > * {
  min-width: 0;
}
</style>
<div class="ta-grid--solar">
  {% for staffer in teaching_assistants %}
    <div class="ta-item">
      {{ staffer }}
      {%- comment -%}
      {% include staffer-card.html staffer=staffer %}
      {%- endcomment -%}
    </div>
  {% endfor %}
</div>
{% endif %}

---

## References
- Douglas R. Carroll, "The Winning Solar Car: A Design Guide for Solar Race Car Teams," 2003.
- https://solarcar.snu.ac.kr/

## Grading (S/U)
- Attendance: 15%
- Assignment: 40%
- Midterm: 20%
- Final exam: 20%
- Attitude: 5% 

## Lecture Schedule

| Week | Date | Lecture | 
|:-------------------:|:-------------------:|-------------------------------------------------------------|
| 1 | 3/6 | Course opening, and basics of solar cars |
| 2 | 3/13 | Engineering design methodology |
| 3 | 3/20 | Presentation of requirements analysis |
| 4 | 3/27 | Solar energy |
| 5 | 4/3 | Strategy |
| 6 | 4/10 | Solar cell and panel |
| 7 | 4/17 | Aerodynamic design |
| 8 | 4/24 | Electrical systems |
| 9 | 5/1 | Battery systems |
| 10 | 5/8 | Chassis & mechanical parts design, CFRP manufacturing |
| 11 | 5/15 | Racing team management | 
| 12 | 5/22 | Team work and face-to-face meeting with mentors – 1 | 
| 13 | 5/29 | Team work and face-to-face meeting with mentors – 2 |
| 14 | 6/5 | Final PT – Solar car design | 
| 15 | 6/12 | Grading, final report | 
