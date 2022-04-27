--- 
layout: post
title: I nostri prossimi incontri
author: Staff Lions
---

Questi i nostri prossimi incontri

## I DIVISIONE Maschile

<a href="https://www.facebook.com/Lionsvolleylatina/">@lions_volley_latina</a> Vs. @asd.sud.pontino.pallavolo

## Under 15 Maschile

<a href="https://www.facebook.com/Lionsvolleylatina/">@lions_volley_latina</a> Vs. @sabaudiavolley

<a href="https://fb.watch/cEMHXnx4bC/">Carichi più che mai....</a>

{% assign sponsors = site.sponsors %}
{% for sponsor in sponsors %}
    {{ sponsor.url | prepend: site.baseurl }}
{% endfor %}
