# ProcessGenius AI — Customer Insight Survey

**Form title (Google Forms):** ProcessGenius AI – Customer Insight Survey

**Intro text (place under the title, above Section A):**
> Thank you for participating. Your responses are valuable in shaping how our product serves your needs. All questions are required and appreciated. This should take about 6–8 minutes to complete.

**Recommended Google Forms setting:** Settings → General → turn ON "Collect email addresses" only if you plan to follow up with respondents; otherwise leave anonymous to encourage candor. Under each question, toggle "Required" on for every question below unless marked *(Optional)*.

---

## Section A: About Your Organization
*Section description: "Tell us a little about your company."*

**Q1. Which industry regulatory regime primarily governs your compliance documentation?**
- Type: **Dropdown**
- Options:
  - Finance (e.g., SEC/FINRA, RBI-type)
  - Pharmaceutical (e.g., FDA-type)
  - Both
  - Other

**Q2. How many employees does your organization have?**
- Type: **Dropdown**
- Options:
  - Fewer than 250
  - 250–999
  - 1,000–3,000
  - 3,001–5,000
  - 5,001–10,000
  - 10,000+

**Q3. What is your organization's approximate annual turnover (USD equivalent)?**
- Type: **Dropdown**
- Options:
  - Under $10 million
  - $10 million – $25 million
  - $25 million – $50 million
  - $50 million – $100 million
  - Over $100 million
  - Prefer not to say

**Q4. What is your role in relation to compliance processes and documentation?**
- Type: **Dropdown**
- Options:
  - I produce it (e.g., Business Analyst)
  - I sign off on it (e.g., Compliance/Audit Manager)
  - I own client delivery for it (e.g., Engagement Lead)
  - Other

---

## Section B: Current Compliance Documentation Workload
*Section description: "Help us understand your current legal/compliance documentation process and spend."*

**Q5. On average, how many weeks does it take your team to produce compliant process documentation for a new process?**
- Type: **Short answer** *(numeric — weeks)*

**Q6. What percentage of your (or your team's) time is spent rewriting documentation due to regulatory changes?**
- Type: **Short answer** *(numeric — %)*

**Q7. How would you rate your team's current documentation accuracy?**
- Type: **Linear scale**
- Scale: 1 to 10
- Labels: "1 = Very inaccurate" to "10 = Fully accurate/audit-ready"

**Q8. Approximately how much does your organization spend annually on compliance documentation (internal staff time and/or external/legal support), in USD equivalent?**
- Type: **Dropdown**
- Options:
  - Under $50,000
  - $50,000 – $150,000
  - $150,000 – $500,000
  - $500,000 – $1 million
  - Over $1 million
  - Not sure / prefer not to say

---

## Section C: Evaluating AI Features
*Section description: "Please rate the importance of each statement below on a scale from 1 (Not at all important) to 7 (Extremely important). There are no right or wrong answers — we're interested in your honest priorities."*

**Q9. Product Capabilities — please rate each statement:**
- Type: **Multiple-choice grid (Linear Scale Grid)**
- Scale: 1 to 7 (Columns: 1 = "Not at all important" → 7 = "Extremely important")
- Rows:
  1. The AI must generate documentation that is compliant on first draft.
  2. Automatically flagging compliance gaps before an audit is important.
  3. The AI's ability to translate complex regulatory clauses into plain language for non-technical stakeholders matters to me.
  4. Faster turnaround on documentation updates when regulations change is important.
  5. Seamless integration with our existing workflow/documentation systems matters.

**Q10. Trust & Oversight Expectations — please rate each statement:**
- Type: **Multiple-choice grid (Linear Scale Grid)**
- Scale: 1 to 7 (Columns: 1 = "Not at all important" → 7 = "Extremely important")
- Rows:
  1. Mandatory human sign-off on any AI-generated output before it reaches a client or auditor is important to me.
  2. Clear labeling of which content is AI-generated versus human-verified is important.
  3. A transparent track record of zero critical compliance misinterpretations would influence my trust in this tool.
  4. Being able to see the specific regulatory source behind an AI-generated recommendation is important.

**Q11. How likely would you be to pilot an AI tool like this within the next 12 months?**
- Type: **Linear scale**
- Scale: 1 to 5
- Labels: "1 = Not at all likely" to "5 = Extremely likely"

---

## Section D: Your Insights
*Section description: "We'd like to hear from you in your own words."*

**Q12. What is your primary concern about using AI for compliance documentation?**
- Type: **Paragraph text**

**Q13. Describe the biggest compliance-documentation-related pain point you face today.**
- Type: **Paragraph text**

**Q14. If this tool worked exactly as you'd want, what would change about your day-to-day work?**
- Type: **Paragraph text**

**Q15. Is there anything else you'd like us to know? *(Optional)***
- Type: **Paragraph text** *(Optional — not required)*

---

## Notes for building this in Google Forms

- **Section breaks:** Use "Add section" (the ≡ icon on the right toolbar) before Q1, Q5, Q9, and Q12 so respondents move through A → B → C → D as discrete pages — this reduces perceived length and improves completion rates.
- **Grids (Q9, Q10):** Use "Multiple choice grid" question type; add rows as listed and columns 1–7. Under grid settings, tick "Require a response in each row" so segmentation data has no gaps.
- **Segmentation readiness:** Q1–Q4 give you the firmographic clusters (industry, size, turnover, role); Q5–Q8 give you workload/spend intensity; Q9–Q11 give you feature-priority and trust-priority vectors suitable for cluster analysis (e.g., k-means on the 1–7 scale responses); Q12–Q15 give qualitative texture to name and validate the resulting clusters.
- **Bias check:** All scale items are worded as single, unambiguous statements (no double-barreled questions) and the grid columns are symmetric and clearly labeled at both ends, consistent with best practice for B2B feature-prioritization surveys.
- **Estimated length:** 15 required questions + 1 optional — comfortably within the 6–8 minute range for a decision-maker audience with moderate-to-high time value (per Priya, Rhea, and Aditi's persona profiles).
