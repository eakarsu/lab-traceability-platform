# Feature status — Laboratory, tissue & specimen operations

| Capability | Status |
| --- | --- |
| Native sidebar and canonical feature registry | Built; 115 pages |
| Shared records, validation, relationships, persistence | Implemented in shared runtime |
| Clickable table rows with centered details popup | Implemented; Edit, Delete, Cancel, keyboard access and mobile layout |
| Domain field forms and source traceability | Imported from static source definitions; historical routes are labeled in mapping |
| CSV exports, attachments, audit and report totals | Implemented |
| At least 15 fictional rows per editable feature | Seeded by startup; measured in reports/seed-verification.json |
| AI question-and-answer workspace | Replaces AI feature tables; questions, context fields, formatted answers, follow-ups and saved history; live provider configuration required |
| Source calculation adapters | Available for explicitly registered calculation variants only |
| Source business-rule and state-machine parity | Incomplete beyond registered adapters and native records; verify each source journey |
| Original account/business data migration | Not performed; source data preserved |
| Provider integrations and external delivery | Not connected; request preparation only |
| Hosted authentication, independent-review roles and tenant isolation | Not migrated; local single-user boundary |

A successful build or populated table is not evidence of full source workflow parity. The source-to-feature map records every extracted definition and route, with explicit exclusions and migration warnings. Test/build reports distinguish checked behavior from remaining work.

| Canonical feature | Native mode | Source entries | Calculators | Status |
| --- | --- | ---: | ---: | --- |
| Clients & customers | records | 0 | 0 | Native records/view |
| Work items & projects | records | 0 | 0 | Native records/view |
| Contacts & parties | records | 0 | 0 | Native records/view |
| Tasks | records | 0 | 0 | Native records/view |
| Calendar | records | 0 | 0 | Native records/view |
| Deadlines & reminders | records | 0 | 0 | Native records/view |
| Notes | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Documents | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Templates | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Invoices & billing | records | 0 | 0 | Native records/view |
| Time tracking | records | 0 | 0 | Native records/view |
| Messages & communications | records | 0 | 0 | Native records/view |
| Reports & analytics | report | 1 | 0 | Native records/view |
| Activity & audit trail | audit | 1 | 0 | Native records/view |
| Provider connections | integration | 1 | 0 | Provider request records only |
| Biobank Collection | records | 1 | 0 | Native records/view |
| Research Donor | records | 1 | 0 | Native records/view |
| Consent Version | records | 1 | 0 | Native records/view |
| Specimen | records | 1 | 0 | Native records/view |
| Freezer Location | records | 1 | 0 | Native records/view |
| Specimen Placement | records | 1 | 0 | Native records/view |
| Access Request | records | 1 | 0 | Native records/view |
| Specimen Access | records | 1 | 0 | Native records/view |
| Material Agreement | records | 1 | 0 | Native records/view |
| Operational Task | records | 5 | 0 | Native records/view |
| Rule Version | records | 5 | 0 | Native records/view |
| Document Requirement | records | 5 | 0 | Native records/view |
| Consent restriction extraction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Research purpose comparison | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Access packet completeness | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Storage discrepancy summary | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Withdrawal impact draft | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Material transfer agreement brief | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Evidence completeness review | records | 5 | 0 | AI question-and-answer workspace; records available as context |
| Operations handoff draft | records | 5 | 0 | AI question-and-answer workspace; records available as context |
| Milk Bank Program | records | 1 | 0 | Native records/view |
| Milk Donor | records | 1 | 0 | Native records/view |
| Milk Donation | records | 1 | 0 | Native records/view |
| Milk Pool | records | 1 | 0 | Native records/view |
| Pool Contribution | records | 1 | 0 | Native records/view |
| Pasteurization Run | records | 1 | 0 | Native records/view |
| Milk Lab Check | records | 1 | 0 | Native records/view |
| Milk Distribution | records | 1 | 0 | Native records/view |
| Milk Recall | records | 1 | 0 | Native records/view |
| Donor packet completeness | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Donation intake reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Pool traceability review | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Processing evidence summary | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Distribution exception draft | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Recall drill communication draft | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Forensic Case | records | 1 | 0 | Native records/view |
| Evidence Item | records | 1 | 0 | Native records/view |
| Custody Transfer | records | 1 | 0 | Native records/view |
| Examination Request | records | 1 | 0 | Native records/view |
| Lab Examination | records | 1 | 0 | Native records/view |
| Instrument Check | records | 1 | 0 | Native records/view |
| Technical Review | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Disclosure Packet | records | 1 | 0 | Native records/view |
| Evidence Disposition | records | 1 | 0 | Native records/view |
| Custody completeness review | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Examination request summary | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Method documentation gap check | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Analyst narrative organization | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Technical review response draft | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Disclosure packet index | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Procurement Case | records | 1 | 0 | Native records/view |
| Recovery Team | records | 1 | 0 | Native records/view |
| Authorized Shipment | records | 1 | 0 | Native records/view |
| Container | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Shipment Container | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Transport Leg | records | 1 | 0 | Native records/view |
| Telemetry Observation | records | 1 | 0 | Native records/view |
| Procurement Handoff | records | 1 | 0 | Native records/view |
| Logistics Incident | records | 1 | 0 | Native records/view |
| Authorized logistics brief | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Transport conflict review | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Container evidence summary | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Handoff chronology | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Delay escalation draft | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Case closeout narrative | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Tissue Bank Program | records | 1 | 0 | Native records/view |
| Tissue Donor | records | 1 | 0 | Native records/view |
| Tissue Recovery | records | 1 | 0 | Native records/view |
| Tissue Lot | records | 1 | 0 | Native records/view |
| Tissue Processing | records | 1 | 0 | Native records/view |
| Tissue Test | records | 1 | 0 | Native records/view |
| Quarantine Review | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Tissue Distribution | records | 1 | 0 | Native records/view |
| Tissue Adverse Event | records | 1 | 0 | Native records/view |
| Consent record extraction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Eligibility evidence gaps | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Processing packet comparison | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Quarantine review preparation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Distribution traceability review | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Adverse event chronology | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Donor Management | records | 1 | 0 | Native records/view |
| Donation Scheduling | records | 1 | 0 | Native records/view |
| Health Screening | records | 1 | 0 | Native records/view |
| Deferral Tracking | records | 1 | 0 | Native records/view |
| Blood Collection | records | 1 | 0 | Native records/view |
| Blood Typing & Testing | records | 1 | 0 | Native records/view |
| Component Processing | records | 1 | 0 | Native records/view |
| Inventory Management | records | 1 | 0 | Native records/view |
| Hospital Orders | records | 1 | 0 | Native records/view |
| Transportation | records | 1 | 0 | Native records/view |
| Adverse Reactions | records | 1 | 0 | Native records/view |
| Equipment Calibration | records | 1 | 0 | Native records/view |
| Staff Certifications | records | 1 | 0 | Native records/view |
| Mobile Drives | records | 1 | 0 | Native records/view |
| Donor Rewards | records | 1 | 0 | Native records/view |
| Eligibility | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Expiration | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Campaign | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Reengagement | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Forecast | records | 1 | 0 | AI question-and-answer workspace; records available as context |

