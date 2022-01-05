---
title: City God Temple
layout: index
---

<h2>Introduction</h2>
<p id="intro">
The culture of the City God in Taoist culture is part of traditional Chinese culture.
<br>
<br>
The ancient people built the city to protect their safety, so they built tall walls, towers, gates, trenches and moats. They believed that there were gods for things that were closely related to people's lives and well beings, so "City God" was worshipped by Chinese folk (Han Dynasty) and Taoists as the god of the city and the people respected him as " City God Master". Only those who have served the country with merit and virtue in history, and those who have been martyred for the benefit of the people, are eligible to be given this honour and have a shrine and temple built to commemorate them. City God is a magistrate in the underworld, and is associated with the city and has developed along with it. Both City God and ‘the cult of City God’ as a folk belief arose in tandem with the city. Taoism has incorporated the City God into its own deity system, describing him as a god who cuts off evil, protects the country and protects the state, and governs the souls of the dead in the underworld.
<br>
<br>
By listing the architectural features of City God temples across China and introducing the historical allusions, celebrities, myths and legends and folk tales behind them, this website aims to popularise the knowledge of City God culture, and to pass on and promote the values of City God culture, which speaks of benevolence and love, values the people, abides by honesty and integrity, upholds justice, promotes harmony and seeks common ground. Whether you are the kind of people who appreciate and love traditional Chinese Taoist culture, or you want to learn about City God culture, you will be able to deepen your understanding of Chinese Taoist culture and City God culture through the vivid image display and textual materials on this website.
</p>

<div id= "exhibit">

{% assign collections = site.exhibits | sort: "site" %}
   {% for exhibit in collections  %}
      <div id = "grid_cell">
          <a href = "{{ exhibit.url | relative_url }}"> <img src="{{ exhibit.index_image_url }}" ></a>
      </div>
   {% endfor %}

</div>
