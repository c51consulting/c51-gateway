# Council Reporting Studio — Rachna partner POC pack

**Prepared for:** Rachna Sangwan / RS Consulting  
**Prepared by:** C51 Consulting  
**Live POC:** https://c51consulting.github.io/c51-gateway/  
**Validation date:** 11 September 2026  
**State:** WORKING BROWSER POC / SYNTHETIC DATA / PARTNER REVIEW

## Why this exists

This POC was built from the council reporting problems discussed with Rachna: fragmented source systems, manual spreadsheet collection, repeated chasing, weak evidence traceability and corporate reporting tools that do not give reviewers a reliable view of what needs judgement.

It demonstrates an approved reporting overlay across existing council software. It does not require source-system replacement or an API connection for the initial workflow.

## The demonstrated product loop

1. Load a standard council reporting CSV from any existing system export.
2. Normalise commitments, owners, progress, evidence and measures.
3. Compare reported status with evidence and target results.
4. Identify missing, stale and contradictory information.
5. Create role-aware notifications and a focused review queue.
6. Record reviewer action and preserve it in the browser.
7. Refresh the executive brief and exception schedule.
8. Download review data and an audit-oriented record.
9. Print or save the executive output as PDF.
10. Preview the product under a partner-selected white-label name.

## Working capabilities

- Real CSV file selection and drag-and-drop intake.
- One-click synthetic example import.
- Required-column validation and clear import errors.
- Automatic normalisation into a common reporting record.
- Rule-based detection of missing evidence, unsupported completion, reported-measure conflicts and stale evidence.
- Persistent imported records, review actions and partner branding using browser storage.
- Role selector for reporting team, responsible officer, manager, executive approver and partner adviser.
- Notification centre generated from current exceptions.
- Evidence and exception filters.
- Review-decision recording.
- Dynamic reporting-cycle counts and executive narrative.
- Downloadable CSV review register.
- Downloadable JSON audit record.
- Downloadable executive exception CSV.
- Print and save-to-PDF executive output.
- Responsive desktop and mobile layout.
- Synthetic-data and capability-boundary notices.

## Functional test results

| Test | Observed result | State |
|---|---|---|
| Public HTTPS deployment | Live product loaded with current release | PASS |
| Navigation | Six product views opened correctly | PASS |
| Sample ingestion | Six records loaded from the supplied CSV | PASS |
| Automatic analysis | Four material exceptions and one evidence gap identified | PASS |
| Measure reconciliation | On-track claim below target was flagged | PASS |
| Stale evidence | Old evidence in the imported record was flagged | PASS |
| Notification generation | Six actionable notifications were created and routed by owner | PASS |
| Review action | Selected exception changed to Review and Review recorded | PASS |
| Persistence | Imported data, review state and branding are stored in the browser | PASS |
| White-label preview | Product changed from Council Reporting Studio to RS Council Reporting | PASS |
| Executive output | Dynamic narrative, decision state and exception schedule rendered | PASS |
| Export controls | CSV, JSON, executive CSV and print/PDF controls are available | PASS |
| Data anonymity | Only fictional council and synthetic operational records are used | PASS |

## What the POC establishes

The product can accept a familiar tabular reporting export and turn it into:

- normalised council commitments;
- evidence and exception controls;
- role-aware actions;
- an executive reporting position; and
- downloadable review and audit outputs.

This demonstrates the product workflow and gives RS Consulting something concrete to test against council practice.

## Honest production boundary

The POC runs in the browser and stores its state on the reviewing device. It does not yet provide hosted multi-user accounts, production database storage, real email delivery, council identity integration, document extraction, live source-system automation or certified council security controls.

Those capabilities should be implemented only after one council workflow, approved test pack, access model and hosting requirements are confirmed.

## Current data entry and customisation

The live POC accepts a correctly structured CSV through file selection or drag-and-drop. Rachna can load the synthetic example, review records and exceptions, record review decisions, change the white-label product name and export review and executive outputs.

The current POC does not include an on-screen form for manually creating or editing individual reporting records. Manual data entry is therefore a configurable proof or production feature, not a current operational capability.

For each selected use case, the operating flow can be configured around the actual council process, including:

- record types, field names and service categories;
- manual forms, CSV templates and approved intake channels;
- draft, submission, evidence-request, review, approval and closure stages;
- council roles, owners and decision rights;
- evidence requirements, currency thresholds and exception rules;
- severity, due dates and escalation paths;
- in-product, email or Teams notifications;
- executive briefs, IP&R outputs, service-review packs, registers and audit exports; and
- RS Consulting, joint or council branding and terminology.

Customisation should be agreed during the paid workflow diagnostic. This preserves a reusable product core while configuring the workflow around a defined council problem.

## Source-agnostic operating model

The initial production service can work without APIs through:

- approved CSV or spreadsheet exports;
- secure upload;
- standard reporting templates;
- a designated reporting inbox;
- controlled file drops;
- structured officer submissions; or
- an anonymised historical reporting pack.

Optional APIs and system connectors can be added later where approved and commercially justified.

## Review questions for Rachna

1. Which existing council report should this reproduce first?
2. Which sources create the most chasing and re-keying?
3. Who submits, reviews and approves the reporting position?
4. Which exception rules matter most?
5. What evidence is required before a claim is accepted?
6. Which council could provide one anonymised historical pack?
7. Would the white-label offer be easier to sell under RS Consulting, a joint identity or the council's brand?
8. Who owns the budget for a paid diagnostic?

## Commercial validation path

### 1. Paid workflow diagnostic

One reporting workflow, current-state map, source inventory, approval rules and production-readiness assessment.

**Indicative anchor:** A$7,500 plus GST.

### 2. Configured proof

One approved historical reporting cycle, configured fields and exception rules, evidence review and agreed executive output.

Pricing follows diagnostic findings.

### 3. Annual council service

Indicative starting position:

- configuration and onboarding: A$15,000 plus GST;
- core licence: A$4,950 per month plus GST;
- multi-workflow or larger-council licence: from A$7,950 per month plus GST;
- custom integrations and specialist delivery: separately scoped.

## Proposed partner model

- RS Consulting leads suitable introductions, workflow interpretation and council relationships.
- C51 configures, operates and supports the technology.
- C51 retains the platform, source code and technical IP.
- RS Consulting can present the configured service under an agreed white-label identity.
- Proposed share for a client originated and actively managed by RS Consulting: 20% of collected net recurring licence revenue.
- Proposed introduction-only share where C51 manages the opportunity: 10% of collected net recurring licence revenue.
- Each party retains fees for the consulting or technical work it performs.
- No exclusivity, source-code transfer or unfunded custom development.
- Final price, scope, service levels and partner terms require written agreement.

## Recommended next meeting outcome

Select one real reporting workflow and one approved historical evidence pack. Confirm the buyer, current operating burden, source formats, approval path and smallest paid proof.

**Commercial state:** WORKING POC / PARTNER FIT TO VALIDATE / NO COUNCIL CUSTOMER, PAID PROOF OR PRODUCTION DEPLOYMENT YET.
