---
layout: default
---

<body>
  <div class="index-wrapper">
    <div class="aside">
      <div class="info-card">
        <h1>HongYii</h1>
        <a href="https://space.bilibili.com/7719769" target="_blank"><img src="https://www.bilibili.com/favicon.ico" alt="" width="25"/></a>
        <a href="http://wpa.qq.com/msgrd?v=3&uin=1491516376&site=qq&menu=yes" target="_blank"><img src="http://im.qq.com/favicon.ico" alt="" width="22"/></a>
        <a href="mailto:18977940567@189.cn?subject=交个朋友？" target="_blank"><img src="http://mail.189.cn/favicon.ico" alt="" width="22"/></a>
      </div>
      <div id="particles-js"></div>
    </div>

    <div class="index-content">
      <ul class="artical-list">
        {% for post in site.categories.blog %}
        <li>
          <a href="{{ post.url }}" class="title">{{ post.title }}</a>
          <div class="title-desc">{{ post.description }}</div>
        </li>
        {% endfor %}
      </ul>
    </div>
  </div>
</body>
