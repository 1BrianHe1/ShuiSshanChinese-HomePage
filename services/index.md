---
title: titles.services
nav:
  order: 1
  tooltip: tooltips.services
---

<link rel="stylesheet" href="{{ '/_styles/service-blocks.css' | relative_url }}">

<div class="page-wrapper">
<div class="page-content">


{% if site.lang == 'zh' %}

<h1 class="page-title">{% include icon.html icon="fa-solid fa-globe" %}平台服务</h1>

<p class="page-intro">
水杉中文致力于为全球中文学习者和教育者提供全方位、智能化的在线学习与教学服务
</p>

<div class="services-grid">

<!-- 板块1: 碎片化学习APP -->
<div class="service-section">
  <div class="section-header">
    <div class="section-title">
      <h2>"水杉中文"碎片化学习APP</h2>
      <div class="section-subtitle">系统性知识建构 · 个性化学习体验</div>
    </div>
  </div>
  
  <div class="section-content">
    <div class="section-gallery-wrapper">
      <div class="section-gallery">
        <div class="gallery-container">
          <div class="gallery-item">
            <img src="{{ '/images/services/shuishanCN_APP.png' | relative_url }}" alt="水杉中文APP">
          </div>
          <div class="gallery-item">
            <img src="{{ '/images/services/Scenario_Learning.png' | relative_url }}" alt="场景沙盒学习">
          </div>
          <div class="gallery-item">
            <img src="{{ '/images/services/Theme_Challenge.jpg' | relative_url }}" alt="主题闯关">
          </div>
          <div class="gallery-item">
            <img src="{{ '/images/services/Practice.png' | relative_url }}" alt="练习模式">
          </div>
          <div class="gallery-item">
            <img src="{{ '/images/services/Recommendation.png' | relative_url }}" alt="智能推送">
          </div>
        </div>
        <div class="scroll-hint">← 滑动查看更多 →</div>
      </div>
      
      <div class="section-links">
        <a href="https://smartlearn.shuishan.net.cn/" class="link-btn" target="_blank">
          <i class="fas fa-rocket"></i> 访问平台
        </a>
        <a href="https://github.com/DASE-CogAI/Shuishan-ChineseEdu" class="link-btn secondary" target="_blank">
          <i class="fab fa-github"></i> 项目简介
        </a>
        <a href="https://b23.tv/4tOPLWG" class="link-btn secondary" target="_blank">
          <i class="fas fa-video"></i> 视频介绍
        </a>
      </div>
    </div>
    
    <div class="section-description">
      <p>平台探索多样化的碎片化语言学习新模式。</p>
      
      <h3>🎮 场景沙盒 </h3>
      <p>告别千篇一律的课本对话，通过「场景沙盒」构建高度定制的中文应用场景。平台依托前沿的通用大模型技术，深度融合文本、图像、音频、视频乃至交互式元素等多种信息模态，构建出沉浸式、动态化、高互动性的智能学习环境。</p>
      
      <h3>🏆 主题闯关 </h3>
      <p>设计富有挑战性和故事性的任务链，将知识点嵌入层层递进的游戏化关卡中。平台持续利用多模态内容生成技术丰富契合特定主题的学习内容。</p>
      
      <h3>🎯 智能推送 </h3>
      <p>基于全域数据采集进行行为分析与特征建模，动态重构学习者画像，实时调整学习内容与路径，实现高效、智能、个性化的学习体验。</p>
    </div>
  </div>
</div>

<!-- 板块2: 教学管理平台 -->
<div class="service-section">
  <div class="section-header">
    <div class="section-title">
      <h2>"水杉中文"一站式中文教学管理平台</h2>
    </div>
  </div>
  
  <div class="section-content">
    <div class="section-gallery-wrapper">
      <div class="section-gallery">
        <div class="gallery-container">
          <div class="gallery-item">
            <img src="{{ '/images/services/2-Student_Port.png' | relative_url }}" alt="学生门户">
          </div>
          <div class="gallery-item">
            <img src="{{ '/images/services/2-Teacher_HSK.png' | relative_url }}" alt="HSK难度改写工具">
          </div>
          <div class="gallery-item">
            <img src="{{ '/images/services/2-Teacher-Writing.png' | relative_url }}" alt="作文批改工具">
          </div>
          <div class="gallery-item">
            <img src="{{ '/images/services/2-Teacher_Practice.png' | relative_url }}" alt="智能习题生成">
          </div>
        </div>
        <div class="scroll-hint">← 滑动查看更多 →</div>
      </div>
      
      <div class="section-links">
        <a href="https://manage.shuishan.net.cn/home" class="link-btn" target="_blank">
          <i class="fas fa-chalkboard-user"></i> 教师门户
        </a>
        <a href="https://cn.shuishan.net.cn/home" class="link-btn" target="_blank">
          <i class="fas fa-user-graduate"></i> 学生门户
        </a>
        <a href="https://docs.qq.com/pdf/DRnRTUHN0S2VVbUFV" class="link-btn secondary" target="_blank">
          <i class="fas fa-book"></i> 使用手册
        </a>
      </div>
    </div>
    
    <div class="section-description">
      <p>兼顾<strong>"教、学、练、测、管"</strong>全链路的一站式中文教学平台，五个环节环环相扣。</p>
      
      <h3>智能中文教学工具</h3>
      <ul>
        <li>HSK细粒度等级难度改写</li>
        <li>实时作文留痕批改</li>
        <li>智能一键习题生成</li>
        <li>多模态内容融合（文本、图像、音视频）</li>
      </ul>
      
      <p>平台将AI能力精准拆解与轻量化封装，打造<strong>"小而美、快而准、易而稳"</strong>的智能教学工具，让中文教师的"教"与"管"更高效。</p>
    </div>
  </div>
