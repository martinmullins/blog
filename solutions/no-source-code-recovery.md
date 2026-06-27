---
layout: page
title: Software Recovery Without Source Code
description: "Source code goes missing more often than people think. When the developer is gone and the code was never handed over, I work from the running application and executable files to document and recover what you need."
---

<p class="page-intro">No source code is the most common legacy software problem I encounter. The developer left. The code was never handed over. The backup failed. A hard drive died. However it happened, you're left with a running application and no way to change it, understand it, or replace it.</p>

## Why source code goes missing

Source code disappears in predictable ways:

- The contractor who built the system kept the code — and the contract never required delivery
- The code existed only on a developer's personal machine and was lost when they left
- Backups were never configured properly and years of code simply don't exist
- A server failure destroyed the only copy
- The original software vendor shut down and the source was never held in escrow

The result is always the same: software you depend on that is effectively a black box.

## What's still possible without source code

More than most people expect.

Running software leaves traces. The executable contains structure. The database has a schema. The application's behaviour can be observed, mapped, and documented. The business logic can be inferred from inputs and outputs.

I can't give you the source code back. What I can do:

<ul class="outcomes-list">
  <li>Document what the application does — screens, workflows, business processes</li>
  <li>Extract and document the database schema and data</li>
  <li>Identify and document the business rules the application enforces</li>
  <li>Produce a functional specification detailed enough to rebuild the system</li>
  <li>Assess what modernization approach makes sense given the situation</li>
  <li>Extract data from proprietary formats so it can be migrated</li>
</ul>

The goal is to convert the software from a black box into something understood — something that can be replicated, replaced, or at minimum documented for risk management.

## What I need

- The running application (preferred) or the executable files
- Any database files associated with the application
- Any documentation that exists, even if partial
- A conversation with the people who use the system

---

{% include contact-form.html
   title="Tell me about your source code situation"
   intro="Describe the software, how it's used, and what problem the missing source code is creating. I'll respond with an honest view of what's recoverable."
   id="nosource"
   segment="No Source Code Recovery"
%}
