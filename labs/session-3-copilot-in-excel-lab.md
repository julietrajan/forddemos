# Ford Manufacturing Operations Demo

**Scenario:**  
You're a manufacturing operations analyst reviewing plant throughput, supplier performance, component quality, delivery performance, launch readiness, warranty signals, and operational risk.

> **NOTE:** This workbook uses entirely fictional synthetic data for Microsoft Copilot training. It does not represent actual Ford production data, plants, suppliers, vehicles, performance, policies, or operational requirements.

## Demo Setup

Use:

`Ford_Manufacturing_Operations_Insights_Demo.xlsx`

---

# Copilot in Excel

## 1. Workbook Orientation

**Worksheet:** `Any`

### Prompt 1 — Quick Workbook Summary

```text
Summarize this workbook in 30 seconds.
```

### Prompt 2 — Leadership Perspective

```text
Explain this workbook as if I am a manufacturing operations director.
```

### Prompt 3 — Understand the Data

```text
What are the most important columns in this workbook and why would they matter to a manufacturing operations leader?
```

---

## 2. Data Cleanup

**Worksheet:** `Operations Data`

### Prompt 1 — Normalize Data

```text
Normalize similar plant, supplier, vehicle program, shift, and component names.
```

### Prompt 2 — Find Duplicates

```text
Identify duplicate records in this table.
```

### Prompt 3 — Detect Outliers

```text
Find unusual or outlier values in Defects, Downtime Hours, Unit Cost, or Scrap Cost.

Explain why each value appears unusual before recommending any change.
```

---

## 3. Calculated Columns

**Worksheet:** `Operations Data`

### Prompt 1 — Create a Performance Category

```text
Create a new column called Production Performance Category using Defect Rate, On-Time %, and Throughput Gap.

Categorize each record as:
- On Track
- Monitor
- At Risk
- Critical

Explain the logic you used.
```

**Worksheet:** `Quality Risk`

### Prompt 2 — Create a Risk Formula

```text
Create a formula to identify items with a worsening defect trend and a Risk Score above the Risk Threshold.
```

**Worksheet:** `Operations Data`

### Prompt 3 — Explain an Existing Formula

```text
Explain the inherited formula in the Operational Risk Score column in simple business language.

Tell me which factors increase the risk score.
```

---

## 4. Production Trend Analysis

**Worksheet:** `Weekly Trend`

### Prompt 1 — Analyze Weekly Trends

```text
Analyze production and defect trends by week.

Identify:
- Improvements
- Deteriorating trends
- Unusual changes
- Areas that may require operational attention

Do not assume a root cause unless the data supports it.
```

**Worksheet:** `Summary`

### Prompt 2 — Analyze Scrap Impact

```text
Identify vehicle programs with the highest estimated scrap impact.

Explain which programs deserve further investigation and why.
```

---

## 5. Plant Performance Analysis

**Worksheet:** `Operations Data`

### Prompt — Compare Plant Performance

```text
Compare manufacturing performance across plants using:
- Units Produced
- Throughput Gap
- Defect Rate
- On-Time %
- Downtime Hours
- Estimated Scrap Impact

Identify the strongest signals and the areas that may require further investigation.

Do not infer causes that are not supported by the data.
```

---

## 6. Supplier Analysis

**Worksheet:** `Operations Data`

### Prompt — Analyze Supplier Performance

```text
Analyze supplier performance using defect rates, supplier confirmation status, components, operational risk, and estimated scrap impact.

Identify suppliers or supplier-component combinations that may require additional attention.

Separate facts from recommendations.
```

---

## 7. Pivot Table

**Worksheet:** `Summary`

### Prompt — Create an Operations Pivot Table

```text
Create a pivot table by Region and Vehicle Program showing:
- Units Produced
- Defects
- On-Time Shipments
- Estimated Scrap Impact

Make the output suitable for an operations review.
```

---

## 8. Visualization

**Worksheet:** `Summary`

### Prompt 1 — Scrap Impact Chart

