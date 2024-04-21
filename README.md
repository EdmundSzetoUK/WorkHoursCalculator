# Weekly Work Hours Calculator

## User story vs. acceptance criteria
User Story:
- User stories articulate the user's perspective on a feature, detailing what they want and why. They help prioritize development efforts and ensure alignment with user needs.
  - As [a user persona], I want [to perform this action] so that [I can accomplish this goal].

Acceptance Criteria:
- Acceptance criteria define the conditions a feature must meet to be considered complete. They offer specific requirements that ensure the feature behaves as expected from the user's viewpoint.

![User Story](/image/UserStory.drawio.png)

## Weekly Work Hours Calculator Requirement
### User Story 
As a project manager, I want a weekly working hours calculator so that I can easily track and visualize the total hours worked by my team to ensure compliance with company regulations

### Acceptance Criteria 
- Use Excel to build the calculator
- The system shall enforce core working hours from
  - Monday to Thursday, between 9:30 to 17:00.
  -  On Fridays, the core working hours shall be between 9:30 to 15:00.
- Uesrs have lunch half hour for lunch time everyday.
- The total weekly working hours must be a minimum of 36.5 hours.
- Users shall be able to select their working time as start time and end time
- Users shall be able to select their working type as either "Office" or "Work From Home."
- For Work From Home days, the maximum allowable working hours shall be 7 hours.
- The system shall provide a warning when the user exceeds the maximum Work From Home working hours.
- The system shall provide a warning when the total weekly working hours fall below the minimum required.
- The system shall include a chart to visualize the weekly working hours.
- The system shall include a pie chart shall be included to show the distribution of working hours between "Office" and "Work From Home" categories.

## Program UI 
Calculator UI
![Calculator UI](/image/Calculator_UI.png)

Calculator Data
![Calculator Data](/image/Data_sheet.png)

Time_select
![Time_select](/image/Time_select.png)

Warning WFH over hour
![Warning_WFH_hours](/image/Warning_WFH_hours.png)

Warning below reqeust weekly time
![Warning_below_reqeust_time](/image/Warning_below_reqeust_time.png)

Over request time (more then 1 hour)
![Over_request](/image/Over_request.png)
