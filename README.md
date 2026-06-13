# Carbon-14 Committed Effective Dose Tool

### 🌐 Launch the tool → **[sanyamjainmittal.github.io/C-14-Dose-Assessment](https://sanyamjainmittal.github.io/C-14-Dose-Assessment/)**

[![Open the tool](https://img.shields.io/badge/Open%20the%20Tool-Live-2d6a4f?style=for-the-badge&logo=html5&logoColor=white)](https://sanyamjainmittal.github.io/C-14-Dose-Assessment/)


A self-contained, browser-based tool for estimating the **committed effective dose** to members of the public from intakes of **Carbon-14 (¹⁴C)** released from nuclear facilities. The tool implements the **Specific Activity (SA) Model** across five exposure pathways and supports both *prospective* (forward) and *retrospective* (measured concentrations) assessments.

No installation. No login. No data leaves your device — every calculation runs locally in your browser.


## ✨ Features

- **Single HTML file** — no installation, no server, no Python or JavaScript runtime to set up. Open in any modern browser (Chrome, Edge, Firefox, Safari).
- **Five exposure pathways** in one unified calculation:
  - Pathway I — Inhalation of atmospheric ¹⁴CO₂
  - Pathway II — Terrestrial plant foods (vegetables, cereals, pulses, root crops, fruits)
  - Pathway III — Animal products (cow milk, meat)
  - Pathway IV — Fish (freshwater and marine)
  - Pathway V — Drinking water (optional, usually minor for ¹⁴C)
- **Two assessment modes** — toggle between *prospective* (atmospheric ¹⁴C drives food concentrations via the SA model) and *retrospective* (use measured ¹⁴C in each matrix).
- **Age-group selection** — adult, child, infant, with corresponding ICRP-recommended ingestion and inhalation dose coefficients.
- **Editable parameters** — specific activity of carbon in air / plant / animal / DIC, intake rates per pathway, dose conversion factors. All defaults are based on standard reference values and can be overridden.
- **Per-pathway and total dose** — results displayed in µSv a⁻¹ with intermediate concentrations shown for transparency.
- **Reproducible** — every input value is on the page; print to PDF for a permanent record.


## 🚀 Usage

1. Open the live URL above (or `index.html` locally).
2. Choose **age group** and **assessment mode** (prospective / retrospective).
3. Enter the relevant input concentration(s):
   - *Prospective mode:* C_air (Bq m⁻³) — the model propagates this to all food matrices.
   - *Retrospective mode:* directly enter measured ¹⁴C in each food matrix.
4. Tick the pathways that apply to your scenario; untick those that do not (e.g. disable marine fish for an inland site).
5. Review or override default intake rates, specific-activity values, and dose coefficients.
6. Click **Calculate** — per-pathway and total committed effective dose appear at the bottom.
7. Use the browser **Print → Save as PDF** for an archivable record.



