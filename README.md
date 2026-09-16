# 📊 Data Science Development: Applied Data Wrangling & Analysis Portfolio

[![Python Version](https://img.shields.io/badge/python-3.10%2B-blue.svg)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/pandas-2.0%2B-150458.svg)](https://pandas.pydata.org/)
[![SciPy](https://img.shields.io/badge/scipy-1.10%2B-blue.svg)](https://scipy.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Status: Active](https://img.shields.io/badge/status-active-success.svg)]()

An applied, portfolio-grade data science repository demonstrating **data hygiene**, **missing value diagnostics & imputation architecture**, **advanced conditional filtering & anomaly detection**, **multi-dimensional statistical aggregation**, **domain-driven spatial filtration**, **algorithmic outlier engineering**, **enterprise data governance**, and **advanced inferential statistics & hypothesis testing** across socioeconomic, public health, labor market, education, and real estate datasets.

---

## 🧭 Activity Navigation Index

| Module / Day | Topic & Core Focus | Applied Methodologies | Target Datasets | Notebook Link |
| :--- | :--- | :--- | :--- | :--- |
| [**Activity 1 (Day 1)**](#-activity-1-day-1--missing-data-diagnostics--imputation-methodologies) | **Data Hygiene & Imputation** | Ingestion, Null Diagnostics, Listwise Deletion vs. Mean & Explicit Categorical Imputation | `nigeria_unemployment_missing_data.csv` | [`day-1-data-wrangling.ipynb`](./day-1-data-wrangling.ipynb) |
| [**Activity 2 (Day 2)**](#-activity-2-day-2--advanced-conditional-filtering--anomaly-auditing) | **Conditional Slicing & Auditing** | Compound Boolean Indexing (`&`, `\|`), Policy Slicing, Resource Allocation, Cross-Feature Auditing | `nigeria_economic_data.csv`<br>`nigeria_nursing_mothers_healthcare.csv`<br>`nigeria_unemployment_missing_data.csv` | [`day-2-data-wrangling & filtering.ipynb`](./day-2-data-wrangling%20%26%20filtering.ipynb) |
| [**Activity 3 (Day 3)**](#-activity-3-day-3--data-aggregation-multi-dimensional-grouping--statistical-reporting) | **Aggregation & Statistical Reporting** | `.groupby()`, Multi-Level Grouping, Aggregation Engines (`.agg()`), Frequency Binning | `nigeria_economic_data.csv`<br>`nigeria_nursing_mothers_healthcare.csv`<br>`nigeria_unemployment_missing_data.csv` | [`day-3-data-aggregation.ipynb`](./day-3-data-aggregation.ipynb) |
| [**Activity 4 (Day 4)**](#-activity-4-day-4--deep-dive-missing-data-architecture-sentinel-evolution--advanced-imputation) | **Missing Data Architecture & Advanced Imputation** | Sentinel Evolution, Nullable `Int32`, Geography Pruning, Skewness & Median Imputation, Subgroup Fill | `nigeria_unemployment_missing_data.csv` | [`day-4-data-wrangling-and-missing-data.ipynb`](./day-4-data-wrangling-and-missing-data.ipynb) |
| [**Activity 5 (Day 5)**](#-activity-5-day-5--exploratory-data-analysis-for-outlier-detection-spatial-engineering--domain-driven-filtration) | **Outlier Detection & Domain-Driven Filtration** | Multi-Stage Pipelines (1–5), Continuous Range Parsing, Feature Engineering (`bhk`, `price_per_sqft`), Domain Thresholding | `house_prices.csv` | [`day-5-outlier-outlier-detection.ipynb`](./day-5-outlier-outlier-detection.ipynb) |
| [**Activity 6 (Day 6)**](#-activity-6-day-6--advanced-statistical-outlier-engineering--algorithmic-anomaly-filtration) | **Statistical & Algorithmic Outlier Engineering** | Empirical Rule ($\mu \pm 1\sigma$), Location-Grouped PPS Filtration, Scatter Diagnostics, Cross-BHK Algorithmic Benchmark Engine | `house_prices.csv` | [`day-6-outlier-outlier-detection.ipynb`](./day-6-outlier-outlier-detection.ipynb) |
| [**Activity 7 (Day 7)**](#-activity-7-day-7--enterprise-data-governance-frameworks--conceptual-foundations-of-inference) | **Enterprise Data Governance** | Governance vs. Management, 6 Enterprise Pillars, Descriptive vs. Inferential Paradigms, 4 Pillars of Inference | Conceptual Architecture | [`day-7-data-governance-and-inferential-statistics.ipynb`](./day-7-data-governance-and-inferential-statistics.ipynb) |
| [**Activity 8 (Day 8)**](#-activity-8-day-8--applied-inferential-statistics-ab-testing--independent-t-testing) | **Applied Inferential Statistics & A/B Testing** | Independent vs. Paired $t$-Tests, A/B Campaign Simulation, Institutional Hypothesis Testing (`scipy.stats.ttest_ind`) | `us_education_system_dataset.csv` | [`day-8-inferential-statistics.ipynb`](./day-8-inferential-statistics.ipynb) |
| [**Activity 9 (Day 9)**](#-activity-9-day-9--advanced-inferential-statistics-one-way-anova-chi-square-independence--correlation-significance) | **Advanced Inferential Statistics** | One-Way ANOVA (`stats.f_oneway`), Chi-Square Test of Independence (`stats.chi2_contingency`), Pearson Correlation Significance (`stats.pearsonr`) | `us_education_system_dataset.csv` | [`day-9-inferential-statistic-part-2.ipynb`](./day-9-inferential-statistic-part-2.ipynb) |

---

## 🍽️ The Core Philosophy: *The Data Kitchen & The Data Chef*

In real-world data science, raw data rarely arrives clean, balanced, or modeling-ready. Just as a world-class restaurant cannot serve meals straight from raw farm crates:

- **Raw Ingredients = Raw Data**: Datasets contain missing values ("spoilage/rot"), inconsistent units, demographic contradictions, formatting range strings, and physical anomalies.
- **The Data Chef = The Data Scientist**: Responsible for inspecting every feature, assessing data hygiene, diagnosing *why* anomalies exist, applying principled cleaning, slicing cohorts, engineering aggregations, and isolating outliers before machine learning modeling.
- **The High-Tech Oven = Machine Learning**: Powerful algorithms training on prepared data. A high-tech oven cannot fix rotten or unwashed food.
- **The Food Safety Code & Health Inspector = Data Governance**: The organizational and ethical framework defining who can access ingredients, how long records can be preserved, strict sanitary standards, traceability, and regulatory compliance.

---

## 📁 Repository Structure

```text
├── day-1-data-wrangling.ipynb                            # Day 1: Ingestion, null diagnostics, and imputation experiments
├── day-2-data-wrangling & filtering.ipynb                # Day 2: Compound conditional filtering & anomaly detection
├── day-3-data-aggregation.ipynb                          # Day 3: Multi-dimensional grouping, aggregation & reporting
├── day-4-data-wrangling-and-missing-data.ipynb           # Day 4: Missing data architecture, sentinel theory & advanced imputation
├── day-5-outlier-outlier-detection.ipynb                 # Day 5: Multi-stage pipeline architecture & domain outlier filtration
├── day-6-outlier-outlier-detection.ipynb                 # Day 6: Advanced statistical outlier engineering & algorithmic filtration
├── day-7-data-governance-and-inferential-statistics.ipynb # Day 7: Enterprise data governance frameworks & inference theory
├── day-8-inferential-statistics.ipynb                    # Day 8: Applied inferential statistics, A/B testing & t-tests
├── day-9-inferential-statistic-part-2.ipynb              # Day 9: Advanced inferential statistics (ANOVA, Chi-Square, Pearson r)
├── nigeria_unemployment_missing_data.csv                 # Employment survey dataset with missing entries (5,000 rows)
├── nigeria_economic_data.csv                             # Socioeconomic indicators & poverty level classification (10,000 rows)
├── nigeria_nursing_mothers_healthcare.csv                # Maternal healthcare access & immunization metrics (10,000 rows)
├── us_education_system_dataset.csv                       # Institutional US educational outcomes dataset (5,000 rows)
├── .gitignore                                            # Standard git ignore rules for Python & Jupyter artifacts
└── README.md                                             # Comprehensive project documentation and portfolio log
```

---

## 📊 Datasets Overview

### 1. `nigeria_unemployment_missing_data.csv` (5,000 Records)
Demographic profiles, labor market engagement, and income data with realistic missingness patterns for data hygiene and labor dynamics exercises.
- **Key Columns**: `Age`, `Gender`, `Region`, `Location` (Urban/Rural), `Education_Level`, `Employment_Status`, `Years_Of_Experience`, `Monthly_Income_NGN`.

### 2. `nigeria_economic_data.csv` (10,000 Records)
Individual socioeconomic indicators, occupation classifications, employment arrangements, monthly income, and poverty status classification.
- **Key Columns**: `Individual_ID`, `Age`, `Gender`, `Region`, `Location`, `Education_Level`, `Occupation`, `Employment_Type`, `Monthly_Income_NGN`, `Poverty_Status`.

### 3. `nigeria_nursing_mothers_healthcare.csv` (10,000 Records)
Demographic and healthcare access dataset examining delivery facilities, immunization coverage, wealth quintiles, and travel distance to clinics.
- **Key Columns**: `Geopolitical_Zone`, `Residence`, `Wealth_Quintile`, `Education_Level`, `Skilled_Birth_Attendance`, `Facility_Delivery`, `Exclusive_Breastfeeding`, `Full_Immunization`, `Distance_to_Facility_km`.

### 4. `house_prices.csv` (13,320 Records)
Real estate and residential property transaction dataset with mixed string formats, range-based square footage, bathroom configurations, and pricing distributions.
- **Key Columns**: `area_type`, `availability`, `location`, `size` (e.g. `'2 BHK'`, `'4 Bedroom'`), `society`, `total_sqft` (e.g. `'1056'`, `'2100 - 2850'`), `bath`, `balcony`, `price`.

### 5. `us_education_system_dataset.csv` (5,000 Records)
Comprehensive national institutional dataset analyzing secondary and post-secondary educational attainment, governance models (`control`: Public vs. Private), NCES locale classifications, Title I funding eligibility, per-pupil expenditure, student-teacher staffing ratios, STEM certification flags, and graduation rates for inferential hypothesis testing and variance modeling.
- **Key Columns**: `institution_id`, `institution_name`, `state_name`, `nces_locale`, `control`, `title_i_status`, `student_teacher_ratio`, `per_pupil_expenditure_usd`, `graduation_rate_pct`, `stem_certified_flag`.

---

## 🔬 Activity 1 (Day 1) — Missing Data Diagnostics & Imputation Methodologies

> **Notebook**: [`day-1-data-wrangling.ipynb`](./day-1-data-wrangling.ipynb)  
> **Primary Dataset**: `nigeria_unemployment_missing_data.csv` (5,000 rows × 8 columns)

### Workflow Overview

```mermaid
flowchart TD
    A[Raw Dataset: 5,000 Records] --> B[Data Inspection & Null Counting]
    B --> C{Formulate Strategy}
    C -->|Strategy 1: Deletion| D[Complete Case Analysis: dropna]
    D --> E[Data Loss: 5,000 to 3,018 - 39.6% Sample Lost]
    C -->|Strategy 2: Statistical Imputation| F[Years_Of_Experience: Mean Imputation ~21.84 yrs]
    C -->|Strategy 3: Categorical Preservation| G[Education_Level: Explicit 'Unknown' Category]
    F --> H[Cleaned Dataset Retaining 100% of Observations]
    G --> H
```

### Phase-by-Phase Breakdown

#### Phase 1: Ingestion & Initial Inspection
- Loaded `nigeria_unemployment_missing_data.csv` using `pandas.read_csv()`.
- Validated initial dimension: **5,000 observations across 8 features**.
- Inspected leading rows (`.head()`) to understand variable types and structural schema.

#### Phase 2: Missing Value Diagnostics ("Identifying the Rot")
Quantified null counts across each column using `.isnull().sum()`:
- **`Education_Level`**: 1,127 missing values (~22.54%)
- **`Years_Of_Experience`**: 500 missing values (10.00%)
- **`Monthly_Income_NGN`**: 408 missing values (8.16%)
- **`Region`**: 250 missing values (5.00%)
- **`Age`, `Gender`, `Location`, `Employment_Status`**: 0 missing values (Complete features)

#### Phase 3: Strategy Formulation
1. **Understand Missingness**: Evaluated whether missing values are Missing Completely at Random (MCAR), Missing at Random (MAR), or Missing Not at Random (MNAR).
2. **Weigh Analytical Cost**: Evaluated data loss resulting from naive row deletion vs. bias introduced by imputation.
3. **Establish Column-Specific Handlers**: Separated continuous metrics from categorical dimensions.

#### Phase 4: Cleaning & Imputation Experiments

##### Strategy 1: Complete Case Deletion (`dropna`)
- Applied `.dropna(inplace=True)` on a cloned dataframe.
- **Outcome**: Row count plummeted from **5,000 to 3,018 rows** (a **39.64% loss of data**).
- **Takeaway**: Listwise deletion severely shrinks sample power and introduces risk of systematic attrition bias.

##### Strategy 2: Statistical Imputation for Continuous Numerical Data
- Calculated the sample mean for `Years_Of_Experience`:
  $$\bar{x} \approx 21.835 \text{ years}$$
- Imputed null entries using `.fillna(average_experience)` to preserve complete observation count while maintaining central tendency.

##### Strategy 3: Explicit Categorical Preservation for `Education_Level`
- Evaluated non-null distribution (Secondary: 45.52%, Primary: 31.24%, Tertiary: 23.24%).
- Converted missing entries into an explicit `'Unknown'` class to retain records for non-education downstream models:
  - Secondary: 35.26% (1,763 rows)
  - Primary: 24.20% (1,210 rows)
  - Unknown: 22.54% (1,127 rows)
  - Tertiary: 18.00% (900 rows)

### Activity 1 Results Matrix

| Metric / Feature | Raw Data | Strategy 1: Drop Missing (`dropna`) | Strategy 2: Targeted Imputation |
| :--- | :--- | :--- | :--- |
| **Total Rows** | 5,000 | 3,018 (**-39.6% reduction**) | 5,000 (**100% sample retained**) |
| **Missing `Years_Of_Experience`** | 500 | 0 | 0 (Imputed with Mean: $\approx 21.84$) |
| **Missing `Education_Level`** | 1,127 | 0 | 0 (Preserved as `'Unknown'`) |
| **Sample Representativeness** | Full (with gaps) | Reduced / Potentially Biased | Maintained across all sub-populations |

---

## 🎯 Activity 2 (Day 2) — Advanced Conditional Filtering & Anomaly Auditing

> **Notebook**: [`day-2-data-wrangling & filtering.ipynb`](./day-2-data-wrangling%20%26%20filtering.ipynb)  
> **Core Concepts**: Boolean Masking, Compound Conditionals (`&`, `|`), Scope Slicing, Anomaly Auditing

### Workflow Overview

```mermaid
flowchart TD
    subgraph S1[Case Study 1: Policy Cohort Slicing]
        A1[Nigerian Economic Data: 10,000 Rows] --> B1["Condition: (Age >= 18) & (Age <= 65)"]
        B1 --> C1[Working-Age Adults: 4,923 Rows]
    end
    subgraph S2[Case Study 2: Targeted Resource Allocation]
        A2[Nursing Mothers Data: 10,000 Rows] --> B2["Condition: (Residence == 'Rural') & (Wealth_Quintile == 'Poorest')"]
        B2 --> C2[High-Priority Mothers: 1,866 Rows]
    end
    subgraph S3[Case Study 3: Anomaly & Inconsistency Auditing]
        A3[Unemployment Survey: 5,000 Rows] --> B3["Condition: (Age < 18) & (Education_Level == 'Tertiary')"]
        B3 --> C3[Flagged Suspicious Records: 52 Rows]
    end
```

---

### Case Study 1: Working-Age Adult Cohort Filtering for Minimum Wage Analysis
- **Dataset**: `nigeria_economic_data.csv` (10,000 records)
- **Real-World Scenario**: The government is establishing a new national minimum wage policy and requires income statistics restricted exclusively to the legally eligible working-age adult population (ages 18 to 65), eliminating non-working minors and retirees from skewing calculations.
- **Filtering Logic**:
  ```python
  adult_only_eco_data = economic_data[(economic_data['Age'] >= 18) & (economic_data['Age'] <= 65)]
  ```
- **Quantitative Finding**:
  - Original Dataset: **10,000 records**
  - Filtered Working-Age Dataset: **4,923 records** (49.23% of total population)
  - Successfully filtered out students, child dependents, and out-of-labor-force cohorts ($0 \le \text{Age} < 18$ and $\text{Age} > 65$).

---

### Case Study 2: Targeted Healthcare Resource Allocation for Vulnerable Mothers
- **Dataset**: `nigeria_nursing_mothers_healthcare.csv` (10,000 records)
- **Real-World Scenario**: A non-profit healthcare NGO operating under strict budget constraints needs to deploy mobile medical teams and pediatric doctors directly to the most vulnerable demographics: mothers in rural communities belonging to the lowest socioeconomic quintile (`Poorest`).
- **Filtering Logic**:
  ```python
  targeted_mothers = health_data[(health_data['Residence'] == 'Rural') & (health_data['Wealth_Quintile'] == 'Poorest')]
  ```
- **Quantitative Finding**:
  - Original Dataset: **10,000 records**
  - High-Priority Vulnerability Cohort: **1,866 mothers** (18.66% of total sample)
  - Enables targeted intervention for skilled birth attendance, facility deliveries, and infant immunization outreach.

---

### Case Study 3: Cross-Feature Anomaly Auditing (Suspicious Data Detection)
- **Dataset**: `nigeria_unemployment_missing_data.csv` (5,000 records)
- **Real-World Scenario**: Data hygiene audit to uncover logical contradictions or potential survey entry errors before training predictive econometric models. Specifically investigating impossible or highly anomalous demographic combinations: respondents under 18 claiming to hold university/tertiary degrees.
- **Filtering Logic**:
  ```python
  suspicious_data = unemployment_data[(unemployment_data['Age'] < 18) & (unemployment_data['Education_Level'] == 'Tertiary')]
  ```
- **Quantitative Finding**:
  - Flagged **52 anomalous records** for manual verification or exclusion.
  - Highlights the necessity of multi-feature cross-validation during the preliminary wrangling phase.

---

### Activity 2 Results Matrix

| Case Study | Dataset Used | Applied Filter Condition | Initial Size | Filtered Size | Analytical Impact |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **1. Minimum Wage Policy** | `nigeria_economic_data.csv` | `(Age >= 18) & (Age <= 65)` | 10,000 | **4,923** | Isolates active labor force; removes minor/retiree distortion |
| **2. Maternal Healthcare NGO** | `nigeria_nursing_mothers_healthcare.csv` | `(Residence == 'Rural') & (Wealth_Quintile == 'Poorest')` | 10,000 | **1,866** | Directs medical personnel to high-vulnerability rural mothers |
| **3. Survey Integrity Audit** | `nigeria_unemployment_missing_data.csv` | `(Age < 18) & (Education_Level == 'Tertiary')` | 5,000 | **52** | Flags data inconsistencies for review before modeling |

---

## 📈 Activity 3 (Day 3) — Data Aggregation, Multi-Dimensional Grouping & Statistical Reporting

> **Notebook**: [`day-3-data-aggregation.ipynb`](./day-3-data-aggregation.ipynb)  
> **Core Concepts**: `.groupby()`, Multi-Level Grouping ("Buckets within Buckets"), Multi-Metric `.agg()`, Frequency Sizing, Strategic Reporting

### Workflow Overview

```mermaid
flowchart TD
    subgraph A1[Scenario 1: Economic Returns to Education]
        D1[Nigerian Economic Data] --> G1["groupby('Education_Level')['Monthly_Income_NGN'].mean()"]
        G1 --> R1["Tertiary: ₦348.6k | Secondary: ₦122.2k | Primary: ₦38.7k"]
    end
    subgraph A2[Scenario 2: Healthcare Geographic Sizing]
        D2[Nursing Mothers Data] --> F2["Filter: Wealth == 'Poorest'"]
        F2 --> G2["groupby('Geopolitical_Zone').size()"]
        G2 --> R2["North West Lead: 601 Mothers (26.6%)"]
    end
    subgraph A3[Scenario 3 & 4: Labor Market Dynamics & Gender Parity]
        D3[Unemployment Survey] --> G3["groupby(['Employment_Status', 'Gender'])['Years_Of_Experience'].mean()"]
        G3 --> R3["Gender Parity Confirmed across all Employment Tiers"]
    end
    subgraph A4[Scenario 5: Multi-Metric Report Card]
        D4[Economic Dataset] --> G4["groupby('Education_Level')['Monthly_Income_NGN'].agg(['min', 'max', 'mean', 'count'])"]
        G4 --> R4["Full Statistical Distribution & Wage Ceilings"]
    end
```

---

### Scenario 1: Economic Returns to Higher Education ("Does Education Pay Off?")
- **Dataset**: `nigeria_economic_data.csv` (10,000 records)
- **Analytical Objective**: Determine whether higher educational attainment translates to statistically significant income premiums in the Nigerian economy.
- **Code Implementation**:
  ```python
  economy_data.groupby('Education_Level')['Monthly_Income_NGN'].mean().round(2)
  ```
- **Quantitative Findings**:
  - **Primary Education**: **₦38,722.55 / month**
  - **Secondary Education**: **₦122,211.60 / month** (3.15x higher than Primary)
  - **Tertiary Education**: **₦348,555.70 / month** (9.00x higher than Primary, 2.85x higher than Secondary)
  - **Takeaway**: Demonstrates steep exponential income scaling linked to higher education completion.

---

### Scenario 2: Resource Allocation & Geographic Prioritization for Nursing Mothers
- **Dataset**: `nigeria_nursing_mothers_healthcare.csv` (10,000 records)
- **Analytical Objective**: Identify the Nigerian geopolitical zone with the greatest concentration of vulnerable mothers in the lowest economic quintile (`Poorest`) to optimize NGO medical supply chains.
- **Code Implementation**:
  ```python
  poorest_mothers = nursing_data[nursing_data['Wealth_Quintile'] == 'Poorest']
  mothers_count_region = poorest_mothers.groupby('Geopolitical_Zone').size()
  ```
- **Quantitative Findings**:
  - **North West**: **601 poorest mothers** (26.56% of total vulnerable cohort — highest priority)
  - **South East**: **374 poorest mothers**
  - **South West**: **363 poorest mothers**
  - **North Central**: **332 poorest mothers**
  - **North East**: **328 poorest mothers**
  - **South South**: **324 poorest mothers**
  - **Takeaway**: Directly informs non-profit resource allocation, establishing that medical outreach logistics must center on the North West zone.

---

### Scenario 3: Labor Market Experience Dynamics across Employment States
- **Dataset**: `nigeria_unemployment_missing_data.csv` (5,000 records)
- **Analytical Objective**: Investigate the relationship between professional experience and employment states (Employed, Underemployed, Unemployed).
- **Code Implementation**:
  ```python
  exp_status = unemployment_data.groupby('Employment_Status')['Years_Of_Experience'].mean().round(2)
  ```
- **Quantitative Findings**:
  - **Employed**: **21.72 years** average experience
  - **Underemployed**: **22.38 years** average experience
  - **Unemployed**: **20.83 years** average experience
  - **Takeaway**: Rebuts the assumption that underemployment and unemployment stem purely from lack of experience. Underemployed individuals possess slightly higher average career longevity.

---

### Scenario 4: Hierarchical Multi-Level Grouping ("Buckets within Buckets" / Gender Equity)
- **Dataset**: `nigeria_unemployment_missing_data.csv` (5,000 records)
- **Analytical Objective**: Disaggregate employment tiers by gender to evaluate if experience distributions differ between men and women in the labor force.
- **Code Implementation**:
  ```python
  exp_status_gender = unemployment_data.groupby(['Employment_Status', 'Gender'])['Years_Of_Experience'].mean().round(2)
  ```
- **Quantitative Findings**:
  - **Employed**: Female (21.47 yrs) vs. Male (21.96 yrs)
  - **Underemployed**: Female (22.39 yrs) vs. Male (22.37 yrs)
  - **Unemployed**: Female (20.96 yrs) vs. Male (20.70 yrs)
  - **Takeaway**: Validates consistent experience parity across genders within each employment tier.

---

### Scenario 5: Multi-Metric Statistical Profiling ("The Full Report Card")
- **Dataset**: `nigeria_economic_data.csv` (10,000 records)
- **Analytical Objective**: Move beyond single-metric averages to generate a multi-dimensional statistical profile capturing min, max, mean, and sample size across education tiers.
- **Code Implementation**:
  ```python
  full_income_report = economy_data.groupby('Education_Level')['Monthly_Income_NGN'].agg(['min', 'max', 'mean', 'count']).round(2)
  ```

#### The Full Income Report Card Matrix

| Education Level | Sample Size (`count`) | Minimum Income (`min`) | Maximum Income (`max`) | Mean Income (`mean`) | Economic Insight |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Primary** | 2,953 | ₦0.00 | ₦764,691.33 | **₦38,722.55** | High baseline density; lowest earnings floor |
| **Secondary** | 2,283 | ₦0.00 | ₦838,454.45 | **₦122,211.60** | 3.15x average income lift over Primary |
| **Tertiary** | 768 | ₦0.00 | ₦2,341,233.81 | **₦348,555.70** | Earnings ceiling exceeds ₦2.34M (2.8x higher max) |

---

## 🛠️ Activity 4 (Day 4) — Deep-Dive Missing Data Architecture, Sentinel Evolution & Advanced Imputation

> **Notebook**: [`day-4-data-wrangling-and-missing-data.ipynb`](./day-4-data-wrangling-and-missing-data.ipynb)  
> **Core Concepts**: Masking vs. Sentinel Representation, IEEE 754 `NaN` Floating-Point Coercion, The NaN "Virus Effect", Modern Nullable `Int32`/`boolean` (`pd.NA`), Geography Pruning, Skewness-Driven Imputation (Mean vs. Median), Group-Based Conditional Imputation

### Workflow Overview

```mermaid
flowchart TD
    A[Raw Unemployment Dataset: 5,000 Records] --> B[Full Column Missingness Audit]
    B --> C{Strategic Treatment by Feature Type}
    C -->|1. Non-Imputable Geography| D["Pruning: dropna(subset=['Region', 'Location'])"]
    D --> E[Clean Spatial Baseline: 4,750 Rows - 250 Pruned]
    C -->|2. Categorical Variable| F["Class Preservation: fillna('Unspecified')"]
    F --> G[Education_Level Retained with Full Variance]
    C -->|3. Skewed Continuous Variable| H[Distribution Check: Mean ₦58.1k vs. Median ₦42.9k]
    H --> I[Median Imputation Selected to Resist Outlier Distortion]
    C -->|4. Group-Dependent Metric| J["Subgroup Mean Fill: groupby('Employment_Status')['Experience']"]
    J --> K[Employed: 21.72 yrs | Underemployed: 22.38 yrs | Unemployed: 20.83 yrs]
    E --> L[Production-Ready Imputed Dataset]
    G --> L
    I --> L
    K --> L
```

---

### Theoretical Architecture: The Evolution of Missingness in Python & Pandas

#### 1. Masking vs. Sentinel Placeholders
- **The Masking Approach**: Allocating an auxiliary boolean array alongside the dataset to flag valid vs. missing cells (high memory footprint, robust type preservation).
- **The Sentinel Approach**: Inserting a reserved placeholder directly inside data structures (e.g., `-9999`, `None`, `np.nan`).

#### 2. The Floating-Point Coercion & "Virus Effect" of `NaN`
In standard NumPy and legacy Pandas, `np.nan` is an IEEE 754 floating-point value. This introduced two major engineering challenges:
1. **Type Coercion**: Adding a single missing value to an integer column automatically upcasted the entire column from `int64` to `float64`.
2. **The "Virus Effect"**: Any standard mathematical operation involving `np.nan` evaluates strictly to `nan`:
   $$\sum (1, \text{nan}, 3, 4) \rightarrow \text{nan} \quad \text{versus} \quad \text{np.nansum}() \rightarrow 8.0$$

#### 3. Modern Pandas Nullable Data Types (`pd.NA`)
Pandas introduced first-class nullable types (`Int32`, `Int64`, `boolean`, `string`) utilizing a dedicated missingness scalar (`<NA>` / `pd.NA`), enabling true integer and boolean storage without float coercion:
```python
nullable_series = pd.Series([1, np.nan, 2, None, pd.NA], dtype='Int32')
# Output: [1, <NA>, 2, <NA>, <NA>], dtype: Int32
```

---

### Mental Models & Root Cause Taxonomy in Machine Learning

| Missingness Mechanism | Root Cause & Context | Analytical Risk | Prescribed Strategy |
| :--- | :--- | :--- | :--- |
| **Missing by Accident (MCAR)** | Random sensor failure, transmission packet loss | Minimal systematic bias; sample size reduction | Statistical imputation (Mean/Median/KNN) |
| **Missing by Logic / Nature (MAR)** | Survey questions that conditionally do not apply to respondent | Systematic bias if dropped | Conditional subgroup imputation or structural zeroing |
| **Missing on Purpose (MNAR)** | Sensitive disclosures (income, wealth, evasiveness) | Heavy truncation bias | Explicit class preservation (`'Unspecified'`) |

---

### Step-by-Step Hands-On Imputation Framework

#### Step 1: Column-by-Column Missingness Audit
- Total initial rows: **5,000**
- Missing counts: `Education_Level` (1,127), `Years_Of_Experience` (500), `Monthly_Income_NGN` (408), `Region` (250).

#### Step 2: Critical Feature Pruning (Row Dropping)
- **Action**: Pruned observations where location coordinates were missing (`dropna(subset=['Region', 'Location'])`).
- **Outcome**: Preserved **4,750 high-integrity observations** (exactly 250 incomplete rows pruned) to prevent geospatial hallucinations.

#### Step 3: Distribution Skewness & Central Tendency Evaluation
- **Analysis**: Calculated central tendency metrics for `Monthly_Income_NGN`:
  - **Median Income**: **₦42,908.88**
  - **Mean Income**: **₦58,114.54** (35.4% higher than median)
- **Visual Diagnostics**: Fitted a histogram with Kernel Density Estimation (KDE), revealing severe right-skewness driven by high-earning outliers.
- **Methodological Choice**: Median imputation is strictly preferred over mean imputation for right-skewed variables to prevent artificial upward inflation of income baselines.

#### Step 4: Explicit Categorical Class Preservation
- Preserved missing `Education_Level` records by mapping them to `'Unspecified'` (`.fillna('Unspecified')`).

#### Step 5: Group-Based Conditional Imputation
- Applied conditional subgroup averages based on `Employment_Status`:
  - **Employed**: **21.72 years**
  - **Underemployed**: **22.38 years**
  - **Unemployed**: **20.83 years**

---

### Activity 4 Results Matrix

| Pipeline Stage | Applied Technique | Target Variable | Dataset Size Before $\rightarrow$ After | Methodological Justification |
| :--- | :--- | :--- | :--- | :--- |
| **1. Geography Pruning** | `dropna(subset=['Region', 'Location'])` | `Region`, `Location` | 5,000 $\rightarrow$ **4,750** rows | Eliminates geospatial fabrication |
| **2. Skewness Assessment** | Median Imputation (₦42.9k) | `Monthly_Income_NGN` | 408 missing $\rightarrow$ **0 missing** | Resists right-skewed outlier inflation |
| **3. Categorical Patch** | `.fillna('Unspecified')` | `Education_Level` | 1,127 missing $\rightarrow$ **0 missing** | Prevents synthetic educational histories |
| **4. Group Imputation** | `.groupby('Employment_Status').mean()` | `Years_Of_Experience` | 500 missing $\rightarrow$ **0 missing** | Preserves intra-cohort career variance |

---

## 🔍 Activity 5 (Day 5) — Exploratory Data Analysis for Outlier Detection, Spatial Engineering & Domain-Driven Filtration

> **Notebook**: [`day-5-outlier-outlier-detection.ipynb`](./day-5-outlier-outlier-detection.ipynb)  
> **Core Concepts**: Multi-Stage DataFrame Pipelines (1–5), Continuous Range Parsing, Feature Engineering (`bhk`, `price_per_sqft`), Domain-Driven Architectural Thresholding, Outlier Pruning

### Workflow Overview

```mermaid
flowchart TD
    A[Raw Housing Dataset: 13,320 Records] --> P1[Pipeline 1: Dimension Pruning]
    P1 --> P2[Pipeline 2: Null Removal & BHK Extraction]
    P2 --> P3[Pipeline 3: String Range Parsing into Float]
    P3 --> P4[Pipeline 4: Price per Sqft Engineering]
    P4 --> P5["Pipeline 5: Domain Outlier Detection (total_sqft / bhk < 300)"]
    P5 --> B[Spotting the Black Sheep: 744 Physical Impossibilities Pruned]
    B --> C[Clean Production Dataset: 12,502 Valid Properties]
```

---

### Theoretical Foundation: Spotting the "Black Sheep" (Good vs. Bad Outliers)
In exploratory data analysis and predictive modeling, outliers represent observations that deviate substantially from the central data distribution:
- **Bad Outliers (Errors & Impossibilities)**: Typos, misplaced decimals, contradictory units (e.g., an 8-bedroom house fitting into 600 total square feet = 75 sqft/room). If left untreated, linear models and neural networks will fit spurious gradients to these physical anomalies.
- **Good Outliers (Genuine Rare Events)**: Legitimate luxury estates (e.g., a 10,000 sqft mansion priced at ₦500M). These should be retained or capped rather than indiscriminately discarded.

---

### The 5-Stage DataFrame Pipeline Architecture

```mermaid
flowchart LR
    D0["Raw Data (13,320)"] --> D1["Pipeline 1: Drop Noisy Cols (13,320)"]
    D1 --> D2["Pipeline 2: Drop NA & Add bhk (13,246)"]
    D2 --> D3["Pipeline 3: Parse total_sqft Ranges (13,246)"]
    D3 --> D4["Pipeline 4: Add price_per_sqft (13,246)"]
    D4 --> D5["Pipeline 5: Prune Outliers < 300 sqft/bhk (12,502)"]
```

#### Pipeline 1 (`housing_data_one`): Feature Selection & Dimension Pruning
- **Action**: Evaluated property pricing relevance with real estate domain experts and pruned 4 non-predictive/noisy attributes (`area_type`, `availability`, `society`, `balcony`).
- **Retained Features**: `location`, `size`, `total_sqft`, `bath`, `price`.

#### Pipeline 2 (`housing_data_two`): Null Removal & Room Feature Engineering (`bhk`)
- **Missing Value Handling**: Dropped sparse rows containing null values (`location`: 1, `size`: 16, `bath`: 73), yielding **13,246 clean rows**.
- **Feature Extraction**: Extracted integer bedroom count (`bhk`) from heterogeneous string categories (`'2 BHK'`, `'4 Bedroom'`, `'1 RK'`):
  ```python
  housing_data_two['bhk'] = housing_data_two['size'].apply(lambda x: int(x.split(' ')[0]))
  ```

#### Pipeline 3 (`housing_data_three`): Continuous Range Parsing into Floats
- **Challenge**: The `total_sqft` column contained mixed string representations including dashed ranges (`'2100 - 2850'`), metric units (`'34.46Sq. Meter'`), and acreage (`'5.31Acres'`).
- **Parsing Engine**: Built a conversion function averaging range intervals and casting plain numerical strings to `float64`:
  ```python
  def convert_sqft_to_num(x):
      tokens = x.split('-')
      if len(tokens) == 2:
          return (float(tokens[0]) + float(tokens[1])) / 2
      try:
          return float(x)
      except:
          return None

  housing_data_three['total_sqft'] = housing_data_three['total_sqft'].apply(convert_sqft_to_num)
  ```

#### Pipeline 4 (`housing_data_four`): Standardized Unit Pricing (`price_per_sqft`)
- **Metric Engineering**: Calculated standardized price per square foot across all locations to evaluate pricing consistency:
  ```python
  housing_data_four['price_per_sqft(100)'] = housing_data_four['price'] * 100 / housing_data_four['total_sqft']
  ```

#### Pipeline 5 (`housing_data_five`): Domain-Driven Architectural Outlier Filtration
- **Domain Knowledge Rule**: In standard civil engineering and architecture, a standard bedroom requires a baseline minimum of **$\approx 300\text{ sqft}$** of total built area (including hallway, bathroom, and kitchen distribution).
- **Anomaly Detection Logic**: Flagged and removed properties violating this physical threshold:
  ```python
  # Filter out properties where average square footage per bedroom is under 300 sqft
  housing_data_five = housing_data_five[~(housing_data_five['total_sqft'] / housing_data_five['bhk'] < 300)]
  ```
- **Quantitative Result**:
  - Properties before filtration: **13,246**
  - Impossible anomalous properties identified: **744 records** (e.g., 6 bedrooms in 1,020 sqft, 8 bedrooms in 600 sqft)
  - Final Clean Production Dataset: **12,502 high-integrity records**

---

### Activity 5 Results Matrix

| Pipeline Stage | Operation / Transformation | Feature Affected | Observations | Analytical Rationale |
| :--- | :--- | :--- | :--- | :--- |
| **Pipeline 1** | Feature Pruning | `area_type`, `society`, etc. | 13,320 rows | Eliminates high-sparsity & noisy features |
| **Pipeline 2** | `bhk` Feature Engineering | `size` $\rightarrow$ `bhk` (int) | 13,246 rows | Extracts numerical room capacity |
| **Pipeline 3** | String Range Conversion | `total_sqft` (float) | 13,246 rows | Averages range intervals (e.g., 2100–2850 $\rightarrow$ 2475) |
| **Pipeline 4** | Unit Metric Engineering | `price_per_sqft` | 13,246 rows | Normalizes price across property sizes |
| **Pipeline 5** | Domain Outlier Pruning | $\frac{\text{total\_sqft}}{\text{bhk}} \ge 300$ | **12,502 rows** | **Removes 744 physical/architectural anomalies** |

---

## 🎯 Activity 6 (Day 6) — Advanced Statistical Outlier Engineering & Algorithmic Anomaly Filtration

> **Notebook**: [`day-6-outlier-outlier-detection.ipynb`](./day-6-outlier-outlier-detection.ipynb)  
> **Core Concepts**: Empirical Rule & Standard Deviation Filtering ($\mu \pm 1\sigma$), Location-Grouped Normalization, Visual Scatter Diagnostics (`plot_scatter_chart`), Domain-Driven Bedroom Price Inversions, Algorithmic Benchmark Lookup Tables (`remove_bhk_outliers`), Quantitative Dataset Pruning

### Workflow Overview

```mermaid
flowchart TD
    D5["Clean Pipeline 5 Dataset: 12,502 Records"] --> P6["Pipeline 6: Location-Grouped PPS Outlier Filter (remove_pps_outliers)"]
    P6 --> R6["Pruned 3,241 Outliers (|PPS - μ_loc| > σ_loc) → 9,261 Records"]
    R6 --> P7["Pipeline 7: Visual Scatter Diagnostic Engine (plot_scatter_chart)"]
    P7 --> V7["Identified Cross-BHK Inversions (2 BHK > 3 BHK in same locality)"]
    V7 --> P8["Pipeline 8: Algorithmic BHK Benchmark Engine (remove_bhk_outliers)"]
    P8 --> R8["Pruned 1,750 Bedroom-Inversion Records (n > 5 benchmark) → 7,511 Final Clean Records"]
```

---

### Theoretical Foundation: The Empirical Rule & Micro-Market Realities

#### 1. The Normal Distribution & The Empirical Rule ($\mu \pm 1\sigma$)
In continuous statistical distributions, the **Empirical Rule** dictates that for an approximately normally distributed feature:
- Approximately **68.27%** of observations lie within $1\sigma$ of the mean ($\mu \pm 1\sigma$).
- Approximately **95.45%** lie within $2\sigma$ ($\mu \pm 2\sigma$).
- Approximately **99.73%** lie within $3\sigma$ ($\mu \pm 3\sigma$).

When evaluating real estate metrics such as `price_per_sqft(100)`, extreme right-tail skewness (ultra-luxury penthouses) and left-tail data entry errors (mislabeled unit prices) will destabilize variance and bias gradient descent. Applying a localized $1\sigma$ bound filters out erratic boundaries while preserving the robust core of property transactions.

#### 2. The Micro-Market Paradox: Why Global Filtration Fails
A fundamental error in real estate data science is computing global dataset means. A price of ₦15,000/sqft may represent an extreme high-end luxury outlier in an outlying rural town, yet simultaneously represent an impossibly low error in a prime commercial center like Ikoyi or Victoria Island. 

Statistical outlier filtration **must be localized**:
$$\mu_{\text{loc}} - \sigma_{\text{loc}} < \text{price\_per\_sqft} \le \mu_{\text{loc}} + \sigma_{\text{loc}}$$

#### 3. Cross-BHK Price Inversion Anomaly
Under standard market equilibrium within the same apartment complex or neighborhood, an apartment with fewer bedrooms should not command a higher price than an apartment with more bedrooms for equivalent square footage. When a 2 BHK apartment costs significantly more per square foot than an adjacent 3 BHK apartment with comparable square footage, it indicates:
- Mislabeled feature tags (e.g., commercial properties coded as residential).
- Uncaptured structural damage or distressed sales.
- Data collection entry typos.

---

### The Extended Pipeline Architecture (Pipelines 6–8)

```mermaid
flowchart LR
    D5["Pipeline 5 (12,502)"] --> D6["Pipeline 6: Location-Grouped PPS (9,261)"]
    D6 --> D7["Pipeline 7: Visual Scatter Engine"]
    D7 --> D8["Pipeline 8: Algorithmic BHK Pruning (7,511)"]
```

#### Pipeline 6 (`housing_data_six`): Location-Grouped Price-per-Square-Foot Statistical Filtration
- **Engineering Logic**: Grouped the dataframe by `location`. Within each isolated neighborhood partition, calculated the mean ($\mu_{\text{loc}}$) and standard deviation ($\sigma_{\text{loc}}$) of `price_per_sqft(100)`. Extracted only properties falling within $[\mu_{\text{loc}} - \sigma_{\text{loc}}, \mu_{\text{loc}} + \sigma_{\text{loc}}]$.
- **Code Implementation**:
  ```python
  def remove_pps_outliers(df):
      df_outcome = pd.DataFrame()
      for key, subdf in df.groupby('location'):
          mean = np.mean(subdf['price_per_sqft(100)'])
          std = np.std(subdf['price_per_sqft(100)'])
          extract_df = subdf[(subdf['price_per_sqft(100)'] > (mean - std)) & 
                             (subdf['price_per_sqft(100)'] <= (mean + std))]
          df_outcome = pd.concat([df_outcome, extract_df], ignore_index=True)
      return df_outcome

  housing_data_six = remove_pps_outliers(housing_data_five)
  ```
- **Quantitative Result**:
  - Input: **12,502 records**
  - Pruned: **3,241 statistical price outliers**
  - Retained: **9,261 clean localized records**

#### Pipeline 7 (`housing_data_seven`): Visual Scatter Diagnostic Engine
- **Objective**: Develop a diagnostic visualization tool to cross-examine bedroom count against total square footage and price across targeted localities.
- **Code Implementation**:
  ```python
  def plot_scatter_chart(df, location):
      bhk2 = df[(df.location == location) & (df.bhk == 2)]
      bhk3 = df[(df.location == location) & (df.bhk == 3)]
      plt.figure(figsize=(15, 10))
      plt.scatter(bhk2.total_sqft, bhk2.price, color='blue', label='2 BHK', s=50)
      plt.scatter(bhk3.total_sqft, bhk3.price, color='green', marker='+', label='3 BHK', s=50)
      plt.xlabel("Total Square Feet Area")
      plt.ylabel("Price (Lakh / Local Unit)")
      plt.title(f"Property Price Distribution: {location}")
      plt.legend()
  ```
- **Empirical Diagnostics**: Evaluated across key micro-markets (e.g., `'Rajaji Nagar'`, `'Whitefield'`, `'Hebbal'`). The visual scatter plots definitively proved that at identical square footages (e.g., 1,700 sqft), certain 2 BHK properties were priced substantially higher than 3 BHK properties in the same neighborhood.

#### Pipeline 8 (`housing_data_eight`): Algorithmic Cross-Bedroom Outlier Filtration Engine
- **Algorithmic Mechanics**: Built a two-pass neighborhood benchmark engine using nested dictionary lookup tables:
  1. **Pass 1 (Benchmark Generation)**: Grouped by `location` and `bhk` to calculate benchmark dictionaries storing `mean`, `std`, and `count` for each bedroom tier.
  2. **Pass 2 (Rule Verification & Filtration)**: For each bedroom tier $bhk$, retrieved the benchmark statistics of the immediate lower tier ($bhk - 1$). If $bhk - 1$ statistics exist with a statistically reliable sample size ($n > 5$), flagged all properties in the higher tier where:
     $$\text{price\_per\_sqft}(100) < \mu_{bhk-1}$$
  3. **Batch Pruning**: Collected all offending indices into a NumPy array and performed an atomic `df.drop(exclude_indices, axis='index')`.
- **Code Implementation**:
  ```python
  def remove_bhk_outliers(df):
      exclude_indices = np.array([])
      for location, location_df in df.groupby('location'):
          bhk_stats = {}
          for bhk, bhk_df in location_df.groupby('bhk'):
              bhk_stats[bhk] = {
                  'mean': np.mean(bhk_df['price_per_sqft(100)']),
                  'std': np.std(bhk_df['price_per_sqft(100)']),
                  'count': bhk_df.shape[0]
              }

          for bhk, bhk_df in location_df.groupby('bhk'):
              stats = bhk_stats.get(bhk - 1)
              if stats and stats['count'] > 5:
                  exclude_indices = np.append(
                      exclude_indices,
                      bhk_df[bhk_df['price_per_sqft(100)'] < stats['mean']].index.values
                  )
      return df.drop(exclude_indices, axis='index')

  housing_data_eight = remove_bhk_outliers(housing_data_seven)
  ```
- **Quantitative Result**:
  - Input: **9,261 records**
  - Pruned: **1,750 bedroom-pricing inversion anomalies**
  - Final Clean Production Dataset: **7,511 pristine, modeling-ready records**

---

### Activity 6 Results Matrix

| Pipeline Stage | Operation / Transformation | Feature Scope | Input $\rightarrow$ Output Rows | Pruned Records | Methodological Rationale |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Pipeline 6** | Location-Grouped PPS Filter | `price_per_sqft(100)` | 12,502 $\rightarrow$ **9,261** | **3,241** | Eliminates local $\pm 1\sigma$ price anomalies per micro-market |
| **Pipeline 7** | Visual Scatter Diagnostics | `total_sqft`, `price`, `bhk` | 9,261 rows | Diagnostic | Uncovers cross-BHK price inversions across neighborhoods |
| **Pipeline 8** | Algorithmic Cross-BHK Pruning | `bhk`, `price_per_sqft(100)` | 9,261 $\rightarrow$ **7,511** | **1,750** | Enforces market pricing parity ($n > 5$ cohort threshold) |

---

### 📉 Complete Real Estate Pipeline Reduction Funnel (Pipelines 1–8)

| Pipeline Phase | Description / Transformation | Observations Remaining | Records Pruned | Cumulative Data Retention | Primary Quality Gain |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Raw Dataset** | Raw Ingestion from CSV | 13,320 | 0 | 100.0% | Initial baseline |
| **Pipeline 1** | Drop Non-Predictive Features | 13,320 | 0 | 100.0% | Reduced feature sparsity |
| **Pipeline 2** | Drop Nulls & Engineer `bhk` | 13,246 | 74 | 99.4% | Integer bedroom normalization |
| **Pipeline 3** | String Range Float Conversion | 13,246 | 0 | 99.4% | Continuous numeric consistency |
| **Pipeline 4** | Standardized Unit Price (`price_per_sqft`) | 13,246 | 0 | 99.4% | Scaled pricing benchmark |
| **Pipeline 5** | Architectural Rule ($\ge 300\text{ sqft/bhk}$) | 12,502 | 744 | 93.9% | Removed physical impossibilities |
| **Pipeline 6** | Localized $1\sigma$ Price-per-Sqft Filter | 9,261 | 3,241 | 69.5% | Removed micro-market price extremes |
| **Pipeline 7** | Multi-Location Visual Scatter Diagnostics | 9,261 | 0 | 69.5% | Verified cross-BHK pricing inversions |
| **Pipeline 8** | Algorithmic Cross-Bedroom Inversion Pruning | **7,511** | **1,750** | **56.4%** | **Final production-grade training dataset** |

---

## ⚖️ Activity 7 (Day 7) — Enterprise Data Governance & Inferential Statistics Foundations

> **Notebook**: [`day-7-data-governance-and-inferential-statistics.ipynb`](./day-7-data-governance-and-inferential-statistics.ipynb)  
> **Core Concepts**: Data Governance vs. Data Management, The Six Enterprise Pillars, Descriptive vs. Inferential Statistics, The Four Pillars of Inference, Population vs. Sample, Null vs. Alternative Hypothesis ($H_0$ vs. $H_a$), $p$-Value Significance Thresholds ($\alpha = 0.05$), Confidence Intervals, Two-Sample Independent $t$-Testing (`scipy.stats`)

### Workflow Overview

```mermaid
flowchart TD
    subgraph G[Part 1: Enterprise Data Governance Architecture]
        A["Organizational Data Assets"] --> P1["Accountability & Data Stewardship"]
        A --> P2["Transparency & Lineage Tracking"]
        A --> P3["Data Quality SLA (Accuracy & Completeness)"]
        A --> P4["Security & Role-Based Access Control (RBAC)"]
        A --> P5["Purpose Limitation & Explicit Consent"]
        A --> P6["Data Retention & Automated TTL Lifecycle"]
    end
    subgraph I[Part 2: Inferential Decision Engine]
        B["Target Population (All US Schools)"] --> S["Representative Sample Data"]
        S --> H{"Hypothesis Formulation"}
        H -->|"H0 (Null)"| H0["Public Rate = Private Rate (No Difference)"]
        H -->|"Ha (Alternative)"| Ha["Public Rate ≠ Private Rate (Significant Difference)"]
        H0 & Ha --> T["scipy.stats.ttest_ind(equal_var=False)"]
        T --> P["p-value vs. α = 0.05 Threshold"]
        P -->|"p < 0.05"| R1["Reject H0: Statistically Significant Disparity"]
        P -->|"p ≥ 0.05"| R2["Fail to Reject H0: Observed Variation is Chance Fluke"]
    end
```

---

### Part 1: Strategic Enterprise Data Governance

#### Data Governance vs. Data Management
A critical enterprise distinction separating operational engineering from organizational strategy:
- **Data Management (Execution)**: Writing Python scripts, running pipelines, wrangling schemas, handling missingness, engineering features, and querying databases.
- **Data Governance (Strategy & Control)**: The overarching institutional constitution. It defines **who** has authorization to access data, **what** downstream purposes are permitted, **how** quality benchmarks are enforced, and **when** records must be purged.

```mermaid
flowchart LR
    subgraph Ops[Data Management: Operational Mechanics]
        M1[Pipeline Scripts] --> M2[Data Wrangling]
        M2 --> M3[Model Training]
    end
    subgraph Gov[Data Governance: Strategic Guardrails]
        G1[Access Permissions] --> G2[Quality Standards]
        G2 --> G3[Retention Limits & Compliance]
    end
    Gov -.->|"Governs & Audits"| Ops
```

#### The Six Pillars of Enterprise Data Governance

| Pillar | Operational Definition | Engineering Implementation | Enterprise Risk Mitigated |
| :--- | :--- | :--- | :--- |
| **1. Accountability** | Explicit designation of data owners and certified data stewards. | Data ownership metadata tagged to tables and schemas. | Neglected schemas, orphan pipelines, blame shifting. |
| **2. Transparency** | Complete auditability of data origin, transformations, and lineage. | Automated data cataloging, commit-level provenance logs. | Regulatory non-compliance (GDPR/NDPR), unexplainable outputs. |
| **3. Data Quality** | Rigorous automated standards for accuracy, validity, and completeness. | Schema assertions, CI/CD validation tests, Great Expectations. | Garbage-in, garbage-out; faulty financial/policy decisions. |
| **4. Security** | Cryptographic controls and strict Role-Based Access Control (RBAC). | Encryption at rest/transit, principle of least privilege. | Unauthorized exfiltration, data leaks, credential theft. |
| **5. Purpose Limitation** | Data collected for one objective cannot be repurposed without consent. | Feature-level tagging, policy-enforced query firewalls. | Customer trust erosion, regulatory penalties. |
| **6. Data Retention** | Defined lifecycles and enforced Time-to-Live (TTL) expiration schedules. | Automated cron jobs purging stale logs and historical data. | Toxic liability storage, excessive storage costs. |

---

### Part 2: Inferential Statistics — The Mathematical Backbone of Machine Learning

#### Why Inferential Statistics Drives Machine Learning
Descriptive statistics merely summarizes observed sample data (the *sample in hand*). Inferential statistics uses probability theory to draw mathematically defensible conclusions about an unobserved wider population (the *pot of soup*):

1. **Feature Selection**: Separates genuinely predictive predictors from stochastic noise ($p < 0.05$ significance tests).
2. **A/B Testing & Causal Inference**: Validates whether conversion rate or revenue differences between treatment cohorts represent genuine product impact or random variance.
3. **Model Validation**: Establishes whether a 1.2% ROC-AUC improvement reflects architectural superiority or random seed fluctuation.

```mermaid
flowchart LR
    A["Descriptive Statistics"] -->|"Summarizes"| B["Observed Sample Data (What Happened)"]
    C["Inferential Statistics"] -->|"Generalizes & Tests"| D["Universal Population Parameters (Truth)"]
    D -->|"Powers"| E["Machine Learning Generalizability"]
```

#### The Four Pillars of Inference

1. **Population vs. Sample**:
   - **Population ($N$)**: The exhaustive universe of interest (e.g., all 130,000 schools in the United States).
   - **Sample ($n$)**: The observed subset subjected to empirical measurement.
2. **The Null Hypothesis ($H_0$) vs. Alternative Hypothesis ($H_a$)**:
   - **Null Hypothesis ($H_0$)**: Presumption of no difference or no effect ("Innocent until proven guilty beyond a reasonable doubt").
   - **Alternative Hypothesis ($H_a$)**: The assertion of a real, systemic disparity or effect.
3. **The $p$-Value Decision Threshold**:
   - The exact probability of observing sample statistics as extreme as those measured, assuming $H_0$ is true.
   - **Decision Rule**:
     $$\text{If } p \le 0.05 \implies \text{Reject } H_0 \quad (\text{Statistically Significant})$$
     $$\text{If } p > 0.05 \implies \text{Fail to Reject } H_0 \quad (\text{Insufficient Evidence})$$
4. **Confidence Intervals (CI)**:
   - A mathematical bracket (typically 95%) guaranteed to contain the true population parameter across repeated sampling.

---

### Hands-On Case Study: U.S. Educational System Graduation Rate Disparity

- **Dataset**: `us_education_system_dataset.csv`
- **Business Question**: Do private secondary schools achieve statistically significantly higher graduation rates than public secondary schools, or is the observed delta an artifact of random sampling variance?
- **Hypothesis Formulation**:
  $$H_0: \mu_{\text{public}} = \mu_{\text{private}} \quad (\text{Equal mean graduation rates})$$
  $$H_a: \mu_{\text{public}} \ne \mu_{\text{private}} \quad (\text{Statistically different graduation rates})$$
- **Code Implementation**:
  ```python
  import pandas as pd
  import numpy as np
  from scipy import stats

  # Load institutional education dataset
  us_edu_data = pd.read_csv('us_education_system_dataset.csv')

  # Isolate cohorts
  public_schools = us_edu_data[us_edu_data['School_Type'] == 'Public']['Graduation_Rate'].dropna()
  private_schools = us_edu_data[us_edu_data['School_Type'] == 'Private']['Graduation_Rate'].dropna()

  # Perform two-sample independent t-test (Welch's t-test for unequal variances)
  t_stat, p_value = stats.ttest_ind(public_schools, private_schools, equal_var=False)

  print(f"Public Mean: {public_schools.mean():.2f}% | Private Mean: {private_schools.mean():.2f}%")
  print(f"t-statistic: {t_stat:.4f} | p-value: {p_value:.4e}")

  # Decision logic
  alpha = 0.05
  if p_value < alpha:
      print("Conclusion: Reject H0. Significant disparity in institutional graduation rates.")
  else:
      print("Conclusion: Fail to Reject H0. No statistically significant difference detected.")
  ```

---

### Activity 7 Strategic Framework Matrix

| Dimension | Descriptive Domain | Inferential Domain | Enterprise Governance Domain |
| :--- | :--- | :--- | :--- |
| **Core Question** | "What does our sample data look like?" | "What does this tell us about the broader reality?" | "Are we ethically, legally, and reliably permitted to use this data?" |
| **Primary Metric** | Mean, Median, Mode, Variance, IQR | $t$-statistic, $z$-score, $p$-value, 95% CI | SLA uptime, Lineage accuracy, Retention TTL |
| **Analytical Scope** | Sample-confined | Universal / Population-wide | Organizational / Regulatory |
| **Failure Mode** | Miscalculation / Skewness oversight | Type I Error ($\alpha$), Type II Error ($\beta$) | Data breach, regulatory fine, ethical breach |

---

## 🧪 Activity 8 (Day 8) — Applied Inferential Statistics: A/B Testing & Independent Samples $t$-Testing

> **Notebook**: [`day-8-inferential-statistics.ipynb`](./day-8-inferential-statistics.ipynb)  
> **Core Concepts**: Independent vs. Paired $t$-Tests, Two-Sample Independent $t$-Test (`scipy.stats.ttest_ind`), Simulation-Driven A/B Testing, $p$-Value Misinterpretation Fallacies, Real-World Hypothesis Testing on Institutional Education Systems

### Workflow Overview

```mermaid
flowchart TD
    subgraph EXP1[Experiment 1: Simulated Marketing A/B Test]
        C1["Control Cohort (n=100, μ=$489.62)"] & T1["Treatment Cohort (n=100, μ=$552.23)"] --> D1["Delta: +$62.62 Spending Lift"]
        D1 --> S1["scipy.stats.ttest_ind()"]
        S1 --> R1["t = 4.7547 | p = 3.82e-6 << 0.05"]
        R1 --> DEC1["Reject H0: Campaign Generates Significant Positive Lift"]
    end
    subgraph EXP2[Experiment 2: US Education Institutional Disparity]
        ED["US Education System Dataset"] --> P_PUB["Public Schools (n=obs, Mean=84.40%)"]
        ED --> P_PVT["Private Non-Profit (n=obs, Mean=87.83%)"]
        P_PUB & P_PVT --> D2["Delta: +3.43% Graduation Advantage"]
        D2 --> S2["scipy.stats.ttest_ind(public_grads, private_grads)"]
        S2 --> R2["t = -12.0869 | p = 0.0000 << 0.05"]
        R2 --> DEC2["Reject H0: Statistically Significant Institutional Disparity"]
    end
```

---

### Theoretical Foundation: The Mechanics of Independent $t$-Testing

#### 1. Independent vs. Paired $t$-Tests
Choosing the correct statistical test is vital to avoid fatal methodological errors:
- **Independent Samples $t$-Test**: Compares the means of **two completely separate groups** where observations in one group have no relationship to observations in the other (e.g., Treatment vs. Control customers; Public vs. Private school students).
- **Paired Samples $t$-Test**: Compares the means of the **same subjects measured twice** under two different conditions (e.g., student test scores *before* vs. *after* a training curriculum).

#### 2. The Great $p$-Value Misinterpretation Fallacy
A rampant error in business analytics is misinterpreting the $p$-value:
- ❌ **Incorrect**: *"There is a 0.01% probability that the null hypothesis is true."*
- ✅ **Correct**: *"Assuming there was absolutely zero true difference between the two groups, the probability of observing a difference as large as (or larger than) our sample result purely due to random sampling chance is 0.01%."*

When $p < \alpha$ (standard $\alpha = 0.05$), the observed effect is exceptionally unlikely to be a stochastic fluke, justifying rejection of $H_0$.

---

### Experiment 1: Controlled Simulation Experiment (Marketing Campaign Lift)

To validate the sensitivity of the two-sample independent $t$-test under controlled conditions, a synthetic customer spending experiment was simulated with known parameters:
- **Control Group**: Customers who did not receive the campaign ($n = 100, \mu = 500, \sigma = 100$).
- **Treatment Group**: Customers exposed to the new promotional campaign ($n = 100, \mu = 550, \sigma = 100$).

```python
import numpy as np
from scipy.stats import ttest_ind

np.random.seed(42)
control = np.random.normal(loc=500, scale=100, size=100)
treatment = np.random.normal(loc=550, scale=100, size=100)

difference = treatment.mean() - control.mean()
t_stat, p_value = ttest_ind(treatment, control)

print(f"Control Mean: ${control.mean():.2f} | Treatment Mean: ${treatment.mean():.2f}")
print(f"Observed Difference: +${difference:.2f}")
print(f"t-statistic: {t_stat:.4f} | p-value: {p_value:.4e}")
```

#### Quantitative Findings:
- **Control Mean**: **$489.62**
- **Treatment Mean**: **$552.23**
- **Net Delta**: **+$62.62** lift in customer spend
- **Calculated $t$-statistic**: **4.7547**
- **Calculated $p$-value**: **$3.819 \times 10^{-6}$** ($p \ll 0.05$)
- **Business Conclusion**: Strong statistical significance. The likelihood that this $62.62 lift occurred by chance alone is less than 4 in 1,000,000. Reject $H_0$; roll out the campaign.

---

### Experiment 2: Real-World Institutional Case Study (US Education Graduation Rates)

- **Dataset**: `us_education_system_dataset.csv`
- **Analytical Objective**: Determine whether Private Non-Profit secondary schools achieve statistically superior graduation rates compared to traditional Public schools, or if the observed delta is within random sampling fluctuation.
- **Categorical Breakdown**: Inspected the `control` governance feature across institutions:
  `['Public', 'Private Religious', 'Private For-Profit', 'Public Charter', 'Private Non-Profit']`
- **Hypothesis Formulation**:
  $$H_0: \mu_{\text{public}} = \mu_{\text{private\_non\_profit}} \quad (\text{Equal mean graduation rates})$$
  $$H_a: \mu_{\text{public}} \ne \mu_{\text{private\_non\_profit}} \quad (\text{Statistically significant difference in rates})$$

```python
# Isolate specific target governance cohorts
public_grads = us_edu_data[us_edu_data['control'] == 'Public']['graduation_rate_pct'].dropna()
private_grads = us_edu_data[us_edu_data['control'] == 'Private Non-Profit']['graduation_rate_pct'].dropna()

# Execute two-sample independent t-test
t_stat, p_value = ttest_ind(public_grads, private_grads)

print(f"Public Mean Graduation Rate: {public_grads.mean():.2f}%")
print(f"Private Non-Profit Mean Graduation Rate: {private_grads.mean():.2f}%")
print(f"Calculated T-Statistic: {t_stat:.4f}")
print(f"Calculated p-value: {p_value:.4f}")

alpha = 0.05
if p_value < alpha:
    print("Result: Significant! We reject the Null Hypothesis. There is a real difference.")
else:
    print("Result: Not significant. We fail to reject the Null.")
```

#### Quantitative Findings:
- **Public Schools Mean**: **84.40%**
- **Private Non-Profit Schools Mean**: **87.83%**
- **Institutional Delta**: **+3.43%** higher graduation rate for Private Non-Profit schools
- **Calculated $t$-statistic**: **-12.0869**
- **Calculated $p$-value**: **0.0000** ($p < 0.0001 \ll 0.05$)
- **Empirical Takeaway**: The $t$-statistic of $-12.09$ represents an extreme deviation of over 12 standard errors from the null hypothesis center. We reject $H_0$ with near 100% statistical confidence, confirming that private non-profit institutions maintain a real, statistically verified advantage in secondary completion rates.

---

### Activity 8 Results Matrix

| Case Study / Domain | Sample Cohorts ($A$ vs. $B$) | Sample Sizes ($n_A, n_B$) | Observed Means ($\bar{x}_A, \bar{x}_B$) | Effect Delta ($\Delta$) | $t$-statistic | $p$-value | Decision at $\alpha=0.05$ |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **Marketing Campaign A/B Test** | Control vs. Treatment | 100 vs. 100 | \$489.62 vs. \$552.23 | **+\$62.62** | **4.7547** | **$3.82 \times 10^{-6}$** | **Reject $H_0$** (Significant Lift) |
| **US Education System Disparity** | Public vs. Private Non-Profit | Multi-District | 84.40% vs. 87.83% | **+3.43%** | **-12.0869** | **0.0000** | **Reject $H_0$** (Significant Advantage) |

---

## 🧩 End-to-End Pipeline Synthesis (Days 1–9)

| Stage | Activity | Key Challenge Solved | Primary Tool / Technique | Core Analytical Deliverable |
| :--- | :--- | :--- | :--- | :--- |
| **Phase 1** | **Baseline Hygiene & Diagnostics** | Initial missingness quantification & listwise deletion cost | `.isnull().sum()`, `.dropna()` | Quantified 39.6% row loss risk in complete case deletion |
| **Phase 2** | **Conditional Slicing & Auditing** | Isolating demographic cohorts & detecting contradictions | Compound boolean masking (`&`, `\|`) | Sliced 4,923 working-age adults; 1,866 priority mothers; 52 audit flags |
| **Phase 3** | **Aggregation & Reporting** | Condensing granular rows into macro policy insights | `.groupby()`, `.agg()`, hierarchical grouping | Multi-metric ROI report cards & geographic allocation plan |
| **Phase 4** | **Architectural Imputation** | Handling skewness, sentinel evolution & subgroup variance | Nullable `Int32`, median patching, group-based fill | Production-grade clean dataframe with zero statistical drift |
| **Phase 5** | **Domain-Driven Outlier Engineering** | Detecting physical impossibilities & non-standard ranges | Range parsers, `price_per_sqft`, domain thresholding | Removed 744 spatial anomalies; produced 12,502 clean records |
| **Phase 6** | **Statistical & Algorithmic Outlier Engineering** | Trimming micro-market price variance & cross-tier pricing inversions | Localized $\pm 1\sigma$ filtration (`remove_pps_outliers`), scatter diagnostics, algorithmic benchmark lookup tables (`remove_bhk_outliers`) | Clean production dataset refined to 7,511 high-integrity records (43.6% total noise pruned) |
| **Phase 7** | **Enterprise Data Governance** | Institutional compliance & ethical lifecycle management | 6 Governance Pillars, Accountability, Data Lineage, Retention TTL | Enterprise data governance policy matrix & risk mitigation blueprint |
| **Phase 8** | **Applied Inferential Statistics & A/B Testing** | Proving business and policy differences over stochastic flukes | Two-sample independent $t$-tests (`scipy.stats.ttest_ind`), simulation benchmarks | Rigorous empirical hypothesis testing engine proving marketing & educational deltas |
| **Phase 9** | **Advanced Inferential Statistics: Multi-Group & Categorical Testing** | Comparing variance across ≥3 groups, testing categorical independence & validating linear correlations | One-Way ANOVA (`stats.f_oneway`), Chi-Square Test of Independence (`stats.chi2_contingency`), Pearson Correlation Significance (`stats.pearsonr`) | Confirmed significant staffing ratio variance across locales, structural Title I / STEM association, and positive expenditure–graduation correlation |

---

## 🚀 Getting Started & Execution

### Prerequisites
- Python 3.8+
- Jupyter Notebook / JupyterLab or VS Code Jupyter Extension
- Required packages: `pandas`, `numpy`, `scipy`, `matplotlib`, `seaborn`

### Installation & Environment Setup
```bash
# 1. Clone the repository
git clone https://github.com/D-James001/Data-Science-Development.git
cd "Data Science Development"

# 2. Create and activate a virtual environment
python -m venv venv

# On Windows:
.\venv\Scripts\activate
# On Linux/macOS:
source venv/bin/activate

# 3. Install dependencies
pip install pandas numpy scipy matplotlib seaborn jupyter
```

### Running the Notebooks
Explore each activity independently:

```bash
# Run Day 1: Missing Data Diagnostics & Baseline Imputation
jupyter notebook day-1-data-wrangling.ipynb

# Run Day 2: Advanced Conditional Filtering & Anomaly Detection
jupyter notebook "day-2-data-wrangling & filtering.ipynb"

# Run Day 3: Multi-Dimensional Grouping & Statistical Aggregation
jupyter notebook day-3-data-aggregation.ipynb

# Run Day 4: Missing Data Architecture, Sentinel Theory & Advanced Imputation
jupyter notebook day-4-data-wrangling-and-missing-data.ipynb

# Run Day 5: Outlier Detection, Spatial Engineering & Domain-Driven Filtration
jupyter notebook day-5-outlier-outlier-detection.ipynb

# Run Day 6: Advanced Statistical Outlier Engineering & Algorithmic Filtration
jupyter notebook day-6-outlier-outlier-detection.ipynb

# Run Day 7: Enterprise Data Governance Frameworks & Conceptual Foundations
jupyter notebook day-7-data-governance-and-inferential-statistics.ipynb

# Run Day 8: Applied Inferential Statistics, A/B Testing & Hypothesis Testing
jupyter notebook day-8-inferential-statistics.ipynb

# Run Day 9: Advanced Inferential Statistics (ANOVA, Chi-Square, Pearson r)
jupyter notebook day-9-inferential-statistic-part-2.ipynb
```

---

## 🔮 Portfolio Roadmap & Upcoming Activities

- [x] **Day 1**: Missing Data Diagnostics, Complete Case Deletion vs. Statistical & Categorical Imputation.
- [x] **Day 2**: Compound Boolean Filtering, Policy Slicing, Vulnerability Subsetting, and Anomaly Auditing.
- [x] **Day 3**: Multi-Dimensional Aggregation, Hierarchical Grouping, and Multi-Metric Report Cards.
- [x] **Day 4**: Missing Data Architecture, Sentinel Evolution, Skewness Imputation, and Subgroup Mean Patching.
- [x] **Day 5**: Exploratory Data Analysis for Outliers, Multi-Stage Pipeline Architecture & Domain-Driven Filtration ($\ge 300\text{ sqft/bhk}$).
- [x] **Day 6**: Advanced Statistical Outlier Engineering, $\mu \pm 1\sigma$ Location Filtering, Visual Scatter Diagnostics & Algorithmic Cross-BHK Anomaly Removal.
- [x] **Day 7**: Enterprise Data Governance Frameworks (6 Pillars: Accountability, Transparency, Quality, Security, Purpose, Retention).
- [x] **Day 8**: Applied Inferential Statistics, Two-Sample Independent $t$-Testing, A/B Testing Simulation & Institutional Hypothesis Testing.
- [x] **Day 9**: Advanced Inferential Statistics — One-Way ANOVA, Chi-Square Test of Independence & Pearson Correlation Significance Testing.
- [ ] **Day 10**: Feature Transformation, Numerical Scaling & Categorical Encoding (One-Hot, Ordinal).
- [ ] **Day 11**: Exploratory Data Analysis (EDA) & Multivariate Visualizations.
- [ ] **Day 12**: Predictive Machine Learning Modeling & Deployment.

---

## 📄 License
This project is open source and available under the [MIT License](LICENSE).