Row popup verification passed: dashboard and feature rows, keyboard/focus, editing and persistence, delete confirmation/cancellation, centered mobile layout and full-record navigation. See `reports/row-popup-verification.json`.

## Verified local build

Build, API, browser and actual `start.sh` checks passed. All 115 feature pages were visited in the browser; 113 editable tables contain at least 15 fictional rows each. CRUD persistence and mobile layout were checked. Evidence is in `reports/verification.json`, `reports/browser-verification.json` and `reports/startup-verification.json`.

These checks cover the native local workspace. Full source-specific business rules, authentication and live provider operations remain incomplete as described above. Test servers were stopped after verification.

## AI workspace verification

All 44 AI feature routes were checked in the browser and show questions and formatted answers instead of the original record table. Existing records are retained as optional context. Questions, follow-ups, saved history across restart, Markdown tables, safe rendering, downloads, provider-failure recovery and mobile layout passed with a mocked provider. See `reports/ai-workspace-verification.json`.

Live answers require `OPENROUTER_API_KEY` and `OPENROUTER_MODEL` in this app's `.env` and an app restart. No live provider call was made during verification. Conversational answers do not execute unmigrated specialist engines, read record attachments automatically or perform external actions.


## AI word limits

Questions support up to 5,000 words with a live counter and server validation. AI responses and record drafts have a 16,000-token output budget and a default 180-second timeout to support answers up to 5,000 words; actual length depends on the request and model. Answers show their word count, and long questions can be expanded. Browser checks passed for 5,000-word questions and answers, saved history, full downloads, mobile layout and rejection of 5,001-word questions. See `reports/word-limit-verification.json` (mock-provider boundary checks).

## Merged AI assistants

44 original AI entries are now grouped into **6 assistants** in the sidebar. Choose up to 8 related capabilities and add up to 10 questions for one provider request and one saved response. Shared context is sent once; repeated questions are removed after trimming and whitespace/case normalization. The total question limit is 5,000 words and the combined answer target is up to 5,000 words.

Original feature URLs still open the appropriate assistant with that capability selected. Existing records and answers stay in place; the assistant history includes answers saved under its member features. Non-AI record tables retain their popup actions. This merges the assistant workflow and navigation; it does not implement previously missing external integrations or specialist engines. See `reports/assistant-merge-map.json` and `reports/assistant-merge-verification.json`.

## Floating Ask AI assistant

Implemented across this workspace. The bottom-right **Ask AI** button opens a persistent chat panel on every page. Use **Ask AI about item** in a row popup or record view, or **Use current item** inside the panel, to supply the selected record.

- Questions about the page, any explicitly chosen app record, and general topics.
- Formatted answers, comparison tables, follow-ups, copy and Markdown download.
- Conversation and question drafts stay intact during in-app navigation. Saved answers persist in SQLite; the last conversation restores in the same browser tab after reload. The latest 50 saved answers are listed; restoring one displays up to 20 turns. Up to four preceding turns are sent as AI context.
- Up to 5,000 input words and a response budget of up to 5,000 words. Output length remains dependent on the provider and the question.
- Page title and description are supplied automatically; record fields and notes are sent only for a selected item. Attachments and unselected records are not included. **New chat** starts without earlier conversation context.
- Existing AI provider configuration, timeout, rate limit and safe response renderer are reused. The assistant answers and drafts; it does not execute record changes or external actions.

Validation: shared backend tests, all 64 app builds/API checks, and all 64 browser checks passed with an injected test provider. Browser checks cover item context, navigation, saved history/reload, follow-ups, new-chat isolation, error recovery, word limits, keyboard controls, mobile bounds, safe Markdown rendering and attachment refresh. See [verification](reports/floating-ai-verification.json).
