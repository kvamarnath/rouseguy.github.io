---
title: Home
layout: default
---

## Upcoming Events 

<div>
{% for event in site.data.events %}
   <p class="event"> 
      <span class="date"> {{ event.date | upcase }} </span>
      <a href=" {{ event.url }}" > {{ event.name }} </a>
   </p>
{% endfor %}
</div>