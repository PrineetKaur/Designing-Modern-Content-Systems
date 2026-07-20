# AI Tone Consistency Checker Examples

### Content Layer: AI Content Infrastructure

Each example below shows a grounded evaluation scenario, the original content, what the evaluation flagged, the corrected version, and why it works — citing the specific prompt from `prompts.md` applied.

---

## Example 1 — Overconfident AI Recommendation

### Scenario

An AI assistant in WorkflowOS surfaces a workflow-optimization suggestion to a team lead, framed with unqualified certainty about its impact.

### Original Content

> This workflow is guaranteed to improve performance.

### Evaluation Findings

| Issue | Risk |
|---|---|
| exaggerated certainty | trust erosion |
| unsupported claim | compliance risk |
| missing limitation framing | unrealistic expectations |

### Improved Content

> This recommendation is based on recent workflow activity and may improve task completion efficiency depending on current team usage patterns.

### Why It Works
*Prompt applied: AI Disclosure Validation Prompt*

It replaces an absolute guarantee with a scoped, evidence-based claim, directly addressing the prompt's checks for misleading certainty and realistic trust expectations.

---

## Example 2 — Robotic Escalation Messaging

### Scenario

An automated incident notification is evaluated after being sent to customers during the EU-region scheduled-export delay already governed under the Product Communication Governance System.

### Original Content

> Incident processing failure detected.

### Evaluation Findings

- emotionally detached
- lacks operational guidance
- unclear customer impact

### Improved Content

> Scheduled exports are delayed for approximately 15% of EU-hosted workspaces. Existing export requests remain queued and no customer data has been lost.

### Why It Works
*Prompt applied: Incident Communication Review Prompt*

It replaces detached system language with a scoped impact figure and a direct reassurance on data integrity — the calm, actionable, transparent behavior the prompt evaluates for. This matches the incident communication already established and audited elsewhere in this repo.

---

## Example 3 — Hidden AI Behavior

### Scenario

An automated task-routing change is applied to a workspace without the admin being told it was AI-generated.

### Original Content

> Your workflow has been updated.

### Evaluation Findings

- hidden automation
- lacks transparency
- unclear workflow ownership

### Improved Content

> Workflow recommendations were generated automatically using recent task activity. Review suggested updates before publishing changes.

### Why It Works
*Prompt applied: AI Disclosure Validation Prompt*

It discloses the automation and sets a review expectation, directly resolving the flagged risks. This is the same AI transparency standard already established and audited elsewhere in this repo.

---

## Example 4 — Tone Drift Across Channels

### Scenario

The same export failure is evaluated as it appears across two channels — product UI and email — to check whether tone stays consistent.

### Product UI

> We couldn't complete your export.

### Email Notification

> Oops! Something weird happened.

### Evaluation Findings

- inconsistent trust behavior
- unstable escalation tone
- fragmented customer experience

### Improved Standard
*Prompt applied: AI Drift Detection Prompt*

> We couldn't complete the export because the selected report exceeds the current file size limit. Reduce the export range and try again.

### Why It Works

Applying one shared standard across both channels removes the tonal gap between a terse UI message and an overly casual email — this is the same error-recovery standard already established and templated elsewhere in this repo, now confirmed consistent across channels.

---

## Example 5 — Multilingual Tone Drift

### Scenario

An AI recommendation message is compared against its localized version to check whether the review-required framing survived translation.

### English

> Review recommendations before activation.

### Localized Version

> Changes will automatically improve performance.

### Evaluation Findings

- misleading certainty
- inconsistent user agency
- localization governance failure

### Corrected Localization
*Prompt applied: Multilingual Tone Evaluation Prompt*

> Review suggested updates before activation.

### Why It Works

The localized version had dropped the review requirement entirely, introducing false certainty the English source never had. The correction restores the same user-agency framing across languages, which is exactly what the prompt checks for.

---

## System Thinking Insight

These examples demonstrate how mature organizations operationalize:

- AI-assisted editorial governance
- measurable tone evaluation
- behavioral consistency infrastructure
- multilingual trust alignment
- scalable communication quality systems

The goal is stable communication behavior across complex AI-enabled ecosystems.
