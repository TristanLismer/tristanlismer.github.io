---
title: "Projects"
permalink: /projects/
layout: single
author_profile: true
---

## 💾 SQL + Data Science Demos

I'm a physicist who loves **data wrangling**. Here’s what I’ve been experimenting with.

### 📊 Photon Interference in SQL

```sql
-- Aggregate phase-varying datasets
SELECT phase1, phase2, phase3,
       AVG(intensity) AS avg_intensity
FROM slit_interference_data
GROUP BY phase1, phase2, phase3;
```

### 🧪 Simulated Higher-Order Interference

Used Python and SQL to model photon interference with artificial GPT-like behavior.

### 🔍 Ideas in Progress

- Tomography visualizer using Dash
- SQL GPT schema to enforce no-signaling constraints
