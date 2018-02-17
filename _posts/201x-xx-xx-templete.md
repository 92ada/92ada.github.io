---
layout:       post
title:        " "
subtitle:     ""
date:         201x-xx-xx xx:xx:xx
author:       "92ada"
header-img:   "img/in-post/xx.jpg"
header-mask:  0.3
catalog:      true
multilingual: false
tags:
    - xx
    - xx
---

<!-- Chinese Version -->
<div class="zh post-container">
    {% capture about_zh %}{% include posts/20xx-xx-xx-xx/zh.md %}{% endcapture %}
    {{ about_zh | markdownify }}
</div>

<!-- English Version -->
<div class="en post-container">
    {% capture about_en %}{% include posts/20xx-xx-xx-xx/en.md %}{% endcapture %}
    {{ about_en | markdownify }}
</div>
