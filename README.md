## Heywood Williams-Tracy

M.S. in Data Science, University of Virginia School of Data Science (2026). B.A. in Public Policy & Data
Science, UNC Chapel Hill (2023).

**Instructional Assistant for DS 2002: Data Science Systems** at UVA — the course
covering the engineering layer beneath data science work: relational and NoSQL data
stores, ETL pipelines, cloud services, containers, and API integration. I held office
hours, walked students through lab environments, and debugged their pipelines with
them. Explaining why a broken pipeline is broken, to someone who has not yet learned to
read the error, turned out to be the fastest way to get rigorous about my own
fundamentals.

**Open to data science, data engineering and ML engineering roles.**

---

### What I work on

**Quantitative trading systems.** Market-making bots for Kalshi's prediction markets —
live order management, inventory and risk limits, and backtesting against recorded
order book data. The current generation is a Rust rewrite of an earlier Python system,
built as a deliberate line-for-line port so the two could be diffed against each other
under golden-fixture parity tests.

**Data engineering.** Serverless ETL and alerting pipelines on AWS — Lambda,
EventBridge, DynamoDB, SNS — defined as infrastructure-as-code with SAM and Terraform.
Also Docker, Kubernetes, and Kinesis, from both DS 2002 and UVA's cloud systems
coursework.

**Applied statistics and ML.** Regression and statistical learning, deep learning
(CNNs, sequence models), computer vision, and geospatial analysis in Python and R.
My MSDS capstone applies this to fund performance — Fama-French factor attribution,
time-varying-parameter Kalman filters, macro-regime models, and Brinson-Fachler
decomposition, on top of a point-in-time data-engineering pipeline.

---

### Selected public work

| Project | What it is |
|---|---|
| [intl-equity-fund-capstone](https://github.com/heywoodwt/intl-equity-fund-capstone) | M.S. Data Science capstone — explaining and predicting an actively-managed international (developed ex-US) equity fund's performance. A point-in-time data-engineering pipeline (FRED macro, Ken French factors, WRDS/FactSet fundamentals), time-varying-parameter Kalman-filter factor attribution and Kalman macro-regime models, Brinson-Fachler performance attribution, and a Streamlit quant tear-sheet dashboard. Anonymized for public release; ~140 tests. |
| [pmr-report-agent](https://github.com/heywoodwt/pmr-report-agent) | Generates a 13-page quarterly real-estate portfolio report from a drop folder of Excel workbooks, PDFs and a slide deck. Code computes, ranks and foots every figure; Claude only reads chart images and drafts prose, and code checks each sentence against its source. Every printed number (608 per report) carries a cell- or page-level locator in a manifest, and a reviewer must approve before the final PDF is written. Byte-identical reruns, 140 tests, Flask review app, Azure infrastructure in OpenTofu. Synthetic data. |
| [kalshi-mm](https://github.com/heywoodwt/kalshi-mm) | Rust market-making bot for Kalshi prediction markets. A line-for-line port of an earlier Python system, with golden-fixture parity tests proving the two agree on fees, observations, and policy output. 7k lines, 136 tests, CI, containerized release. |
| [job_alert_bot](https://github.com/heywoodwt/job_alert_bot) | Serverless AWS pipeline that scrapes job listings, deduplicates against DynamoDB, and alerts via SNS. SAM IaC, 31 tests under `moto`. |
| [resume_link_tracker](https://github.com/heywoodwt/resume_link_tracker) | Generates a resume for each application with company-specific short links, then logs every recruiter click through API Gateway, Lambda, and DynamoDB with SNS email alerts. A Chalice API serves click analytics and matplotlib plots from S3. |
| [Cville_Parking_Ticket_EDA](https://github.com/heywoodwt/Cville_Parking_Ticket_EDA) | Geocoding and interactive mapping of Charlottesville parking enforcement data. |
| [PGB_FantasyFootball](https://github.com/heywoodwt/PGB_FantasyFootball) | Season-long analysis off the ESPN Fantasy API; reconstructs PPR scoring from raw stat lines. |
| [Flood_Analysis_PLCY_698](https://github.com/heywoodwt/Flood_Analysis_PLCY_698) | County-level flood risk and disaster-relief funding analysis in R, for the Environmental Defense Fund. |
| [ds_5030_work](https://github.com/heywoodwt/ds_5030_work) | Graduate statistical learning coursework — regression, classification, resampling, regularization. |

Some of my work including trading work is still in private repositories. Happy to walk through any of it.

---

### Tools

`Python` · `Rust` · `R` · `SQL` · `pandas` · `scikit-learn` · `PyTorch` · `AWS (Lambda, DynamoDB, SNS, Kinesis, SAM)` · `Azure` · `Docker` · `Kubernetes` · `Terraform / OpenTofu` · `Claude API` · `Git`...

---

[Website](https://heywood.williams-tracy.org) · [LinkedIn](https://www.linkedin.com/in/heywoodwt/)
