---
layout: page
permalink: /publications/
title: publications
years: [2025, 2024, 2023, 2022, 2021, 2020, 2019, 2018, 2017, 2016, 2015]
conference_years: [2025, 2024, 2023, 2022, 2021, 2019, 2018, 2017, 2016, 2015, 2014, 2013, 2012]
nav: true
nav_order: 1
---

<div class="publications">

{::nomarkdown}
<details class="pub-section" open>
  <summary><span class="h2">JCR journals</span></summary>
{:/}
{% for y in page.years %}
{::nomarkdown}
  <details class="pub-year"{% if forloop.index <= 2 %} open{% endif %}>
    <summary><span class="year">{{ y }}</span></summary>
  <div class="bibwrap">
{:/}
{% bibliography -f aamor_journals -q @*[year={{y}}]* %}
{::nomarkdown}
  </div>
  </details>
{:/}
{% endfor %}
{::nomarkdown}
</details>
{:/}

{::nomarkdown}
<details class="pub-section" open>
  <summary><span class="h2">conferences</span></summary>
{:/}
{% for y in page.conference_years %}
{::nomarkdown}
  <details class="pub-year"{% if forloop.index <= 2 %} open{% endif %}>
    <summary><span class="year">{{ y }}</span></summary>
  <div class="bibwrap">
{:/}
{% bibliography -f aamor_conferences -q @*[year={{y}}]* %}
{::nomarkdown}
  </div>
  </details>
{:/}
{% endfor %}
{::nomarkdown}
</details>
{:/}

</div>
