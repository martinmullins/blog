---
layout: page
title: Proprietary Data Format Recovery
description: "Years of business data trapped in a format you can't read. I analyse custom and proprietary data files, extract the contents, and deliver your data in formats you can actually use."
---

<p class="page-intro">Proprietary data formats are one of the cruellest legacy software problems. The software that created the data is gone — the vendor closed, the developer retired, the application won't run on modern hardware — but the data itself still exists. It just can't be read.</p>

## How data gets trapped

Every piece of software that stores data makes a choice about format. Most chose proprietary binary formats — compact, fast, and completely opaque to anything other than the software that created them.

When the software dies, the data becomes unreadable:

- Accounting software stores transaction history in a `.dat` or `.bin` format only that software understands
- A custom inventory system used its own binary database format
- An industry-specific tool stores project data in a format that only runs on Windows XP
- A point-of-sale system has years of sales data in a format the new system can't import

The data still physically exists. The bytes are there. But without knowing the format specification, reading it is a technical challenge.

## What I do

I analyse proprietary data files to determine their structure and extract their contents.

<ul class="outcomes-list">
  <li>Binary file analysis — determining record structures, field layouts, and encoding</li>
  <li>Data extraction from proprietary formats to CSV, JSON, SQL, or other structured formats</li>
  <li>Validation of extracted data against the original application's output</li>
  <li>Delivery of clean, portable data ready for import into your new system</li>
  <li>Documentation of the format for future reference</li>
</ul>

Not every format is recoverable. Some are encrypted or structured in ways that aren't readable without the original software. I'll be honest about that upfront.

## What I need

- The data files (copies — the originals don't need to be at risk)
- Access to the original software if it can still be run, even in emulation
- Any documentation or format specifications that exist
- Sample data where the contents are known, for validation

---

{% include contact-form.html
   title="Tell me about your data format problem"
   intro="Describe the software that created the data, the file types involved, and what you need to do with the data. I'll respond with an honest view of what's recoverable."
   id="proprietary"
   segment="Proprietary Data Recovery"
%}
