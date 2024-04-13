# IBM BAW Course Exercises
    - Developing workflow solutions using IBM Business Automation Workflow V20.0.0.1 Course code WB835 / ZB835 ERC 1.0
    - Traine in BPM Using IBM Business Automation Workflow Tool

# Introduction
    - IBM Business Automation Workflow is a platform to create workflow applications to improve productivity.
    - Workflow applications coordinate work between tasks that are performed by humans and automated tasks to improve daily business operations.
    - IBM Business Automation Workflow is part of the IBM Digital Business Automation platform, which includes various product offerings 
        that you can use to digitize all aspects of business operations, while providing real-time insight into your business.

## Objectives
     - Start IBM Business Automation Workflow
     - Create a process application in Workflow Center
     - Use the Process Admin console and other tools to aid in troubleshooting
     - Export and import process applications
     - Translate business process workflow steps that are documented in the process discovery and analysis into process model tasks
     - Create the foundation for a process by adding the appropriate lanes to the default pool
     - Model the expected process flow for the initial process model
     - Decompose business process workflow steps that are documented in the process discovery and analysis into process model tasks
     - Create a linked process
     - Add gateways to a process
     - Model the appropriate sequence flows for each gateway
     - Add a timer intermediate event to a process based on business requirements
     - Model an escalation path in a process with IBM Process Designer
     - Add a new swimlane and activity for legal review to meet additional requirements
     - Validate the process application and create a snapshot
          
## Tools
    - VMware WorkStation 17 Player
    - IBM BAW

## Business Process Workflow Scenario "Hiring Requisition process"
  ### Problem
      - The company wants to reduce rework by introducing a more structured process for the Hiring Requisition process
  ### Core requirements
      - 1.1   : A Hiring Manager submits a hiring requisition to the HR Department. The request contains the following information:
                - Customer details: Requisition number, Date of request, Requester   , Date position available ,
                                    Job title         , Job description, Job level   , Number of people managed, Division , 
                                    Department        , Salary to offer, Bonus amount, Hiring Manager comments , New position
      - 2.1.1 : If the answer to “New position” is Yes, the request is forwarded to a General Manager. 
      - 2.1.2 : After the General Manager receives the request, the General Manager indicates approval or disapproval.
      - 2.2.1 : If the request is not approved, the General Manager specifies a reason and the request is closed.
      - 2.2.2 : If the request is approved, a salary compliance check is conducted.
      - 2.3   : The Hiring Manager is notified of the General Manager’s decision after the General Manager approval step.
      - 2.4.1 : After the requisition is submitted, an automated system checks for salary compliance.
      - 2.4.2 : If the request meets salary compliance, the hiring request is automatically posted to the HR Positions database and made available for dissemination.
      - 2.5   : When a request violates the established salary guidelines of the company, the HR Administrator can approve or reject the requested salary override.
      - 2.6   : If the salary override is approved, the request is posted to the HR Positions database and made available for dissemination.
      - 2.7.1 : If the HR Administrator rejects the requested salary, 
      - 2.7.2 : The HR Administrator must provide comments for the violation, add a proposed salary
      - 2.7.3 : Send the request back to the Hiring Manager who originated the request.
      - 2.8.1 : When the Hiring Manager gets the request back because of a rejection, the Hiring Manager can negotiate an adjusted salary or can cancel the request.
      - 2.8.2 : If the negotiation is successful, the request is resubmitted back to the same HR Administrator.
      - 2.9   : All hiring requests must be added to the HR Positions database regardless of the disposition at the end of the process during a finalization activity.
      - 2.10.1: The HR Administrator has 4 hours to complete the review.
      - 2.10.2: If the review is not completed within 4 hours, an email is sent to the HR Administrator.
      - 2.10.3: The email notifies the HR Administrator of the missed deadline.
  
## Exercise 1. Creating the process application
    - Start the IBM Workflow Center deployment environment
    - Create and manage a process application
    - Explore other tools
    - Export the process application
    - Import the process application
   
## Exercise 2. Playback 0: Creating the To-Be process
    - Create a process
    - Create process activities
    - Model the process teams
    - Assign the activities to the appropriate Team
    - Create a linked process
    - Attach the linked process 
   
## Exercise 3. Playback 0: Controlling process flow
    - Create gateways for parent process
    - Create gateways for the linked process
    - Modeling timer intermediate events
    - Add new process requirements to the process
    - Validate the process model and take a snapshot

## Exercise 4. Playback 1: Controlling process flow with business data

## Exercise 5. Playback 1: Business data, services, and coaches

## Exercise 6. Playback 1: User interface design and implementation

## Exercise 7. Playback 1: Conducting the Playback session

## Exercise 8. Playback 2: Integrations

## Exercise 9. Playback 3: Handling errors and deploying your process application

## Exercise 10. Implementing a custom routing solution

## Exercise 11. Implementing the "four eyes" policy by using a team filter

## Exercise 12. Building a cancellation pattern

## Exercise 13. Building web service connections

## Exercise 14. Handling content events in a process

## 
