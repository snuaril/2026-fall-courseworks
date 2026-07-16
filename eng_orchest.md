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
- Attendance: TBD
- Assignment: TBD
- Final Exam: TBD
- Attitude: TBD
- Project: TBD

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
