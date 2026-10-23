# DataMan Product Backlog

## Sources

This backlog uses these files from my repository:
- `docs/requirements.md`
- `docs/decisions/m3-backlog-triage-record.md`
- `docs/decisions/m3-product-owner-decision-record.md`
- `requirements.md` has been revised to fit with all records and backlogs.

## Priority Order

1. US-01
2. US-03
3. US-02
4. US-04

## Stories
---
### US-01 — Gain Feedback

**Requirement ID:** FR-01
**User Story:** As a learner, I want to receive feedback after submitting an answer so that I can know whether to continue or try again.
**Acceptance Criteria:**
- Given learner completes a problem, when submitting an answer, then receives feedback before continuing or trying again.
**Relative Effort:** S — Effort is medium compared to FR-02 in which the effort comes from the user alone.
**Dependency / Constraint:** None.
**Priority:** 1
**Readiness:** Move Forward
**Priority Rationale:** This rank is defensible because this is core criteria with no risks, capable of doing a good impact for many users. No dependencies are
  in this requirement and with the priority being high, stakeholder needs can be met easily.
---
### US-02 — Retry Attempts

**Requirement ID:** FR-02
**User Story:** As a learner, I want another attempt after an incorrect answer so that I can correct my work.
**Acceptance Criteria:**
- Given learner completes a problem, when an incorrect answer is submitted, then another attempt is given so the user can correct their work.
**Relative Effort:** S — Effort is relatively small compared to FR-01.
**Dependency / Constraint:** Answer-checking flow
**Priority:** 3
**Readiness:** Refine
**Priority Rationale:** This rank needs refinement because this requirement has a dependency on the flow of answer checking.
A possible constraint is related to the user of the device alone.

### US-03 — Practice Sets

**Requirement ID:** FR-04, NFR-02
**User Story:** As a parent/guardian, I want to create a set of custom practice problems so that I can correct my work.
**Acceptance Criteria:**
- Given a need to use help as feedback, when creating practice problems for one set, then practice problem sets are stored and used as feedback for a user to correct their work.
**Relative Effort:** L — Effort is relatively large compared to NFR-02 as there are many dependencies that other roles must give effort in.
**Dependency / Constraint:** Privacy matters and activity data
**Priority:** 2
**Readiness:** Defer
**Priority Rationale:** This rank is deferred due to the session approach along with activity data not being ready.
  It is unknown on how the data will be managed and large effort also has to be given as well.

### US-04 — Visual Feedback

**Requirement ID:** NFR-01
**User Story:** As a developer, I want to show feedback after an incorrect answer through keyboard navigation so that users can understand withoyt relying on color alone.
**Acceptance Criteria:**
- Given a developer adds feedback for incorrect answers, when a user completes a problem, then shows feedback if the answer is incorrect through keyboard navigation.
**Relative Effort:** M — Effort is relatively medium as this is not required but will be necessary for users who learn in different ways.
**Dependency / Constraint:** None
**Priority:** 4
**Readiness:** Move Forward
**Priority Rationale:** This rank is defensible because for learners who learn in different methods, it will help them move smoothly.
  There has to be medium effort given due to the diversity of users but overall, no constraints or depencies are present.

## Open Questions Carried Forward

- **Q-02:** Other activities of DataMan are yet to be explored and do not have any stories yet due to unknown dependencies and possible constraints.
- **Q-03:** The discovery of any difficulties within the modernized version of DataMan compared to the original does not have a story yet.

## Revisions After Triage and Release Planning

State what changed in this backlog because of your triage record and your Product
Owner decision record.
- US-03 — Defer — Due to the session approach not being ready, this story has to be deferred until further notice.

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
