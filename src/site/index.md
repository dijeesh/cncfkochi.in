---
title: CNCF Kochi
subtitle: Cloud Native Compute Foundation - Kochi Community
layout: layouts/base.njk
---


## Welcome

We are a group of peoples interested in talking about Cloud Native and Open source Technologies. We’re excited about microservices, containers, the distributions that run them and the solutions that deploy, manage, and extend them. Any skill level is welcome. Contact us if you are interested in speaking at or sponsoring the meet-up. We welcome content and demos.



## Post pages


<ul class="listing">
{%- for page in collections.post -%}
  <li>
    <a href="{{ page.url }}">{{ page.data.title }}</a> -
    <time datetime="{{ page.date }}">{{ page.date | dateDisplay("LLLL d, y") }}</time>
  </li>
{%- endfor -%}
</ul>







