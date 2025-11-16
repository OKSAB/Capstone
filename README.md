# Transportation Safety & Infrastructure Optimization – Saudi Arabia (DSC Capstone)

This repository hosts the data, Python code, and SQL scripts for a capstone project on **transportation safety and infrastructure optimization** in Saudi Arabia.

**Diagnostic Question**

> Diagnose the causes and propose solutions for road accidents in Saudi Arabia. Identify trends in different regions over the past decade. How will policy solutions differ by region?

The repo is designed to support two core deliverables:

- A government-ready **policy memo** (8–10 pages).
- A **12–15 slide presentation** for Saudi decision makers.

---

## 1. Objectives

This project aims to:

- Describe **levels and trends** of road crashes, injuries, and fatalities across Saudi regions over the past decade.
- Compute **key indicators** (e.g., crashes and fatalities per 100,000 population, per registered vehicle, by road type).
- Identify **regional patterns and risk factors** (infrastructure, enforcement, driver behaviour, environment).
- Compare and assess **existing policies and interventions** (e.g., speed cameras, black-spot treatment, awareness campaigns).
- Propose **region-specific policy options** for transportation safety and infrastructure optimization.
- Provide evidence-based inputs to Vision 2030 goals related to **quality of life, transport & logistics, and health**.

---

## 2. Repository Structure

Planned structure (can be adjusted as the project evolves):

```text
ksa-transport-safety-capstone/
├─ data_raw/        # Original datasets (read-only: csv, xlsx, shapefiles, etc.)
├─ data_clean/      # Cleaned & transformed datasets ready for analysis
├─ notebooks/       # Jupyter notebooks for EDA, modelling, and visualization
├─ sql/             # SQL scripts for data exploration and aggregation
├─ src/             # Reusable Python modules (ETL, analysis, plotting)
├─ figures/         # Exported charts, maps, and tables for memo and slides
├─ docs/            # Draft policy memo, slide outlines, and notes
└─ README.md
```
---

## 3. Initialize repository and environment

### 3.1 Clone the repository

1. Open a terminal (Command Prompt, PowerShell, or a shell).
2. Navigate to the folder where you want the project to be:
   cd /path/to/your/projects
3. git clone https://github.com/OKSAB/capstone
4. cd ksa-transport-safety-capstone

### 3.2 Create a virtual environment and install dependencies
1. python -m venv .venv
2. Activate the virtual environment:

 - Windows (PowerShell):
.venv\Scripts\Activate.ps1

 - macOS / Linux:
source .venv/bin/activate

3. pip install -r requirements.txt
