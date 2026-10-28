---
title: "Home"
layout: homelay
sitemap: false
permalink: /
---

<h2 class="home-hero">{{ site.name }}</h2>
<p class="home-hero-sub">{{ site.title }}, {{ site.institution }}<br>Affiliate Astronomer at Space Sciences Lab<br>Miller Professor</p>

<div class="chip-container" markdown="0">
<a href="{{ site.url }}{{ site.baseurl }}/research" class="chip">Galactic Archaeology</a>
<a href="{{ site.url }}{{ site.baseurl }}/research" class="chip">Resolved Stellar Populations</a>
<a href="{{ site.url }}{{ site.baseurl }}/research" class="chip">Stars and Galaxies</a>
<a href="{{ site.url }}{{ site.baseurl }}/research" class="chip">Near-Field Cosmology</a>
<a href="{{ site.url }}{{ site.baseurl }}/research" class="chip">Statistical Modeling</a>
<a href="{{ site.url }}{{ site.baseurl }}/research" class="chip">Space Telescopes</a>
</div>

My research focuses on understanding how galaxies form by studying the resolved stellar populations of nearby galaxies. Using observations from facilities like the Hubble Space Telescope and the James Webb Space Telescope, I investigate the formation histories, chemical abundance patterns of galaxies in and around the Local Group to constrain models of galaxy formation, dark matter distribution, and the physics of star formation across cosmic time. I lead several major observational programs, including a comprehensive <a href="https://archive.stsci.edu/hlsp/m31-satellites">HST survey of M31's satellite system</a>, the <a href="https://ers-stars.github.io/">JWST Early Release Science program on resolved stellar populations</a>, and the J-Virgo Treasury survey of the Virgo Cluster. As Project Scientist for the <a href="https://www.ipac.caltech.edu/project/uvex">Ultraviolet Explorer (UVEX) mission</a>, I am developing the next generation of UV surveys that will map millions of local low-mass star-forming galaxies, survey low-metallicity massive stars, provide new insights into the transient sky at UV wavelengths.

<div class="callout callout-success" markdown="0">
<div class="callout-title"><i class="fa-solid fa-bullhorn callout-icon"></i> We're Hiring: Postdoctoral Scholars</div>
<p>
I am seeking up to <strong>two postdoctoral scholars</strong> to join my group at UC Berkeley, starting Fall 2027. The positions focus on imaging and spectroscopy of resolved stellar populations in nearby galaxies with HST, JWST, Euclid, DESI, and Keck, including JWST/HST surveys of M31 and Local Group dwarfs, a JWST treasury program in the Virgo Cluster, a large JWST program on Centaurus A, and a Euclid survey of the Local Volume. Part of each position is available for independent research. The deadline to apply is <strong>December 15, 2026</strong>. <a href="https://aprecruit.berkeley.edu/JPF05593">Apply here &rarr;</a>
</p>
</div>

{% assign review_arxiv = "https://arxiv.org/abs/2610.36040" %}
{% assign review_movie = "https://doi.org/10.5281/zenodo.23627360" %}

<div class="banner-frame review-feature" markdown="0">
<a href="{% if review_arxiv != "" %}{{ review_arxiv }}{% else %}{{ review_movie }}{% endif %}" class="review-feature-img">
<img src="{{ site.url }}{{ site.baseurl }}/images/review-fig7.jpg" alt="Simulated dwarf galaxy rendered as resolved stars, with HST, JWST, Roman, and Rubin footprints and its star formation history, color-magnitude diagram, and chemical abundances" loading="lazy">
</a>
<div class="review-feature-body">
<div class="review-feature-kicker">Review Article · Physics Reports</div>
<div class="review-feature-title">The Stellar Populations of Resolved Galaxies</div>
<p>A review of galaxy formation through the lens of resolved stars, from the history of HST and the Local Group through the new frontiers with JWST, Roman, and Rubin. Image: Galaxy archaeology in practice for a simulated dwarf galaxy. The movie shows its evolution across cosmic time.</p>
<div class="review-feature-links">
{% if review_arxiv != "" %}<a href="{{ review_arxiv }}" class="chip"><i class="fa-solid fa-file-lines"></i> Read the review</a>{% else %}<span class="chip chip-pending"><i class="fa-solid fa-file-lines"></i> arXiv link coming soon</span>{% endif %}
<a href="{{ site.url }}{{ site.baseurl }}/images/review-fig7-fullres.jpg" class="chip"><i class="fa-solid fa-image"></i> Full-resolution figure</a>
<a href="{{ review_movie }}" class="chip"><i class="fa-solid fa-film"></i> Watch the movie</a>
</div>
</div>
</div>

<div class="callout callout-info" markdown="0">
<div class="callout-title"><i class="fa-solid fa-award callout-icon"></i> Honors & Awards</div>
<p>
<strong>Miller Professorship</strong><br>
<strong>AAS Newton Lacey Pierce Prize</strong><br>
<strong>Hellman Fellowship</strong><br>
<strong>Sloan Research Fellowship</strong><br>
<strong>Alexander von Humboldt Fellowship</strong>
</p>
</div>

### About me

I am a Professor in the [Astronomy Department at UC Berkeley](https://astro.berkeley.edu/), where I returned as faculty in 2016 after completing my undergraduate degree here in 2004. I earned my PhD in Astrophysics from the University of Minnesota in 2010, advised by Evan Skillman, and held postdoctoral and Hubble Fellowship positions at the University of Washington and UC Santa Cruz before joining the Berkeley faculty.

You can read more on my [biography]({{ site.url }}{{ site.baseurl }}/bio/) page or browse my [publications]({{ site.url }}{{ site.baseurl }}/publications/).
