---
layout: page
title: Classic ASP Web Application Modernization
description: "Classic ASP web applications built in the early 2000s are still running on aging IIS servers across Australia. I document and modernize Classic ASP applications before the infrastructure fails."
---

<p class="page-intro">Classic ASP (Active Server Pages) had its peak in the early 2000s. Thousands of internal web applications, customer portals, and business tools were built on it. Many are still running — on old servers, on old versions of IIS, with nobody left who understands the code.</p>

## The Classic ASP problem

Classic ASP applications are a quiet risk. They're web-based, so they often get overlooked in legacy software audits — but they're running on infrastructure that is years past end-of-life.

The specific risks:

- The application runs on Windows Server 2003 or 2008 — both end-of-life — because upgrading the server would break the application
- Classic ASP uses VBScript or JScript that modern developers don't know
- The code mixes HTML, business logic, SQL queries, and data access in ways that make it extremely hard to understand
- The database backend is often SQL Server 2000 or 2005, itself unsupported
- Security vulnerabilities in Classic ASP applications can't be patched if nobody understands the code

## What I do

<ul class="outcomes-list">
  <li>Code audit and documentation — what the application does, page by page</li>
  <li>Business logic extraction from embedded VBScript/JScript</li>
  <li>Database schema and query documentation</li>
  <li>Security vulnerability assessment</li>
  <li>Modernization options — rewrite in a modern web stack, move to a cloud platform</li>
  <li>Migration plan with priority order based on business risk</li>
</ul>

## What I need

- Access to the application source files
- Access to or a schema of the underlying database
- A description of what the application does and who uses it

---

{% include contact-form.html
   title="Tell me about your Classic ASP application"
   intro="Describe what the application does, what server it runs on, and what's driving the need to modernize. I'll respond with an honest assessment."
   id="classicastp"
   segment="Classic ASP Modernization"
%}