```text
Create a chart showing Estimated Scrap Impact by Vehicle Program.

Use a clear title and make the chart easy for manufacturing leadership to interpret.
```

### Prompt 2 — Plant Performance Chart

```text
Create a chart comparing production volume and defects across plants.

Highlight any plant where the relationship between production and defects deserves further investigation.
```

---

# Quality and Risk Analysis

## 9. Risk Watchlist

**Worksheet:** `Quality Risk`

### Prompt 1 — Highlight Risk Review Items

```text
Highlight all items approaching risk review status.
```

### Prompt 2 — Apply Risk Conditional Formatting

```text
Apply conditional formatting to identify records with a worsening defect trend.

Use red for the highest concern and amber for items requiring monitoring.
```

### Prompt 3 — Identify Leadership Risks

```text
Identify the quality-risk items that need leadership attention.

For each item, explain:
- Plant
- Vehicle Program
- Supplier
- Component
- Risk signal
- Customer impact
- Risk score
- Recommended follow-up

Base the explanation only on information available in the workbook.
```

---

## 10. Calibration Risk

**Worksheet:** `Quality Risk`

### Prompt — Investigate Calibration Risk

```text
Identify records where calibration evidence is missing or pending.

Show the related:
- Plant
- Supplier
- Component
- Defect trend
- Risk score
- Review status

Prioritize the records that deserve investigation first and explain the prioritization.
```

---

## 11. Supplier Readiness

**Worksheet:** `Quality Risk`

### Prompt — Analyze Supplier Readiness

```text
Analyze supplier readiness across the portfolio.

Identify patterns involving suppliers marked Conditional or At Risk.

Determine whether these risks are concentrated around particular:
- Plants
- Vehicle programs
- Components

Do not infer a cause unless the workbook provides evidence.
```

---

# Leadership Decision Support

## 12. Leadership Attention

**Worksheet:** `Operations Data`

### Prompt — Identify What Leadership Needs to Know

```text
Show me the operational records that require leadership attention.

Group the findings into:
- Quality
- Supplier
- Production
- Calibration
- Validation coverage

For each group, summarize the business issue and identify the information leadership should review.
```

---

## 13. Saturday Validation Coverage

**Worksheet:** `Operations Data`

### Prompt — Support the Validation Coverage Decision

```text
Analyze records where Saturday Coverage is marked Decision Required.

For these records, summarize:
- Plant
- Vehicle Program
- Supplier
- Component
- Throughput Gap
- Defect Rate
- Downtime Hours
- Operational Risk Score

Based only on the available data, explain what leadership should consider before making a decision.

Do not make the final decision for leadership.
```

---

## 14. Ask Copilot to Find What You Didn't Ask

**Worksheet:** `Any`

### Prompt — Discover Hidden Insights

```text
Act as a manufacturing operations analyst.

Review this workbook and identify three patterns, risks, or relationships that I may have overlooked.

For each finding:

1. Explain what you observed.
2. Show the data supporting it.
3. Explain why it could matter operationally.
4. Suggest the next question I should investigate.

Do not infer facts that aren't supported by the workbook.
```

---

# Executive Dashboard Challenge

**Worksheet:** `Summary`

### Prompt — Build an Executive Operations Dashboard

```text
Create an Executive Manufacturing Operations Dashboard from this workbook.

Include:
- Total Units Produced
- Overall Defect Rate
- On-Time Delivery
- Estimated Scrap Impact
- Top Risk Vehicle Program
- Plant performance
- Weekly production and quality trend
- Supplier risk indicators
- Quality risk watchlist
- Leadership attention items
- Executive summary with recommended actions

Use an executive-friendly layout with red, amber, and green indicators.

Keep the dashboard focused on decisions rather than displaying every available metric.
```

---

# Executive Briefing

**Worksheet:** `Any`

### Prompt — Prepare a One-Minute Leadership Brief

