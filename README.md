# IBM BAW Course Exercises
    - Developing workflow solutions using IBM Business Automation Workflow V20.0.0.1 Course code WB835 / ZB835 ERC 1.0
    - Traine in BPM Using IBM Business Automation Workflow Tool

# Introduction
    - IBM Business Automation Workflow is a platform to create workflow applications to improve productivity.
    - Workflow applications coordinate work between tasks that are performed by humans and automated tasks to improve daily business operations.
    - IBM Business Automation Workflow is part of the IBM Digital Business Automation platform, which includes various product offerings 
        that you can use to digitize all aspects of business operations, while providing real-time insight into your business.

## Objectives
     - 1.1: Start IBM Business Automation Workflow
     - 1.2: Create a process application in Workflow Center
     - 1.3: Use the Process Admin console and other tools to aid in troubleshooting
     - 1.4: Export and import process applications    
     - 2.1: Translate business process workflow steps that are documented in the process discovery and analysis into process model tasks
     - 2.2: Create the foundation for a process by adding the appropriate lanes to the default pool
     - 2.3: Model the expected process flow for the initial process model
     - 2.4: Decompose business process workflow steps that are documented in the process discovery and analysis into process model tasks
     - 2.5: Create a linked process    
     - 3.1: Add gateways to a process
     - 3.2: Model the appropriate sequence flows for each gateway
     - 3.3: Add a timer intermediate event to a process based on business requirements
     - 3.4: Model an escalation path in a process with IBM Process Designer
     - 3.5: Add a new swimlane and activity for legal review to meet additional requirements
     - 3.6: Validate the process application and create a snapshot
     - 4.1: Create simple variables in a process
     - 4.2: Implement timer intermediate events in a process
     - 4.3: Implement gateways for a process
     - 4.4: Implement routing for an activity     
     - 5.1: Determine and organize data when provided with a written process
     - 5.2: Add business objects and object type
     - 5.3: Create a client-side human service 
     - 5.4: Add variables and business objects to a process application
     - 5.5: Create and configure a coach to obtain process participant input
     - 5.6: Model a coach by using the concept of grids
     - 5.7: Add coach controls to control process flow
     - 5.8: Create a client-side human service and coach for the General Manager review activity
     - 5.9: Implement an activity by attaching a service and mapping data
     - 6.1: Create tabs on a coach
     - 6.2: Change the appearance of a coach by applying a custom theme
     - 6.3: Change the coach layout for a mobile format
     - 6.4: Configure controls to respond to different screen sizes
     - 6.5: Debug the coach by using a responsive sensor
     - 7.1: Log on to the Process Portal and create an instance of a process
     - 7.2: Demonstrate that the process follows the various paths modeled
     - 7.3: Use Process Portal to view the state of activities in a process
     - 7.4: Create a toolkit
     - 7.5: Create a snapshot in the Workflow Center
     - 7.6: Export the process application
     - 8.1: Create a decision service
     - 8.2: Create and configure a UCA
     - 8.3: Start a process with a message start event
     - 8.4: Use tagging to organize assets
     - 8.5: Query a database to obtain information and populate a list variable
     - 8.6: Create environment variables (ENVs) and exposed process variables (EPVs)
     - 8.7: Change a text control to a single select control
          
## Tools
    - VMware WorkStation 17 Player
    - IBM BAW

## Business Process Workflow Scenario "Hiring Requisition process"
  ### Problem
      - The company wants to reduce rework by introducing a more structured process for the Hiring Requisition process
  ### Core Requirements
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
    - Implement the intermediate timer event
    - Create the process flow variables for the Hiring Request Process
    - Create process flow variables for the Approve Hire Request linked process
    - Implement gateways
    - Implement routing for an activity
    - Review artifact references
    
## Exercise 5. Playback 1: Business data, services, and coaches
    - Build business objects and variables
    - Create a reusable client-side human service and define input controls
    - Reuse and debug the client-side human service
    
## Exercise 6. Playback 1: User interface design and implementation
    - Group controls into tabs on a coach
    - Change the appearance of the coach by applying a custom theme
    - Customize controls
    - Modify the mobile layout

## Exercise 7. Playback 1: Conducting the Playback session
    - Prepare for the playback
    - Demonstrate the Review Needed path
    - Demonstrate the Review Not Needed path
    - Demonstrate activity tracking
    - Reset the environment
    - Create the Hiring Requisition Toolkit and take a snapshot

## Exercise 8. Playback 2: Integrations
    - Create a decision service
    - Implement a message start event
    - Apply asset tags
    - Create a service to query a database and populate a list
    - Change an input to a single select on a coach
    
## Exercise 9. Playback 3: Handling errors and deploying your process application

## Exercise 10. Implementing a custom routing solution

## Exercise 11. Implementing the "four eyes" policy by using a team filter
    - Modify the process
    - Create the team filter service
    - Apply the team filter service to the activity assignment
    - Test the four eyes policy

## Exercise 12. Building a cancellation pattern

## Exercise 13. Building web service connections

## Exercise 14. Handling content events in a process

## 
