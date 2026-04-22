# Governance

Governance gets built too late or too heavy. Too late means an incident forces the conversation — a biased output, a data breach, a regulatory inquiry. Too heavy means a review process so burdensome that teams route around it, and the governance exists on paper while the real decisions happen elsewhere.

The goal is governance that scales: lightweight enough to move fast on low-risk applications, rigorous enough to earn trust on high-stakes ones. Change management determines whether governance becomes an enabler or a blocker. How it is introduced, who owns it, and how consistently it is applied all shape whether the organisation treats it as protection or bureaucracy.

---

## Framework 1: The AI Risk Tiering Model

Not all AI use cases carry the same risk. Treating them identically creates bottlenecks without proportionate safety benefit.

| Tier | Type | Description | Example |
|---|---|---|---|
| Tier 1 | Assistive | AI augments human decision-making. Human reviews every output before action. | AI-drafted customer email reviewed by an agent before sending |
| Tier 2 | Automated with Override | AI makes decisions within defined parameters. Humans can intervene but are not in the loop by default. | AI-powered claims triage that flags edge cases for human review |
| Tier 3 | Autonomous | AI acts without human review within its operational boundary. Highest governance bar. | Real-time fraud detection that blocks transactions automatically |

Map every AI use case to a tier before development begins. The tier determines the approval pathway, the monitoring requirements, and the rollback protocol.

**Change management lens:** Resistance to governance is usually resistance to ambiguity. People do not know what will be reviewed, who will review it, or how long it will take — so they avoid the process. Publishing clear tier criteria eliminates that ambiguity and makes compliance the path of least resistance.

---

## Framework 2: The AI Decision Rights Matrix

A governance RACI adapted for AI programmes. Four roles that need to be explicitly assigned, not assumed.

| Role | Definition |
|---|---|
| Accountable (A) | The executive who owns the outcome and the risk. One person per use case — no joint accountability. |
| Responsible (R) | The team building and operating the AI system day-to-day. |
| Consulted (C) | Legal, risk, compliance, and domain experts whose input is required before deployment. |
| Informed (I) | Stakeholders who need visibility but do not have decision rights. |

The most common governance failure is an accountability gap at the top. Technical teams build something, nobody owns the risk explicitly, and when something goes wrong the post-mortem reveals that everyone assumed someone else was accountable.

**Change management lens:** Decision rights clarity is a prerequisite for psychological safety. People take more considered risks when they know who has the authority to approve them — and when accountability is distributed fairly, not dumped on the team lowest in the hierarchy.

---

## How to Apply

**Introduce the tiering model early, before the use case pipeline gets crowded.** Once twenty use cases are in flight without a tiering framework, retrofitting it becomes a political exercise. Getting it in place when the programme is small means it becomes habit before it becomes friction.

**Run a known unknowns review with Legal and Risk before they are needed for approvals.** Bringing governance partners in as advisors during the strategy phase — rather than gatekeepers during the approval phase — fundamentally changes the relationship. They become part of the design, not a barrier to it.

**Make the RACI visible and revisit it quarterly.** Accountability decays. People change roles. Use cases expand scope. A RACI that was accurate at launch may be dangerously wrong eighteen months later.

**Frame governance as a competitive advantage, not a constraint.** Organisations that can demonstrate responsible AI practices move faster with regulators, earn more trust from customers, and attract talent that cares about working ethically. That framing shift matters for internal adoption.
