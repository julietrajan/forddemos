# Copilot in Word Demo

This demo shows how Copilot in Word can help transform rough notes, interpret an operational bulletin, create multilingual content, and generate a leadership briefing from an Excel workbook.

> **Training note:** The documents, data, scenarios, organizations, plants, suppliers, operational results, and business outcomes used in this demonstration are fictional and intended solely for Microsoft Copilot training.

---

# Demo 1: Turn Rough Notes into an Executive Business Review

## Scenario

You have received rough notes from several teams before a regional business review.

Instead of manually organizing and rewriting the information, use Copilot in Word to turn the notes into a concise, leadership-ready document.

## Rough Notes

Copy and paste the following notes into a blank Word document:

```text
New policy sales increased by 11%.

Retirement solutions exceeded target.

Advisor productivity improved in Boston and Hartford.

Customer retention improved from 89% to 92%.

Claims processing turnaround improved by 7%.

Concerns:
- Underwriting turnaround increased.
- New business submissions decreased in two territories.
- There is an advisor vacancy in one sales district.

Risks:
- Competition is increasing in retirement products.
- Claims volume is rising.

Support required:
- Advisor hiring support
- Marketing support
```

## Prompt 1: Create the Regional Business Review

```text
Create a one-page regional business review for senior leadership.

Include:
- Highlights
- Concerns
- Risks
- Support required
- Recommended actions

Keep it concise, executive, and action-oriented.

Do not add information that is not included in the notes.
```

## Follow-up Prompt 1: Add an Executive Summary

```text
Add a short executive summary at the top of the document.

Summarize overall performance, the most important concern, and the support required from leadership.
```

## Follow-up Prompt 2: Sharpen the Tone

```text
Make the tone sharper but professional.

Use concise, leadership-focused language and make the actions and decisions required immediately clear.

Do not change or add any facts.
```

## Follow-up Prompt 3: Convert Key Sections into a Table

```text
Convert the Concerns, Risks, and Support Required sections into a table.

Use the following columns:
- Category
- Issue
- Business implication
- Recommended action

Do not add information that is not supported by the original notes.
```

## What This Demonstrates

- Transforming rough notes into a structured document
- Role-based writing for senior leadership
- Iterative document refinement
- Tone adjustment
- Document restructuring
- Converting narrative content into a table
- Maintaining factual grounding

---

# Demo 2: Analyze an Operational Quality Bulletin

## Demo Setup

Open or paste the contents of:

`Ford_Operational_Quality_Bulletin.docx`

## Scenario

You are a plant or program leader who has received a detailed operational quality bulletin.

You do not simply need a shorter version of the document. You need to understand:

- What the bulletin requires
- What actions must be completed
- What risks remain unresolved
- What requires leadership attention
- What should be communicated to the team

## Prompt 1: Summarize and Operationalize the Bulletin

```text
Summarize this operational quality bulletin for a plant or program leader.

Create a practical launch-readiness action plan with:
- Action
- Owner, if stated
- Target checkpoint
- Current status
- Risk if the action remains unresolved

Highlight anything requiring:
- A leadership decision
- Leadership review
- Escalation

Do not add information that is not in the document.

If an owner, status, or target checkpoint is not stated, clearly mark it as Not specified rather than inferring it.
```

## Follow-up Prompt 1: Create a Manager Verification Checklist

```text
What should a manager verify before communicating this bulletin to the team?

Create a practical checklist based only on the document.

Group the checklist into:
- Requirements to understand
- Actions and ownership to confirm
- Risks and escalations to review
- Timelines or checkpoints to verify
- Communication points to prepare

Do not introduce requirements that are not present in the bulletin.
```

## Follow-up Prompt 2: Create a Spanish Version

```text
Create a Spanish version of the manager verification checklist.

Preserve the original meaning and structure.

Do not overwrite or replace the current English content.

Add the Spanish version immediately below the English version.
```

## Optional Follow-up Prompt: Create a Team Communication

```text
Based only on this bulletin and the manager verification checklist, draft a concise communication for the impacted team.

Include:
- Why the bulletin matters
- What team members need to do
- What managers will verify
- What issues require escalation
- Any stated timeline or checkpoint

Use plain language and avoid unnecessary jargon.

Do not add information that is not in the bulletin.
```

## Optional Follow-up Prompt: Create a Leadership Briefing

```text
Prepare a one-minute leadership briefing based on this bulletin.

Structure it as:
1. What has changed
2. What actions are required
3. What remains unresolved
4. What could affect launch readiness
5. What requires leadership attention

Clearly distinguish stated requirements from unresolved items.

Do not add information that is not in the document.
```

## What This Demonstrates

- Summarizing a long document for a specific role
- Extracting actions and ownership
- Identifying missing information
- Creating a launch-readiness action plan
- Generating a manager checklist
- Identifying leadership decisions and escalations
- Translating content while preserving meaning
- Adding translated content without replacing the original
- Reusing the same source for different audiences

---

# Demo 3: Create a Leadership Briefing from an Excel Workbook

## Demo Setup

Attach or reference:

`Ford_Manufacturing_Operations_Insights_Demo.xlsx`

## Scenario

You are preparing for an operations leadership review.

The supporting workbook contains information about:

- Plant throughput
- Supplier performance
- Component quality
- Delivery performance
- Launch readiness
- Warranty signals
- Operational risk

Instead of manually copying tables and writing a report, use Copilot in Word to turn the workbook insights into a one-page leadership briefing.

## Prompt 1: Create an Executive Operations Review

```text
Using the attached manufacturing operations workbook, create a one-page executive operations review.

Focus on:
- What happened
- What changed
- Key quality, supplier, and operational risks
- Business impact
- Items requiring leadership attention
- Recommended actions

Present the output as a leadership briefing.

Clearly distinguish:
- Facts found in the workbook
- Risks identified from the data
- Recommendations

Do not add information that is not supported by the workbook.
```

## Follow-up Prompt 1: Anticipate Leadership Questions

```text
Based on this operations review, identify the 10 questions that the CIO or Operations Leadership team is most likely to ask.

Prioritize questions about:
- Plant performance
- Supplier readiness
- Quality risks
- Production throughput
- Defects
- Downtime
- Delivery performance
- Estimated scrap impact
- Calibration evidence
- Leadership decisions

Base the questions only on information found in the workbook and the operations review.
```

## Follow-up Prompt 2: Suggest Strong Responses

```text
Suggest a strong response to each of the 10 leadership questions.

For every response:
- Start with the direct answer
- Reference the relevant evidence from the workbook
- State what is confirmed
- Identify what remains unknown or requires further investigation
- Recommend the next action where appropriate

Do not invent missing facts, causes, owners, timelines, or commitments.
```

## Follow-up Prompt 3: Create a Leadership Q&A Table

```text
Convert the leadership questions and suggested responses into a table.

Use the following columns:
- Leadership question
- Suggested response
- Supporting evidence
- Information gap
- Recommended next action

Keep the responses concise and suitable for a live leadership meeting.
```

## Follow-up Prompt 4: Create Talking Points

```text
Create concise talking points for presenting this operations review to leadership.

Organize the talking points into:
1. Opening summary
2. What is performing well
3. What requires attention
4. Key risks
5. Leadership decisions required
6. Recommended next actions

Keep the talking points concise enough for a five-minute presentation.

Do not add information that is not supported by the workbook.
```

## Follow-up Prompt 5: Create a Closing Recommendation

```text
Add a short closing recommendation to the operations review.

The recommendation should:
- Summarize the most important operational priority
- State the immediate next action
- Identify any leadership support required
- Avoid introducing new facts

Keep it to no more than three sentences.
```

## What This Demonstrates

- Grounding a Word document in an Excel workbook
- Transforming workbook data into executive communication
- Identifying leadership-relevant insights
- Separating facts, risks, and recommendations
- Anticipating executive questions
- Preparing evidence-based responses
- Creating leadership Q&A
- Generating presentation talking points
- Moving from data analysis to decision-ready communication

---

# Suggested Demo Flow

## Demo 1: Create from Rough Notes

1. Paste the rough notes into Word.
2. Ask Copilot to create the one-page regional business review.
3. Add an executive summary.
4. Sharpen the tone.
5. Convert concerns, risks, and support required into a table.

**Teaching point:** Copilot can move from incomplete notes to a structured, executive-ready document through iterative refinement.

---

## Demo 2: Understand and Act on a Document

1. Open `Ford_Operational_Quality_Bulletin.docx`.
2. Ask Copilot to summarize it for a plant or program leader.
3. Generate the launch-readiness action plan.
4. Ask what a manager should verify.
5. Create the Spanish version below the English checklist.
6. Optionally create a team communication or leadership briefing.

**Teaching point:** Copilot can turn a detailed operational document into role-specific actions, checklists, communications, and multilingual content.

---

## Demo 3: Create from an Excel Workbook

1. Attach or reference `Ford_Manufacturing_Operations_Insights_Demo.xlsx`.
2. Create the one-page executive operations review.
3. Ask for the 10 most likely leadership questions.
4. Generate suggested answers.
5. Convert the questions and answers into a table.
6. Generate presentation talking points.
7. Add a closing recommendation.

**Teaching point:** Copilot can help connect data analysis with executive communication and leadership preparation.

---

# Full Word Demo Journey

The three demos show a progression:

1. **Rough notes → Structured business review**
2. **Operational document → Action plan and manager checklist**
3. **Excel data → Executive briefing and leadership Q&A**

The broader story is:

**Create → Refine → Understand → Translate → Analyze → Communicate → Prepare**

---

# Key Takeaway

Copilot in Word is not limited to generating or summarizing text.

It can help users:

- Transform rough notes into structured documents
- Adapt content for different audiences
- Refine tone and structure
- Extract requirements and actions
- Create practical checklists
- Translate content while preserving meaning
- Use supporting files to create grounded reports
- Anticipate leadership questions
- Prepare evidence-based responses
- Move from operational information to decision-ready communication

---

# Training Disclaimer

This demonstration uses fictional training materials and synthetic data created solely for Microsoft Copilot training.

The documents, metrics, plants, suppliers, vehicle programs, operational risks, actions, and outcomes used in this demonstration should not be interpreted as actual Ford Motor Company information.

Do not add customer-confidential, production-sensitive, supplier-confidential, personal, or proprietary information to the training documents or prompts.