</div>

<!-- 板块3: 知识图谱 -->
<div class="service-section">
  <div class="section-header">
    <span class="section-number">3</span>
    <div class="section-icon">🔗</div>
    <div class="section-title">
      <h2>国际中文教育知识图谱</h2>
      <div class="section-subtitle">38万节点 · 100万关系 · 三层本体</div>
    </div>
  </div>
  
  <div class="section-content">
    <div class="section-gallery-wrapper">
      <div class="section-gallery">
        <div class="gallery-container">
          <div class="gallery-item">
            <img src="{{ '/images/services/3-Knowledge-Graph.png' | relative_url }}" alt="国际中文教育知识图谱">
          </div>
          <div class="gallery-item">
            <img src="{{ '/images/services/3-Knowledge-Graph_2' | relative_url }}" alt="知识图谱结构展示">
          </div>
        </div>
        <div class="scroll-hint">← 滑动查看更多 →</div>
      </div>
      
      <div class="section-links">
        <a href="https://kg.chineseplus.net" class="link-btn" target="_blank">
          <i class="fas fa-diagram-project"></i> 访问知识图谱
        </a>
      </div>
    </div>
    
    <div class="section-description">
      <p>教育部中外语言交流合作中心围绕国际中文教育标准体系统筹规划，华东师范大学"水杉中文"团队协同攻关打造的<strong>首个大规模语义网络</strong>。</p>
      
      <h3>核心数据</h3>
      <ul>
        <li>整合<strong>16类实体</strong>：字、词、语法、文化点等</li>
        <li>覆盖超<strong>38万语言节点、100万语义关系</strong></li>
        <li>融合《国际中文教育中文水平等级标准》《HSK大纲》及《HSK3.0考试大纲》</li>
      </ul>
      
      <h3>三大分层本体结构</h3>
      <ul>
        <li><strong>语言知识层</strong>：汉字、词汇、语法等要素</li>
        <li><strong>评估资源层</strong>：可评测的海量题目资源</li>
        <li><strong>文化拓展层</strong>：语言+文化”双轨并进</li>
      </ul>
    </div>
  </div>
</div>

<!-- 板块4: 学习分析引擎 -->
<div class="service-section">
  <div class="section-header">
    <span class="section-number">4</span>
    <div class="section-icon">📊</div>
    <div class="section-title">
      <h2>个性化学习分析引擎</h2>
      <div class="section-subtitle"></div>
    </div>
  </div>
  
  <div class="section-content">
    <div class="section-gallery">
      <div class="gallery-container">
        <div class="gallery-item">
          <img src="{{ '/images/services/4-Learning_Analysis_1.png' | relative_url }}" alt="个性化学习分析">
        </div>
        <div class="gallery-item">
          <img src="{{ '/images/services/4-Learning_Analysis_2.png' | relative_url }}" alt="学习知识地图">
        </div>
      </div>
      <div class="scroll-hint">← 滑动查看更多 →</div>
    </div>
    
    <div class="section-description">
      <p>依托知识图谱提供的资源体系，融合行为数据追踪与多粒度学情评估，绘制可视、个性化知识地图、让学习者与系统都能精准把握中文学情。</p>
      
      <h3>核心能力</h3>
      <ul>
        <li><strong>精准评估 </strong>：数据驱动、精准定位薄弱环节 </li>
        <li><strong>·可视化地图</strong>：形成完整的学习历程画像</li>
        <li><strong> 定制化路径</strong>："一人一路"的定制化学习。</li>
      </ul>
    </div>
  </div>
</div>

