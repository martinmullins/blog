---
layout: page
title: ColdFusion Web Application Modernization
description: "Adobe ColdFusion web applications built in the early 2000s are running on aging infrastructure across Australia. I document and modernize ColdFusion applications before the server fails."
---

<p class="page-intro">ColdFusion web applications were fast to build and easy to deploy in the early 2000s. Many are still running, on servers that are years past end-of-life, maintained by people who no longer work at the business. The application keeps running until the day it doesn't.</p>

## The ColdFusion problem

ColdFusion (originally Allaire, then Macromedia, now Adobe) produced a huge number of intranet tools, customer portals, and business applications in the late 1990s and early 2000s. The platform still exists, but the developer community has long moved on.

The specific risks:

- The application runs on Windows Server 2003 or 2008, both end-of-life
- ColdFusion licensing is expensive and the upgrade path between major versions is not straightforward
- The developers who built these applications have moved into modern web development and aren't coming back to ColdFusion
- Security vulnerabilities in older ColdFusion versions are well-known and actively exploited
- The database backend is often SQL Server 2000 or 2005, itself unsupported and vulnerable

ColdFusion applications are also notorious for mixing business logic, HTML, and database queries in single `.cfm` files — making them very hard to understand without reading through the code line by line.

## What I do

<ul class="outcomes-list">
  <li>Code audit and documentation — what each template does, what data it reads and writes</li>
  <li>Business logic extraction from CFML code</li>
  <li>Database schema and query documentation</li>
  <li>Security vulnerability assessment</li>
  <li>Modernization options — rewrite in a modern web framework, cloud migration</li>
  <li>Priority-ranked migration plan based on business risk</li>
</ul>

## What I need

- Access to the ColdFusion source files (`.cfm`, `.cfc`)
- Access to or a schema of the underlying database
- A description of what the application does and who relies on it

---

{% include contact-form.html
   title="Tell me about your ColdFusion application"
   intro="Describe the application, what server it runs on, and what's driving the need to modernize. I'll respond with an honest assessment of the options."
   id="coldfusion"
   segment="ColdFusion Modernization"
%}
