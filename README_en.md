# Balmoral Case — VerdeCapital

**Languages:** [Español](README.md) · [English](README_en.md) · [Português](README_pt.md)

**Project:** CopernicusLAC Panama Hackathon 2026 — Food Security

**Description:** A use case showing how VerdeCapital structured a $2.4M USD green loan for Finca Balmoral (Chiriquí, Panama) using Copernicus satellite data (Sentinel‑2, Sentinel‑3, ERA5) as technological collateral to strengthen food security.

**Quick summary**
- **Sector:** Agriculture — Banana
- **Location:** Chiriquí, Panama
- **Structured loan:** $2,400,000 USD (7 years, 6.8% APR)
- **Monitored area:** 1,800 ha
- **Verified water reduction:** 41%
- **Estimated payback:** 3.2 years

**Problem**
- **Root cause:** Conventional irrigation systems with high water and diesel consumption.
- **Financial risk:** Banks rejected financing due to lack of verifiable guarantees and objective data.

**Proposed solution**
- **Satellite assessment:** Sentinel‑2 time series (NDVI, NDWI) and Sentinel‑3 (LST) to build a Farm Health Report.
- **Conditioned green loan:** Disbursements tied to quarterly satellite-verified metrics.
- **Monitoring platform:** Dashboard integrated with VerdeCapital API and Copernicus, updated every ~10 days.

**Implementation timeline**
- Aug 2024 — Initial satellite diagnosis (36 months of data).
- Sep 2024 — Loan structuring and approval (48 h).
- Oct–Dec 2024 — Drip irrigation installation and IoT sensor deployment (1,200 ha).
- Jan 2025 → — Continuous monitoring and carbon credit generation.

**Technology and data**
- **Sentinel‑2 MSI:** NDVI, NDWI, and crop classification (10 m).
- **Sentinel‑3 SLSTR:** Land surface temperature (LST).
- **ERA5 (CDS):** Climate reanalysis to model water demand.
- **Integration:** VerdeCapital API ↔ Copernicus Dataspace Ecosystem.

**Key financial results**
- **Projected annual operational savings:** +$512,600 (fuel, water, maintenance, credits).
- **Total benefit vs conventional rate:** +$604,000 (includes Ley 37/2016 tax deduction).

**Social and environmental impact**
- **Water saved per cycle:** ~172,000 m³
- **Avoided emissions (CO₂):** 1,240 t/year (verifiable)
- **Rural employment secured:** 340 direct jobs
- **Replication potential:** 120+ producers in Panama

**How to replicate**
1. Collect 24–36 months of Sentinel‑2 imagery for the farm.
2. Calculate indicators: NDVI, NDWI, LST and classify plots.
3. Generate the Farm Health Report and present it to the credit committee.
4. Structure the loan with verifiable metrics and a monitoring dashboard.