<!-- 板块5: 数智人学伴 -->
<div class="service-section">
  <div class="section-header">
    <span class="section-number">5</span>
    <div class="section-icon">🤖</div>
    <div class="section-title">
      <h2>数智人中文学伴 - Liwa Pal</h2>
      <div class="section-subtitle">AI陪伴 · 自然交互 · 情感关怀</div>
    </div>
  </div>
  
  <div class="section-content">
    <div class="section-gallery">
      <div class="gallery-container">
        <div class="gallery-item">
          <img src="{{ '/images/services/5-liWA.png' | relative_url }}" alt="丽娃学伴 - Liwa Pal">
        </div>
      </div>
      <div class="scroll-hint">← 滑动查看更多 →</div>
    </div>
    
    <div class="section-description">
      <p><strong>丽娃学伴（LiWa Pal）</strong>为学习者，提供随时随地的陪伴式、交互式中文学习体验。</p>
      
      <h3>🗣️ 自然交互</h3>
      <p>支持稳定、自然的中文听说交互，依据学习者语言水平动态控制表达难度，使词汇、句式与交际任务与能力阶段相匹配，帮助学习者在贴近真实情境的对话中逐步提升中文理解与表达能力。</p>
      
      <h3>💡 情感关怀</h3>
      <p>关注学习者的情绪状态变化，适时调整教学节奏、反馈方式与激励策略，在关键学习节点提供鼓励与引导，缓解学习焦虑，增强学习信心。</p>
    </div>
  </div>
</div>

<!-- 板块6: 智辅工具集
<div class="service-section">
  <div class="section-header">
    <span class="section-number">6</span>
    <div class="section-icon">🛠️</div>
    <div class="section-title">
      <h2>国际中文教学智辅工具集</h2>
      <div class="section-subtitle">小而美 · 快而准 · 易而稳</div>
    </div>
  </div>
  
  <div class="section-content">
    <div class="section-gallery">
      <div class="gallery-container">
        <div class="gallery-item">
          <div class="placeholder">
            📸 HSK改写工具<br>
            <small>请添加图片/视频素材</small>
          </div>
        </div>
        <div class="gallery-item">
          <div class="placeholder">
            📸 作文批改工具<br>
            <small>请添加图片/视频素材</small>
          </div>
        </div>
        <div class="gallery-item">
          <div class="placeholder">
            📸 智能备课工具<br>
            <small>请添加图片/视频素材</small>
          </div>
        </div>
      </div>
      <div class="scroll-hint">← 滑动查看更多 →</div>
    </div>
    
    <div class="section-description">
      <p>团队深入调研一线教师真实痛点与核心需求，聚焦中文作为第二语言教学的关键环节，将前沿AI能力精准拆解与轻量化封装。</p>
      
      <h3>核心工具</h3>
      <ul>
        <li>✏️ <strong>HSK细粒度等级难度改写</strong>：自动调整教学材料难度</li>
        <li>📝 <strong>实时作文留痕批改</strong>：过程化写作指导与反馈</li>
        <li>📚 <strong>智能一键备课生成</strong>：快速生成完整教学方案</li>
        <li>🎯 <strong>个性化练习生成</strong>：针对性练习材料自动生成</li>
        <li>📊 <strong>学情智能分析</strong>：多维度学习数据可视化</li>
      </ul>
      
      <p>让教学工作更高效，让教师能够更专注于创造性教学活动。</p>
    </div>
  </div>
</div> -->

</div><!-- 结束 services-grid -->

{% else %}

<!-- 英文版类似结构 -->
<h1 class="page-title">{% include icon.html icon="fa-solid fa-globe" %}Platform Services</h1>

<p class="page-intro">
Shuishan Chinese is dedicated to providing comprehensive and intelligent online learning and teaching services for Chinese learners and educators worldwide
</p>

<div class="services-grid">

<!-- 英文版各板块内容... -->
<div class="service-section">
  <div class="section-header">
    <span class="section-number">1</span>
    <div class="section-icon">📱</div>
    <div class="section-title">
      <h2>Shuishan Chinese Fragmented Learning APP</h2>
      <div class="section-subtitle">Systematic Knowledge Construction · Personalized Learning</div>
    </div>
  </div>
  
  <div class="section-content">
    <div class="section-gallery">
      <div class="gallery-container">
        <div class="gallery-item">
          <div class="placeholder">
            📸 Scenario Sandbox<br>
            <small>Please add image/video</small>
          </div>
        </div>
      </div>
      <div class="scroll-hint">← Swipe for more →</div>
    </div>
    
    <div class="section-description">
      <p>The platform aims at systematic knowledge construction and explores diverse new models of fragmented learning.</p>
      
      <div class="section-links">
        <a href="https://smartlearn.shuishan.net.cn/" class="link-btn" target="_blank">
          <i class="fas fa-rocket"></i> Visit Platform
        </a>
        <a href="https://github.com/DASE-CogAI/Shuishan-ChineseEdu" class="link-btn secondary" target="_blank">
          <i class="fab fa-github"></i> Project Info
        </a>
      </div>
    </div>
  </div>
</div>

<!-- 其他板块省略，结构相同 -->

</div><!-- 结束 services-grid -->

{% endif %}

</div>
</div>
