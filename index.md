---
layout: default
title: Home
display-title: "#NG2019"
is_home: true
order: 1
---

Elections Results for the 2019 General Elections as conducted by INEC, please see [Disclaimer](disclaimer)


<h2 class="f5 normal mt4 gray pb1 bb b--light-gray c-sans-serif">Latest Results</h2>

{% assign posts = site.posts | where_exp: "post", "post.note != true" %}

<ul class="list ma0 pa0 c-linky-visited">

{% include list.html post-limit=10 %}

</ul>

<hr class="pb4">
