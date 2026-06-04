---
title: "About"
layout: gridlay
sitemap: false
permalink: /about/
---

## About

<div class="section-card">
<div class="pi-card">
<img src="{{ site.url }}{{ site.baseurl }}/images/{{ site.photo }}" class="pi-photo" alt="{{ site.name }}" loading="lazy">
<div>
<h3 class="pi-name">{{ site.name }}</h3>
<p style="font-style: italic; color: var(--text-secondary);">{{ site.title }}, {{ site.institution }}</p>
<div class="pi-links">
{% if site.email %}<a href="mailto:{{ site.email }}" class="icon-link" title="Email"><i class="fa-solid fa-envelope"></i></a>{% endif %}
{% if site.links.cv and site.links.cv != "" %}<a href="{{ site.url }}{{ site.baseurl }}/{{ site.links.cv }}" class="icon-link" title="CV"><i class="ai ai-cv"></i></a>{% endif %}
{% if site.links.google_scholar and site.links.google_scholar != "" %}<a href="{{ site.links.google_scholar }}" class="icon-link" title="Google Scholar"><i class="ai ai-google-scholar"></i></a>{% endif %}
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

<div class="section-card">
<h3>Research Focus</h3>
<p>My research investigates the star formation histories, chemical evolution, and structural properties of nearby galaxies—particularly dwarf galaxies and Local Group members like the Andromeda galaxy and the Magellanic Clouds. By studying resolved stellar populations across cosmic time, I aim to understand how galaxies form and evolve, the nature of dark matter, and the physics of star formation in diverse environments.</p>

<p>I am the Project Scientist and Stars & Galaxies Science Lead for <strong>UVEX (Ultraviolet Explorer)</strong>, a NASA MIDEX mission launching in the coming years to survey the ultraviolet sky. I also lead multiple Treasury programs with JWST and HST, including surveys of the Virgo Cluster and detailed studies of resolved stellar populations in nearby galaxies. My group has secured extensive observing time across major facilities including the Hubble Space Telescope, JWST, Keck Observatory, and the VLA.</p>
</div>

<div class="section-card">
<h3>Education & Career</h3>
<p><strong>Education:</strong> I completed a BA in Physics and Astrophysics from UC Berkeley in 2004, and earned my PhD in Astrophysics from the University of Minnesota in 2010, advised by Evan Skillman. My dissertation focused on the star formation histories of nearby dwarf galaxies.</p>

<p><strong>Career:</strong> After my PhD, I held postdoctoral positions at the University of Washington and served as a Hubble Fellow at UC Santa Cruz and the University of Washington. I have been on the faculty at UC Berkeley since 2016, first as an Assistant Professor and since 2020 as an Associate Professor in the Astronomy Department.</p>
</div>

{% if site.data.awards %}
<div class="section-card">
<h3>Awards & Honors</h3>
<ul>
{% for award in site.data.awards %}
<li>{{ award.name | replace: "-","&#8211;" }}</li>
{% endfor %}
</ul>
<p>Additional recognitions include the <strong>Newton Lacy Pierce Prize</strong> from the American Astronomical Society (2019), the <strong>Sloan Fellowship</strong> from the Alfred P. Sloan Foundation (2017), the <strong>Alexander Humboldt Fellowship</strong> (2018&#8211;2021), and the <strong>Hellman Faculty Fellowship</strong> (2018).</p>
</div>
{% endif %}

<div class="section-card">
<h3>Group & Mentoring</h3>
<p>I work with a group of graduate students and postdoctoral researchers studying nearby galaxies and resolved stellar populations. Current members and former group members are listed on the <a href="{{ site.url }}{{ site.baseurl }}/team/">team</a> page.</p>
</div>
