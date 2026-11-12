---
title: "Memory Systems for Mixture-of-Experts Inference"
featured: true
sitemap: true
order: 1
affiliation: "Hong Kong Baptist University"
period: "Aug 2026 – Present"
summary: "Exploring expert scheduling and processing-in-memory to reduce tail latency in mixture-of-experts inference."
description: "Research on expert scheduling and processing-in-memory for mixture-of-experts inference."
---

<p class="academic-meta">{{ page.affiliation }} · {{ page.period }}</p>

## Research question

How can a memory system reduce the tail latency of mixture-of-experts inference when expert workloads are uneven?

## My contributions

- Investigate whether expert access frequencies from the prompt-processing (prefill) stage can guide a CPU scheduler in selecting less frequently used experts for offloading to processing-in-memory (PIM).
- Study how to map expert matrix operations onto the PIM hardware hierarchy to reduce communication within PIM and make better use of memory bandwidth.

## Status

Ongoing research on scheduling and hardware mapping.
