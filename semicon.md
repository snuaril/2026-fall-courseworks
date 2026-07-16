---
layout: page
title: 오픈소스 기반 반도체 칩 종합설계 - 설계 및 제작 실습
description: >-
    Course policies and information.
---

# 오픈소스 기반 반도체 칩 종합설계 - 설계 및 제작 실습
Open-Source-Based Semiconductor Chip Design and Fabrication Practice

M2866.004200
> Just as open-source technologies enabled 3D printers to produce prototypes right on our desks and made it easy for anyone to design and manufacture PCBs using open-source tools and online services, a new era has arrived—one in which anyone can design and fabricate actual silicon chips using open-source semiconductor design tools and domestic "MyChip" fabrication services.
> This course is intended for students who have completed a C/C++-based software course or possess equivalent programming skills and are interested in
implementing their own algorithms as hardware accelerators or custom digital semiconductor chips. Students will work in teams to develop their ideas into high-level hardware designs, follow the open-source toolchain workflow to complete chip layout and sign-off, and participate in a multi-project wafer (MPW) fabrication process to produce real chips. After receiving the fabricated chips, they will carry out measurement and testing in the lab—experiencing the entire process firsthand. By the end of the semester, students will gain hands-on experience turning code and imagination into silicon and come to realize the empowering potential of the Silicon Maker Era ,where anyone with an idea can design, verify, and manufacture a digital chip.

- __Location__: Bld 43-201
- __Lecture__: Friday 13:00 - 15:50

## Instructor
{% assign instructors_main = site.staffers | where: "role", "instructor" %}
{% assign instructors_semicon = site.staffers | where: "role", "instructor_semicon" %}
{% assign instructors = instructors_main | concat: instructors_semicon %}
{% if instructors and instructors.size > 0 %}
<style>
.instructor-grid--semicon {
  display: grid;
  grid-template-columns: 1fr;
  gap: 24px;
}
@media (min-width: 768px) {
  .instructor-grid--semicon {
    grid-template-columns: repeat(2, minmax(0, 1fr));
  }
}
.instructor-grid--semicon > * {
  min-width: 0;
}
</style>
<div class="instructor-grid--semicon">
  {% for staffer in instructors %}
    <div>
      {{ staffer }}
    </div>
  {% endfor %}
</div>
{% endif %}

## Teaching Assistants
{% assign teaching_assistants = site.staffers | where: 'role', 'ta_semicon' %}
{% if teaching_assistants and teaching_assistants.size > 0 %}
<style>
.ta-grid--semicon {
  display: grid;
  grid-template-columns: 1fr;
  gap: 24px;
}
@media (min-width: 768px) {
  .ta-grid--semicon {
    grid-template-columns: repeat(2, minmax(0, 1fr));
  }
}
.ta-grid--semicon > * {
  min-width: 0;
}
</style>
<div class="ta-grid--semicon">
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
- https://snu-semiconductor.vercel.app/

## Grading (S/U)
- Attendance: 5%
- Assignment: 65%
- Final exam: 20%
- Quiz: 5%
- Attitude: 5% 

## Lecture Schedule

| Week | Date | Lecture | 
|:-------------------:|:-------------------:|-------------------------------------------------------------|
| 1 | 9/4 | Course introduction and understanding of the semiconductor design process using open-source tools |
| 2 | 9/11 | Introduction to semiconductor design computing and development environments |
| 3 | 9/18 | Arduino and application examples (self-driving cars, game programming) |
| 4 | TBD | Verilog programming and SystemC/C++ |
| 5 | 10/2 | Principles of implementing hardware simulators using programming languages (C++) |
| 6 | 10/9 | Co-Simulation and Co-Emulation (integration of Arduino, Ubuntu, and SystemC testbenches) |
| 7 | 10/16 | Pong Game #1 (Understanding video signals) |
| 8 | 10/23 | Pong Game #2 (Dot matrix graphics and LCD modeling) |
| 9 | 10/30 | Pong Game #3 (Graphics device modeling and testbench implementation) |
| 10 | 11/6 | Pong Game #4 (Bitmap image implementation) |
| 11 | 11/13 | Pong Game #5 (BFM modeling and simulation acceleration techniques) | 
| 12 | 11/20 | Pong Game #6 (Finite State Machines and external interrupt handling) | 
| 13 | 11/27 | Pong Game #7 (Co-Emulation verification) |
| 14 | 12/4 | Pong Game #8 (Synthesis, Sign-off) | 
| 15 | 12/11 | Pong Game #9 (My Chip fabrication completion)| 
| 16 |   -   | My Chip fabrication completion |
