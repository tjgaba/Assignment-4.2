# Sprint 1 Planning Session

- Date:           13 Jan 2026

- Sprint Goal:    Successfully confirm booking procurement by verifying on the main-system database, 
                  not just verification via the confirmation message sent to you. Note: Ask receptionist for 
                  double checking the booking on the dashboard.

## Attendees
- Product Owner: Bit Cube
- Scrum Master: TJ Gaba
- Development Team: Dev Team 1

## Velocity Target

Note: 
- Although subtask **DO NOT** amount to points, but count as DoD/Dependancies for
the completion of [Story #1], they are necessary to be attended to since
the subtasks themselves were required on Assignment 2.1 and do make a difference 
on the durndown chart. Also fully aware that the above concept (subtask/subpoint) 
might not part of the taught content, but added it for context and understanding.

- So since subtasks are relatively tasks themselves, therefore should also be putted on the 
Product Backlog, then respectively be assigned into the Sprint Backlog to be attended to by 
the Dev team. 

Hint: 

**Sprint #1: TimeBox = 4-weeks** 

    **Time Frame: For [Story #1] = 1-week** 
  
            Note: One(1)sprint = 20 points according to assignment 2.2.
            [Story #1] velocity; 8 + 8 + 2 + 2 = 20 points
            Subtask Span = 6 days
              - 6 subtasks → 6 working days  
              - 1 subtask can fit per day to cover the 6 day period.
              
            ---
            
            *The following is just for comprehension/understanding - not necessarily part of the questionnaire requirements*
              - 2 + 1 + 2 + 1 + 1 + 1 = 8 substory 'points'  
              - 8 ÷ 6 days = 1.33  substory 'points' per day are needed to complete [Story #1].
              - Therefore Velocity for these subtasks = 1.33.
              - Rounded-off: 2 . 
            This means a highly recommended 1 sub-task can 
            be done in one day to cover [Story #1] timeframe: 6 days.
            
    **Time Frame: For [Story #2] = 1-week** 
    
    **Time Frame: For [Story #3] = 1-week**  
    
    **Time Frame: For [Story #4] = 1-week** 

**Total Story Points**  
Total Story Points

8 + 8 + 2 + 2 + 5 + 8 + 8 + 8 + 2 + 2 = 53 story points

Velocity = 20 points per sprint.            (Velocity changes according to Assignment 2.2)
            53 / 20 = 2.65 (Rounded = 3)
            Therefire 3 Sprints.

**Velocity = 20.**

## Selected User Stories for [Sprint 1] - (Including subtasks of [Story #1])

| Story # ----------------| Title -------------------------- -| Story Points- |

| [Story #1]--------------| Basic room booking--------------- | 8 -------------|

| [Story #1 - subtask 1]--| Design booking data model-------- |----------------|

| [Story #1 - subtask 2] 	| Implement availability check logic|----------------|

| [Story #1 - subtask 3] 	| Create booking API endpoint-------|----------------|

| [Story #1 - subtask 4] 	| Build booking UI component--------|----------------|

| [Story #1 - subtask 5] 	| Add validation and error handling |----------------|

| [Story #1 - subtask 6] 	| Write tests -----------------------|----------------|

| [Story #2]--------------| Recurring meetings----------------| 8 -------------|

| [Story #4]--------------| Capacity filtering----------------| 2  -------------|

| [Story #10]-------------| Visitor assistance----------------| 2 -------------|


## Dependencies

[Story #1 - subtask 1] - Design booking data model
- Blocked by -None 
- Blocking -[Story #1 - subtask 2]

[Story #1 - subtask 2] - Implement availability check logic
- Blocked by -[Story #1 - subtask 1] 
- Blocking -[Story #1 - subtask 3]

[Story #1 - subtask 3] - Create booking API endpoint
- Blocked by -[Story #1 - subtask 2] 
- Blocking -[Story #1 - subtask 4]

[Story #1 - subtask 4] - Build booking UI component
- Blocked by -[Story #1 - subtask 3] 
- Blocking -[Story #1 - subtask 5]

[Story #1 - subtask 5] - Add validation and error handling
- Blocked by -[Story #1 - subtask 4] 
- Blocking -[Story #1 - subtask 6]

[Story #1 - subtask 6] - Write tests
- Blocked by -[Story #1 - subtask 5] 
- Blocking -[Story #1] As an Employee, i  want to Select an automation option

[Story #1] - Basic room booking
- Blocked by -[Story #1 - subtask 6]
- Blocking -[Story #2]

[Story #2] - Recurring meetings
- Blocked by - [Story #1] - Basic room booking
- Blocking -[Story #4]

[Story #4] - Capacity filtering 
- Blocked by -[Story #2] - Recurring meetings
- Blocking -[Story #10]

[Story #10] - Visitor assistance
- Blocked by - [Story #4] - Capacity filtering 
- Blocking - None (No additional tasks under Sprint Backlog)

## Risks
| Risk                                        				| Probability | Impact | Mitigation                                                       						|
| --------------------------------------------------------------------- | ----------- | ------ | -------------------------------------------------------------------------------------------------------------- |
| (Story 1) Booking logic allows double bookings                  	| Medium      | High   | Clearly define booking rules, review the logic with a teammate, and test common booking scenarios early     	|
| (SubStory 1)Design errors in booking data model         		| Medium      | High   | Go through the database design with the team and check it carefully 						|
| (SubStory 2)Incorrect availability check logic          		| Medium      | High   | Explain clearly what the logic should do, have a teammate check it, and test it early 				|
| (SubStory 3)API endpoint fails or returns wrong data    		| Medium      | High   | Test the API using tools like Postman, check responses, and run tests 						|
| (SubStory 4)UI component usability issues               		| Medium      | Medium | Test the interface quickly, ask a teammate to review, and follow design guidelines 				|
| (SubStory 5)Validation and error handling missing cases 		| High        | Medium | Make clear rules for input checks, add both server and client checks, and test them both 			|
| (SubStory 6)Tests not covering edge cases               		| Medium      | High   | Write tests for normal and unusual cases and have teammates review them 					|
| (Story 2) Recurring meetings not created correctly               	| Medium      | High   | Explain recurrence rules clearly, review the implementation with the team, and test typical repeat patterns 	|
| (Story 4) Capacity filtering returns incorrect rooms             	| Low         | Medium | Clarify capacity requirements, test with sample room data, and have a teammate review the logic             	|
| (Story 10) Visitor assistance workflow is unclear or incomplete  	| Low         | Medium | Walk through the flow with the team, test basic user actions, and refine based on feedback                  	|

- Key notes: 
    - Risk → Something that might go wrong with the subtask.
    - Probability → Likelihood it will occur (Low/Medium/High).
    - Impact → How badly it affects the Increment or Sprint if it happens.
    - Mitigation → Practical action to reduce the risk.

## Standup Cadence
Time: 30 mins
Format: 
- Yesterday : Assigned Story #1,2,10 & 4 to the Spring  Backlog, and started to work on Story #1; Starting with; The Design booking data model
- Today : Today we attended the; Incorrect availability check logic.
- Blockers : The only blocker today was the design errors we encounter from [Story #1 - subtask 1]. But that was successfully handled. 
