---
layout: page
title: 
tagline: Supporting tagline
---
{% include JB/setup %}

<<任它潮起潮落 且自静候花开>>	



######### 因为一无所有，所以无惧失去。我没有文采，没有深奥的思想，只有真诚的心。


####### <欢迎你的到来，和我一起听汐品茗>

			
			


\> Articles:

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
