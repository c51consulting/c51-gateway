# CouncilFlow — source-agnostic ingestion, notification and output model

**Prepared for partner workflow review**  
**State:** PROPOSED OPERATING ARCHITECTURE / NOT YET A PRODUCTION INTEGRATION

## 1. Role of the platform

CouncilFlow is designed to operate as an approved reporting and evidence overlay across existing council systems.

It does not require a council to replace its finance, planning, asset, records, project or customer systems. It receives approved snapshots and evidence from those systems, applies common reporting controls, and produces a traceable consolidated view.

“Source agnostic” means CouncilFlow works from standard information packages rather than depending on a particular vendor or mandatory API. Every production workflow still requires an approved transfer method, access control and data-retention decision.

## 2. API-independent intake options

A council can begin with one or more of these controlled channels:

| Intake route | Typical source | User action | Best use |
|---|---|---|---|
| Guided secure upload | CSV, XLSX, PDF, DOCX and image evidence | Officer selects the reporting period and uploads the approved file | Initial proof and low-volume reporting |
| Standard reporting workbook | Any system capable of spreadsheet export | Officer exports data into a controlled template | Repeatable quarterly submissions |
| Reporting inbox | Approved reports and evidence attachments | Officer sends or forwards material to a designated council address | Existing email-led reporting processes |
| Managed file drop | Approved network or cloud folder | Officer places the period snapshot in an agreed location | Recurring multi-team submissions |
| Structured web form | Narrative update, measure, milestone and evidence reference | Responsible officer completes required fields | Missing or inconsistent source structures |
| Batch evidence pack | Historical ZIP or document bundle | Reporting team submits one approved review pack | Diagnostic and retrospective validation |

Possible later connections—APIs, database views, SFTP, records-management connectors or approved workflow automation—are optional extensions. The initial value proposition does not depend on them.

## 3. Common intake contract

Each submitted item is normalised into the same control record:

- council and reporting period;
- strategic outcome, plan item or service commitment;
- responsible business unit and accountable owner;
- claimed status and progress;
- measure, milestone or narrative update;
- source system or document;
- evidence file or reference;
- submission timestamp and submitter;
- validation state;
- reviewer decision and reason;
- approval state and version.

This common contract allows different software inputs to be assessed through the same reporting workflow.

## 4. Processing controls

CouncilFlow applies the following sequence:

1. **Register** — record the source, reporting period, owner and submission time.
2. **Parse** — extract the submitted fields and evidence references.
3. **Validate** — check required fields, file type, period, owner and completeness.
4. **Match** — associate the update with the correct plan item, service, milestone and measure.
5. **Reconcile** — compare the narrative claim with the submitted evidence and prior period.
6. **Flag** — identify late, missing, unsupported or contradictory information.
7. **Review** — route the exception to an authorised reviewer.
8. **Approve** — retain the decision, reason, reviewer and approved version.
9. **Report** — generate the relevant operational, executive and public-reporting output.

The overlay does not silently change source-system records. It preserves the source snapshot and records how the consolidated conclusion was reached.

## 5. Human control and approval

The proposed control model is:

- Business-unit officers submit or confirm their updates.
- Reporting staff validate the source and resolve routine gaps.
- Accountable managers respond to exceptions.
- Authorised executives approve the consolidated reporting position.
- CouncilFlow records actions and decisions but does not replace delegated authority.

Automated classification or summarisation must remain reviewable. Low-confidence matches, contradictions and missing evidence are routed to a person rather than automatically accepted.

## 6. User notifications

Notifications are event-based and role-specific, avoiding generic broadcast noise.

### Responsible officer

- Submission due soon.
- Submission overdue.
- Required evidence missing.
- Clarification requested.
- Update returned for correction.
- Update accepted.

### Reporting team

- New submissions ready for validation.
- Failed or incomplete imports.
- Evidence and narrative conflict.
- Business unit remains overdue.
- Review queue approaching reporting deadline.

### Accountable manager

- Material exception requires decision.
- Repeated missed reporting obligation.
- Delivery status changed materially.
- Evidence remains unresolved after escalation.

### Executive or governance user

- Executive report ready for approval.
- Material risk or exception remains open.
- Approved report has changed.
- Final reporting pack available.

## 7. Notification channels

The first production version should support:

- in-application task and exception queue;
- configurable email notification;
- daily or weekly digest;
- reporting-cycle deadline summary;
- downloadable exception list.

Optional channels can be added only when approved:

- Microsoft Teams or Slack;
- council workflow/task platform;
- SMS for selected critical events;
- webhooks or system APIs.

Every notification should link to the relevant record, show why action is required, identify the due date and avoid exposing sensitive evidence in the message itself.

## 8. Outputs

CouncilFlow should produce audience-specific outputs from the same approved record set:

| Output | Audience | Format |
|---|---|---|
| Submission completeness view | Reporting team | Interactive dashboard and CSV/XLSX |
| Exception and evidence queue | Officers and managers | Dashboard, task list and email digest |
| Service or plan-item status | Service owner | Dashboard and PDF brief |
| Quarterly executive brief | Executive team | Dashboard, PDF and DOCX |
| Councillor reporting pack | Councillors | Approved PDF/DOCX pack |
| IP&R progress report | Governance/reporting team | Structured workbook, PDF/DOCX and machine-readable export |
| Evidence register | Internal audit and assurance | Filterable register and export |
| Decision and approval log | Governance and audit | Immutable audit-oriented export |
| Public-reporting extract | Community publication process | Approved, redacted export |

No public output is automatically published. It is generated as an approved export for the council’s existing publication process unless separate publication authority is configured.

## 9. Recommended initial proof

Use one anonymised historical quarterly reporting pack and no live system connection.

1. Agree the council’s standard commitment, owner, measure, evidence and approval fields.
2. Receive approved exports or documents through a secure upload.
3. Configure the common intake contract.
4. Reproduce the existing report.
5. Identify missing, overdue and contradictory records.
6. Compare the CouncilFlow output with the council’s completed reporting process.
7. Measure reporting effort, exception volume, rework and time to approval.

This proves workflow value before either party promises integrations or incurs material build cost.

## 10. Production decisions required

Before using live council information, confirm:

- data classification and permitted hosting location;
- identity, access and delegated approval rules;
- approved intake channels;
- file scanning and retention requirements;
- records-management obligations;
- privacy and redaction controls;
- audit-log retention;
- notification rules and escalation timing;
- output templates and publication controls;
- support, recovery and service-level requirements.

## 11. Partner proposition

RS Consulting can lead workflow discovery, council relationships, IP&R interpretation and client management. C51 can configure and operate the technical overlay, normalisation controls, evidence workflow, reporting views and support.

The commercial offer is therefore an approved reporting service layered across the council’s existing tools—not a forced software replacement and not an unfunded custom integration project.

**Current evidence state:** the demonstrator proves the interface and review journey. Source ingestion, notifications, persistent records and production outputs remain specifications until implemented and validated with an approved test pack.
