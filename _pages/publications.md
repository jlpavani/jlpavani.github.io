---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Oliveira, C.M.; \textbf{Pavani, J.}; Krieger, J.E.; Alvim, R.O.; Mourão-Junior, C.A.; Pereira, A.C.: Body adiposity index accessing the type 2 diabetes mellitus development risk: The Baependi Heart Study. Diabetology & Metabolic Syndrome, 2019, 11(76), 76-80.

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
