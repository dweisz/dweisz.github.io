---
title: "Team"
layout: gridlay
sitemap: false
permalink: /team/
---

## PI

<div class="section-card">
<div class="pi-card">
<img src="{{ site.url }}{{ site.baseurl }}/images/{{ site.photo }}" class="pi-photo" alt="{{ site.name }}" loading="lazy">
<div>
<h3 class="pi-name">{{ site.name }}</h3>
<p style="font-style: italic; color: var(--text-secondary);">{{ site.title }}, {{ site.institution }}</p>
<div class="pi-links">
{% if site.email %}<a href="mailto:{{ site.email }}" class="icon-link" title="Email"><i class="fa-solid fa-envelope"></i></a>{% endif %}
{% if site.links.google_scholar and site.links.google_scholar != "" %}<a href="{{ site.links.google_scholar }}" class="icon-link" title="Google Scholar"><i class="ai ai-google-scholar"></i></a>{% endif %}
{% if site.links.cv and site.links.cv != "" %}<a href="{{ site.url }}{{ site.baseurl }}/{{ site.links.cv }}" class="icon-link" title="CV"><i class="ai ai-cv"></i></a>{% endif %}
{% if site.links.github and site.links.github != "" %}<a href="{{ site.links.github }}" class="icon-link" title="GitHub"><i class="fa-brands fa-github"></i></a>{% endif %}
{% if site.links.researchgate and site.links.researchgate != "" %}<a href="{{ site.links.researchgate }}" class="icon-link" title="ResearchGate"><i class="ai ai-researchgate"></i></a>{% endif %}
</div>
{% if site.data.pi[0].education %}
<ul style="margin-top: var(--space-4);">
{% for education in site.data.pi[0].education %}
<li>{{ education | replace: "-","&#8211;" }}</li>
{% endfor %}
</ul>
{% endif %}
</div>
</div>
</div>

{% if site.data.team_members.size > 0 %}
{% assign students = site.data.team_members | where_exp: "item", "item.info contains 'PhD' or item.info contains 'Student' or item.info contains 'Postbac'" %}
{% assign postdocs = site.data.team_members | where_exp: "item", "item.info contains 'Postdoc' or item.info contains 'Postdoctoral' or item.info contains 'Fellow'" %}
{% assign others = site.data.team_members | where_exp: "item", "item.info contains 'Visiting'" %}

{% if students.size > 0 %}
## Students

<div class="team-grid">
{% for member in students %}
<div class="team-card">
{% if member.photo and member.photo != '' %}<img src="{{ site.url }}{{ site.baseurl }}/images/{{ member.photo }}" class="team-photo" alt="{{ member.name }}" loading="lazy">{% else %}<span class="team-photo team-photo-placeholder" role="img" aria-label="{{ member.name }}"><i class="fa-solid fa-user"></i></span>{% endif %}
<h4 class="team-name">{{ member.name }}</h4>
<p class="team-info">{{ member.info }}</p>
<div class="team-links">
{% if member.email %}<a href="mailto:{{ member.email }}" class="icon-link" title="Email"><i class="fa-solid fa-envelope"></i></a>{% endif %}
{% if member.website %}<a href="{{ member.website }}" class="icon-link" title="Website"><i class="fa-solid fa-house"></i></a>{% endif %}
{% if member.scholar %}<a href="{{ member.scholar }}" class="icon-link" title="Google Scholar"><i class="ai ai-google-scholar"></i></a>{% endif %}
{% if member.github %}<a href="{{ member.github }}" class="icon-link" title="GitHub"><i class="fa-brands fa-github"></i></a>{% endif %}
</div>
</div>
{% endfor %}
</div>
{% endif %}

{% if postdocs.size > 0 %}
## Postdocs

