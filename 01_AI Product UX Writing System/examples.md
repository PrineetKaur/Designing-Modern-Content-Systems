# AI Product UX Writing System — Examples

### Content Layer: In-Product Experience

---

# How to Read These Examples

Each example follows this structure:

**Scenario:** The product context, user type, and situation that triggered the content decision.

**Without System Prompt:** Copy written without using this system's prompt infrastructure. This is the kind of output you'd get from ad-hoc writing, a generic AI generation, or a first draft with no framework applied.

**With System Prompt:** Copy produced using the relevant prompt from `prompts.md`, with the system's principles applied: clarity, trust framing, recovery guidance, and tone standards.

**Why It Works:** The specific content design decisions that make the second version stronger.

---

# Example 1 — AI Copilot Entry Point

**Scenario:** A B2B project management platform has launched an AI copilot that helps operations managers automate repetitive task assignments. This is the placeholder copy shown inside the copilot input field when a user opens it for the first time.

*Prompt used: Prompt 5 — AI Onboarding Flow Generator*

---

**Without System Prompt**

> Ask me anything.

---

**With System Prompt**

> Describe a repetitive task your team handles manually, like assigning weekly reports or routing approvals. The assistant will suggest automation steps for you to review before anything is activated.

---

**Why It Works**

The original provides the user with no frame of reference for what the AI can or should do, which either leads to off-topic inputs or to complete non-use. The revised version names a specific use case to orient the user, signals that the AI *suggests* rather than *acts*, and makes human review explicit, reducing first-use anxiety for enterprise users who are accountable for workflow changes.

---

# Example 2 — AI Recommendation Transparency

**Scenario:** A B2B analytics platform surfaces a recommended pricing tier to a sales rep based on a customer's usage data. The recommendation appears in a sidebar card during account review.

*Prompt used: Prompt 3 — AI Trust Pattern Generator*

---

**Without System Prompt**

> Recommended action available.

---

**With System Prompt**

> Based on this account's usage over the last 90 days, the Growth tier may be a better fit. This suggestion updates automatically as usage data changes — review before presenting to the customer.

---

**Why It Works**

The original creates a black-box recommendation with no source, no confidence framing, and no instruction, leaving the rep to either ignore it or act on it blindly. The revised version names the data source, qualifies the suggestion, signals that it's dynamic, and prompts human review before the recommendation reaches a customer. This is especially important in enterprise sales contexts where the rep's credibility is on the line.

---

# Example 3 — AI Error Recovery

**Scenario:** A user on a B2B content platform uploads an Excel file to an AI summarization feature that only supports PDF and DOCX. It's their first time using the feature. The error message appears immediately after upload.

*Prompt used: Prompt 2 — AI Error Message Generator*

---

**Without System Prompt**

> Something went wrong.

---

**With System Prompt**

> We couldn't generate a summary because Excel files aren't supported. Upload a PDF or DOCX version of this file and try again. If you need help converting the file, visit the Help Center.

---

**Why It Works**

The original tells the user nothing actionable (no cause, no next step, no path forward). Most users in this situation either retry the same action or abandon the workflow entirely. The revised version names the specific cause (Excel isn't supported), gives a concrete fix (convert and re-upload), and adds an escalation path for users who don't know how to convert. The result is continued workflow rather than abandonment.

---

# Example 4 — Empty State Guidance

**Scenario:** A new user lands on the Automations dashboard of a B2B operations platform for the first time. They have no automations yet. This is the state they see before any interaction has occurred.

*Prompt used: Prompt 4 — Empty State UX Generator*

---

**Without System Prompt**

> No automations found.

---

**With System Prompt**

> You haven't set up any automations yet. Start with a pre-built template for common workflows, or describe a repetitive task and the assistant will suggest steps to automate it.

---

**Why It Works**

The original is a dead end — it confirms an empty state but offers no direction. For a new user encountering this for the first time, it signals that the product has nothing to offer them right now. The revised version reframes the empty state as a starting point, offers two concrete entry paths (template or assistant), and removes the implication that something is missing. This is particularly important for AI-powered features where first-use experience determines long-term adoption.

---

# Example 5 — AI Disclosure After Automated Action

**Scenario:** A marketing team uses an AI feature to generate a campaign draft from uploaded customer engagement data. The draft is ready, and the user lands on a review screen. The confirmation message appears at the top of the screen.

*Prompt used: Prompt 3 — AI Trust Pattern Generator*

---

**Without System Prompt**

> Campaign generated successfully.

---

**With System Prompt**

> Draft campaign generated using your last 60 days of customer engagement data. Review all messaging before publishing; the assistant may not have captured recent segment changes.

---

**Why It Works**

The original reads like a success state, which may prompt a user to publish without reviewing — especially under time pressure. The revised version confirms the action while immediately introducing a review expectation, names the data source so the user can assess relevance, and proactively flags a known limitation (recent segment changes). In regulated or brand-sensitive industries, this kind of disclosure directly reduces compliance and reputational risk.

---

# Example 6 — AI Uncertainty Communication

**Scenario:** A B2B logistics platform uses AI to predict the most efficient shipping route for a customer order. The prediction is based on historical data, but current conditions are unavailable. The message appears alongside the suggested route in the dispatch interface.

*Prompt used: Prompt 6 — AI Uncertainty Messaging Generator*

---

**Without System Prompt**

> Best route identified.

---

**With System Prompt**

> This route is based on historical delivery patterns and may not reflect current road or weather conditions. Confirm with your dispatch team before scheduling.

---

**Why It Works**

The original implies a certainty the system cannot actually provide. In a logistics context, acting on a false "best" recommendation has real operational cost. The revised version names the data basis, explicitly flags the gap in real-time awareness, and assigns the confirmation step to a human — preserving accountability where it matters most. Communicating uncertainty clearly is not a weakness; it is what builds durable trust in AI tooling over time.

---

# Example 7 — Escalation Guidance

**Scenario:** A user on a B2B HR platform attempts to generate a compliance report. Midway through generation, the process fails because the user's workspace permissions were changed by an admin during the session. The error appears on the report generation screen.

*Prompt used: Prompt 7 — AI Workflow Recovery Assistant*

---

**Without System Prompt**

> Failed to process request.

---

**With System Prompt**

> We couldn't complete the report because your workspace permissions changed during this session. Your previous selections have been saved. Refresh the page and try again if the issue continues. Contact your workspace administrator to confirm your access level.

---

**Why It Works**

The original gives the user nothing to work with — no cause, no reassurance about data loss, no next step. In an HR context where compliance reporting is time-sensitive, this kind of dead-end error creates significant stress and support burden. The revised version names the cause, reassures the user that their work wasn't lost, gives a self-service recovery step, and provides a clear escalation path. Each of those four elements maps directly to the Error Recovery Model in `system.md`.

---

# Cross-System Design Note

These examples demonstrate a consistent pattern: the gap between the two versions is never just about word choice. It is about whether the content is doing operational work, orienting the user, setting expectations, preserving agency, and enabling recovery. That is what distinguishes a mature UX writing system from a style guide.
