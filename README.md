# EduDataCollection

A research framework for collecting, documenting, and organizing publicly available K–12 education datasets from state education agencies across the United States.

Current target states include Michigan so far with the long-term goal of creating a scalable workflow that can be extended to all 50 states.

---

## Motivation

State education agencies publish large amounts of valuable educational data, including assessment results, enrollment statistics, financial records, staffing information, accountability metrics, and student demographic data. However, these datasets are often distributed across different websites, dashboards, downloadable reports, and custom data portals.

Researchers frequently spend significant time locating, downloading, organizing, and documenting these datasets before analysis can begin.

---

## Project Goals

### Data Collection

Acquire publicly available educational datasets from state education agencies and related public data portals, including:

* Assessment and test score data
* Enrollment and demographic data
* Financial and expenditure reports
* Teacher and staffing records
* Accountability and performance metrics
* Additional education related datasets as available

### Documentation

Maintain detailed records of:

* Dataset names and descriptions
* Source URLs
* Available reporting years
* Geographic coverage
* Collection methods
* Download procedures
* State specific portal structures

### Automation

When possible, automate data acquisition through:

* Public APIs
* Download endpoints
* Bulk export systems
* Scripted retrieval workflows

Because each state's education data system is structured differently, automation is implemented on a state by state basis.

Additional states may be added as the project expands.

---

## Workflow

1. Identify state education data sources
2. Document portal structure and available datasets
3. Locate bulk-download options or public APIs
4. Collect and organize datasets by category
5. Record metadata and collection procedures
6. Maintain reproducible code and documentation
7. Store outputs in a standardized folder structure

---

## Technology

* Python
* Requests
* Pandas
* JSON / CSV
* Jupyter Notebooks
* Google Colab
* GitHub
* Google Drive

---

## Research Use

This repository is intended for educational research, data collection, documentation, and reproducible workflow development.

---

## Disclaimer

This project does not collect private student information and interacts only with publicly available educational data systems.
