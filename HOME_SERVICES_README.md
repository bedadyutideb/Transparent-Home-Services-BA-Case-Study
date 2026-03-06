# 🏠 Transparent Construction & Home Services Platform — BA Case Study

## Business Problem Statement
India's residential construction and home services market is largely informal and fragmented. Homeowners rely on unverified local providers through word-of-mouth and phone calls, resulting in pricing opacity, inconsistent quality, and zero accountability. This case study was initiated to answer three core business questions:
- How can pricing transparency and scope standardization be introduced into an informal market?
- What system design would ensure contractor accountability and protect customer payments?
- How can a platform scale a trust-based service model across Indian cities?

---

## Project Overview
A complete end-to-end Business Analysis case study for a conceptual on-demand home services platform targeting India's residential construction and repair market. The project covers the full BA lifecycle — from problem identification and stakeholder analysis through to requirements documentation, process design, and success measurement.

| Artifact | Description |
|----------|-------------|
| Executive Summary | Business context, problem statement, objectives, and KPIs |
| Stakeholder Analysis | Stakeholder identification, roles, pain points, and influence-interest mapping |
| BRD | Business requirements, AS-IS vs TO-BE, assumptions, risks, and success criteria |
| FRD | Functional requirements across 5 actor modules with system rules and NFRs |
| User Stories | 6 user stories with acceptance criteria across 3 epics |
| Process Flow | AS-IS pain points and TO-BE improvements documented |
| BPMN Diagram | End-to-end service booking and delivery flow across 5 swimlanes |

---

## 🔍 Problem Identified

### Current State (AS-IS)
The existing home services market suffers from:
- Verbal quotations with no standardized pricing or Bill of Quantities (BOQ)
- Untrained, unverified labour with no accountability mechanism
- Cash-based informal payments with no dispute resolution
- No documentation of work scope, progress, or completion
- High rates of cost overruns, rework, and customer disputes

### Future State (TO-BE)
The proposed platform addresses each pain point through:
- Digital BOQ-based estimates with itemized labour and material breakup
- Trained, uniformed service teams following standardized SOPs
- Escrow-based milestone payments released only after customer approval
- Photo-documented execution with before/after evidence
- Real-time job tracking and structured feedback collection

---

## 👥 Stakeholders Identified

| Stakeholder | Role | Key Pain Point |
|-------------|------|----------------|
| Business Owner / Product Sponsor | Vision & approval | Limited performance data |
| Operations Manager | Daily service oversight | Manual coordination, no real-time visibility |
| Service Partners | On-ground execution | Irregular demand, unclear job assignments |
| End Customers | Service requestors | Last-minute cancellations, lack of trust |
| Customer Support Team | Issue resolution | High manual follow-ups, incomplete information |
| Data & Analytics Team | Insights & reporting | Inconsistent data capture, no measurable KPIs |

**Influence-Interest Classification:**
- High Influence / High Interest: Business Owner, Operations Manager
- Medium Influence / High Interest: Service Partners
- Low Influence / High Interest: End Customers

---

## 📋 Requirements Summary

### Business Requirements (BRD)
| Requirement | Description |
|-------------|-------------|
| BR-1 | Requirement Standardization — Convert customer needs into standardized scopes of work |
| BR-2 | Transparent Estimation — Generate itemized estimates showing labour and material breakup |
| BR-3 | Skilled Execution — Services delivered by trained teams following SOPs |
| BR-4 | Scheduling & Tracking — Allow scheduling, tracking, and documentation of work |
| BR-5 | Controlled Payments — Milestone-based payments released only after customer approval |
| BR-6 | Accountability & Records — Retain records of work, costs, and performance |

### Functional Modules (FRD)
- **Customer Module** — Registration, service selection, BOQ review, escrow payment, job tracking, approvals, and ratings
- **Worker Module** — Profile management, job assignment, task checklists, photo documentation, milestone submission
- **Supervisor Module** — BOQ compliance verification, quality checks, change request initiation
- **Operations Module** — Job monitoring dashboard, SLA tracking, dispute resolution, payment release
- **System Rules** — BOQ locking post-approval, audit trail for all cost changes and approvals

