---
title: "AI Infrastructure for Clinical Applications"
featured: true
sitemap: true
order: 4
affiliation: "DIAN Team · HUST Tongji Hospital"
summary: "Built a Go backend and shared language-model API for medical applications developed with HUST Tongji Hospital."
description: "Backend systems and language-model integration for a DIAN Team collaboration with HUST Tongji Hospital."
---

<p class="academic-meta">{{ page.affiliation }}</p>

## Project question

How can clinical applications share backend services for OCR and large language models while handling concurrent requests?

## My contributions

- Designed a Go backend with Redis caching and goroutine pools, and helped run containerized services behind Nginx.
- Built a shared API for multiple language models, with dynamic routing and response caching.

## Reported project result

The shared API reduced redundant model calls by 40% in the project.
