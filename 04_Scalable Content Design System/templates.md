# Scalable Content Design System Templates

### Content Layer: Shared Principles & Governance

Each template below shows its reusable structure, the scenario it applies to, a filled-in example, and why the structure works. Several of these templates are the reusable source of fixes already applied in this repo's other systems — noted where relevant.

---

## Template 1 — AI Error Recovery Template

### Scenario

Applies whenever a WorkflowOS action fails partway through — for example, a report export blocked by a size limit — and the user needs to understand what happened and how to continue.

### Structure

| Component | Purpose |
|---|---|
| What happened | explain issue clearly |
| Why it happened | reduce ambiguity |
| Recommended next step | support recovery |
| Escalation guidance | maintain workflow continuity |

### Example

> We couldn't complete the export because the selected report exceeds the current file size limit. Reduce the export range and try again.

### Why It Works

Each structure component maps directly onto the filled example: the failure is named, the cause is explained, and a concrete next step is given. This is the same reusable pattern behind the fix validated in the Content Audit + Fix System's Error Recovery Audit.

---

## Template 2 — AI Recommendation Template

### Scenario

Applies to any WorkflowOS surface where AI generates a suggestion — workflow routing, task assignment — that requires a human decision before it takes effect.

### Structure

| Component | Purpose |
|---|---|
| Recommendation source | explain context |
| AI limitation framing | avoid false certainty |
| User review expectation | preserve agency |

### Example

> This recommendation is based on recent workflow activity and requires admin review before activation.

### Why It Works

It names the source of the recommendation and sets an explicit review expectation, satisfying the AI Governance Alignment rule against misleading certainty. This is the same pattern behind the fix validated in the Content Audit + Fix System's AI Recommendation Audit.

---

## Template 3 — Empty State Template

### Scenario

A new workspace with no automations configured yet; the admin needs direction on how to get started rather than a bare "nothing here" screen.

### Structure

| Component | Purpose |
|---|---|
| Explain absence | reduce confusion |
| Suggest next step | support workflow initiation |
| Reinforce product value | improve adoption |

### Example

> You haven't created any automations yet. Start with a workflow template or describe a repetitive task for the assistant to help automate.

### Why It Works

It explains why the space is empty, gives a concrete starting action, and frames that action in terms of product value — reducing the chance a new user abandons the workflow before starting.

---

## Template 4 — Incident Communication Template

### Scenario

Applies to operational incidents affecting a subset of workspaces — such as the EU-region scheduled-export delay already governed in the Product Communication Governance System and reviewed in the Content Audit + Fix System.

### Structure

| Component | Purpose |
|---|---|
| Impact scope | clarify operational effect |
| Workflow status | explain current state |
| Resolution status | reduce uncertainty |
| Trust reinforcement | preserve confidence |

### Example

> Scheduled exports are delayed for approximately 15% of EU-hosted workspaces. Existing requests remain queued and no customer data has been lost.

### Why It Works

It scopes the impact with a real figure and reinforces data integrity, matching the same incident communication standard already established elsewhere in this repo. Keeping the figure consistent here closes the loop on that recurring scenario across all three layers.

---

## Template 5 — Onboarding Guidance Template

### Scenario

A new Enterprise admin's first onboarding step in WorkflowOS — the same moment already governed by the Product Communication Governance System's Lifecycle Messaging Framework and confirmed in the Content Audit + Fix System's Onboarding Clarity Audit.

### Structure

| Component | Purpose |
|---|---|
| Workflow orientation | explain product behavior |
| AI assistance explanation | improve trust |
| User enablement | support successful onboarding |

### Example

> Welcome to WorkflowOS. Start by connecting your existing project tools to enable automated task recommendations and approval routing.

### Why It Works

It orients the admin toward one specific first action tied to real product value. This template is the reusable source of the onboarding pattern already applied and audited elsewhere in this repo.

---

## Template Governance Rules

Templates should:

- preserve terminology consistency
- avoid false certainty
- maintain accessibility
- support localization readiness
- align with AI governance standards
- reduce workflow ambiguity

---

## Operational Usage

Teams should:

- adapt templates to workflow context
- avoid unnecessary customization
- preserve governance structures
- maintain trust patterns
- validate localization compatibility
