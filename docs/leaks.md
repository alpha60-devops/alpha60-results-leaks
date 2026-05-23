---
layout: default
title: "USA Leaks"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Analysis of Leaks peer-to-peer distribution"
---

{::nomarkdown}
<img src="../resources/a60-logo-block-gray.simple.svg?sanitize=true" height="50" width="100">
{:/}

<script defer type="text/javascript" crossorigin="anonymous" id="geojson-map"
	src="../resources/izzi-map-leaflet-geojson-v7.3.js">
</script>

<!-- Preload the CSS without blocking rendering -->
<link rel="preload" href="../resources/izzi-table-wcag-22.css" as="style" onload="this.onload=null;this.rel='stylesheet'">

<!-- Fallback for users who have JavaScript disabled -->
<noscript>
  <link rel="stylesheet" href="../resources/izzi-table-wcag-22.css">
</noscript>

<div style="height: 50px;"></div>


# Hacks and Leaks
<div style="height: 50px;"></div>


## Graphs

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

{::nomarkdown}
{% include leaks-downloads-by-week-normalized-start.svg %}
{:/}
<div style="height: 25px;"></div>

### Graph by Top Country Downloaders
{::nomarkdown}
{% include leaks-usa-downloads-by-country.svg %}
{:/}
<div style="height: 25px;"></div>

### Graph by Individual Leak
{::nomarkdown}
{% include leaks-usa-downloads-by-btiha.svg %}
{:/}

<div style="height: 50px;"></div>


## Maps

{% include leaks-usa-spatial-carto-table.html %}
<div style="height: 50px;"></div>


## Tables

<script defer type="text/javascript" crossorigin="anonymous" id="table-sort"
	src="../resources/izzi-table-sort-wcag-22.js">
</script>

<!-- Preload the CSS without blocking rendering -->
<link rel="preload" href="../resources/izzi-table-sort-wcag-22.css" as="style" onload="this.onload=null;this.rel='stylesheet'">

<!-- Fallback for users who have JavaScript disabled -->
<noscript>
  <link rel="stylesheet" href="../resources/izzi-table-sort-wcag-22.css">
</noscript>

{% include leaks-meta-collection-table.html %}
<div style="height: 25px;"></div>

{% include leaks-media-objects-table.html %}
<div style="height: 25px;"></div>

{% include leaks-geo-slices-usa-weeks-1-5-15.html %}
<div style="height: 25px;"></div>

{% include leaks-geo-slices-africa.html %}
<div style="height: 25px;"></div>

{% include leaks-geo-slices-asia.html %}
<div style="height: 50px;"></div>


## Commentary, Questions

### Russian Internet Outages shown by week by week by country.

Ukraine drone activity in Moscow and other parts of Russia in the early part of May has led to
mobile internet disruptions in previously un-impacted cities Moscow and SPB, one of which lasted 19 days. Mobile internet in Moscow/SPB was impact from May 5 [Moscow Times Mobile Internet] (https://www.themoscowtimes.com/2026/05/05/mobile-internet-outages-reported-in-moscow-and-st-petersburg-amid-security-concerns-a92682). Cloudflare Radar is does not show any notable slowdowns in [network traffic over the period 2026-05-01 to 2025-06-09](https://radar.cloudflare.com/ru?dateStart=2026-05-01&dateEnd=2026-05-09).


### Sub-Collection GeoJSON.



{::nomarkdown}
<svg width="100" height=100>
	<circle cx="20" cy="50" r="10" fill="black"/>
</svg>
{:/}
