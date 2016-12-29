---
layout: default
---

<body>
  <div class="index-wrapper">
    <div class="aside">
      <div class="info-card">
        <h1>Henry Yang</h1>
        <a href="http://weibo.com/henryyangmicroblog" target="_blank"><img src="http://www.weibo.com/favicon.ico" alt="" width="25"/></a>
        <a href="https://twitter.com/yanghanyutwitte" target="_blank"><img src="https://twitter.com/favicon.ico" alt="" width="25"/></a>
        <a href="https://github.com/henryyang1993" target="_blank"><img src="https://github.com/favicon.ico" alt="" width="25"/></a>
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
