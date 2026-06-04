---
title: "Curriculum Vitae"
layout: gridlay
sitemap: false
permalink: /cv/
---

<style>
h3 {
  color: #003cba;
  margin-top: 1.75rem;
}

[data-bs-theme="dark"] h3 {
  color: #FDB927;
}

.site-container p {
  margin-bottom: 0.35rem;
}

.site-container dl {
  margin-bottom: 0.35rem;
}

.site-container dd {
  margin-top: 0;
  margin-bottom: 0;
}

.site-container ul {
  margin-top: 0.15rem;
  margin-bottom: 0.4rem;
}
</style>

## Curriculum Vitae

### Education

{% for edu in site.data.education %}
**{{ edu.degree }}** in {{ edu.field }} ({{ edu.start }} – {{ edu.end }})
: {{ edu.institution }}
{% if edu.details %}
{% for detail in edu.details %}
  - {{ detail }}
{% endfor %}
{% endif %}

{% endfor %}

### Academic Positions

**Associate Professor**, Astronomy Department, UC Berkeley (July 2020 – Present)

**Assistant Professor**, Astronomy Department, UC Berkeley (July 2016 – June 2020)

**Hubble Fellow**, University of Washington (Sept 2014 – June 2016)

**Hubble Fellow**, UC Santa Cruz (Sept 2013 – Aug 2014)

**Visiting Scholar and Humboldt Fellow**, Max-Planck Institut Für Astronomie, Heidelberg, Germany (Summers 2011 – 2019)

**Postdoctoral Researcher**, University of Washington (Oct 2010 – Aug 2013)

### Professional Membership

**Full Member**, American Astronomical Society (2010 – Present)

### Major Science Program Membership

**Project Scientist and Stars & Galaxies Science Lead**, Ultraviolet Explorer (UVEX) (2021 – Present)

**Full Member**, Dark Energy Spectroscopic Instrument (DESI) (2019 – 2021, 2024 – Present)

### Awards

**Miller Professorship**, Miller Institute (2026-2027)

**Newton Lacy Pierce Prize**, American Astronomical Society (2019)

**Hellman Faculty Fellowship**, Hellman Foundation (2018)

**Alexander Humboldt Fellowship**, Humboldt Foundation (2018 – 2021)

**Alfred P. Sloan Fellowship**, Sloan Foundation (2017)

**Hubble Fellowship**, Space Telescope Science Institute (2013 – 2016)

**Doctoral Dissertation Fellowship**, University of Minnesota (2009 – 2010)

**Russel Penrose Fellowship**, University of Minnesota (2004 – 2006)

**John E. Person Community Scholar**, UC Berkeley (2000 – 2004)


### Teaching

**Astro 128** – Undergraduate Astronomy Data Lab (Spring 2019, 2020, 2021 2024, 2025)

**Astro 218** – Graduate-level Galaxies (Fall 2021, 2023)

**Astro 250** – Graduate-level Stellar Populations (Fall 2016, Spring 2022, 2026)

**Astro 7A** – Intro to Astro for Intended Majors (Fall 2017, 2018, 2019, 2025)

**Astro 292** – Chemical Evolution Forum (Spring 2019)

**Astro 292** – Cosmic Dawn Forum (Fall 2016)

**Astro 98/198** – Python DeCal Mentor (Spring 2019, Fall 2025)

### Select Department and University Service

**Faculty Athletics Council** (2025 - present)

**Vice Chair**, Astronomy Department (2024 – 2025)

**Head Graduate Advisor** (2019 – 2026)

**Undergraduate Coding Curriculum Committee** (2024-2025)

**Graduate Recruitment Committee** (2020 – 2021, 2022 – 2023)

**Speaker Diversity Committee** (2021 – 2022)

**Student Prize Committee** (2022 – 2023)

**Colloquium Organizer** (2016 – 2021, 2026)

### Select Professional Service

**NASA Euclid Users Panel**, Chair, NASA (2025 – Present)

**JWST Proposal Review**, STScI (2022 – 2026)

**Keck Time Allocation Committee**, UCO (2017-2020, 2025)

**TMT Science Advisory Panel**, TIO (2024)

**Hubble Fellowship Selection Committee**, STScI (2023 – 2024)

**HST / JWST Long Term Variability Working Group**, STScI (2023 – 2024)

**Publication Referee** for A&A, ApJ, AJ, MNRAS, PASP (2009 – Present)

### Select Conference Organization

**UVEX Leadership Meeting** (June 2025), Organizer

**Cosmic Origins: The First Billion Years** (Sept 2024), SAC member

**Small Galaxies, Cosmic Questions II** (July 2024), SOC member

**Early Disk Galaxy Formation: From JWST to the Milky Way** (Feb 2023), SOC member

**The Intersection of Age Measurements Across Cosmic Time** (Dec 2019), Organizer

**Star Clusters Over Cosmic Time** (Dec 2019), SOC member

**Faint End of the Galaxy UVLF** (Dec 2018), Organizer

**Bay Area Local Group Meeting** (Dec 2018), Organizer

**Globular Clusters Across Cosmic Time** (Dec 2018), Organizer

### Select Recent Talks

**Colloquium** – Caltech (January 2026)

**Colloquium** – University of Minnesota (Feb 2025)

**UVEX/NASA Senior Requirements Review** – Caltech, UVEX Science Requirements (Feb 2025)

**Colloquium** – Northwestern University (Feb 2025)

**Colloquium** – University of Minnesota (Sept 2024)

**Contributed Talk** – Dwarf Galaxies in the LSST Era, KICP, Chicago (July 2024)

**UCB Lunch Talk** – UC Berkeley (March 2024)

**NASA Reverse Site Visit** – Caltech, UVEX: Low-Mass Galaxies Science Case (Sept 2023)

**Colloquium** – Stanford University (May 2023)

### Select Major Observing Programs & Grants

**Exploring the Accretion History and Halo of Giant Elliptical Cen A with Resolved Stars** – co-I & Admin PI, JWST Cycle 5, 131.3 hours

**The Metallicity Distribution Functions of M31 Ultra-Faint Dwarf Galaxies** – co-PI & Admin PI, HST Cycle 33, 99 orbits

**J-Virgo: A JWST Treasury Survey of the Virgo Cluster** – PI, JWST Cycle 4,146.6 hours

**Resolving the Local Volume with Euclid** – co-PI, 2025, NASA/ADAP

**A Closer Look at the Formation and Evolution of M31's Inner Disk** – co-I, JWST Cycle 3, 26.5 hours

**The Ultraviolet Explorer (UVEX)** – NASA MIDEX, Project Scientist, Stars & Galaxies Science Lead

**Alpha Elements and the Baryon Cycle in Isolated Dwarf Galaxies** – PI, JWST Cycle 2, 25.3 hours

**JWST ERS for Resolved Stellar Populations** – PI, 27.3 hours

**The Local Group Legacy Database of HST Photometry** – co-I & Admin PI

**Tracing the 6-D Orbital and Formation History of the Complete M31 Satellite System** – PI, 244 orbits
