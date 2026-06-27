---
layout: page
title: Crystal Reports Migration & Recovery
description: "Crystal Reports is embedded in legacy systems across Australian businesses. When the underlying system changes or Crystal Reports becomes unmaintainable, I extract the business logic and migrate to modern reporting."
---

<p class="page-intro">Crystal Reports is woven into more legacy systems than most businesses realise. It ships embedded in dozens of older ERP, accounting, and business management platforms — and it's been used to build standalone reporting solutions that have quietly become business-critical.</p>

## The Crystal Reports problem

Crystal Reports has a specific failure mode: it becomes invisible infrastructure. Reports get built, they run, they produce the numbers that drive decisions — and nobody thinks about them until something breaks.

What breaks:

- The ERP or accounting system it was embedded in is being replaced, and the reports can't be carried across
- The report was built to connect to a specific database version that no longer exists
- The developer who built the reports retired and took their knowledge with them
- Crystal Reports licensing has changed and renewal isn't straightforward
- The underlying data model has changed and nobody knows how to update the reports

The real problem is that Crystal Reports often contain business logic — calculations, grouping rules, filtering conditions, derived metrics — that exists nowhere else. Replacing the report requires understanding what it calculates, not just what it displays.

## What I do

<ul class="outcomes-list">
  <li>Audit of existing Crystal Reports — what they do, what data they use, what business logic they contain</li>
  <li>Documentation of report logic in plain language</li>
  <li>Data source analysis — what databases and fields the reports depend on</li>
  <li>Migration to modern reporting tools — SSRS, Power BI, Metabase, or custom</li>
  <li>Rebuild of critical reports in a supported, maintainable format</li>
</ul>

## What I need

- The Crystal Reports files (`.rpt`)
- Access to or a description of the underlying data source
- An understanding of which reports are business-critical versus historical

---

{% include contact-form.html
   title="Tell me about your Crystal Reports situation"
   intro="Describe what you're running, what's changing, and what you need to preserve. I'll respond with an honest view of the options."
   id="crystal"
   segment="Crystal Reports Migration"
%}
