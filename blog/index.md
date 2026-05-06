---
title: titles.blog
nav:
  order: 5
  tooltip: tooltips.blog
---

<div class="page-wrapper">
<div class="page-content">

{% if site.lang == "zh" %}

<h1 class="page-title">{% include icon.html icon="fa-solid fa-newspaper" %} 新闻动态</h1>

欢迎来到水杉中文项目的新闻页面。在这里我们分享项目的最新进展，包括：

- {% include icon.html icon="fa-solid fa-bullhorn" %} 项目更新和新功能发布
- {% include icon.html icon="fa-solid fa-trophy" %} 获奖和认可
- {% include icon.html icon="fa-solid fa-handshake" %} 合作项目和活动
- {% include icon.html icon="fa-solid fa-graduation-cap" %} 学术成果和研讨会

<!-- ### 如何添加新闻

要添加新闻文章，在 `_i18n/zh/_posts/` 目录下创建新的 Markdown 文件，文件名格式为：`YYYY-MM-DD-标题.md` -->

{% elsif site.lang == "en" %}

<h1 class="page-title">{% include icon.html icon="fa-solid fa-newspaper" %} News</h1>

Welcome to the Shuishan Chinese project news page. Here we share the latest updates, including:

- {% include icon.html icon="fa-solid fa-bullhorn" %} Project updates and new feature releases
- {% include icon.html icon="fa-solid fa-trophy" %} Awards and recognitions
- {% include icon.html icon="fa-solid fa-handshake" %} Collaborative projects and events
- {% include icon.html icon="fa-solid fa-graduation-cap" %} Academic achievements and seminars

### How to Add News

<!-- To add news articles, create new Markdown files in `_i18n/en/_posts/` directory with filename format: `YYYY-MM-DD-title.md` -->

{% endif %}

{% include section.html %}

{% include search-box.html %}

<!-- {% include tags.html tags=site.tags %} -->

{% include search-info.html %}

{% include list.html data="posts" component="post-excerpt" %}

</div>
</div>
