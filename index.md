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

## Projects

{% assign section = site.pages | where: "path", "projects.md" | first %}
{{ section.content | markdownify }}

## Papers

{% assign section = site.pages | where: "path", "papers.md" | first %}
{{ section.content | markdownify }}

## Scientific Conferences and Schools

{% assign section = site.pages | where: "path", "conferences.md" | first %}
{{ section.content | markdownify }}

## Teaching

{% assign section = site.pages | where: "path", "teaching.md" | first %}
{{ section.content | markdownify }}

## Education

{% assign section = site.pages | where: "path", "education.md" | first %}
{{ section.content | markdownify }}

## About

{% assign section = site.pages | where: "path", "about.md" | first %}
{{ section.content | markdownify }}
