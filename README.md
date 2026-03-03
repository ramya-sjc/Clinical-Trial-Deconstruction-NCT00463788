# Clinical-Trial-Deconstruction-NCT00463788
Phase II Oncology Trial Deconstruction and Operational Risk Assessment - Cetuximab + Cisplatin in Triple-Negative Metastatic Breast Cancer (NCT00463788)

## Project Objective

The objective of this project is to:
- Extract and structure trial-level data from ClinicalTrials.gov
- Analyze study design logic and endpoint strategy
- Evaluate statistical outcomes
- Assess operational complexity and safety reporting
- Identify potential risk areas from a clinical operations perspective

## Data Source

The primary data source is the publicly available ClinicalTrials.gov JSON record for NCT00463788.
The raw JSON file is stored in the `Data/` folder to ensure transparency, traceability, and reproducibility of the analysis.

## Skills Demonstrated
- Clinical protocol interpretation  
- Endpoint evaluation (BOR, PFS, OS, TTR)  
- Interpretation of statistical outputs (OR, HR, CI, p-values)  
- Safety signal review (MedDRA-coded adverse events)  
- Risk-based operational thinking  
- GCP awareness and compliance considerations  

---

## Study Background
This porject presents a structured deconstruction of Phase II randomized Oncology Trial evaluating the perfomance of Cetuximab in combination with Cisplatin versus Cisplatin alone in patients with Triple Negative Metastatic Breast Cancer (Estrogen Receptor [ER] Negative, Progesterone Receptor [PgR] Negative, and Human Epidermal Growth Factor Receptor 2 [HER2] Negative).

The study was sconducted as a randomized, open-label, parrarel-group design comparing:
Experimental arm: Cetuximab + Cisplatin
Control arm: Cisplatin alone


## Study Design
Study Type: Interventional
Study Phase: II
Allocation: Randomized (2:1 ratio)
Primary Purpose: Treatment
Condition: Metastatic Breast Cancer (Breast Neoplasm)


## Intrvention Summary
Experimental Arm: 
- Cetuximab (400 milligram per square meter [mg/m^2] initial dose, followed by 250 mg/m^2 weekly) by IV (intravenous infusion)
- Cisplatin (75 mg/m^2 IV every 3 weeks), 6 cycles.

Control Arm:
- Cisplatin (75 mg/m^2 evry 3 weeks), 6 cycles.
- Option to switch to receive cetuximab + cisplatin regim upon progression.

Treatment discontinued upon:
- Disease progression
- Unacceptable toxicity
- Withdrawal of consent

## Study Objectives
Primary Objective:
To determine whether the combination of cetuximab + cisplatin improves Best Overall Response (BOR) compared to cisplatin alone, and to assess whether the response exceeds a predefined threshold of 0.2

Secondary Objective:
Compare the differences between the two treatment groups using:
- Progression-Free Survival (PFS) Time
- Overall Survival (OS)
- Time to Response (TTR)
- Safety profile

---

### Further extraction and analytical documentation will be added progressively.
