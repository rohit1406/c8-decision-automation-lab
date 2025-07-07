# Documentation

## Scenario
The Camundanzia insurance company has successfully implemented Process Orchestration throughout their organization. As a next step, they would like to introduce Decision Automation using Decision Model and Notation (DMN).  

Camundanzia would like to enhance their existing Request Car Insurance process with automated decisions using DMN. The current version of the process no longer meets the business requirements as it only considers Driver Experience.  

The updated version of the process will also need to consider Car Type. In addition, the Insurance Manager also expects to make regular changes to the Policy Rules in the future. Therefore, the new version of the Request Car Insurance process must be easy to maintain.  


## User Story
### User Story 1
> As an Insurance Manager
> I want to update Policy Rules without the need for a Developer
> So that I can ensure that Camundanzia's exposure to risk is minimized

### User Story 2
> As an Insurance Manager
> I want to automatically approve requests from experienced drivers with small cars
> So that my Insurance Specialist can focus on more complex Requests

### User Story 3
> As an Insurance Manager
> I want to automatically reject requests from inexperienced drivers with luxury cars
> So that my Insurance Specialist can focus on more complex Requests

## Acceptance Criteria
The initial acceptance criteria that we will be working to are:  
+ Requests should be rejected for a Family or Luxury car if the Driver has less than 2 years of experience
+ Requests should be accepted for a Small car if the Driver has more than 2 years of experience
+ Requests should be accepted if the Driver has more than 4 years of experience
+ All other requests will be determined by an Insurance Specialist
+ The Insurance Manager can review each Request after completion

*[DMN]: Decision Model and Notation