```text
Prepare a one-minute manufacturing operations briefing based on this workbook.

Structure it as:

1. What's going well
2. What needs attention
3. Emerging quality or supplier risks
4. Decisions leadership may need to make
5. Recommended next actions

Clearly distinguish observations from recommendations.

Do not add information that isn't supported by the workbook.
```

---

# Copilot Premium / Analyst

## Advanced Analysis with Python

**Worksheet:** `Any`

### Prompt — Forecast and Identify Risk Clusters

```text
Using Python, analyze historical production throughput and forecast next-quarter production performance.

Then identify clusters of recurring operational risk across:
- Plant
- Supplier
- Vehicle Program
- Component
- Defect trends
- Downtime
- Supplier readiness

Create:

1. A production forecast
2. A forecast visualization
3. A risk-cluster analysis
4. A concise executive summary

Explain which areas may deserve leadership attention and why.

Clearly distinguish historical observations, forecast results, and recommendations.
```

---

# Copilot in Word

### Prompt — Create an Executive Risk Summary

```text
Using insights from this workbook, write a 150-word executive operational risk summary for manufacturing leadership.

Focus on:
- Production performance
- Quality
- Supplier readiness
- Operational risk
- Areas requiring leadership attention

Use concise executive language.

Clearly distinguish facts from recommendations.
```

---

# Suggested Demo Flow

1. **Understand** — Summarize the workbook
2. **Clean** — Find inconsistent values and duplicates
3. **Calculate** — Generate and explain formulas
4. **Analyze** — Explore weekly manufacturing trends
5. **Compare** — Compare plants and suppliers
6. **Visualize** — Create pivot tables and charts
7. **Investigate** — Analyze quality and calibration risk
8. **Prioritize** — Identify leadership-attention items
9. **Decide** — Explore Saturday validation coverage
10. **Discover** — Ask Copilot what you may have overlooked
11. **Dashboard** — Build an executive operations view
12. **Forecast** — Use Python for advanced analysis
13. **Communicate** — Create an executive summary in Word

---

# Key Takeaway

Copilot in Excel can help manufacturing teams move from raw operational data to structured analysis, quality and supplier insights, risk prioritization, decision support, visualization, and executive-ready communication within a connected workflow.

The value isn't simply asking Copilot to summarize a spreadsheet.

The progression is:

**Data → Understanding → Quality → Risk → Decisions → Actions**

---

# Appendix: Intentional Data Issues

The **Operations Data** worksheet contains intentional data-quality issues for demonstration purposes.

| Issue | Location | What to Look For | Expected Demo Outcome |
|---|---|---|---|
| Vehicle Program | F15 | Electric Sport Utility | Normalize to Electric SUV |
| Vehicle Program | F42 | Pickup Truck with trailing space | Normalize to Pickup Truck |
| Supplier | H89 | Vector Embedded Systems | Normalize to Vector Embedded |
| Plant | D145 | Dearborn Assy | Normalize to Dearborn Assembly |
| Shift | G222 | Nights | Normalize to Night |
| Supplier | H319 | Blue Harbour Components | Normalize to Blue Harbor Components |
| Component | I411 | Torque sensor | Normalize to Torque Sensor |
| Duplicate | Row 520 | Duplicate record | Remove or flag |
| Duplicate | Row 575 | Duplicate record | Remove or flag |
| Defect outlier | Row 201 | 420 defects | Investigate or flag |
| Downtime outlier | Row 201 | 96 downtime hours | Investigate or flag |
| Cost outlier | Row 201 | $1,450 unit cost and $609,000 scrap cost | Investigate or flag |
| Quality outlier | Row 378 | 310 defects and 82.5 downtime hours | Investigate or flag |

---

# Training Disclaimer

This demonstration uses **fictional synthetic data created solely for Microsoft Copilot training**.

Plant names, vehicle programs, suppliers, components, production values, defects, costs, risks, warranty signals, and operational outcomes in the workbook should not be interpreted as actual Ford Motor Company operational information.

Do not add customer-confidential, production-sensitive, supplier-confidential, or proprietary information to the training workbook.
