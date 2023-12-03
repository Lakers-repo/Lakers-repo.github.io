---
layout: page
title: About
description: 只要我写的够快，bug就追不上我
comments: true
menu: 关于
permalink: /about/
---

Stay focused,Stay hungry.

<br>
**简单的编程爱好者**，只要我写的够快，bug就追不上我。

## Contact

<ul>
{% for website in site.data.social %}
<li>{{website.sitename }}：<a href="{{ website.url }}" target="_blank">@{{ website.name }}</a></li>
{% endfor %}
</ul>
