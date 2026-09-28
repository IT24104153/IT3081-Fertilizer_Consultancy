# Fertilizer Consultancy Project — FINAL CLEAN VERSION

## Project purpose

This is the finalized IT3081 Statistical Modelling consultancy project for a Sri Lankan paddy fertilizer decision-support problem.

The project contains the final dataset, R scripts, task reports, statistical outputs, Task 10 functional dashboard, Task 11 expert evidence, and Task 12 senior-management recommendations.

Old AI-generated scripts, superseded analyses, duplicate Task 11 documents, repair notes, and internal verification files have been removed from this clean version.

---

## Start here

1. Read `RUN_ME_FIRST.md`.
2. Open `Fertilizer_Consultancy_Project.Rproj` in RStudio.
3. To regenerate executable analysis outputs, run:

```r
source("scripts/00_run_all.R")
```

4. To open the functional Task 10 dashboard on Windows, double-click:

`OPEN_TASK10_DASHBOARD.bat`

or open:

`task10_ui/index.html`

---

## Final task documents

- Task 1 — `docs/TASK_1_INDUSTRY_PROBLEM.md`
- Task 2 — `docs/02_research_landscape.md`
- Task 3 — `docs/TASK_3_DATASET_UNDERSTANDING.md`
- Task 4 — `docs/TASK_4_STATISTICAL_INFERENCE.md`
- Task 5 — `docs/TASK_5_PREDICTIVE_STATISTICAL_MODELLING.md`
- Task 7 — `docs/TASK_7_PCA_CRITICAL_EVALUATION.md`
- Task 8 — `docs/TASK_8_BAYESIAN_CRITICAL_EVALUATION.md`
- Task 9 — `docs/TASK_9_TIME_SERIES_CRITICAL_DISCUSSION.md`
- Task 10 — `docs/TASK_10_INDUSTRY_INNOVATION_PROPOSAL.md`
- Task 11 — `docs/TASK_11_INDUSTRY_EXPERT_VALIDATION.md`
- Task 12 — `docs/TASK_12_FINAL_CONSULTANCY_RECOMMENDATIONS.md`

Dataset Selection requirement:
- `docs/SECTION_6_DATASET_SELECTION.md`

Task 6 experimental-design work:
- `scripts/06_experimental_design_eval.R`
- related `output/reports/06_*` files are regenerated when the R script is run.

---

## Important supporting documents

Lecture/lab alignment and validation notes are retained where they help defend the work:

- `docs/TASK_4_LECTURE_LAB_ALIGNMENT.md`
- `docs/TASK_5_LECTURE_LAB_ALIGNMENT.md`
- `docs/TASK_8_LECTURE_LAB_ALIGNMENT.md`
- `docs/TASK_11_EVIDENCE_REGISTER.md`
- `docs/TASK_12_EVIDENCE_TRACEABILITY.md`
- `docs/TASK_12_MANAGEMENT_SUMMARY.md`

These are supporting documents, not older competing versions.

---

## Evidence and outputs

- Dataset: `Fertilizer_Dataset.csv`
- R scripts: `scripts/`
- Tables and reports: `output/reports/`
- Figures: `output/figures/`
- Industry expert evidence: `evidence/task11/`
- Functional dashboard: `task10_ui/`

The optional Task 11 follow-up feedback form is kept separately in:

`optional_support/`

It is not required to run the main project.

---

## Final modelling position

The Task 5 model stack used by the Task 10 dashboard is:

- Urea → LASSO
- TSP → LASSO
- MOP → Gamma GLM

The system is presented as **decision support**, not an autonomous fertilizer prescription engine.

The final management recommendation is to proceed with a **controlled, expert-supervised pilot**, subject to:

1. approved agricultural standards;
2. qualified agricultural review;
3. real-world field validation;
4. continuous model monitoring;
5. transparent data/model governance.

---

## Important statistical boundaries

- The dataset is observational.
- Predictive accuracy does not prove agronomic optimality.
- The current data do not prove higher yield, lower cost, or environmental improvement.
- Existing `Recommended_N`, `Recommended_P2O5`, and `Recommended_K2O` fields are excluded from independent Urea/TSP/MOP prediction to prevent target leakage.
- The present data are not a genuine time series.
- PCA remains exploratory rather than the default production representation.
- Task 11 industry evidence supports organizational/implementation relevance but does not replace agronomic field trials.

---

## Final submission note

This ZIP is the cleaned final project. There is no `legacy_original/` folder and no superseded analysis should be submitted from an older ZIP.
