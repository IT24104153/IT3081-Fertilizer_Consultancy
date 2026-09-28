# RUN ME FIRST — FINAL PROJECT

## 1. Open the R project

Open:

`Fertilizer_Consultancy_Project.Rproj`

in RStudio.

Do not run the scripts from a random working directory.

## 2. Install required packages once

```r
install.packages(c(
  "dplyr", "tidyr", "ggplot2", "corrplot",
  "car", "lmtest", "glmnet", "tibble"
))
```

## 3. Run the executable statistical tasks

```r
source("scripts/00_run_all.R")
```

This runs the executable R tasks in order.

Task 2 is a literature-review document and does not require R execution.

Task 11 is based on documentary industry-expert evidence and is therefore not an executable statistical script.

## 4. Main results

- Reports/tables: `output/reports/`
- Figures: `output/figures/`
- Final task documents: `docs/`
- Expert evidence: `evidence/task11/`

## 5. Task 10 dashboard

On Windows, double-click:

`OPEN_TASK10_DASHBOARD.bat`

or open:

`task10_ui/index.html`

The dashboard runs locally without internet access.

## 6. Important

Use this clean final project only. Do not mix scripts or outputs from older project ZIPs.
