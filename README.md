<img src="https://raw.githubusercontent.com/rulangyuezhao-cmd/rulangyuezhao-cmd/main/assets/chelsea-banner.svg" alt="Chelsea Zhao — engineering, data and applied AI. From production processes to tools people can use." width="100%">

[LinkedIn](https://www.linkedin.com/in/zhao-chelsea/) | [Résumé](resume/Chelsea_Zhao_Resume.pdf)

My route into AI started in chemical engineering: production processes, quality problems, and the people who have to make a system work every day. That experience now shapes how I build software and evaluate models.

I work across the application and the analysis: preparing data with SQL and Python, building desktop interfaces, connecting APIs, running models on remote Linux machines, and turning the results into something a person can inspect and use.

**I'm looking for opportunities in data science, machine learning and AI engineering.**

## Industry experience & applied AI

### Wolseley Express · AI checkout
*University of Toronto CMTE industry project · January–October 2026*

**Question**  
How can a parts-counter application identify all parts and quantities in a checkout image and support branch staff?

**Result**  
Developed and piloted an application covering **107 SKUs**, with **94.5% complete-checkout accuracy on 2,905 validation images**. This measure requires every part and quantity to be correct; it is validation-set performance.

**Methods**

- **Machine learning — computer vision:** PyTorch, YOLO object detection, SAM-assisted annotation and DINOv2 visual features.
- **Software development — desktop applications:** Python, Tkinter/ttk checkout UI, PyQt6/Qt annotation tools, event-driven interfaces and worker threads.
- **Data engineering & deployment:** SQL preparation and cleaning, HTTP/REST APIs, Azure Blob/Table Storage, Git/Azure DevOps, Docker and remote Linux/GPU workflows using SSH and SCP.
- **Product development:** branch-staff requirements, senior-developer collaboration and workflow refinement.

**Confidentiality:** application code, company data and infrastructure details are not shared publicly. [Public project summary →](https://github.com/rulangyuezhao-cmd/meng-data-science-portfolio/tree/main/courses/che1800)

### Big Data & AI Case Competition · U of T IMI / Scotiabank
*Industry-sponsored competition · November 2023–March 2024*

**Question**  
How can financial-risk analysis combine structured records and other signals to flag cases for further investigation?

**Result**  
Analyzed **560K records** and placed **Top 5 of 70 teams**.

**Methods**

- **Data preparation & analytics:** SQL and Python for organizing, cleaning, preprocessing and analyzing records.
- **Machine learning — classification:** XGBoost and LightGBM, with class-imbalance and false-negative tradeoffs.
- **Machine learning — anomaly detection:** unsupervised methods and graph/network analysis.
- **Language & evidence analysis:** web scraping and NLP/LLM-assisted validation.

**Confidentiality:** competition code and underlying data are not shared publicly. This was a competition, not employment with Scotiabank.

### Atlantic Packaging · Manufacturing analytics
*Process Engineer Co-op · August 2021–September 2022*

**Question**  
Which production and process changes can improve packaging performance and reduce operating costs?

**Result**  
Controlled process-parameter testing contributed to **$300K in annual savings** and a **36% cost reduction** in the targeted process.

**Methods**

- **Data analytics:** SQL and Python to consolidate, prepare, analyze and visualize production, cost and process data.
- **Business intelligence:** **DOMO and Excel KPI dashboards** and analytical reporting.
- **Process improvement:** controlled parameter testing and communication with technical and operational stakeholders.

My other industry experience spans process engineering at **Crystal Claire** and GMP operations at **Eurofins CDMO Alphora**, connecting quality, manufacturing and cross-functional delivery.

## Featured MEng & public projects

### ReasonEval · Looking beyond an LLM's final answer
*MIE1512H · Winter 2026 (January–April)*

**Question**  
How closely do automated evaluations of mathematical reasoning agree with human annotations?

**Result**  
Evaluated **3,400 solutions from 12 language models**. The public notebooks analyze saved inference scores; they do not reproduce the original GPU scoring pipeline.

**Methods**

- **AI — language-model inference:** ReasonEval-7B, PyTorch, Hugging Face and GPU/CPU offloading.
- **Data analysis & model evaluation:** pandas, saved Parquet outputs, human-annotation comparisons and visual error analysis.

[Explore ReasonEval →](https://github.com/rulangyuezhao-cmd/mie1512-reasoneval-portfolio)

### MEng Data Science Portfolio · Assumptions made visible

**Question**  
How do statistical and machine-learning approaches compare across salary data, process analytics and financial forecasting?

**Result**  
**15 runnable CPU analyses** document results, baselines and limitations. Some simple forecasting baselines outperform the fitted models; those comparisons remain visible.

**Methods**

- **Statistical analysis — hypothesis testing:** Welch's t-test, unequal-variance ANOVA and variance checks.
- **Statistical analysis — uncertainty:** bootstrap resampling and confidence intervals.
- **Machine learning:** classification, regression, clustering, anomaly detection and PCA.
- **Time-series analysis:** forecasting with held-out evaluation and explicit baselines.
- **Data preparation:** Python, SQL, pandas and NumPy.

These are documented public adaptations of original coursework. [Choose an analysis →](https://github.com/rulangyuezhao-cmd/meng-data-science-portfolio)

### Teacher-AID · GenAI Genesis
*Two-day hackathon · March 2026*

**Question**  
How can a teacher generate assessments grounded in a student's learning history and inspect the results?

**Result**  
Contributed end to end to a prototype spanning the interface, backend, deployment, synthetic classroom data and evaluation dashboards.

**Methods**

- **AI — retrieval-grounded generation:** DeepSeek and retrieval of student/concept history.
- **Software development:** FastAPI, API integration and UI/backend workflows.
- **Data & evaluation:** synthetic datasets and dashboards.

[Explore Teacher-AID →](https://github.com/DarkinCoder/teacheraid)

## Technical toolkit

| Area | Tools & skills |
| --- | --- |
| **AI development tools** | Codex · Claude Code |
| **Data processing & analytics** | SQL · Python · pandas · NumPy · Databricks/PySpark · data cleaning, preprocessing and EDA |
| **Business intelligence** | DOMO · Excel · KPI dashboards · analytical reporting |
| **Machine learning** | scikit-learn · XGBoost · LightGBM · classification · regression · clustering · model evaluation |
| **Deep learning** | PyTorch · TensorFlow/Keras coursework · dense neural networks · LSTM |
| **Reinforcement learning** | Fundamentals |
| **Computer vision** | OpenCV · YOLO · SAM · DINOv2 · object detection · annotation and segmentation workflows |
| **LLMs & applied AI** | Hugging Face · DeepSeek · ReasonEval · retrieval-augmented generation · GPU/CPU offloading |
| **Statistical analysis & visualization** | SciPy · statsmodels · Matplotlib · Bokeh · hypothesis testing · bootstrap confidence intervals · SHAP · LIME |
| **Programming & software engineering** | Python · OOP · HTML · CSS · JavaScript · FastAPI · HTTP/REST APIs |
| **Desktop development** | Tkinter/ttk · PyQt6/Qt · event-driven interfaces · worker threads · annotation tools |
| **Cloud & development environments** | Azure Blob/Table Storage · GCP · Docker · Linux · remote Linux/GPU workflows · SSH · SCP · VS Code |
| **Version control & collaboration** | Git · GitHub · Azure DevOps |

## Methods I've used and studied

The list below spans my projects, original coursework and documented portfolio adaptations. The linked course pages identify what is currently runnable; original neural-network, Prophet, SHAP/LIME and other experiments are not all reproduced in the compact public programs.

**Supervised learning and regression**  
Ordinary least squares / linear regression · Ridge (L2) and Lasso (L1) regression · logistic regression · support vector regression (SVR) · k-nearest neighbours · decision trees · random forest classification and regression · gradient-boosted trees with XGBoost and LightGBM · class weighting and imbalanced classification

**Unsupervised learning and anomaly detection**  
K-means · agglomerative hierarchical clustering (Ward linkage) · Gaussian mixture models · principal component analysis (PCA) and reconstruction · graph/network analysis

**Statistical inference and analysis**  
Hypothesis testing · independent-samples t-tests, including Welch's t-test · one-way ANOVA and Welch's ANOVA · Levene's variance test · bootstrap resampling and confidence intervals · Pearson correlation · IQR outlier screening · descriptive statistics · exploratory data analysis

**Time series and forecasting**  
ARIMA · SARIMA/SARIMAX and exogenous-variable modelling · Holt–Winters / exponential smoothing · vector autoregression (VAR) · Prophet · seasonal/trend regression · lag features · moving-average signals · persistence and seasonal-naive baselines

**Deep learning, computer vision and language models**  
Dense neural networks · LSTM networks · YOLO object detection · SAM-assisted segmentation · DINOv2 visual features · pretrained LLM inference · GPU/CPU offloading · retrieval-grounded generation · NLP-assisted validation · reinforcement learning fundamentals

**Optimization, interpretation and evaluation**  
Batch gradient descent · grid search · stratified cross-validation · time-series cross-validation · held-out evaluation · confusion matrices · accuracy and balanced accuracy · precision/recall and F1 · ROC AUC · MAE/RMSE · silhouette score · permutation importance · partial dependence · SHAP · LIME · Jensen–Shannon distribution comparison

[Browse the course timeline and evidence →](https://github.com/rulangyuezhao-cmd/meng-data-science-portfolio/blob/main/COURSE_COVERAGE.md)

## Education

**University of Toronto**  
M.Eng., Chemical Engineering — Data Analytics & Machine Learning emphasis; conferred October 2026.  
B.A.Sc., Chemical Engineering — Bioengineering and Engineering Business minors; conferred June 2023.

*Course dates refer to the original academic sessions. Portfolio reconstruction and documentation updates are labelled separately.*
