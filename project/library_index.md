# Library Index · Internal IT Help Desk (Scenario B2)

Owner: Abdullah · Index version: v1 · Date: 2026_10_15

## Templates (templates/)

| Template | Task | Main variables | Version | Status |
|----------|------|----------------|---------|--------|
| IT-Reply-Ticket | Resolve a support ticket | [TICKET] [DESK_FACTS] [LANGUAGE] [TONE] [MAX_WORDS] | v1 · 2026_10_15 | Approved (5/5 · 6/6 · 5/5) |
| IT-Summarize-Thread | Shorten a ticket thread | [THREAD] [LANGUAGE] [MAX_WORDS] | v1 · 2026_10_15 | Approved (5/5 · 6/6 · 5/5) |
| IT-Route-Ticket | Route tickets to teams | [TICKET] [CATEGORIES] [DESK_FACTS] [LANGUAGE] | v1 · 2026_10_15 | Approved (5/5 · 6/6 · 5/5) |
| IT-Rewrite-Answer | Explain it simply | [TECH_ANSWER] [LANGUAGE] [TONE] [MAX_WORDS] | v1 · 2026_10_15 | Approved (5/5 · 6/6 · 5/5) |
| IT-Draft-Notice | Planned maintenance notice | [SERVICE_NAME] [MAINT_WINDOW] [EMPLOYEE_ACTION] [DESK_FACTS] [LANGUAGE] [TONE] [MAX_WORDS] | v1 · 2026_10_15 | Approved (5/5 · 6/6 · 5/5) |

## Shared blocks and rules

| File | What it is | Version |
|------|-----------|---------|
| blocks/IT-Facts-v1_2026_10_15.md | The 7 approved Desk Facts, used as [DESK_FACTS] | v1 · 2026_10_15 |
| rules/IT-Rules-v1_2026_10_15.md | Five Desk rules: data, verification, fairness, policy, human decision | v1 · 2026_10_15 |

## The five [LANGUAGE] values (the same in every template)

| Value | Meaning |
|-------|---------|
| Arabic | Answer in Arabic only |
| English | Answer in English only |
| Automated (default) | Reply in the main language of the input |
| Bilingual | Two separate versions: Arabic, then English |
| Mixed | One reply that merges Arabic and English |

## Change log
- v1 · 2026_10_15 · First library: 5 templates, Facts block, rules file, Test Results Report.
