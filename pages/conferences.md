---
layout: single
show_meta: false
title: Conferences
permalink: "/conferences/"
---

### 2017
<ul>
{% for conference in site.data.conferences2017 %}
<!-- {% assign conference = member[1] %} -->
  <li>
    <p> <a href="{{ conference.website }}" target="_blank">{{ conference.name }}</a> - {{ conference.city }} - {{ conference.country }}</p>
      {% if conference.slides != "" %}
         {% for slide in conference.slides %}
         <ul>
            <!-- <div class="column"> -->
            <a href="{{ slide }}" target="_blank">Slides {% if forloop.length != 1 %} #{{ forloop.index }} {% endif %}</a>
            <!-- </div> -->
         </ul>
         {% endfor %}
     {% endif %}
  </li>
{% endfor %}
</ul>


### 2016
<ul>
{% for conference in site.data.conferences2016 %}
<!-- {% assign conference = member[1] %} -->
  <li>
    <p> <a href="{{ conference.website }}" target="_blank">{{ conference.name }}</a> - {{ conference.city }} - {{ conference.country }}</p>
      {% if conference.slides != "" %}
         {% for slide in conference.slides %}
         <ul>
            <!-- <div class="column"> -->
            <a href="{{ slide }}" target="_blank">Slides {% if forloop.length != 1 %} #{{ forloop.index }} {% endif %}</a>
            <!-- </div> -->
         </ul>
         {% endfor %}
     {% endif %}
  </li>
{% endfor %}
</ul>

### 2015
<ul>
{% for conference in site.data.conferences2015 %}
<!-- {% assign conference = member[1] %} -->
  <li>
    <p> <a href="{{ conference.website }}" target="_blank">{{ conference.name }}</a> - {{ conference.city }} - {{ conference.country }}</p>
      {% if conference.slides != "" %}
         {% for slide in conference.slides %}
         <ul>
            <!-- <div class="column"> -->
            <a href="{{ slide }}" target="_blank">Slides {% if forloop.length != 1 %} #{{ forloop.index }} {% endif %}</a>
            <!-- </div> -->
         </ul>
         {% endfor %}
     {% endif %}
  </li>
{% endfor %}
</ul>

There are talks older than this ones (not listed on this website); I've been speaking at conferences since 2012. 

<!-- {% include conferences %} -->