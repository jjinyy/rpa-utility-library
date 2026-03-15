# rpa-utility-library

A collection of reusable utility modules built to fill gaps in UiPath's default capabilities.
Extracted and modularized from 20+ RPA projects across manufacturing, logistics, and pharma.

---

## Background

UiPath is a powerful automation platform, but advanced Excel manipulation
and real-time progress monitoring aren't natively supported or require cumbersome workarounds.
Instead of reimplementing the same logic project after project,
packaged common utilities into reusable modules.

---

## What's included

**Excel utilities**

| Module | Description |
|--------|-------------|
| `Excel Sheet Delete` | Delete a specific sheet |
| `Pivot Table` | Create pivot tables programmatically |
| `Pivot Table ColSum` | Column sum on pivot tables |
| `Rename Excel Sheet` | Rename sheets dynamically |

**Progress monitoring**

| Module | Description |
|--------|-------------|
| `Show Progress` | Real-time automation progress display |

---

## Why this exists

Across 20+ RPA projects, the same gaps in UiPath's default activities kept coming up.
Building reusable modules meant the next project could start faster
and the same bugs didn't need to be fixed twice.
Reusability and delivery speed were the goals.

---

## Stack

`UiPath` `Python` `Excel (COM automation)`
```
