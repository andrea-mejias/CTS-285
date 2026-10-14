# DataMan Requirements Register

## Project Context

Our goal is to do a modernized DataMan on a website based on the 1977 DataMan made by Texas Instruments, used by many kids for educational purposes worldwide. The primary users expected to use this modernized DataMan are students from grades K-12. This project will solve any hardware conflicts and fix any setbacks that came from using the 1977 DataMan, while catering to students in this modern era of technology.

## Evidence Notes

- **E-01 — Source:** 4th Grade Teacher Interview on Students’ Use of the 1977 DataMan
  **Evidence:** When interviewing a fourth-grade teacher about how her students are not enjoying DataMan as expected, looking at the 1977 manual shows that there was a gap within the learning process. Observing how students used the Answer Checker on DataMan gave more of an answer. The Answer Checker manual section states that there is a three-attempt limit before getting the correct answer, and yet the learners are not told visually on where they are in the attempt sequence. Students could not tell whether they were wrong or had run out of attempts. The students are working against the main goal which is to keep a learner practicing rather than disengaging. 

- **E-02 — Source:** 1977 DataMan manual, “Hints for Parents and Teachers” (p. 19) and “Please Try Me Out” (p. 3)  
  **Evidence:** Feedback is given through flashing lights for right answers, “EEE” with blinking lights for wrong answers, and a “light show” reward after a user succeeds with a session. The manual states that these are intended to motivate users positively in using the 1977 DataMan. The feedback relies on visual displays, with no textual explanation of what message is being given.

- **E-03 — Source:** 1977 DataMan manual, “Memory Bank” (pp. 4, 21) 
  **Evidence:** A user of the 1977 DataMan can store up to ten custom problems using the Memory Bank key. Due to hardware limitations, the storage for storing previous problems is low. The manual describes this as a head start for practice sets and activities that teach users how to improve at certain problems they struggle with. The web version can vastly enhance the storage limitations of DataMan and give more space for users to receive more help in any other variety of problems they may encounter.

- **E-04 — Source:** 1977 DataMan manual, “Appendix” (p. 24) and Power Saver Feature (p. 19)
  **Evidence:** The 1977 DataMan depends on a nine-volt battery that lasts about fifteen hours for use. A dim display, erratic display, or unresponsive keys signal that the battery must be replaced. The device itself powers off for power-saving purposes after about five minutes staying idle, if the Power Saver Feature is enabled. Any broken units of DataMan would have to be mailed and insured to a service facility for fixing or be exchanged at an exchange center if there are no facilities available to fix the issue. The website version aims to remove these hardware conflicts thanks to advancing modern technology today.

## Functional Requirements

### FR-01
**Requirement:** The system must show the learner how many attempts remain on the current problem before it reveals the correct answer.
**Source/Rationale:** E-01 and manual pp. 3, 20
Learners could not tell whether they were wrong or out of attempts, which works against keeping them practicing with DataMan.

### FR-02
**Requirement:** 
**Source/Rationale:** 

### FR-03
**Requirement:** The system must check a learner’s answer to a problem, report whether it is correct, and keep a running score of right answers out of problems tried.
**Source/Rationale:** E-01; manual pp. 2, 3, 20
Answer checking and score keeping are the core features of Answer Checker in the 1977 DataMan. The other requirements such as attempt count, feedback, and custom problem sets all depend on it.

### FR-04
**Requirement:** The system must allow an authorized user to create a custom set of practice problems for a learner to work through that set.
**Source/Rationale:** E-03 and manual pp. 4, 21 (Memory Bank)
Teachers and parents are identified stakeholder groups, and the original limits of problem sets go up to ten problems entered key by key.

## Non-Functional Requirements

Write at least three non-functional requirements. Each requirement should describe a measurable quality, constraint, or condition the system must satisfy.

### NFR-01
**Requirement:** The system must show feedback after an incorrect through keyboard navigation and must not rely on color alone.
**Source/Rationale:** E-02 and Manual pp. 19–20
The 1977 DataMan gives right and/or wrong feedback through light patterns and “EEE” only, which does not explain the results to some users.

### NFR-02
**Requirement:** The system must encrypt customer information while stored in the production database.
**Source/Rationale:** E-03 Project constraint;
The 1977 DataMan never stored personal information in its Memory Bank, only storing up to ten problems. The new DataMan being a web version will store more information, hence why some of that information must be protected from being used for unethical purposes. What’s important is that child-privacy rules should be instated for protection of users using DataMan.

### NFR-03
**Requirement:** The system must display search results within two seconds under normal operating conditions.  
**Source/Rationale:** E-02; E-03; project constraint to be confirmed (Q-03)
The 1977 DataMan reacts to answers immediately and is built around timed, speed-focused practice, so slow responses would hurt the experience. With larger storage than the Memory Bank, users will need to find the saved problem sets. The two-second limit can be verified later with response-time testing. What counts as a “search result” in DataMan is yet to be determined.

## Open Questions / Assumptions

Do not turn an unsupported idea into a confirmed requirement. Record unresolved items here until evidence supports a decision.

- **Q-01:** What does customer information and search results mean for DataMan?
- **Q-02:** What other activities from the 1977 DataMan will be covered?
- **Q-03:** Will there be more difficulties with the web version of DataMan that could differ from the original?

## Final Quality Check

Before submitting, confirm that each requirement is:

- [ ] Clear enough for another team member to interpret consistently.
- [ ] Supported by evidence, a stakeholder need, or a confirmed project constraint.
- [ ] Testable or verifiable later.
- [ ] Solution-neutral enough for this stage of the project.
- [ ] Focused on one main capability or quality.
- [ ] Classified correctly as functional or non-functional.

Also confirm:

- [ ] At least four functional requirements are included.
- [ ] At least three non-functional requirements are included.
- [ ] Every confirmed requirement has a source/rationale.
- [ ] Open questions and assumptions are separated from confirmed requirements.
- [ ] The simulation decision record is saved at `docs/decisions/m2-elicitation-decision-record.md`.
- [ ] This file is saved as `docs/requirements.md`, committed, and synced to GitHub.
