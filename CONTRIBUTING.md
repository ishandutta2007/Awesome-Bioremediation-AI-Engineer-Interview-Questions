# Contributing

Thanks for helping grow this resource! A few simple guidelines:

## Adding a New Question

1. Pick the right category file under `questions/`. If none fit, propose a new category in an issue first.
2. Follow this format:

```markdown
### Q: <question text> 🟡

**Why it's asked:** One or two sentences on what the interviewer is actually evaluating.

**Answer:**
A model answer, framework, or structured approach. Use bullet points or numbered
steps where possible — interviewers reward structure.

**Follow-ups:**
- A likely follow-up question
- Another likely follow-up question
```

3. Use the difficulty tags:
   - 🟢 Junior / APM
   - 🟡 Mid-level PM
   - 🔴 Senior / Lead / Principal

4. Keep answers **frameworks, not scripts** — the goal is to teach the reasoning pattern, not give people a memorized paragraph to recite.

## Style Guidelines

- Prefer clarity over cleverness.
- If a question is company-specific (e.g., "asked at an environmental biotech startup"), you may note it, but write the answer generically so it's useful to everyone.
- Cite sources for any specific degradation rate, cost, or performance statistics, and for any regulatory claims — these vary a lot by jurisdiction and pollutant type.
- Flag when a technique, chassis organism, or enzyme engineering approach is evolving quickly (this field moves fast, especially around plastics-degrading enzymes) so readers know to verify against current literature.
- Avoid overstating current technology readiness; most engineered bioremediation systems remain at pilot/field-trial scale rather than widely deployed commercial systems, and answers should reflect that honestly.
- Do not include actionable technical detail for engineering organisms to persist or spread uncontrollably in the environment, even when framed as an interview question or answer — keep containment/environmental-release content at the conceptual/policy level, consistent with the Synthetic Biology Designer and Engineered Living Materials companion repos.
- No copy-pasted content from paid courses, books, or proprietary interview-prep platforms (e.g., Glassdoor verbatim reports, exam-dump sites). Original phrasing only.

## Reporting Issues

Found an outdated or incorrect answer (e.g., an evolving regulation, deprecated technique)? Open an issue or submit a PR with the fix — flag what changed and why.

## Code of Conduct

Be kind. Many contributors and readers are early in their careers or transitioning from environmental science/microbiology backgrounds into ML engineering, or from ML/data science backgrounds into environmental biotechnology — write answers you'd have wanted when you were starting out.
