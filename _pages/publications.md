---
layout: single
author_profile: true
title: Publications
jekyll:
  sort_by: [type,year,month]
permalink: /publications/
---

Total pubs: {% bibliography_count -f references %}

- :ledger: Journal articles: {% bibliography_count -f references --query @article %}
- :newspaper: Conference and workshop articles: {% bibliography_count -f references --query @inproceedings %}, including {% bibliography_count -f references --query @inproceedings[tier!=workshop] %} in :large_orange_diamond:  top-tier venues 
- :notebook: Edited volumes: {% bibliography_count -f references --query @proceedings %}
- :black_nib: Preprints and other non-peer-reviewed publications (excluding blog articles): {% bibliography_count -f references --query @misc %}

Bibliometrics: [h-index 24, 5.5K+ citations on Google Scholar](https://scholar.google.com/citations?user=5oCYOE0AAAAJ&hl=en)

## 2024

{% bibliography --query @*[year=2024] %}

## 2023

{% bibliography --query @*[year=2023] %}

## 2022

{% bibliography --query @*[year=2022] %}

## 2021

{% bibliography --query @*[year=2021] %}

## 2020

{% bibliography --query @*[year=2020] %}

## 2019

{% bibliography --query @*[year=2019] %}

## 2018

{% bibliography --query @*[year=2018] %}

## 2017

{% bibliography --query @*[year=2017] %}

## 2016

*(before 2017 my last name was "Gladkova")*

{% bibliography --query @*[year=2016] %}

## 2015

{% bibliography --query @*[year=2015] %}

<!--

# Publications sorted by type

## Journal articles

{% bibliography --query @article %}

## Top-tier conference articles

{% bibliography --query @inproceedings[tier!=workshop] %}

## Other conference and workshop articles

{% bibliography --query @inproceedings[tier=workshop] %}

## Non-peer-reviewed publications

{% bibliography --query @misc %}

## Edited volumes

{% bibliography --query @proceedings %}

-->