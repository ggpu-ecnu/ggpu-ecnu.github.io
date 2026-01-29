---
layout: archive
title: "Teaching and Students"
permalink: /teaching/
author_profile: true
---

{% include base_path %}

## Student Recruitment

I am always looking for self-motivated Ph.D. and Master students to join my group.

*   **Requirements (Ph.D./Master):** 1-2 Ph.D. students and 2-3 Master students per year.
*   **For candidates:** I am looking for students who are upright, diligent, love coding, enjoy thinking, and have the ability to work under pressure.

## His Research Principles

1.  **Problem and tool-driven research:** Solve a problem, develop a tool, and help the industry.
2.  **Solve real problems:** Solve open problems or real problems that exist in the industry.
3.  **From software to system:** Not only write code, but also develop software systems, either open source or commercial.

## Former Students (Only list those who are active in academia)

*   [Siyuan Jiang](https://www.emich.edu/computer-science/faculty/s-jiang.php), Associate Professor at Eastern Michigan University
*   [Jianwen Li](https://lijwen2748.github.io/) (with Jifeng He), Professor at ECNU
*   [Ting Su](https://tingsu.github.io/) (with Jifeng He), Professor at ECNU
*   [Yueling Zhang](https://scholar.google.com/citations?user=-g6QrssAAAAJ&hl=en), Associate Professor at ECNU
*   [Shufang Zhu](https://shufang-zhu.github.io/), Assistant Professor at University of Liverpool
*   [Chengyu Zhang](https://chengyuzhang.com/), Assistant Professor at Loughborough University
*   [Jingling Sun](https://jinglingsun.github.io/), Assistant Professor at UESTC
*   [Yechuan Xia](https://dblp.org/pid/317/0591.html), Research Fellow at ECNU

<hr>

## Teaching

{% assign teaching_items = site.teaching | sort: 'date' | reverse %}
{% for post in teaching_items %}
### {{ post.title }}

<p>{{ post.type }}{% if post.venue %}, <i>{{ post.venue }}</i>{% endif %}{% if post.date %}, {{ post.date | date: "%Y" }}{% endif %}</p>

{{ post.content }}

<hr>
{% endfor %}
