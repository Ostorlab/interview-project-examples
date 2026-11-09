# An SEO content plan for Kitewren

Kitewren is a fictional tool that gives every security finding an owner. Nobody has mapped which search queries belong to which of its pages, and a teammate's draft note chases a keyword the product cannot honestly serve. As the marketing intern, build a reusable query-to-page mapping sheet, turn it into a priority list and one page brief, and prove the sheet on next month's export. The scenario date, Monday 2026-10-05, is separate from your submission deadline.

## Start, access, and scope

Your 24 hours start when you click **Start** on the link in your invitation email; the exercise zip becomes available at that moment. Send your submission back within 24 hours of clicking Start. You are not expected to work for the full 24 hours: organize your own working time and breaks within the window. There are no surprise messages or overnight availability requirements, and hours worked are not scored. The clock tests bounded execution and verification, not motivation or sleep sacrifice.

No AI tool is provided: you may use any AI tool you already have. AI is allowed and encouraged for drafting, critique, organization, formulas, automation, and checking. No purchase is needed. Free/offline text, slides, or spreadsheets work; tool choice and code are not graded. Check AI output against the local inputs. Optional outside research adds no marks and cannot prove fictional facts. Do not publish, post, send messages, run ads, create accounts, use real addresses or customer information, or connect systems.

Baseline skills: clear writing, reading a small CSV, basic percentages, and spreadsheet formulas or clear tables. No SEO experience, security expertise or programming is required. The local glossary defines every search and security term.

## Inputs and setup

Keep the raw inputs unchanged and cite their IDs (K, N, G, P).

- [Product facts and glossary](inputs/product-and-glossary.md): approved claims P1–P5 and all terms.
- [SEO rules and handoff notes](inputs/seo-rules.md): rules S1–S9, exclusions X1–X2 and an unverified draft note D1.
- [October keyword export](inputs/keyword-export.csv): 20 query rows.
- [Page inventory](inputs/page-inventory.csv): eight pages.
- [Next-month export](inputs/next-month-export.csv): 11 rows.

These inputs are the complete universe. Mark gaps unknown or flag them for Ada or Bo; never invent a fact, capability or number. All 31 rows must stay visible (mapped, merged, excluded or flagged).

## Core work

1. **Build the reusable mapping sheet.** A spreadsheet with formulas or an explicit rule table applying S1–S8 to every query: normalized query, resolved page, intent, cluster or exclusion, weight, score. Per cluster CL0–CL5: query count, impressions, clicks and CTR (sum of clicks ÷ sum of impressions, two decimals). Keep an exclusion ledger. A teammate must be able to add a new export without inventing rules; a manual system gives exact steps and shows both runs.
2. **Find conflicts and choose the top three actions.** Name any cannibalized cluster, its primary page and what happens to the other. List the top three S8 actions with score and a one-line justification. Correct D1 where the inputs contradict it. Write a note to Bo (at most 150 words) with the three actions and the queries you will not target, labeled **draft; do not send**.
3. **Write one page brief for the top action** (at most 500 words): cluster and main query IDs, dominant intent by impressions, H2 outline, internal links from existing live pages with anchor text, title (≤60 characters) and meta (≤155) with counts, the P5 CTA, a claim map to P-IDs, and what the page must not say.
4. **Rewrite titles and meta descriptions for three existing pages.** Include every page that breaks an S7 limit or makes a claim P1–P5 do not support; choose the rest and say why. Show old and new text, character counts and P-IDs.
5. **Rerun the same sheet on the next-month export (S9).** Mark each row as replacing an October row (name it) or new, recompute the cluster table and top three, and state what changed, what did not and why. Record any rule refinement and rerun one October query through it.

Optional stretch: an internal-link map across all live pages; not needed for full marks.

## Submission and acceptance

Submit an archive or repository with opening instructions, the editable sheet, raw inputs and all deliverables above. A teammate should be able to:

- Trace any query from raw row to intent, cluster or exclusion, page and score, and recompute any cluster CTR.
- See which queries are not targeted and why, with no capability claimed beyond P1–P5.
- Confirm every new title is at most 60 characters and meta at most 155.
- Rerun the next-month export without changing rules and see what changed.
- Find no ranking promise, traffic forecast or claimed result.

Include a short decision/work log: priorities, one obstacle and response, one validation/refinement, limits, next step. Include an AI-use note with one accepted, corrected or rejected output and how you checked it; if no AI was used, say so; do not fabricate a failure, expose accounts, or submit full prompt histories. Give a **3–5-minute recording or equivalent concise text walkthrough**, equally acceptable.

A correct, traceable sheet matters more than polished copy.

## Scoring

Weights: usable result **40**, accuracy/verification **25**, prioritization **20**, communication/handoff **15**, total 100. Full marks possible on core alone; no AI detectors, hours-worked, prose-polish, or content-volume score.
