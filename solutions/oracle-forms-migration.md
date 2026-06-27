---
layout: page
title: Oracle Forms & Reports Migration
description: "Oracle Forms and Reports applications run critical processes at enterprises and government agencies across Australia. I document Oracle Forms applications and produce realistic migration plans."
---

<p class="page-intro">Oracle Forms and Oracle Reports were the standard for building enterprise database front-ends through the 1990s and 2000s. Complex, data-intensive applications — financial processing, HR systems, inventory management — were built on Forms. Migrating them is one of the most technically demanding legacy challenges an organisation can face.</p>

## The Oracle Forms problem

Oracle Forms applications are built around tight integration with Oracle Database. The Forms themselves contain PL/SQL triggers, business logic, and validation rules that aren't visible in the database schema — they live in the form definition files.

The problems this creates:

- Oracle Forms is effectively end-of-life for new development
- The developers who built and maintained these systems are senior and retiring
- Business logic is distributed across database triggers, stored procedures, and form triggers — making it extremely difficult to understand the full system
- Oracle's own migration path is complex and expensive
- The application may depend on versions of Oracle Database that are themselves approaching end-of-life

## What I do

<ul class="outcomes-list">
  <li>Audit and documentation of Forms and Reports applications</li>
  <li>PL/SQL trigger and business logic extraction and documentation</li>
  <li>Database schema and stored procedure documentation</li>
  <li>Functional specification of each form — screens, validations, workflows</li>
  <li>Migration options analysis — Oracle APEX, web rebuild, commercial replacement</li>
  <li>Phased migration plan with realistic effort and risk assessment</li>
</ul>

## What I need

- Access to the Forms/Reports source files (`.fmb`, `.rdf`)
- Database access or a schema export
- A list of forms and reports that are business-critical
- Context on the business processes the system supports

---

{% include contact-form.html
   title="Tell me about your Oracle Forms environment"
   intro="Describe the system, the scale, and what you're trying to achieve. I'll respond with an honest assessment of the migration options and effort involved."
   id="oracleforms"
   segment="Oracle Forms Migration"
%}
