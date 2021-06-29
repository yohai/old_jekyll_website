---
layout: publications
permalink: /publications/
title: publications
nav: true
---  
You can also check out my [google scholar profile](https://scholar.google.com/citations?user=b7Io-mAAAAAJ)
<div class="publications">
  {% assign sorted_pubs = site.publications | sort: "date" | reverse %}
  
    {% for pub in sorted_pubs %}
     {% include pubformat.html %} 
    {% endfor %}

</div>
Liked my publications? consider [praying for more](../assets/pdf/tefila.pdf)