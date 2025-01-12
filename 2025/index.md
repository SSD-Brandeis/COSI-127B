---
layout: default
title: Home
nav_order: 1
description: "Database Management Systems (COSI 127B)"
banner_image: /assets/css/p2.jpg
banner_heading: "Database Management Systems"
banner_description: "COSI 127B"
permalink: /
---

|----------|----------|
| __Instructors__{: .fs-4} | [<u>Subhadeep Sarkar</u>](https://subhadeep.net){:target="_blank"}, Shubham Kaushik, and James Chen |
| __Class Timings & Location__{: .fs-4} | Tue & Fri 12:45 PM – 2:05 PM| Olin-Sang: 101|
| __Recitation Timings & Location__{: .fs-4} | Fri 3:20 PM – 4:20 PM| Abelson-Bass: 131|

## <u>Course Description</u>
We live in a data-driven world! In fact, every two days, we create as much data as we created from the dawn of humanity up to 2003. We generate an unprecedented amount of data every day through our daily activities in every facet of life, including business, governance, management, research, and scientific activities. Storing, managing, and accessing this large volume of data is an enormous challenge in the face of ever-changing application requirements and performance goals. Database systems are the backbone of any large-scale data management infrastructure. This class presents a comprehensive introduction to the fundamental concepts of database systems. We will start by discussing the classical approaches to database design and the fundamental building blocks and operating principles of database systems. The primary focus of the course will be on the core concepts of the internals of database systems, covering entity-relationship and relational data models, commercial relational query languages (SQL and relational algebra), file organization, storage and memory management, indexing and hashing, query optimization, query processing, transaction processing, concurrency control, and recovery. Finally, we will cover the new trends in data management in the era of big data and data management in the cloud to highlight the evolution of database systems over the years.

## <u>Prerequisites</u>
__COSI 21A__ and __COSI 12B__. A working knowledge of C/C++, Java, or Python programming and a fundamental understanding of data structures and algorithms is required. 

## <u>Learning Goals</u>
Students who successfully complete all components of this course will be able to demonstrate the following by the end of the semester.
1. Familiarization with the history and evolution of database management systems design over the past decades. 
2. Understanding of the importance and challenges associated with large-scale data management and analysis.
3.  Knowledge about the key components of a relational database system and their working principle. 
4. Ability to interact with relational data stores using a working knowledge of SQL.
5. Understanding of the fundamental performance tradeoffs in data structures and access methods design, and the importance of such design decisions on the overall performance of a relational data system. 
6. Understanding of the impact of the ever-changing workload and application requirements on the design of modern relational data systems. 

## Instructor

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

{% assign teaching_assistants = site.staffers | where: 'role', 'Teaching Assistant' %}
{% assign num_teaching_assistants = teaching_assistants | size %}
{% if num_teaching_assistants != 0 %}

## Teaching Assistants

{% for staffer in teaching_assistants %}
{{ staffer }}
{% endfor %}
{% endif %}
