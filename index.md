---
layout: page
title: 
tagline: Supporting tagline
---
{% include JB/setup %}

<<任它潮起潮落 且自静候花开>>     
                    
               
   
      
   
> 	>一无所有，所以无惧失去    
 
> 	>欢迎与我一起听汐品茗    



			
			


\> Articles:

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
