---
layout: default
title: Home
---

<div id="the-list" class="list-group ">
    <a href="#" class="list-group-item list-group-item-action active">Classes</a>
    {% for item in site.data.vancamp %}
      <p> {{item.link}} - {{item.num}}</p>
    {% endfor %}
</div>

