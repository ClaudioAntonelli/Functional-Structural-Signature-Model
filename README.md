This repository contains the datasets used during the validation of the model and the results obtained.

The /dataset folder includes three controlled test environments:
 - RAW_BASELINE_3_DOMAINS.csv: empirical real project data collected across three distinct software application domains (Billing, Data Platform, Integration).
 - RAW_BASELINE_STANDARD.csv: synthetic benchmark dataset generated with ideal structural alignment to establish optimal theoretical convergence boundaries.
 - RAW_BASELINE_EXTREME.csv: synthetic stress-test dataset artificially injected with structural noise and process anomalies to isolate severe outliers.

The /output folder stores the result sets of the tests applied to validate the model:
 - 3_domains/: results from benchmarking real-world project data across three distinct application domains (Billing, Data Platform, Integration).
 - standard_baseline/: results from benchmarking synthetic data with ideal structural alignment (theoretical baseline).
 - extreme_baseline/: results from benchmarking synthetic stress-test data injected with structural noise and severe process anomalies.
 - sensitivity_analysis/: evaluation of the Project Coherence Class assignment under varying quantile configurations, demonstrating that model performance and diagnostic stability are independent of threshold selection.
