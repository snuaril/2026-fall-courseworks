---
layout: page
title: 'Engineering Orchestration'
description: >-
    Course policies and information.
---
# Engineering Orchestration
M2177.011600
> This course uses the principles of musical orchestration as a medium to develop the coordination, integration, and collaboration skills required in engineering projects through a project-based learning format. Students will learn basic music theory and the scientific concepts of sound such as acoustics and resonance, and will cultivate creativity and teamwork through simple composition, arrangement, and ensemble performance. Practical workshops will include music creation using AI and other digital tools, as well as group activities that highlight the importance of balance, timing, and cooperation, putting into practice the fusion of technical design and emotional expression. Ultimately, the course aims to complement the result-oriented and efficiency-driven nature of engineering thinking, while enhancing empathy, emotional intelligence, and leadership skills.

- __Location__: Bld 43-201
- __Lecture__: Thursday 14:00 – 16:50
  
## Instructors
{% assign instructors = site.staffers | where: 'role', 'instructor' %}
{% assign instructors_eng_orch = site.staffers | where: 'role', 'instructor_eng_orch' %}
{% assign all_instructors = instructors | concat: instructors_eng_orch %}
{% for staffer in all_instructors %}
{{ staffer }}
{% endfor %}

## Teaching Assistants
{% assign teaching_assistants = site.staffers | where: 'role', 'ta_eng_orch' %}
{% assign num_teaching_assistants = teaching_assistants | size %}
{% if num_teaching_assistants != 0 %}
{% for staffer in teaching_assistants %}
{{ staffer }}
{% endfor %}
{% endif %}

![]({{ '/assets/images/eng_orch/eng_orch_poster.jpeg' | relative_url }})

## Admin support
{% assign admins = site.staffers | where: 'role', 'admin_eng_orch' %}
{% for staffer in admins %}
{{ staffer }}
{% endfor %}

---

## Grading
- Attendance: 10%
- Task: 30%
- Medium: 20%
- Final: 30%
- Random Evaluation: 5%
- Etc: 5%

## Assignment
TBD

## Course Structure

| Part | Theme | Educational Meaning |
|:----:|----|----|
| 1 | Encounter | Listening to others, forming teams, recognizing difference |
| 2 | Rhythm | Timing, communication, role division, coordination |
| 3 | Harmony | Integration, creativity, narrative, AI co-creation |
| 4 | Performance | Final system integration and public presentation |

## Lecture Schedule

| Week | Theme |
|:----:|----|
| 1 | Course opening |
| 2 | Music Is Going Electric |
| 3 | AI and Music: Introduction and workshop |
| 4 | No in-class lecture for Korean Thanksgiving days |
| 5 | Team meeting and rehearsal |
| 6 | **Mid-performance in Gangwondo** |
| 7 | K-Pop workshop: Making beats and sampling |
| 8 | Writing Lyrics and Performing Chang (Traditional Korean Vocal Singing) or Rap |
| 9 | Conducting & orchestration |
| 10 | Understanding AI and Human for collaboration |
| 11 | Field Experience |
| 12 | Building the Performance Structure |
| 13 | Full Rehearsal |
| 14 | **Final performance** |
| 15 | Final report, reflection, and feedback |
