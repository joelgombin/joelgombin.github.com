---
layout: page
title: "Welcome!"
---

I'm Joël. I'm new to [Github](http://www.github.com/joelgombin), and hopefully in the next months you'll find here some code. I mainly code in `R`, and I might do so more in the future with [François Briatte](http://phnk.com/).

The last blog entrys can be found below.




<section class="content">
  <ul class="listing">
    {% for post in site.posts %}
    <li>
      <span>{{ post.date | date: "%B %e, %Y" }}</span> <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
    {% endfor %}
  </ul>
</section>
