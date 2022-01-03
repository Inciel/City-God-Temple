---
title: City God Temple
layout: index
---

<h2>Introduction</h2>
<p>fshfsjcjsnvchfsjcjsnvcvdcvcvvxchfsjcjsnvcvdcvcvvxchfsjcjsnvcvdcvcvvxch
fsjcjsnvcvdcvcvvxchfsjcjsnvcvdcvcvvxchfsjcjsnvcvdcvcvvxcvdcvcvvxcnsc</p>

<div id= "exhibit">

   {% for exhibit in site.exhibits %}
      <div id = "grid_cell">
          <a href = "{{ exhibit.url | relative_url }}"><img src="{{ exhibit.index_image_url }}" width=500px height=auto></a>
          <p id=indextitle><a href = "{{ exhibit.url | relative_url }}"> {{ exhibit.name }} </a></p>
      </div>
   {% endfor %}

</div>