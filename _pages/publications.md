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

<details class="pub-section" open>
<summary><span class="h2">JCR journals</span></summary>
{% for y in page.years %}
<details class="pub-year"{% if forloop.index <= 2 %} open{% endif %}>
<summary><span class="year">{{ y }}</span></summary>
<div class="bibwrap">
{% bibliography -f aamor_journals -q @*[year={{y}}]* %}
</div>
</details>
{% endfor %}
</details>

<details class="pub-section" open>
<summary><span class="h2">conferences</span></summary>
{% for y in page.conference_years %}
<details class="pub-year"{% if forloop.index <= 2 %} open{% endif %}>
<summary><span class="year">{{ y }}</span></summary>
<div class="bibwrap">
{% bibliography -f aamor_conferences -q @*[year={{y}}]* %}
</div>
</details>
{% endfor %}
</details>

{% comment %}
<details class="pub-section" open>
<summary><h2 style="display:inline">Ph.D. thesis</h2></summary>
<details class="pub-year" open>
<summary><h3 class="year" style="display:inline">2018</h3></summary>
{% bibliography -f aamor_phd %}
</details>
</details>
{% endcomment %}

</div>
