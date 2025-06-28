# XCCY Swap – EPE & PFE Simulation

## Purpose

This project presents a Monte Carlo–based simulation engine for computing **Expected Positive Exposure (EPE)** and **Potential Future Exposure (PFE)** for cross-currency swaps (XCCY). It was built as a proof of concept to explore how real-world capital markets instruments can be modeled using transparent, modular Python code — bridging the gap between domain expertise and product-thinking.

---

## Why This Project Matters

Traditional exposure modeling often lives in legacy systems or rigid spreadsheets. This prototype:

- Demonstrates **risk exposure simulation** aligned with regulatory and internal frameworks
- Helps visualize **credit exposure evolution** across swap tenors (3M, 6M, 1Y)
- Adds overlays like **regulatory thresholds** (e.g. 5% PFE limit, SACCR add-ons) for risk governance context

This project reflects my continued investment in upskilling and translating real-world experience into open, explainable tools for the risk, treasury, and RegTech space. Also, this would help me lay the foundation for future Product Leadership in Risk Technology.

---

## Key Features

- Monte Carlo FX path simulation for cross-currency swaps
- Computation of EPE and PFE across user-defined time steps
- Shaded PFE bands to visualize risk buffers
- Max PFE point annotations for quick stress interpretation
- Overlay of regulatory lines — including PFE limits and SACCR equivalents
- Chart export (`.png`) for easy integration into reports or presentations

---

## Demo Snapshot

![exposure_profile_chart](https://github.com/user-attachments/assets/b0031eb6-df0c-4da7-a892-8df2e2ad408f)

> *EPE & PFE exposure envelopes across 3M, 6M, and 1Y swap tenors — with regulatory thresholds clearly overlaid.*

---

## Tech Stack

- **Python**: numpy, pandas, matplotlib
- Modular, class-based design
- Jupyter and script compatible

---

## Next Steps

- Add collateral logic (thresholds, minimum transfer amounts)
- Build netting set exposure calculations
- Compare internal models (IMM) with SACCR add-on approximations
- Create a Streamlit UI or lightweight dashboard

---

## Author

[Sanket Sapre](https://www.linkedin.com/in/sanket-sapre-483a102a/), a Senior Consutant in Model Risk and Regulatory Reporting, currently upskilling into **Risk Data Product Management**. This project is part of a broader portfolio of open prototypes aimed at modernizing capital and treasury risk workflows through product-led thinking.
