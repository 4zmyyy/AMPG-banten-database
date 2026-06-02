# AMPG Banten · Member Database Mobilization Analysis
**Golkar Youth Wing (AMPG) · Banten Province · 2020–2025**

---

## Overview

This project documents the data collection and organizational mobilization effort
carried out by PD I AMPG Banten across 8 regencies/cities in preparation for the
2024 General Election.

The core challenge: Banten started in the **red zone** of national database
completion rankings. Within **7 days**, the province moved into Cluster 1 and
reached **#5 nationally** — competing against provinces with significantly larger
organizational infrastructure.

---

## National Result

| Rank | Province |
|------|----------|
| 1 | Sulawesi |
| 2 | Jawa Timur |
| 3 | Sumatera Utara |
| 4 | Jawa Barat |
| **5** | **Banten ← from Red Zone** |

> If Kota Cilegon and Kabupaten Tangerang had reached full completion,
> Banten would have ranked **#1 nationally**.

---

## Scope

- **Province-level board (PD I):** 116 members tracked
- **Regencies/Cities covered:** 8 PD II chapters

---

## Key Findings

| Region | SK (Official) | Filled | Rate | Rakorda |
|--------|--------------|--------|------|---------|
| Kota Tangerang | 41 | 54 | 131.7% ↑ | ✅ Done |
| Kota Tangerang Selatan | 136 | 123 | 96.3% | ❌ Pending |
| Kota Serang | 64 | 58 | 90.6% | ✅ Done |
| Kabupaten Tangerang | 65 | 24 | 36.9% ⚠️ | ❌ Pending |
| Kabupaten Pandeglang | 43 | 33 | 76.7% | ❌ Pending |
| Kabupaten Serang | 21 | 21 | 100% | ❌ Pending |
| Kabupaten Lebak | 43 | 47 | 109.3% ↑ | ❌ Pending |
| Kota Cilegon | 70 | 15 | 21.4% ⚠️ | ❌ Pending |

## Visualizations
<img width="1187" height="590" alt="ampg 1" src="https://github.com/user-attachments/assets/66dabe6e-01ee-4050-a553-b1cb76c33128" />
<img width="1189" height="590" alt="ampg 2" src="https://github.com/user-attachments/assets/cf3199bc-807a-4576-8ab7-60221831f43b" />



### Completion Rate by Region
<img width="1187" height="590" alt="ampg 1" src="https://github.com/user-attachments/assets/2eb8c95f-893c-4873-8fef-981784cac03d" />


### SK vs Filled — Gap Analysis
<img width="1189" height="590" alt="ampg 2" src="https://github.com/user-attachments/assets/02a6df95-1249-4e3e-bc67-266028c84869" />


**⚠️ Critical bottlenecks:** Kota Cilegon (21.4%) and Kabupaten Tangerang (36.9%)
were the primary gaps preventing a national #1 ranking.

**↑ Organic growth:** Kota Tangerang and Kabupaten Lebak exceeded their official
SK count — indicating active recruitment beyond official decree.

---

## Methodology

- Cross-referencing SK (official appointment decrees) against submitted member forms
- Identifying discrepancies where actual participation exceeded official SK count
- Flagging chapters below PP AMPG minimum threshold (50 members at Kab/Kota level)
- Coordinating follow-up across all 8 chapters simultaneously within a 7-day window

---

## PP AMPG Minimum Composition Standards

| Level | Minimum Members |
|-------|----------------|
| Provinsi | 75 |
| Kabupaten/Kota | 50 |
| Kecamatan | 25 |
| Kelurahan/Desa | 10 |

---

## Repository Structure

```
├── data/
│   ├── provincial_board.csv       # PD I level summary
│   └── regional_chapters.csv     # Per-region breakdown with completion rates
├── analysis/
│   └── completion_rate_by_region.ipynb  # Visualization & gap analysis
├── slides/
│   └── database_evaluation_rakorda.pptx
└── README.md
```

---

## Running the Analysis

```bash
pip install pandas matplotlib numpy jupyter
cd analysis
jupyter notebook completion_rate_by_region.ipynb
```

---

## Context

AMPG (Angkatan Muda Partai Golkar) is the youth wing of Golkar, one of Indonesia's
largest and oldest political parties. Database mobilization at provincial scale
requires coordinating across bureaucratic, geographic, and organizational layers
simultaneously — with real electoral consequences tied to completion rates.

This work was conducted by the OKK (Organisasi, Keanggotaan, dan Kaderisasi)
division of PD I AMPG Provinsi Banten.
