# Kitewren SEO rules

Apply S1–S8 in order. Ada owns exports; Bo approves briefs and actions.

**S1. Merge.** Lowercase, trim, collapse repeated spaces. Same normalized query **and** resolved page (S2) = one query: add impressions and clicks; position = impression-weighted average, one decimal.

**S2. Pages.** A `redirected` URL counts as its `redirect_to` page, never separately. `noindex` is not live. Flag unknown URLs to Ada.

**S3. Intent.** A signal matches a query word starting with it; first match wins.

| Order | Intent | Signals |
| --- | --- | --- |
| 1 | navigational | `kitewren`, `login`, any other product or company name |
| 2 | transactional | `demo`, `trial`, `template`, `download`, `buy` |
| 3 | commercial | `tool`, `software`, `best`, `vs`, `alternative`, `compare` |
| 4 | informational | anything else |

**S4. Clusters.** Same matching; first row wins. No match: `unclustered`, listed, not targeted or totaled.

| Cluster | Topic | Triggers |
| --- | --- | --- |
| CL0 | Brand (never ranked) | `kitewren` |
| CL1 | Finding ownership | `owner`, `assign`, `accountab` |
| CL2 | Finding triage | `triage`, `prioriti` |
| CL3 | Tracking in a sheet | `spreadsheet`, `tracker`, `track` |
| CL4 | Due dates and reminders | `due`, `deadline`, `reminder` |
| CL5 | Status reporting | `report`, `summary`, `dashboard` |

**S5. Do not target** (before S4). **X1**: contains `auto-fix`, `autofix`, `automatic fix`, `auto-remediation`, `automatic remediation`, `scanner`, `certification`, `certified` or `certify` (ruled out by P3/P4). **X2**: navigational for another product or company. Excluded queries go in a ledger, never in totals or scores. Rule-based automatic assignment (P1) is not excluded.

**S6. Cannibalization**: after S2, two or more live pages get impressions from one target cluster (CL1–CL5).

**S7. Limits.** One cluster per page; title ≤ **60** characters, meta ≤ **155**, counting spaces. Claims only from P1–P5; CTA per P5. No ranking, traffic or results promises. Internal links only from live pages. Fix any live or draft page over a limit before it is next published.

**S8. Priority.** Weight each query by position: below 4.0 → 0; 4.0–10.9 → 1; 11.0–20.9 → 0.5; 21.0+ → 0. Score = sum of impressions × weight. Action: **new page** if no live page has the cluster as `primary_topic` (publishing a draft counts as new); **merge** if cannibalized (primary = page with more cluster clicks; say whether the other is redirected or re-targeted); else **refresh**. Rank by score (tie: impressions); 0 = no action. Top three = the month's list; brief the first.

**S9. Next month.** The export holds only new or changed queries. Match by normalized query plus resolved page: a match **replaces**, no match is **new**, absent queries carry over. Reapply S3–S8.

**D1 (teammate draft, unverified):** "'auto-fix vulnerabilities tool' is our biggest keyword, so build it next. Leave both ownership pages. The triage checklist is a second triage page. We can promise Bo a top-three ranking."
