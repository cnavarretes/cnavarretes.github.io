---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
ORCID <img src="https://orcid.org/assets/vectors/orcid.logo.icon.svg" alt="orcid" width="30"/> <a href="https://orcid.org/0000-0002-4777-9934" style="color:#84CC27">0000-0002-4777-9934</a>

You can find all my publications on <u><a href="https://ui.adsabs.harvard.edu/search/filter_author_facet_hier_fq_author=NOT&filter_author_facet_hier_fq_author=(*%3A*%20NOT%20author_facet_hier%3A%221%2FNavarrete%2C%20C%2FNavarrete%2C%20Carolina%22)&filter_author_facet_hier_fq_author=author_facet_hier%3A%221%2FNavarrete%2C%20C%2FNavarrete%2C%20C%C3%A9sar%20O%22&filter_database_fq_database=NOT&filter_database_fq_database=((database%3Aastronomy%20OR%20database%3Aphysics)%20NOT%20database%3A%22earthscience%22)&filter_database_fq_database=database%3A%22physics%22&fq=%7B!type%3Daqp%20v%3D%24fq_database%7D&fq=%7B!type%3Daqp%20v%3D%24fq_author%7D&fq_author=((*%3A*%20NOT%20author_facet_hier%3A%221%2FNavarrete%2C%20C%2FNavarrete%2C%20Carolina%22)%20NOT%20author_facet_hier%3A%221%2FNavarrete%2C%20C%2FNavarrete%2C%20C%C3%A9sar%20O%22)&fq_database=(((database%3Aastronomy%20OR%20database%3Aphysics)%20NOT%20database%3A%22earthscience%22)%20NOT%20database%3A%22physics%22)&q=%20author%3A%22Navarrete%2C%20C%22&sort=date%20desc%2C%20bibcode%20desc&p_=0">ADS</a>.</u>

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
