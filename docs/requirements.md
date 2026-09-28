# Functional Requirements
- DataMan must preserve in-progress record information when a user's session is interrupted.
- DataMan must allow an authorized employee to create a new customer record.
- DataMan must allow users to search for a customer by customer ID.
- DataMan must allow an auditor to review the change history for a record.
- DataMan must allow an authorized employee to update a customer's mailing address.
- DataMan must allow Priya to generate a weekly correction summary.

Nowadays, students may have little time to use DataMan in certain circumstances. It is important that the session's information is recorded if the session is interrupted. Otherwise, a user will not remember what they once inputted on DataMan and cannot navigate any log page to find their previous actions. The Memory Bank was a feature that was implemented into the original DataMan, which enabled users to look through problems they got correct. There was only a storage limit of six problems due to hardware limitations stated on the manual section, but when DataMan is implemented onto a website, the open storage is larger in this day and age. When using Priya, it must be used ethically and checked for any mistakes along the run.

# Non-Functional Requirements
- Customer information must be encrypted while stored in the production database.
- Only authorized managers may delete customer records.
- The system must be available from 7:00 a.m. to 7:00 p.m. Monday through Friday except during scheduled maintenance.
- The application must support the browsers approved by the organization.
- The weekly correction summary must load within three seconds under normal operating conditions.
- Search results must display within two seconds under normal operating conditions.

Maintenance of keeping loading speeds stable is very important when it comes to users interacting with DataMan. When it came to the original DataMan, the answers always came quickly, so the website should be maintained to work the same as the original did. We have to use efficient applications that can run the website as fast as DataMan did. Although these are non-functional requirements, they are needed to be known in order to build on with the website. Customers being given the option to delete their own records would lead to possible deletion accidents, but would not really be a requirement as some users can be responsible of what actions they do with their records.


# Requirements that are Not Ready
- The whole system needs to be faster.
- The system should look more modern.
- DataMan should use AI to fix mistakes.
- Put a large green Save button at the top of every page.
- DataMan needs to be easier.
- Make search better.

All of these are very vague and do not give light to any development options whatsoever. These would be useful as small ideas but would not parse through as eligible notes for development unless there is more context added to the requirements. AI is expected to be used in DataMan but there needs to be specifics on how it will be managed, as many misuse AI for the wrong reasons. The requirement of DataMan needing to be easier is not compatible as it states in both the story and manual sections that DataMan is meant to be fun for kids to use, which makes it easier along the run. Learning through each attempt makes using DataMan less tedious. The system is already running faster and is efficient in the original DataMan, which makes the vague requirement of the system needing to be faster invalid. The website will be just as fast as the original DataMan.

# Proposed Solutions
- The system must show the learner how many attempts remain on the current problem before it reveals the correct answer.
- Feedback after an incorrect answer must be available through keyboard navigation and must not rely on color alone.

When interviewing a fourth-grade teacher about how her students are not enjoying DataMan as expected, looking at the 1977 manual shows that there was a gap within the learning process. Along with interviewing the teacher and observing how students used the Answer Checker on DataMan, it gave more of an answer. The Answer Checker manual section states that there is a three-attempt limit before getting the correct answer, and yet the learners are not told visually on where they are in the attempt sequence. Students could not tell whether they were wrong or had run out of attempts. The students are working against the main goal which is to keep a learner practicing rather that disengaging. Therefore, this is a feedback requirement.
According to the observation on how students are operating with DataMan, students have not figured out if they ran out of attempts or they got the question wrong. Feedback is critical in helping students learn when doing math and if they do not see the feedback, they will not learn how to do the next tries in a better view. Although this is non-functional, it is needed for some who struggle with registering visual cues.
