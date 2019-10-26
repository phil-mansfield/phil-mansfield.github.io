---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---


You can also find my articles on <u><a href ="https://ui.adsabs.harvard.edu/search/filter_author_facet_hier_fq_author=AND&filter_author_facet_hier_fq_author=author_facet_hier%3A%221%2FMansfield%2C%20P%2FMansfield%2C%20Philip%22&filter_database_fq_database=OR&filter_database_fq_database=database%3A%22astronomy%22&fq=%7B!type%3Daqp%20v%3D%24fq_database%7D&fq=%7B!type%3Daqp%20v%3D%24fq_author%7D&fq_author=(author_facet_hier%3A%221%2FMansfield%2C%20P%2FMansfield%2C%20Philip%22)&fq_database=(database%3A%22astronomy%22)&q=author%3A(%22mansfield%2C%20philip%22)&sort=date%20desc%2C%20bibcode%20desc&p_=0">ADS</a></u> and <u><a href="https://scholar.google.com/citations?user=DcN3RwQAAAAJ&hl=en&oi=ao">Google scholar</a></u>.

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
