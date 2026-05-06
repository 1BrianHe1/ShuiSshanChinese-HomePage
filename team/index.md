---
title: titles.team
nav:
  order: 4
  tooltip: tooltips.team
---

<style>
.team-department-title {
  font-size: 2.5rem;
  color: var(--primary);
  font-weight: var(--bold);
  text-align: center;
  margin: 60px auto 40px auto;
  padding: 30px 20px;
  max-width: 1200px;
  background: linear-gradient(135deg, rgba(255, 255, 255, 0.95), rgba(232, 243, 232, 0.95));
  border-radius: 16px;
  box-shadow: 0 4px 20px rgba(95, 184, 120, 0.2);
  border-left: 6px solid var(--primary);
}

.portrait {
  width: 180px !important;
  max-width: 180px !important;
  margin: 30px !important;
}

.portrait-image {
  width: 180px !important;
  height: 180px !important;
}

.portrait-name {
  font-size: 1.3rem !important;
  font-weight: var(--bold) !important;
  margin-top: 10px !important;
}

.portrait-description {
  font-size: 1.1rem !important;
  margin-top: 8px !important;
}
</style>

<div class="page-wrapper">
<div class="page-content">

{% if site.lang == 'zh' %}

<h1 class="page-title">{% include icon.html icon="fa-solid fa-users" %} 水杉中文团队</h1>

华东师范大学**数据科学与工程学院**、**国际汉语文化学院**和**华东师范大学孔子学院工作办公室**的研究团队紧密合作，依托研究团队在数据科学与工程、人工智能、国际中文教育领域的深厚积淀和扎实基础。

{% else %}

<h1 class="page-title">{% include icon.html icon="fa-solid fa-users" %} Shuishan Chinese Team</h1>

The research team from **School of Data Science and Engineering**, **School of International Chinese Language and Culture**, and **Office of Confucius Institute** at East China Normal University work closely together, leveraging deep expertise in data science, artificial intelligence, and international Chinese education.

{% endif %}

{% include section.html %}

<div class="team-department-title">
  {% if site.lang == 'zh' %}
    {% include icon.html icon="fa-solid fa-building-columns" %} 数据科学与工程学院
  {% else %}
    {% include icon.html icon="fa-solid fa-building-columns" %} School of Data Science and Engineering
  {% endif %}
</div>

{% include list.html data="members" component="portrait" filter="department == 'dase'" %}

{% include section.html %}

<div class="team-department-title">
  {% if site.lang == 'zh' %}
    {% include icon.html icon="fa-solid fa-building-columns" %} 国际汉语文化学院
  {% else %}
    {% include icon.html icon="fa-solid fa-building-columns" %} School of International Chinese Language and Culture
  {% endif %}
</div>

{% include list.html data="members" component="portrait" filter="department == 'sichcc'" %}

{% include section.html %}

{% if site.lang == 'zh' %}
## 加入我们

我们欢迎对中文教育技术、人工智能和在线教育感兴趣的研究人员和学生加入我们的团队。如有兴趣，请通过联系页面与我们取得联系。

{% else %}
## Join Us

We welcome researchers and students interested in Chinese education technology, artificial intelligence, and online education to join our team. If interested, please contact us through the contact page.

{% endif %}

</div>
</div>
