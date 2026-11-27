---
layout: page
title: INSIDE
subtitle: Digital twin for post-operative monitoring of implanted knee
permalink: /
redirect_from:
  - /about/
  - /about.html
---

<img width="120" src="../assets/img/funding/Logo_France_2030.svg" style="float: right; margin-left: 30px; clear:both;"/>

Total knee arthroplasty is the most common joint replacement surgery, with revision rates varying by surgical approach. Postoperative dissatisfaction can increase further in revision cases; it is often linked to persistent pain or limited function, significantly impacting quality of life. 
Beyond infection risks, dissatisfaction has been associated with improper implant positioning, joint instability, mechanical complications (loosening, wear), unbalanced surrounding tissues, and patella overloading.

The INSIDE project centers the digital twin (DT) on the implanted prosthesis within its human environment, leveraging existing multi-scale models to improve prediction of patient dissatisfaction. The project unites research teams with expertise in patient monitoring across different levels: patient/clinical, joint/implant, bone, and cellular. These multi-scale, multi-fidelity data will be merged using  metamodels that account for both measurement and simulation uncertainty. Supported by a Technical Industrial Center and a DT company, INSIDE will develop a knee prosthesis DT updated with patient-specific data to predict complications early.

The INSIDE project (grant number ANR-25-PESN-0007) is funded under the [PEPR Santé Numérique](https://www.inria.fr/fr/pepr-sante-numerique-projets). Coordinated by University Lyon 1, the consortium brings together seven partner teams: LBMC, HCL, LYOS, LaMCoS, CETIM, TIMC, Platon, LIO - ETS and TwinSight.

<img width="600" src="../assets/img/partners_map.svg" style="display: block; margin: 0 auto;" />


# General Presentation

INSIDE, funded for 4 years, is divided into 5 Work Packages (WPs).

{% for post in site.wps %}
    {% include wps.html %}
{% endfor %}
