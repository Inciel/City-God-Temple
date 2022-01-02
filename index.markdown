---
title: City God Temple
layout: index
---

<div id="introduction">
  <h2>
  introduction
  </h2>
</div>

<div id= "exhibit">

   {% for exhibit in site.exhibits %}
      <div id = "grid_cell">
          <a href = "{{ exhibit.url | relative_url }}"><img src="{{ exhibit.index_image_url }}" width=200px height=auto></a>
          <p><a href = "{{ exhibit.url | relative_url }}"> {{ exhibit.name }} </a></p>
      </div>
   {% endfor %}

</div>