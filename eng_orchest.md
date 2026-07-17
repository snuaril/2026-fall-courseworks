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

## Teaching Assistant
{% assign teaching_assistants = site.staffers | where: 'role', 'ta_eng_orch' %}
{% assign num_teaching_assistants = teaching_assistants | size %}
{% if num_teaching_assistants != 0 %}
{% for staffer in teaching_assistants %}
{{ staffer }}
{% endfor %}
{% endif %}

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
| 1 | Why Orchestration? Why engineers need orchestration in the AI era<br />- Overview of course structure and projects |
| 2 | Encounter: team formation and percussion workshop<br />- Individual expertise and interests introduction |
| 3 | Where does inspiration come from?<br />- Team meeting and rehearsal |
| 4 | Midterm preparation during the Korean Thanksgiving period<br />- Online or team-based guidance |
| 5 | Rhythm: preparing the first team presentation |
| 6 | **Midterm Presentation**<br />- Possibly linked to SNU Arts Week |
| 7 | Percussion workshop: synchronizing rhythm among team members |
| 8 | Writing lyrics, chant, or rap<br />- Team workshop |
| 9 | Conducting and leadership: creating harmony without command |
| 10 | AI Co-Creation: is AI a tool, partner, or collaborator? |
| 11 | Narrative: connecting fragments into a meaningful story |
| 12 | Rehearsal 1: building the structure of the final project |
| 13 | Rehearsal 2: integrating the whole performance |
| 14 | **Final Performance** |
| 15 | Final report, reflection, and feedback |
