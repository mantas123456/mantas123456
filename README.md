### Mantas Valantinavičius

Measurement scientist in Malta: laboratory quality and measurement, with Python and SQL for the data.

- 14 years in research and testing labs (2011–2025). Part of the team that took solid biofuel and SRF (solid recovered fuel) testing through ISO/IEC 17025 accreditation, start to finish
- Accredited fuel methods run hands-on (calorimetry, ICP-OES, ion chromatography, CHNS); emissions measurement against regulatory limits; TGA-GC-MS and DSC
- Acting laboratory manager at the University of Malta (2019–2023): set up Raman, ESEM, portable XRD and XRF, wrote their SOPs; CFD of the megalithic temples validated against field sensors
- Since 2025: packaging-waste reporting for the Lithuanian GPAIS register; writing a handbook on EU sustainability reporting (CBAM, Scope 3, CSRD)
- Python, SQL and Power BI for monitoring, validation and reporting automation; CFD and XDEM modelling

**Laboratory quality**

| Project | What it shows |
| --- | --- |
| [lab-quality-toolkit](https://github.com/mantas123456/lab-quality-toolkit) | `labqc` on PyPI: GUM uncertainty budgets, method validation, PT scores, Westgard QC rules and emission conversions. Tested, with a browser app and a validation report |
| [lab-accreditation-handbook](https://mantas123456.github.io/lab-accreditation-handbook/) | Free practical ISO/IEC 17025 guide: a page per clause, editable templates, gap-analysis and audit-planning tools |
| [measurement-uncertainty-handbook](https://mantas123456.github.io/measurement-uncertainty-handbook/) | Method validation and measurement uncertainty (GUM, Nordtest, Monte Carlo, bootstrap) with Python notebooks on synthetic data, calculated with `labqc`; CI runs every notebook before publishing. Early draft, first chapters in progress |

**Data engineering and modelling**

| Project | What it shows |
| --- | --- |
| [energy-data-pipeline](https://github.com/mantas123456/energy-data-pipeline) | ENTSO-E load data into PostgreSQL with idempotent upserts, SQL marts, data-quality checks and CI integration tests |
| [energy-forecasting-dashboard](https://github.com/mantas123456/energy-forecasting-dashboard) | Day-ahead demand forecasting with leak-free features, rolling backtest, naive baselines and an honest comparison with the grid operator's forecast |
| [f1-podium-prediction](https://github.com/mantas123456/f1-podium-prediction) | Finding and removing data leakage; season-based testing against a simple baseline |
| [NLP_Player_Feedback_Analysis](https://github.com/mantas123456/NLP_Player_Feedback_Analysis) | Topic tagging and sentiment checked against hand labels |

**Environmental compliance (in progress)**

| Project | What it shows |
| --- | --- |
| [esg-workflows-handbook](https://mantas123456.github.io/esg-workflows-handbook/) | Step-by-step CBAM, Scope 3, VSME and CSRD/ESRS workflows for EU SMEs. Regulatory facts tracked with sources and check dates, worked examples recomputed in CI. CBAM and Scope 3 drafted, CSRD in progress |

**Tools:** Python (pandas, scikit-learn, XGBoost, Streamlit), SQL/PostgreSQL, Docker, Power BI, MkDocs, OpenFOAM, pytest, GitHub Actions

[CV and portfolio](https://mantas123456.github.io) · [LinkedIn](https://www.linkedin.com/in/mantas-valantinavicius) · [Email](mailto:mantas.valantinavicius@gmail.com)