<div class="team-grid">
{% for member in postdocs %}
<div class="team-card">
{% if member.photo and member.photo != '' %}<img src="{{ site.url }}{{ site.baseurl }}/images/{{ member.photo }}" class="team-photo" alt="{{ member.name }}" loading="lazy">{% else %}<span class="team-photo team-photo-placeholder" role="img" aria-label="{{ member.name }}"><i class="fa-solid fa-user"></i></span>{% endif %}
<h4 class="team-name">{{ member.name }}</h4>
<p class="team-info">{{ member.info }}</p>
<div class="team-links">
{% if member.email %}<a href="mailto:{{ member.email }}" class="icon-link" title="Email"><i class="fa-solid fa-envelope"></i></a>{% endif %}
{% if member.website %}<a href="{{ member.website }}" class="icon-link" title="Website"><i class="fa-solid fa-house"></i></a>{% endif %}
{% if member.scholar %}<a href="{{ member.scholar }}" class="icon-link" title="Google Scholar"><i class="ai ai-google-scholar"></i></a>{% endif %}
{% if member.github %}<a href="{{ member.github }}" class="icon-link" title="GitHub"><i class="fa-brands fa-github"></i></a>{% endif %}
</div>
</div>
{% endfor %}
</div>
{% endif %}

{% if others.size > 0 %}
## Other Members

<div class="team-grid">
{% for member in others %}
<div class="team-card">
{% if member.photo and member.photo != '' %}<img src="{{ site.url }}{{ site.baseurl }}/images/{{ member.photo }}" class="team-photo" alt="{{ member.name }}" loading="lazy">{% else %}<span class="team-photo team-photo-placeholder" role="img" aria-label="{{ member.name }}"><i class="fa-solid fa-user"></i></span>{% endif %}
<h4 class="team-name">{{ member.name }}</h4>
<p class="team-info">{{ member.info }}</p>
<div class="team-links">
{% if member.email %}<a href="mailto:{{ member.email }}" class="icon-link" title="Email"><i class="fa-solid fa-envelope"></i></a>{% endif %}
{% if member.website %}<a href="{{ member.website }}" class="icon-link" title="Website"><i class="fa-solid fa-house"></i></a>{% endif %}
{% if member.scholar %}<a href="{{ member.scholar }}" class="icon-link" title="Google Scholar"><i class="ai ai-google-scholar"></i></a>{% endif %}
{% if member.github %}<a href="{{ member.github }}" class="icon-link" title="GitHub"><i class="fa-brands fa-github"></i></a>{% endif %}
</div>
</div>
{% endfor %}
</div>
{% endif %}
{% endif %}

{% if site.data.affiliates.size > 0 %}
## Group Affiliates

<div class="team-grid">
{% for member in site.data.affiliates %}
<div class="team-card">
{% if member.photo and member.photo != '' %}<img src="{{ site.url }}{{ site.baseurl }}/images/{{ member.photo }}" class="team-photo" alt="{{ member.name }}" loading="lazy">{% else %}<span class="team-photo team-photo-placeholder" role="img" aria-label="{{ member.name }}"><i class="fa-solid fa-user"></i></span>{% endif %}
<h4 class="team-name">{{ member.name }}</h4>
<p class="team-info">{{ member.info }}</p>
<div class="team-links">
{% if member.email %}<a href="mailto:{{ member.email }}" class="icon-link" title="Email"><i class="fa-solid fa-envelope"></i></a>{% endif %}
{% if member.website %}<a href="{{ member.website }}" class="icon-link" title="Website"><i class="fa-solid fa-house"></i></a>{% endif %}
{% if member.scholar %}<a href="{{ member.scholar }}" class="icon-link" title="Google Scholar"><i class="ai ai-google-scholar"></i></a>{% endif %}
{% if member.github %}<a href="{{ member.github }}" class="icon-link" title="GitHub"><i class="fa-brands fa-github"></i></a>{% endif %}
</div>
</div>
{% endfor %}
</div>
{% endif %}

{% if site.data.alumni.size > 0 %}
## Alumni

<div class="section-card">
<table class="alumni-table">
<thead>
<tr><th>Name</th><th>Role</th><th>Duration</th><th>Current Position</th></tr>
</thead>
<tbody>
{% for member in site.data.alumni %}
<tr>
<td>{{ member.name }}</td>
<td>{{ member.role }}</td>
<td>{{ member.duration }}</td>
<td>{{ member.info }}</td>
</tr>
{% endfor %}
</tbody>
</table>
</div>
{% endif %}

## Openings

We are always looking for motivated students and postdocs interested in astronomy research. Please see the [for students]({{ site.url }}{{ site.baseurl }}/for_students/) page for details on undergraduate, PhD, and postdoctoral opportunities.
