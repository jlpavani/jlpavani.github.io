---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

[6] Oliveira, C.M.; **Pavani, J.**; Liu, C.; Balcells-Camps, M.; Capasso, R.; Alvim, R.O.; Mourão-Junior, C.A.; Krieger, J.E.; Pereira, A.C.: Comparing different metabolic indexes to predict type 2 diabetes mellitus in a five years follow-up cohort: The Baependi Heart Study. *PLoS One*, 2022. [**To Appear**]

[5] **Pavani, J.**; Moraga, P.: A Bayesian joint spatio-temporal model for multiple mosquito-borne diseases. Methodological and Computational Contributions on Bayesian Statistics: BAYSM 2021, *Springer Proceedings in Mathematics & Statistics*, 2022. [**To Appear**]

[4] Oliveira, C.M.; Rosa, F.F.; Alvim, R.O.; Mourão-Junior, C.A.; Balcells-Camps, M.; Liu, C.; **Pavani, J.**; Capasso, R.; Dias, F.A.L.; Krieger, J.E.;  Pereira, A.C.: Body mass index is superior to other body adiposity indexes in predicting incident hypertension in a highly admixed sample after 10-year follow-up: The Baependi Heart Study. *The Journal of Clinical Hypertension*, 2022. [[DOI](https://doi.org/10.1111/jch.14480)]

[3] Oliveira, C.M.; **Pavani, J.**; Krieger, J.E.; Alvim, R.O.; Balcells-Camps, M.; Mourão-Junior, C.A.; Pereira, A.C.; Liu, C.: Triglyceride glucose index as a tool to motivate early lifestyle modification in young adults at diabetes risk: The Baependi Heart Study. *Preventive Medicine Reports*, 20, 1-4, 2020. [[DOI](https://doi.org/10.1016/j.pmedr.2020.101172)]

[2] **Pavani, J.**; Alvares, D.: Statistically validating patient self-reporting questionnaires in medicine. *SAGE Research Methods Cases: Medicine & Health*, 1-19, 2020. [[DOI](https://dx.doi.org/10.4135/9781529726763)]

[1] Oliveira, C.M.; **Pavani, J.**; Krieger, J.E.; Alvim, R.O.; Mourão-Junior, C.A.; Pereira, A.C.: Body adiposity index accessing the type 2 diabetes mellitus development risk: The Baependi Heart Study. *Diabetology & Metabolic Syndrome*, 11(76), 76-80, 2019. [[DOI](https://doi.org/10.1186/s13098-019-0467-1)]

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
