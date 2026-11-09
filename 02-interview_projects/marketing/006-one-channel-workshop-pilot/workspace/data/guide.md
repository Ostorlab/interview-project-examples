# Export definitions

registrations.csv is a frozen 2026-11-04 08:00 UTC+00:00 snapshot with one row per person. person_id is unique. status is registered, cancelled or waitlist. marketing_opt_in and suppression are current permissions, not predictions. source is a self-reported discovery channel and may differ from an attribution system. It should not be used to infer a person's browsing history. IDs R001 onward are artificial.

channel-results.csv describes six completed small campaigns. spend_eur is actual EUR spend; attributed_registrations counts a channel touch, not unique cross-channel people. confirmed_unique is a campaign-level deduplicated total repeated on each row for context; never sum it across channels. clicks and impressions belong to the named row. Use clicks/impressions for click rate and spend_eur/attributed_registrations for channel cost per attributed registration. A zero denominator means undefined, not zero. Report which measure you selected.

search.csv is a small editorial research sample, not a full market export. monthly_searches is an estimate, difficulty is a 0–100 estimate, and intent describes the query's likely need. Rows may share a topic; do not sum search volumes as unique people. Current_page is a maintained path or blank, not a demand to create a new URL. Use the sample to justify one useful next move, and say that broader SEO conclusions require more data.

Any assignment-specific exclusion or correction appears in updates.md. It replaces a named older suggestion, not the whole dataset. Preserve raw files in a submission or describe calculations so another person can reproduce a small sample with a calculator.
