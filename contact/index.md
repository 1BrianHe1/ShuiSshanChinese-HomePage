---
title: titles.contact
nav:
  order: 6
  tooltip: tooltips.contact
---

<div class="page-wrapper">
<div class="page-content">

{% if site.lang == 'zh' %}

<h1 class="page-title">{% include icon.html icon="fa-regular fa-envelope" %}联系我们</h1>

## 水杉中文项目团队

### 联系方式

如果您对我们的研究项目感兴趣，或希望了解更多关于水杉中文在线学习平台的信息，欢迎通过以下方式与我们联系：

**邮箱：** your.email@example.com  
**电话：** +86-xxx-xxxx-xxxx

### 地址

您的大学/机构名称  
您的学院/系所  
详细地址

{% else %}

<h1 class="page-title">{% include icon.html icon="fa-regular fa-envelope" %}Contact Us</h1>

## Shuishan Chinese Project Team

### Contact Information

If you are interested in our research projects or would like to learn more about the Shuishan Chinese online learning platform, please feel free to contact us:

**Email:** your.email@example.com  
**Phone:** +86-xxx-xxxx-xxxx

### Address

Your University/Institution Name  
Your College/Department  
Detailed Address

{% endif %}

{%
  include button.html
  type="email"
  text="your.email@example.com"
  link="your.email@example.com"
%}
{%
  include button.html
  type="phone"
  text="+86-xxx-xxxx-xxxx"
  link="+86-xxx-xxxx-xxxx"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps"
  link="https://maps.google.com/"
%}

{% if site.lang == 'zh' %}
## 访问我们

在此处添加地图或访问指南...

{% else %}
## Visit Us

Add map or visiting guide here...

{% endif %}

<!-- 如需添加地图，取消下方注释并填入正确的地图嵌入代码
<div class="map-container">
  <iframe 
    src="YOUR_GOOGLE_MAPS_EMBED_URL" 
    width="100%" 
    height="450" 
    style="border:0;" 
    allowfullscreen="" 
    loading="lazy" 
    referrerpolicy="no-referrer-when-downgrade">
  </iframe>
</div>
-->

</div>
</div>
