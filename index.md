---
layout: page
title: Rubaci
tagline: Local Ruby User Group in Ostrava
---
{% include JB/setup %}

Pro všechny příznivce programovacího jazyka Ruby, frameworku Ruby on Rails, Sinatra aj.

## Základní informace

Příhlášky na pravidelné srazy (meetup) na [srazy.info](http://srazy.info/rubaci-cz-meetup/2347)

[Důležité informace o srazech](/meetup-info.html)

[Github repozitář stránek](https://github.com/3lancers/rubaci_cz)

Facebook profil [Rubaci.cz](http://www.facebook.com/rubaci), Twitter [@rubaci_cz](https://twitter.com/#!/rubaci_cz)

## Následující meetup

Předpokládaný termín 26.6.2012 (čekám na potvrzení od CPITu)
    
## Blog

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

