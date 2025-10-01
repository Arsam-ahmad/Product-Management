# Consumer App — User Experience & Sprint Summary

This repository captures a concise, **evidence‑based view of consumer‑app user experience work**: categorized use‑cases, progress by sprint, and Voice‑of‑Customer (VoC) inputs. It is designed so a product owner or stakeholder can see **where we are**, **what’s blocked**, and **what ships next** at a glance.

> **Why this exists:** To align business, design, and engineering on prioritization and outcomes, while keeping a clean artifact for career‑fair conversations and recruiter review.

---

## Repository Contents

- **`Consumer app sprint summary.xlsx`** — Primary dashboard with the `Summary` sheet (used below) and supporting detail tabs.
- **`Consumer App User Experience Summary -V01.xlsx`** — Structured backlog of UX issues/use‑cases with short descriptions and owners.
- **`Customer experience VOC inputs.xlsx`** — Raw/curated Voice‑of‑Customer inputs: app reviews, support tickets, and field notes.
- **`/assets/screenshot.png`** *(optional)* — Dashboard snapshot used in the README (exported from Excel).

> If you rename or move files, update the links in this README accordingly.

---

## Quick Snapshot

- **Sheet parsed:** `Discussion points ` in `Consumer app sprint summary.xlsx`  
- **Total use‑cases tracked:** _see table below_  
- **Top categories represented:** Functionality/User Journey, App Performance, Business Agility, Error Mapping, UI Improvements, and Misinformation.

---

## Category Breakdown (from the Summary sheet)

_(Category table not parsed—open the spreadsheet for details.)_

**Columns**  
- **Total Use Cases:** Count per category.  
- **Pending Requirement / Pending on Tech / Pending Priority:** Triaging buckets that signal *where the bottleneck is* (requirements vs. engineering vs. prioritization).  
- **Description:** Working definition of each category to keep grooming consistent.

---

## Progress Status (pipeline view)

_(Progress table not parsed—open the spreadsheet for details.)_

**How to read**  
- Status lines map directly to sprint planning buckets (e.g., *Included in Sprint 2.0*, *Discussion planned with Business*).  
- Use this to **sequence next actions** (clarify requirement → unblock tech → pull into sprint).

---

## How to Update the Data

1. Open **`Consumer app sprint summary.xlsx`** → **`Summary`** sheet.  
2. Adjust counts in **Category** rows and **Progress status** rows.  
3. Refresh the embedded chart(s) as needed (Excel → *Chart Design* → *Refresh*).  
4. Keep **descriptions** crisp; they’re used as definitions during grooming.  
5. When new VoC arrives, log it in **`Customer experience VOC inputs.xlsx`** and link the item to a **use‑case ID** in the UX summary file.

> Tip: Add a small *“Data last updated: YYYY‑MM‑DD”* note in cell A1 of each sheet.

---

## Suggested Views (optional but helpful)

- **Pareto chart** of category counts to spotlight the 20% categories causing 80% impact.  
- **Cumulative flow** by progress status to visualize work‑in‑process and bottlenecks.  
- **Aging report**: conditional formatting on items open >14 days.

---

## Folder Structure

```
.
├── Consumer app sprint summary.xlsx
├── Consumer App User Experience Summary -V01.xlsx
├── Customer experience VOC inputs.xlsx
└── assets/
    └── screenshot.png   # optional
```

---

## Usage & Attribution

This repo is a demonstration of **product ownership operating cadence** (backlog hygiene, cross‑functional alignment, and outcome tracking).  
If you fork it, please remove or redact any proprietary details and **do not include confidential data**.

**Author:** Arsam Ahmad — Product Owner / MS in Computer Engineering  
**Contact:** LinkedIn / Email listed on resume

---

## Changelog

- **v1.0** — Initial upload of spreadsheets and dashboard README.
