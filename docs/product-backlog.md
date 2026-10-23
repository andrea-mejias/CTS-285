# DataMan Product Backlog
[WILL REVISE SOON]
## Sources

This backlog uses these files from my repository:
- `docs/requirements.md`
- `docs/decisions/m3-backlog-triage-record.md`
- `docs/decisions/m3-product-owner-decision-record.md`
requirements.md has been revised to fit with all records and backlogs.

## Priority Order

List every story ID from highest priority to lowest. The story blocks below must
appear in this same order.

1. [US-01]
2. [US-03]
3. [US-02]
4. [US-04]

## Stories
<!-- Copy one story block for each story. Do not change the field labels. -->

### US-01 — Gain Feedback

**Requirement ID:** [FR-01]
**User Story:** As a learner, I want to receive feedback after submitting an answer so that I can know whether to continue or try again.
**Acceptance Criteria:**
- Given [starting condition], when [action or event], then [observable result].
- [Write one line for each condition. Each line must state a result that another
person can see and check.]
**Relative Effort:** [S] — Effort is medium compared to FR-02 in which the effort comes from the user alone.
**Dependency / Constraint:** None.
**Priority:** [1]
**Readiness:** Move Forward
**Priority Rationale:** [Why this rank is defensible. Name the factors you used:
value, effort, dependency, risk, uncertainty, or stakeholder need.]
---
### US-02 — Retry Attempts

**Requirement ID:** [FR-02]
**User Story:** As a learner, I want another attempt after an incorrect answer so that I can correct my work.
**Acceptance Criteria:**
- Given [starting condition], when [action or event], then [observable result].
**Relative Effort:** [S] — [Effort is relatively small compared to FR-01.]
**Dependency / Constraint:** [Answer-checking flow]
**Priority:** [3]
**Readiness:** [Refine]
**Priority Rationale:** [reason]

### US-03 — Practice Sets

**Requirement ID:** [FR-04, NFR-02]
**User Story:** As a parent/guardian, I want to create a set of custom practice problems so that I can correct my work.
**Acceptance Criteria:**
- Given [starting condition], when [action or event], then [observable result].
**Relative Effort:** [L] — [comparison]
**Dependency / Constraint:** [Privacy matters and activity data]
**Priority:** [2]
**Readiness:** [Refine]
**Priority Rationale:** [reason]

### US-04 — Visual Feedback

**Requirement ID:** [NFR-01]
**User Story:** As a developer, I want to show feedback after an incorrect answer through keyboard navigation so that users can understand withoyt relying on color alone.
**Acceptance Criteria:**
- Given [starting condition], when [action or event], then [observable result].
- [Write one line for each condition. Each line must state a result that another
person can see and check.]
**Relative Effort:** [M] — [Effort is relatively medium as this is not required but will be necessary for users who learn in different ways.]
**Dependency / Constraint:** None
**Priority:** [4]
**Readiness:** [Move Forward]
**Priority Rationale:** [Why this rank is defensible. Name the factors you used:
value, effort, dependency, risk, uncertainty, or stakeholder need.]
---
<!-- A non-functional requirement (NFR) can become its own story. It can also
become a constraint or an acceptance criterion on another story. If you use it as a
constraint, put its ID in that story's Requirement ID field. -->

## Open Questions Carried Forward

List each open question or assumption from `docs/requirements.md` that affects this
backlog. Do not turn an unresolved question into a confirmed story.

- **[Q-__]:** [Which story waits on this question, or why no story exists for it
yet.]

## Revisions After Triage and Release Planning

State what changed in this backlog because of your triage record and your Product
Owner decision record.
- [Story ID — what changed — which record caused the change.]
- [If nothing changed, say so, and say why the original decision still holds.]

## Before You Submit
- [ ] The file path is exactly `docs/product-backlog.md`.
- [ ] All bracketed prompts and unused story blocks are deleted.
- [ ] Every story has all eight required fields: Story ID, Requirement ID, User
Story, Acceptance Criteria, Relative Effort, Dependency / Constraint, Priority,
Priority Rationale.
- [ ] Every Requirement ID exists in `docs/requirements.md`.
- [ ] Each acceptance criterion states a result another person can observe and
check.
- [ ] The story blocks follow the Priority Order list.
- [ ] Large or uncertain stories are marked Refine or Defer, not hidden as Move
Forward.
- [ ] No story or criterion names a framework, database, or screen layout, unless a
requirement makes it a constraint.
- [ ] The file renders correctly on GitHub.
- [ ] The change is committed with a message that describes it
