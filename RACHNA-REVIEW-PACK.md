# CouncilFlow — partner review and validation pack

**Prepared for:** Rachna Sangwan / RS Consulting  
**Prepared by:** C51 Consulting  
**Review environment:** [CouncilFlow demonstrator](https://c51consulting.github.io/c51-gateway/)  
**Validation date:** 11 September 2026  
**State:** WORKING DEMONSTRATOR / SYNTHETIC DATA / COMMERCIAL MODEL FOR DISCUSSION

## 1. Purpose

CouncilFlow is a council-focused corporate reporting workflow designed to reduce manual collection, reconciliation and review of progress updates across fragmented business systems.

The demonstrator tests a practical workflow rather than claiming a completed council implementation. It uses fictional council, commitment, employee and performance data.

The proposed partnership is a white-label channel arrangement:

- RS Consulting introduces and manages suitable council relationships.
- C51 operates, configures and supports the technology.
- Each council engagement begins with workflow discovery and validation.
- Production integrations and delivery commitments are scoped only after the council's systems, controls and security requirements are known.

## 2. Problem hypothesis

Council corporate reporting frequently requires officers to collect updates from spreadsheets, project registers, finance systems, planning systems and other disconnected sources. Narrative progress claims may be late, unsupported or inconsistent with source evidence.

CouncilFlow provides a controlled path:

1. **Gather** structured updates and evidence references.
2. **Validate** reporting period, ownership and completeness.
3. **Reconcile** narrative claims against measures, milestones and evidence.
4. **Review** late, unsupported or inconsistent claims.
5. **Report** an approved executive view with a traceable decision record.

## 3. Demonstrated workflow

The current demonstrator includes:

- Corporate overview with delivery confidence, review volume, evidence gaps and material exceptions.
- Delivery commitments with owner, progress and status.
- Five-stage reporting workflow and current-cycle controls.
- Evidence register with source, date and review status.
- Evidence filtering for verified, review and missing states.
- Exception queue for missing approvals, contradictory results and overdue submissions.
- Review actions that record the requested follow-up state.
- Executive brief with outcome confidence and explicit approval decisions.
- Synthetic-data and illustrative-output notices.

## 4. Functional validation results

| Test | Action | Expected result | Observed result | State |
|---|---|---|---|---|
| Publication | Open the public review URL | Workspace loads over HTTPS | Page loaded with correct title and council overview | PASS |
| Primary navigation | Open each of the five workspace views | Selected view replaces the previous workspace content | Overview, workflow, evidence, exceptions and executive views all loaded | PASS |
| Reporting-stage traceability | Open Reporting workflow | Five controlled stages and cycle counts are visible | Gather, Validate, Reconcile, Review and Report displayed with record counts | PASS |
| Evidence filtering | Select Missing in the evidence register | Only missing evidence remains | EV-093 was isolated with source shown as Not supplied | PASS |
| Evidence review action | Select Review on the missing evidence row | Action records a visible review state | Control changed to Review recorded and became inactive | PASS |
| Exception routing | Request evidence for EX-014 | Follow-up state is visibly recorded | Control changed to Evidence requested and became inactive | PASS |
| Executive summary | Open Executive brief | Exceptions, evidence gaps and approval decision are consolidated | Three exceptions, five gaps and hold-approval decision displayed | PASS |
| Data anonymity | Review all visible records | No real council, employee or performance data appears | Fictional North Valley Regional Council and synthetic records used | PASS |

## 5. Workflow result

The demonstrator proves that the proposed user journey can:

- direct attention to reporting exceptions instead of requiring review of every update;
- connect a reported commitment to an evidence state;
- distinguish late, missing and contradictory information;
- record the action taken against an exception; and
- consolidate reviewed information into an executive decision view.

It does **not** yet prove automated data collection, integration with council systems, measured time savings, production security, multi-tenant isolation or deployment inside a council environment. Those require a real workflow, approved test data and technical discovery.

## 6. Questions for RS Consulting

Please assess the demonstrator against a real council reporting cycle:

1. Which reporting step causes the most chasing, re-keying or judgement?
2. Which systems and spreadsheets usually supply the source information?
3. Who submits, reviews and approves each quarterly update?
4. What evidence is required before a progress claim can be accepted?
5. Which exception types matter most to executives and Councillors?
6. What must appear in the final corporate or IP&R report?
7. What would a council need to see before sponsoring a paid proof?
8. Which one council or anonymised historical reporting pack could validate the workflow?
9. Should the initial product sit under the RS Consulting brand, a joint brand or the council's own brand?
10. Does the live Forbes service-review opportunity provide a suitable entry point, subject to its experience, referee, insurance and commercial gates?

## 7. Proposed paid validation path

### Stage 1 — workflow diagnostic

- One reporting workflow.
- Current-state map.
- Source and evidence inventory.
- Exception and approval rules.
- Production-readiness assessment.
- Indicative fee: **A$7,500 plus GST**.

### Stage 2 — configured proof

- One anonymised historical reporting cycle.
- Configured commitments, owners, measures and gates.
- Evidence and exception review.
- Executive output.
- Scope and price set after Stage 1.

### Stage 3 — council licence

Draft commercial anchors for discussion:

| Component | Indicative commercial position |
|---|---:|
| Configuration and onboarding | A$15,000 plus GST |
| Core council licence | A$4,950 per month plus GST |
| Larger council or multi-workflow licence | From A$7,950 per month plus GST |
| Custom integrations | Separately scoped |
| Initial licence term | 12 months |

No council price or delivery commitment is agreed until the workflow and technical requirements are validated.

## 8. Draft white-label channel model

- C51 retains the platform, source code, operating method and technical IP.
- RS Consulting receives a non-exclusive right to present the configured service under its brand.
- RS Consulting leads introductions and client relationships where agreed.
- C51 performs platform configuration, operation, technical delivery and support.
- RS Consulting retains fees for consulting work it performs.
- C51 retains fees for technical work, integrations and support it performs.
- Proposed partner share: **20% of net recurring licence revenue** for clients originated and actively managed by RS Consulting.
- Proposed referral share: **10% of net recurring licence revenue** for an introduction where C51 manages the opportunity and account.
- Revenue share applies only to collected licence revenue, excludes GST, refunds and third-party pass-through costs, and continues only while the council remains paid and the agreed partner role is performed.
- No exclusivity, minimum build obligation, source-code transfer or unfunded custom development is included.
- Final pricing, discounts, scope, service levels and contractual terms require written agreement.

## 9. Recommended next decision

Use the next discussion to select one real council reporting workflow and determine:

- the workflow owner and buyer;
- the operational consequence of the current manual process;
- the available historical evidence;
- the smallest credible paid validation;
- the preferred white-label presentation; and
- whether the opportunity gives both parties meaningful revenue, client access and strategic value.

**Current commercial state:** QUALIFIED PARTNER HYPOTHESIS / WORKFLOW DEMONSTRATED / BUYER AND PAID PROOF NOT YET CONFIRMED.
