# US 50-State Cottage Food Laws & FDA Label Data (2026)

Open-source structured JSON & CSV dataset covering **all 50 US states**' cottage food annual sales caps, home-kitchen mandatory label disclosures, permit/registration notes, allowed sales channels, and official state regulatory links — alongside an engineering reference for deterministic **FDA 21 CFR 101.9** Nutrition Facts rounding.

> **Interactive Web Tools (No Signup Required):**
> - [50-State Cottage Food Label Maker (Avery & Thermal PDFs)](https://cottagefoodtools.com/cottage-food-label-maker)
> - [Texas Cottage Food Label Rules & $150k SB 541 Generator](https://cottagefoodtools.com/cottage-food-labels/texas)
> - [FDA 21 CFR 101.9 Nutrition Facts Generator](https://cottagefoodtools.com/nutrition-label-generator)
> - [US Top-9 & UK/EU 14 Allergen Matrix Generator](https://cottagefoodtools.com/allergen-matrix-generator)

## What Is Included

- `data/us-cottage-food-states-2026.csv` — Spreadsheet-ready summary table across all 50 states.
- `docs/fda-21cfr1019-rounding-reference.md` — Deterministic 21 CFR 101.9 rounding rules & 2020 %DV increments used for nutrition panels.

## Sample Snapshot (Top States)

| State | 2026 Sales Cap | Mandatory Disclosure Preview |
| :--- | :--- | :--- |
| **Texas (TX)** | Up to $150,000 gross annual sales (SB 541, inflation-indexed) | `THIS PRODUCT WAS PRODUCED IN A PRIVATE RESIDENCE THAT IS NOT SUBJECT TO GOVERNMENTAL LICENSING OR INSPECTION.` |
| **California (CA)** | Up to $75,000 (Class A) or $150,000 (Class B) | `Made in a Home Kitchen` (minimum 12-point type; include County Permit #) |
| **Florida (FL)** | Up to $250,000 gross annual sales | `Made in a cottage food operation that is not subject to Florida's food safety regulations.` |

## Disclaimer

This dataset is provided under the MIT License for informational and software engineering purposes only. It does **not** constitute legal advice or FDA regulatory certification. Cottage food statutes, county permits, and type-size mandates change periodically—always verify current requirements directly with your state Department of Agriculture or Health Department.
