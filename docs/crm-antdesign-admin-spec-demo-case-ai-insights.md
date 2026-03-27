# crm-antdesign-admin-spec｜Demo Case：AI Customer Insights Page

## User request
Design an AI customer insights page for a CRM system.

---

## Skill classification
**Page type:** AI analytics page

### Why
Because the page must do more than show KPIs:
- identify high-value customers
- identify silent customers
- identify risk customers
- produce recommendations and actions

So it should not be treated as a plain statistics page.

---

## Recommended structure
```text
Title + subtitle
Time and scope filters
KPI insight cards
Customer segmentation insight cards
Trend charts
Detail table
Action recommendation section
```

---

## Recommended Ant Design mapping
- `PageHeader`
- `Tabs` / `Segmented`
- `TreeSelect`
- `Select`
- `Button`
- `Card`
- `Statistic`
- `Table`
- `Tag`
- `Badge`
- chart container

---

## Key constraints
- do not make it a pure KPI dashboard
- do not remove recommendations/action layer
- do not style it like a marketing AI landing page
- keep the page implementation-friendly

---

## Expected deliverables from the skill
- page type decision
- page goal
- information architecture
- section breakdown
- component mapping
- prompt template for downstream UI generation

---

## Why this is a strong demo case
This example clearly shows the skill's value:
1. it prevents page-type misclassification
2. it improves output structure quality
3. it helps AI generation tools produce more realistic admin pages
