---
layout: page
permalink: /publications/
title: publications
description: publications by categories in reversed chronological order.
years: [2020]
nav: true
---


<div class="publications">

{% for y in page.years %}
  <h2 class="year">{{y}}</h2>
  <!-- {% raw %} {% bibliography -f papers -q @*[year={{y}}]* %} {% endraw %} -->
  @inproceedings{kim2020recsys,
    title={Do Channels Matter? Illuminating Interpersonal Influence on Music Recommendations},
    author={Kim, Hyun Jeong and Park, So Yeon and Park, Minju and Lee, Kyogu},
    booktitle={RecSys '20 Fourteenth ACM Conference on Recommender Systems}
    pages={663--668},
    year={2020},
    publisher={Association for Computing Machinery,}
  }
{% endfor %}

</div>
