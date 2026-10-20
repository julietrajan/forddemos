# Copilot in Excel Lab Guide

Classification: Public. This demo uses a fictional Microsoft Fake Company created for demonstration purposes. Any resemblance to real organizations, people, products, services, or data is coincidental. Do not use customer confidential information in this repository.

## Timing
60 minutes

## Objective
Use Copilot to analyze a multi-sheet operational dataset, create charts, forecast trends, and identify data quality issues.

## Demo setup
Use the provided fictional Northstar Mobility artifacts. Keep the demo focused on prompts and expected outcomes rather than slide lecture content.

## Trainer flow
| Time | Activity | Artifact |
| --- | --- | --- |
| 0-5 min | Set context and data-sensitivity reminder | Prompt guide |
| 5-15 min | First Copilot demo and discussion | Excel workbook with operations, defects, forecast, lookup, and dashboard sheets. |
| 15-35 min | Guided hands-on prompt sequence | Supporting files |
| 35-50 min | Scenario challenge | Supporting files |
| 50-60 min | Debrief, expected outputs, Q&A | Prompt guide |

## Data sensitivity language
Use this short talk track: "Today we are using fictional, Public sample content. In production, apply your organization's sensitivity labels, respect DLP policies, and avoid entering regulated, customer-confidential, personal, or unreleased business information into prompts unless your tenant policies and the data label permit it. Copilot follows Microsoft 365 permissions and labels, but users are still responsible for choosing appropriate source content and outputs."

## Copy/paste prompts
### Prompt 1
```
Analyze this workbook and tell me the three biggest operational issues by plant and product line.
```

### Prompt 2
```
Create a chart showing weekly defect rate by plant and highlight any worsening trend.
```

### Prompt 3
```
Build a management dashboard with throughput, defect rate, on-time percentage, and top risk drivers.
```

### Prompt 4
```
Forecast the next four weeks of throughput by plant and explain assumptions.
```

### Prompt 5
```
Find duplicates, missing values, and inconsistent product names in the Operations Data sheet.
```

### Prompt 6
```
Apply conditional formatting to flag defect rates above 3.5% and on-time delivery below 92%.
```

### Prompt 7
```
Extract shift type, product family, and week number into new columns and create a new worksheet with only high-risk records.
```

### Prompt 8
```
Analyze information across the Operations Data and Parts Risk sheets to recommend where to focus tomorrow's standup.
```

## Expected outputs
- A concise summary or analysis that cites the source artifact where possible.
- Structured next steps with owners, risks, and decisions.
- A reusable example the trainer can adapt live in the session.

## Troubleshooting
- If Copilot cannot access a file, confirm it is opened from OneDrive, SharePoint, or the active Microsoft 365 app as appropriate.
- If a response is too generic, add role, audience, format, and constraints to the prompt.
- If the output may include sensitive material, ask Copilot to remove confidential details and keep only public-safe language.
