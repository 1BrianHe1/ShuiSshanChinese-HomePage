---
title: titles.projects
# nav:
#   order: 3
#   tooltip: tooltips.projects
---

<div class="page-wrapper">
<div class="page-content">

{% if site.lang == 'zh' %}

<h1 class="page-title">{% include icon.html icon="fa-solid fa-wrench" %} 研究项目</h1>

## 水杉中文 - AI赋能的国际中文在线学习平台

我们致力于开发基于人工智能技术的国际中文在线学习平台，通过创新的教学方法和智能化工具，为全球中文学习者提供更加高效、个性化的学习体验。

### 研究方向
- 智能化中文教学系统
- 自然语言处理在中文教育中的应用
- 个性化学习路径规划
- 在线教育平台架构

{% elsif site.lang == 'en' %}

<h1 class="page-title">{% include icon.html icon="fa-solid fa-wrench" %} Research Projects</h1>

## Shuishan Chinese - AI-Powered International Chinese Online Learning Platform

We are dedicated to developing an AI-powered online Chinese learning platform. Through innovative teaching methods and intelligent tools, we provide global Chinese learners with more efficient and personalized learning experiences.

### Research Areas
- Intelligent Chinese teaching systems
- Natural language processing in Chinese education
- Personalized learning path planning
- Online education platform architecture

{% endif %}

{% include section.html %}

## {% if site.lang == 'zh' %}进行中的项目{% else %}Ongoing Projects{% endif %}

{% include list.html component="card" data="projects" filter="group == 'active'" style="small" %}

{% include section.html %}

## {% if site.lang == 'zh' %}已完成的项目{% else %}Completed Projects{% endif %}

{% include list.html component="card" data="projects" filter="group == 'completed'" style="small" %}

</div>
</div>
