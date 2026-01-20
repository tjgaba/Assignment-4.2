#  Sprint 1 Mid-Sprint Checkpoint

## Progress Snapshot
- Planned points: 53
- Completed points: 5
- In progress: 1
- Not started: 6
- Status: On track 

## At-Risk Work
*Story #1 – Subtask 1* - Is done.

*Story #1 – Subtask 2* - Is done.

*Story #1 – Subtask 3* - Is done.

*Story #1 – Subtask 4* 

  - (Build booking UI component): At risk because it depends on the completed booking API endpoint (Story #1 – subtask 3); any required changes to the API may cause rework or delays.

*Story #1 – Subtask 5*

  - (Validation and error handling): At risk because it depends on the booking UI component (Story #1 – subtask 4); delays or changes in the UI will delay validation implementation.

*Story #1 – Subtask 6*

  - (Write tests): At risk because it depends on validation and error handling being completed (Story #1 – subtask 5); late completion may reduce available time for thorough testing.

*Story #2*

  - (Recurring meetings): At risk because it is blocked by the completion of Story #1 (Basic room booking); any delay in finishing Story #1 impacts the start of recurring meetings.

*Story #4* 

  - (Capacity filtering): At risk because it depends on Story #2 (Recurring meetings); delays in recurring meetings reduce the time available to implement capacity filtering.

*Story #10*

  - (Visitor assistance): At risk because it depends on Story #4 (Capacity filtering); being last in the dependency chain increases the likelihood of it being deferred.


## Decisions Taken

  - Focused the sprint scope on completing Story #1 (Basic room booking) before starting dependent stories.
  - Deferred Story #2 (Recurring meetings) until Story #1 is fully completed, as per dependency constraints.
  - Agreed to address remaining validation, testing, and UI refinements before moving on to new functionality.

## Blockers

**Resolved:**

    - Dependency blocker between Story #1 – subtask 1 (design booking data model) and subtask 2 (availability check logic) was resolved once the data model was finalized.
- Dependency blocker between Story #1 – subtask 2 and subtask 3 (booking API endpoint) was resolved after availability logic was completed.

**Outstanding:**

  - Story #2 (Recurring meetings) remains blocked until Story #1 is fully completed.
  - Story #4 (Capacity filtering) remains blocked by Story #2.
  - Story #10 (Visitor assistance) remains blocked by Story #4.

## Team Health

  - The team is collaborating well and progressing steadily through tasks. Communication is clear,blockers are being identified and managed early. So overall morale is positive.
