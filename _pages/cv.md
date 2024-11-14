---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education 教育经历
======
* Bilibili University 哔哩哔哩大学
* Bilibili University High School 哔哩哔哩大学附属中学
* Bilibili University Primary School 哔哩哔哩大学附属小学  

Work experience 工作经历
======
* Tech enthusiast 科技爱好者

Skills 技能
======
* C/C++
* Python

Publications 出版物
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks 演讲
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching 教育
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership 服务和领导
======
* I'm just a student bro 我只是一个学生而已，哥们
