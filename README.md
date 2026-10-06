# Time Series Analysis — R Labs (BDBA)

**Student GitHub repo:** https://github.com/iedaejin/time-series-analysis-labs

This repository is **for students only**. Do not add instructor keys, graders, answer banks, or private notes here.

These are the student R labs for **Time Series Analysis** (Bachelor in Data and Business Analytics). Use **Posit Cloud** or local RStudio.

## Posit Cloud workflow

1. Create one Posit Cloud assignment per lab folder.
2. Students open `tutorial.Rmd` and click **Run Document** (needs `learnr` and `fpp3`).
3. They answer the questions, type their name, and download the `.txt`.
4. They upload that text file. It contains their name, the date, and each answer.

The longer session notebook in the same folder is optional guided analysis. The file to submit is the `.txt` from the tutorial. Do not Knit the whole session notebook on Posit Cloud if a chunk fails; the tutorial runs one exercise at a time.

```r
install.packages(c("learnr", "fpp3", "tidyverse"))
# From the lab folder:
rmarkdown::run("tutorial.Rmd")
```

Every lab folder has `tutorial.Rmd` and `lab_submission.R`.

## Packages

```r
install.packages(c("learnr", "fpp3", "tidyverse"))
library(fpp3)
```

## Lab sequence

Open `tutorial.Rmd` in each folder. The session notebook is optional.

| Folder | Tutorial | Session |
|--------|----------|--------:|
| `Lab_01_Introduction_R` | `tutorial.Rmd` | 1 |
| `Lab_02_Time_Series_Graphics` | `tutorial.Rmd` | 2 |
| `Lab_03_Autocorrelation` | `tutorial.Rmd` | 3 |
| `Lab_04_Classical_Decomposition` | `tutorial.Rmd` | 4 |
| `Lab_05_STL_BoxCox` | `tutorial.Rmd` | 5 |
| `Lab_06_Benchmark_Forecasts` | `tutorial.Rmd` | 6 |
| `Lab_07_Simple_Exponential_Smoothing` | `tutorial.Rmd` | 7 |
| `Lab_08_Residuals_Analysis` | `tutorial.Rmd` | 8 |
| `Lab_09_Review_Exercises` | `tutorial.Rmd` | 9 |
| `Lab_11_Trended_ETS` | `tutorial.Rmd` | 11 |
| `Lab_12_Seasonal_ETS` | `tutorial.Rmd` | 12 |
| `Lab_13_Error_Metrics` | `tutorial.Rmd` | 13 |
| `Lab_14_Train_Test_CV` | `tutorial.Rmd` | 14 |
| `Lab_15_Stationarity_Differencing` | `tutorial.Rmd` | 15 |
| `Lab_16_ARMA` | `tutorial.Rmd` | 16 |
| `Lab_17_Nonseasonal_ARIMA` | `tutorial.Rmd` | 17 |
| `Lab_18_ETS_Accuracy_Stationarity_ARIMA` | `tutorial.Rmd` | 18 |
| `Lab_19_Final_Course_Review` | `tutorial.Rmd` | 19 |

Sessions **10** (midterm) and **20** (final exam) have no student lab here.

## AI policy

Do not submit GenAI-written lab solutions. You may ask AI to explain class code or help debug *your* code.

**Faculty:** Prof. Dae-Jin Lee (`daelee@faculty.ie.edu`) · IE University — Scitech
