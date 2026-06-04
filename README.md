# EduDataHelper

Automated collection of public K–12 educational datasets from state education agencies and data portals, starting with Michigan's education platform.

---

## Motivation

State education agencies publish large volumes of public data but rarely offer bulk-download functionality. Researchers spend significant time manually navigating web interfaces to download datasets across years, districts, and reporting categories.
EduDataHelper automates this process, creating reproducible, programmatic workflows for educational data acquisition so researchers can focus on analysis, not collection.  

---

## Current Features — Michigan (MiSchoolData)

- Accesses the MiSchoolData backend API directly, bypassing manual web navigation
- Retrieves datasets across all available school years automatically
- Supports Intermediate School District (ISD) level geographic filtering
- Automates requests across dozens of educational reporting categories
- Generates structured logs of successful and failed dataset requests

---

## Example Workflow

1. **Select a state module** — start with Michigan or a future state implementation
2. **Define geography** — choose districts, counties, ISDs, or other regional units
3. **Specify years** — select one or more reporting years to retrieve
4. **Submit requests** — automated API calls are made to the state's education data system
5. **Receive outputs** — downloadable datasets and processing logs are generated

---

## Technology

- Python
- Requests
- JSON / CSV
- Jupyter Notebooks / Google Colab

---

## Disclaimer

This project interacts only with publicly available educational data systems and is intended for research and data collection purposes.
