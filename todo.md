---
layout:       todo
title:        "TODO"
subtitle:    
author:       "92ada"
header-img:   "img/todo-bg.jpg"
header-mask:  0.3
catalog:      true
multilingual: false
---

<!-- Chinese Version -->
<div class="zh post-container">
    {% capture about_zh %}{% include TODO/zh.md %}{% endcapture %}
    {{ about_zh | markdownify }}
</div>

<!-- English Version -->
<div class="en post-container">
    {% capture about_en %}{% include TODO/en.md %}{% endcapture %}
    {{ about_en | markdownify }}
</div>
