# 📈 Order Trend Analysis | Electrical Equipment Industry

### Analyze and monitor pattern in order trends for a manufacturing company specializing in wires, switches, and button using Tableau.

## 📌 Table of Contents
- <a href="#overview">Overview</a>
- <a href="#analysis-preview">Analysis Preview</a>
- <a href="#dataset">Dataset</a>
- <a href="#tools-technologies">Tools & Technologies</a>
- <a href="#project-structure">Project Structure</a>
- <a href="#exploratory-data-analysis-eda">Exploratory Data Analysis (EDA)</a>
- <a href="#business-questions--key-findings">Business Questions & Key Findings</a>
- <a href="#dashboard">Dashboard</a>
- <a href="#author-contact">Author & Contact</a>

<h2><a class="anchor" id="overview"></a>📝 Overview</h2>

This project aims to analyze and monitor order data to identify trends and periods of decline. The insights will enable data-driven strategies to reduce risks of order downturns and align performance with company benchmarks.
- Conduct trend analysis of orders from Jan 2023 – Dec 2024
- Quantify performance and growth rates
- Compare performance against company-defined thresholds

<h2><a class="anchor" id="analysis-preview"></a>🔗 Analysis Preview</h2>

<h2><a class="anchor" id="credits"></a>🪪 Credits</h2>

NaN

<h2><a class="anchor" id="dataset"></a>📊 Dataset</h2>

`.xlsx` files located in `/data/` folder

| Feature   | Description                                | Data Type |
|-----------|--------------------------------------------|-----------|
| Months    | Order timeline captured by month | Date/Time |
| Category  | Product classification grouping | Categorical |
| Orders    | Total order volume placed for the given category month | Integer   |



<h2><a class="anchor" id="tools-technologies"></a>🛠️ Tools & Technologies</h2>

| Task                 | Tools Used                          |
|----------------------|-------------------------------------|
| Data Analysis        | Tableau                             |
| Data Visualization   | Tableau                             |
| Presentation         | Tableau Story                       |
| On-screen marking    | Epic Pen                            |

<h2><a class="anchor" id="project-structure"></a>📁 Project Structure</h2>

```
03_Trend_Analysis/
│
├── data/
│
├── workbooks/             # Tableau workbook
│
├── visuals/               # Mockups and visualization image
│
├── README.md              # High-level project overview
├── .gitignore             # Ignore data, models, logs if using Git

```

<h2><a class="anchor" id="exploratory-data-analysis-eda"></a>🔍 Exploratory Data Analysis (EDA)</h2>

For trend analysis we need Orders (Rows) over Months (Columns):

<IMAGE>

Here, we are going to explore the visual and identify patterns which provide key business insights.

### 1. Trends:
- Orders show consistent growth throughout 2023. 
- However, a sharp decline is observed since the beginning of 2024.
- Related Questions:
  - What were max and min sales?
  - What was month of max/min sales?
  - What is the overall % drop?
  - What is the reason for downturn?

---

### 2. Recovery phase:
- Recovery is observed from lowest sales point towards Dec 2024.
- Recovery slope is potentially less steeper than decline.
- Related Questions
  - What is the average % MoM change from lowest sales?
  - What is the reason for slow upturn?

---

### 3. Benchmark:
- Have the orders made complete recovery or partial recovery w.r.t to company benchmark?
- How far we are from complete recovery?

<IMAGE>

<h2><a class="anchor" id="business-questions--key-findings"></a>📈 Business Questions & Key Findings</h2>

### 1. Trends

We observed strong and consistent growth in 2023 with an **average 5.30% MoM rate**, peaking at **665 orders** in Dec 2023.
However, from the start of 2024, orders faced a sharp downturn for **8 consecutive months**, resulting in an overall **-54.59% decline**.
The key reasons for this fall were reduced **lead flow**, **inconsistent follow-ups**, and an **overdependence on a single channel**.

---

### 2. Recovery Phase

These issues were quickly identified by the analytics team and reported to sales and marketing teams in mid-Q1 through root-cause and bottleneck analysis. From Apr 2024 (Q2), the following corrective actions were implemented to drive recovery:

* Diversified acquisition channels
* Strengthened lead generation processes
* Re-engaged lapsed customers with targeted campaigns

As a result, early signs of improvement were visible from Apr 2024 itself, with **positive percentage changes starting in Sep 2024 (Q3)**.
Since then, we have maintained positive growth at an **average 5.98% (\~6%) MoM rate**, nearly a percent more than 2024 average.

---

### 3. Benchmark

Although the action plan was rolled out in Apr 2024 and improvements were observed, orders dropped below the company’s threshold in May 2024.
Order volume has remained under the threshold, but since Sep 2024 we have achieved an **84.67% recovery against the benchmark**.
The analytics team has forecasted a **full recovery by Mar 2025**, with orders expected to exceed the standard by **10% in May 2025**.

---

### Final Report:

<IMAGE>

<h2><a class="anchor" id="dashboard"></a>💹 Dashboard</h2>

### 1. Order by Month (Top-Right Chart)

#### What it shows?
- Line chart tracks monthly order volume from Jan 2023 onwards.

#### How to read?
- Pay attention to current order volume against Company Threshold
  - Above 450: Business is healthy
  - Below 450: Business is declining
- Note: As per the analytical team, volume will exceed the standard in Mar 2025.

---

### 2. Pecentage Change (Orders) by Month (Bottom-Right Chart)

#### What it shows?
- Line Chart tracks MoM % change from Jan 2023 onwards.

#### How to read?
 - Pay attention to zero-line
   - Above 0: Order volume is growing
   - At or Below 0: Order volume is growing

---

<h2><a class="anchor" id="author-contact"></a>📝 Author & Contact</h2>

#### **Gaurav Patil**
- Data Analyst 
- 🔗 [LinkedIn](https://www.linkedin.com/in/gaurav-patil-in/)
