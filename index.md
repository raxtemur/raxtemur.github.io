---
layout: default
title: ""
---



## Navigation

- [Appointments](#appointments)
- [Projects](#projects)
- [Papers](#papers)
- [Scientific Conferences and Schools](#scientific-conferences-and-schools)
- [Teaching](#teaching)
- [Education](#education)
- [About](#about)

---

## Appointments

{% assign section = site.pages | where: "path", "appointments.md" | first %}
{{ section.content | markdownify }}
<div class="page-break"></div>

## Projects

{% assign section = site.pages | where: "path", "projects.md" | first %}
{{ section.content | markdownify }}
<div class="page-break"></div>

## Papers

{% assign section = site.pages | where: "path", "papers.md" | first %}
{{ section.content | markdownify }}
<div class="page-break"></div>

## Scientific Conferences and Schools

{% assign section = site.pages | where: "path", "conferences.md" | first %}
{{ section.content | markdownify }}
<div class="page-break"></div>

## Teaching

{% assign section = site.pages | where: "path", "teaching.md" | first %}
{{ section.content | markdownify }}

## Education

{% assign section = site.pages | where: "path", "education.md" | first %}
{{ section.content | markdownify }}
<div class="page-break"></div>

## About

{% assign section = site.pages | where: "path", "about.md" | first %}
{{ section.content | markdownify }}
