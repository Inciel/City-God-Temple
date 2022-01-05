---
title: Gallery
layout: Gallery
---
<div>
<h2>Gallery</h2>
</div>

<div id= "exhibit">

   {% assign collections = site.exhibits | sort: "site" %}
   {% for exhibit in collections  %} 

  <div id = "grid_cell">
    <a href = "{{ exhibit.url | relative_url }}"> <img src="{{ exhibit.index_image_url }}" width=200px height=auto opacity=100> </a>

    <a href = "{{ exhibit.url | relative_url }}"> <p> {{ exhibit.name }} </p></a>

    <p> Build Time: {{ exhibit.time }} </p> 
 </div>

{% endfor %}

</div>
