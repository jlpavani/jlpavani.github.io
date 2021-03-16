---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

[3] Oliveira, C.M.; Pavani, J.; Krieger, J.E.; Alvim, R.O.; Balcells-Camps, M.; Mourão-Junior, C.A.; Pereira, A.C.; Liu, C.: Triglyceride glucose index as a tool to motivate early lifestyle modification in young adults at diabetes risk: The Baependi Heart Study. Preventive Medicine Reports, 2020, 20.

[2] Pavani, J.; Alvares, D.: Statistically validating patient self-reporting questionnaires in medicine, SAGE Research Methods: Medicine \& Health Cases, SAGE Publishing, 2020, 1-19.

[1] Oliveira, C.M.; Pavani, J.; Krieger, J.E.; Alvim, R.O.; Mourão-Junior, C.A.; Pereira, A.C.: Body adiposity index accessing the type 2 diabetes mellitus development risk: The Baependi Heart Study. Diabetology & Metabolic Syndrome, 2019, 11(76), 76-80.

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
