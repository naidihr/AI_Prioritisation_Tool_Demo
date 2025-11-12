# AI Prioritisation Calculator

## Overview
The **AI Prioritisation Calculator** is an Excel-based tool developed to support safe and effective deployment of chest X-ray (CXR) artificial intelligence (AI) systems within radiology services.  
It enables clinical teams to model and decide which AI-detected CXR findings should be prioritised for reporting to optimise the detection of lung cancer and other critical abnormalities, while managing radiology workloads efficiently.

This tool was developed and validated using real-world data from the **Greater Manchester AI Radiology Prioritisation (AIRPORT)** study, as described in:

> Bramley R, *et al.* “Systematic Prioritisation of AI-Detected Chest X-ray Abnormalities for Optimised Lung Cancer Detection.” *BJR-AI* (in review), preprint available at [medRxiv](https://www.medrxiv.org/content/10.1101/2024.12.30.24319499v2).

---

## Purpose
- Support clinical AI project leads, radiologists, and service managers in selecting which AI findings should trigger expedited reporting.
- Provide a reproducible, data-driven method to balance high sensitivity for lung-cancer detection against operational feasibility.
- Allow exploration of the impact of different prioritisation strategies on diagnostic performance metrics (sensitivity, specificity, PPV, NPV).

---

## Data Source
The workbook includes anonymised summary data from two real-world patient cohorts:

1. **Cancer Cohort (n = 1,282):**  
   Primary-care GP-referred patients with confirmed lung cancer who had a CXR within six months of diagnosis.  
   Cases where the reporter could not detect an abnormality or recommend further action were excluded.

2. **Referral Cohort (n = 13,802):**  
   Consecutively acquired GP-referred CXRs over an eight-week period representing the general adult referral population.

> Additional workbooks exist for A&E and All-Adult populations.  
> The dataset used should reflect the target population in which AI prioritisation is intended to be applied.

---

## Target Users
- Clinical Radiologists  
- Lung Cancer Physicians  
- Radiology and Cancer Service Managers  
- AI Programme Leads and Project Managers  

---

## Workbook Structure

| Sheet | Purpose |
|-------|----------|
| **1. Introduction and Purpose** | Describes objectives, data sources, and user guidance. |
| **2. Step-by-Step Guide** | Provides detailed instructions for using the calculator. |
| **3. AI Findings Prevalence** | Displays the number of CXRs associated with each of the 124 AI findings across both cohorts and their relative prevalence. |
| **4. Performance Metrics** | Calculates modelled sensitivity, specificity, PPV, and NPV for the user’s selected findings. |

---

## How to Use

### Step 1 – Review AI Findings
Open the **AI Findings Prevalence** sheet to explore how often each of the 124 AI-detected findings occurs in the cancer and referral cohorts.  
The *Relative Prevalence* column shows how much more common each finding is in cancer cases.

### Step 2 – Select Findings to Prioritise
In the yellow **Select** column, enter **“Y”** beside each finding you wish to prioritise.  
Selections may be based on:
- High relative prevalence in the cancer cohort, or  
- Clinical judgement that a finding is critical or high-risk.

### Step 3 – Review Performance Metrics
Navigate to the **Performance Metrics** sheet.  
The workbook automatically recalculates overall modelled diagnostic performance (sensitivity, specificity, PPV, NPV) based on your chosen findings.

### Step 4 – Interpret Results
Use the results to inform local decisions about which AI findings should be prioritised in clinical workflows.  
Balancing high sensitivity and NPV—accepting a necessarily lower PPV—helps optimise early detection of lung cancer and other critical findings while maintaining reporting efficiency.

---

## Notes
- The tool contains **no patient-identifiable data**.  
- Supplier-specific configuration may be required because each AI system defines findings differently.  
- Versions tailored to particular AI suppliers can be provided **freely on request** to research or NHS teams.

---

## Citation
If you use or adapt this tool, please cite:

> Bramley R et al. *Systematic Prioritisation of AI-Detected Chest X-ray Abnormalities for Optimised Lung Cancer Detection.* medRxiv 2024; https://www.medrxiv.org/content/10.1101/2024.12.30.24319499v2

---

## Contact
For configuration assistance or collaboration enquiries, please contact:  
**Dr Rhidian Bramley**  
Consultant Radiologist, The Christie NHS Foundation Trust  
Clinical Lead for Diagnostics, Digital and Innovation, Greater Manchester Cancer Alliance  

---

*© 2025 Greater Manchester Cancer Alliance – for non-commercial academic and NHS use.*