---

## 📖 User Stories

### Epic 1: Booking & Estimation
- **Customer** — Review auto-generated BOQ with locked itemized pricing
- **Supervisor** — Approve or reject BOQ before customer payment is collected

### Epic 2: Job Execution & Trust
- **Worker** — Upload before/after photos as mandatory proof before milestone completion
- **Customer** — Payment held in escrow and released only upon customer approval

### Epic 3: Exception Handling
- **Worker/Supervisor** — Flag extra work via formal Change Request without stalling the project
- **Ops Team** — Monitor SLA compliance and intervene when milestone approvals exceed 24 hours

---

## 🔄 BPMN Process Flow

The BPMN diagram covers the end-to-end service booking and delivery lifecycle across 5 swimlanes:

1. **Customer** — Service need identification, service selection, slot booking, service confirmation, and feedback
2. **Platform System** — Booking validation, partner availability check, auto-assignment, and notifications
3. **Service Partner** — Job acceptance, travel, service execution, and status update
4. **Customer (Return)** — Service completion confirmation and rating submission
5. **Operations/Support** — Continuous job status monitoring and escalation handling

---

## 📌 Business Recommendations

Based on the analysis and requirements defined in this case study:

1. **Launch with a limited service catalog (Phase 1)** — Restrict initial scope to minor civil works (plumbing, electrical) and modular renovations. This reduces operational complexity and allows quality control before scaling.

2. **Prioritise Tier-2 and Tier-3 city adoption** — Assumptions indicate faster digital adoption in smaller cities where the informal market gap is largest and competition from organized players is lowest.

3. **Invest in worker training before platform launch** — The platform's value proposition depends entirely on service quality. Launching with untrained workers would replicate the existing problem and damage trust early.

4. **Use escrow as a marketing differentiator** — Payment protection is the most tangible trust signal for a first-time customer. Lead all customer-facing communication with this feature.

5. **Build the Operations Dashboard as a Day 1 priority** — Without real-time job visibility, the Ops team cannot intervene in delays or disputes. This is the internal backbone of the entire platform.

---

## 📊 Success Metrics (KPIs)

| Metric | Target |
|--------|--------|
| Completed jobs (MVP) | ≥ 50 jobs |
| Cost variance | ≤ 5% from BOQ estimate |
| Average customer rating | ≥ 4.2 / 5.0 |
| Rework rate | ≤ 10% |
| Repeat usage intent | ≥ 30% |
| Booking-to-cancellation rate | < 10% |
| Manual coordination time reduction | 60% via automation |

---

## ⚠️ Key Risks & Mitigation

| Risk | Impact | Mitigation |
|------|--------|------------|
| Labour attrition | High | Better pay, dignity, and career growth path |
| Cost variance from BOQ | High | Strict BOQ enforcement and locked estimates |
| Customer distrust | High | Escrow payments + photo documentation |
| Ops overload at scale | Medium | Limited MVP scope with manual override options |
| Legal disputes | Medium | Clear Terms & Conditions and audit trail |

---

## 🛠️ Tools & Techniques Used

- Business Requirements Document (BRD)
- Functional Requirements Document (FRD)
- User Stories with Acceptance Criteria
- BPMN 2.0 Process Diagram
- AS-IS / TO-BE Process Mapping
- Stakeholder Analysis with Influence-Interest Matrix
- MoSCoW-aligned scope definition (In-Scope / Out-of-Scope)

---

## 📝 Scope

**In Scope (Phase 1)**
- Minor civil works: Plumbing, Electrical
- Modular renovations: Kitchen, Bathroom
- Standardized city-wise rate cards and BOQ transparency
- Milestone-based escrow payments
- Digital photo validation and quality checklists

**Out of Scope (Phase 1)**
- Greenfield construction or structural expansion
- Government permits or regulatory approvals
- B2B, commercial, or government infrastructure projects
- AI-based cost forecasting or automated resource allocation
- Multi-currency support

---

## 👤 Author
**Bedadyuti Debnath**
BA Case Study — Conceptual Project | January 2026
