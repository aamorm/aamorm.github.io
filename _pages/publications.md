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
<div class="pub-toolbar" aria-label="Publications controls">
  <button id="pub-expand-all" type="button" class="btn-small" aria-pressed="false">Expand all</button>
  <button id="pub-collapse-all" type="button" class="btn-small">Collapse all</button>
</div>
{:/}

{::nomarkdown}
<details class="pub-section" open>
  <summary><span class="h2">JCR journals</span></summary>
{:/}
{% for y in page.years %}
{::nomarkdown}
  <details class="pub-year" data-year="{{ y }}"{% if forloop.index <= 2 %} open{% endif %}>
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
  <details class="pub-year" data-year="{{ y }}"{% if forloop.index <= 2 %} open{% endif %}>
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

{::nomarkdown}
<script>
document.addEventListener('DOMContentLoaded', function () {
  const root = document.querySelector('.publications');
  if (!root) return;

  const btnExpand   = root.querySelector('#pub-expand-all');
  const btnCollapse = root.querySelector('#pub-collapse-all');
  if (!btnExpand || !btnCollapse) return;

  const allDetails = () => root.querySelectorAll('details');

  function setAll(open) {
    allDetails().forEach(d => { d.open = !!open; });
    updateState();
  }

  function updateState() {
    const details = allDetails();
    const openCount = Array.from(details).filter(d => d.open).length;
    const allOpen = details.length > 0 && openCount === details.length;

    btnExpand.setAttribute('aria-pressed', allOpen ? 'true' : 'false');
    // 👇 activa/desactiva el modo “todo expandido”
    root.classList.toggle('all-expanded', allOpen);
  }

  btnExpand.addEventListener('click', () => setAll(true));
  btnCollapse.addEventListener('click', () => setAll(false));

  root.addEventListener('toggle', (e) => {
    if (e.target.tagName === 'DETAILS') updateState();
  }, true);

  updateState();
});
</script>
{:/}

</div>
