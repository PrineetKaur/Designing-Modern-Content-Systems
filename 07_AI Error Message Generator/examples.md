# AI Error Message Generator Examples

### Content Layer: AI Content Infrastructure

Each example below shows a grounded failure scenario, the original content, what a review flagged, the generated fix, and why it works — citing the specific prompt from `prompts.md` used to generate it.

---

## Example 1 — Export Failure

### Scenario

An Enterprise workspace owner's scheduled report export fails because the report exceeds the platform's file size limit.

### Original Content

> Upload failed.

### Evaluation Findings

- names the wrong action (upload vs. export)
- no cause given
- no recovery step

### Improved Content
*Prompt applied: Export Failure (Structured Recovery Prompt Variation)*

> We couldn't complete the export because the selected report exceeds the current file size limit. Reduce the export range and try again.

### Why It Works

It names the actual failing action, explains the cause, and gives a concrete recovery step — the three things the Export Failure prompt requires. This is the same export-failure standard already established and reused as a reusable template elsewhere in this repo; this is its point of origin as a generated message.

---

## Example 2 — Hidden AI Failure

### Scenario

WorkflowOS's AI recommendation engine can't generate suggestions because recent workflow activity data is temporarily unavailable, and the admin needs to know whether to wait or proceed manually.

### Original Content

> Recommendation unavailable.

### Evaluation Findings

- doesn't disclose this is an AI-dependent feature
- no explanation for why
- no path forward

### Improved Content
*Prompt applied: AI Recommendation Failure (Structured Recovery Prompt Variation)*

> We couldn't generate recommendations because recent workflow activity is unavailable right now. Try again later or continue manually.

### Why It Works

It discloses that the feature depends on recent activity data, explains the unavailable state honestly, and preserves the user's ability to continue without the AI feature — satisfying the prompt's requirement to disclose AI dependency and support manual continuation.

---

## Example 3 — Enterprise Escalation

### Scenario

The same EU-region scheduled-export delay already governed under the Product Communication Governance System and reviewed under the Content Audit + Fix System needs a generated escalation-severity message.

### Original Content

> System unavailable.

### Evaluation Findings

- no impact scope
- no reassurance on data integrity
- alarmist without being informative

### Improved Content
*Prompt applied: Escalation Messaging Prompt*

> Scheduled exports are delayed for approximately 15% of EU-hosted workspaces. Existing export requests remain queued and no customer data has been lost.

### Why It Works

It scopes the impact with a real figure and directly addresses data integrity, satisfying the prompt's requirement for realistic expectations without panic escalation. This matches the incident communication already established elsewhere in this repo.

---

## Example 4 — Poor Recovery Guidance

### Scenario

A customer with no technical background hits a failed sign-in and needs a clear, non-alarming next step.

### Original Content

> Authentication failed.

### Evaluation Findings

- technical framing
- no recovery step
- no escalation path if the issue continues

### Improved Content
*Prompt applied: Authentication Failure (Structured Recovery Prompt Variation)*

> We couldn't verify your sign-in request. Try signing in again or contact your workspace administrator.

### Why It Works

It replaces technical jargon with plain language and gives a concrete next step without disclosing security-sensitive detail — satisfying the prompt's requirement to preserve calm and trust. This is the same accessibility fix already established and audited elsewhere in this repo.

---

## Example 5 — Localization Risk

### Scenario

A generic connection-failure message is reviewed for multilingual readiness before being shipped across regions.

### Original Content

> Something weird happened.

### Evaluation Findings

- unclear meaning
- poor translation quality
- inconsistent tone

### Improved Content
*Prompt applied: Localization Governance Prompt*

> We couldn't complete the request because the connection was interrupted. Check your network connection and try again.

### Why It Works

It replaces vague, idiomatic phrasing that translates poorly with a literal, unambiguous description of the failure and a concrete recovery step — directly addressing the prompt's checks for translation ambiguity and recovery clarity.

---

## System Thinking Insight

These examples demonstrate how mature organizations operationalize:

- AI-assisted recovery-oriented error generation
- consistent AI disclosure during failure states
- severity-appropriate escalation messaging
- localization-ready error structures
- scalable, trustworthy failure communication

The goal is recovery infrastructure, not isolated interface copy.
