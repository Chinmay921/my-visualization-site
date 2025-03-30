
---
layout: default
title: Assignment 2
---

# How Safe Is SF Now? A 20-Year Crime Retrospective

Crime often feels like a constant. But has San Francisco actually become more or less dangerous over time? Using over two decades of crime data, we take a closer look at how patterns have shifted — both in terms of volume and geography.

## Dataset Overview

This story draws on a publicly available dataset from the San Francisco Police Department, covering over two decades of reported crimes from 2003 to 2024. The data includes incident-level records with information on date, time, location, police district, and crime category.

For this analysis, we focus specifically on a subset of offenses often referred to as **“focus crimes”** — including assault, burglary, robbery, larceny/theft, drug violations, and other high-impact categories.

---

## Total Reported Crime by Year

We begin by looking at overall reported crime volumes to understand how they’ve changed over time.

<div class="viz-container">
  <img src="/assets/images/focus_crime_trends_in_SF.png" alt="Yearly crime trend in SF" class="viz-img">
  <div class="viz-caption">Total reported focus crimes in San Francisco, 2003–2024.</div>
</div>

---

## Where in SF? Geographic Patterns

Next, we explore **how crime is distributed across different areas of the city**. The map below displays crime counts across districts.

<div class="map-container">
  <iframe src="/focus_crime_districts.html" loading="lazy"></iframe>
</div>

---

## Hotspot Analysis: What Changed?

To compare how hotspots evolved, we created a side-by-side interactive view of different time periods.

<div class="map-container">
  <iframe src="/focus_crime_hotspot_comparison.html" loading="lazy"></iframe>
</div>

---

## So, When Is SF Most Dangerous?

While the volume of crime has generally declined since 2003, **the decline has not been evenly distributed across all areas**. Certain districts remain consistently high-risk.

Understanding these geographic patterns is crucial for policymakers, residents, and newcomers who want a clearer picture of what’s happening on the ground.

---

<div class="conclusion">
  <h2>Conclusion</h2>
  <p>
    San Francisco’s crime story is not one of constant rise or fall — but of evolution.
    Some neighborhoods have seen dramatic improvements, while others remain hotspots.
    Our hope is that data-driven insights like these will inform smarter decisions, better policing, and safer communities.
  </p>
</div>

---

<footer class="site-footer">
  <p>&copy; 2025 Arun, Sarah, Chinmay | Data Story</p>
</footer>
