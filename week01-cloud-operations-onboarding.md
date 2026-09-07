# Week 1: Cloud Operations Onboarding

## HarborTech Ticket Summary
The purpose of this task is to investigate the bounds of AWS Academy's Learner Lab.

## Client Impact
This onboarding task has no potential client impact.

## AWS Services Involved
This task involves the Identity & Access Management (IAM) service.

## Virtualization Connection
This week's activity is to find the bounds of what I as an intern am allowed to do within AWS Academy's Learner Lab. This relates to managed cloud services because all cloud admins also have vendor or employer-imposed restrictions that must be found and worked within. 

## Evidence Reviewed
I opened the AWS Academy website (https://awsacademy.instructure.com), confirmed that "AWS Academy Learner Lab" is one of my available courses, and that I can see and access the "AWS Academy Learner Lab" Module.
I clicked on the "Launch AWS Academy Learner Lab" link within the above mentioned module, opened the readme, and confirmed the "Region restriction" subsection lists "us-east-1" and "us-west-2" as the only two available Regions under normal circumstances.
I located the "AWS Identity and Access Management (IAM)" subsection within the readme and confirmed that IAM is restricted to disallow creation of users, groups, and any roles that aren't service-linked roles.
The "Environment Overview" subsection states that when the session timer reaches "0" within Learner Lab, the current active session is forced to end without deleting any data or resources that were created.
The above subsection also states that remaining lab budget can take 8-12hrs to reflect all charges that have been incurred in the Learner Lab and that if the lab budget reaches $0 my lab account will be disabled and all saved data within the Learner Lab will be lost.
The "Environment Navigation" subsection states that the "Reset" button within the Learner Lab UI will revert my instance to it's state at time of creation, erasing all changes I've made without resetting the lab budget.

Document the evidence you reviewed. Your weekly skeleton will suggest likely evidence sources, but you should include the evidence that actually informed your conclusion.

## Operational Analysis

Explain what the evidence shows. Separate findings from assumptions and connect the evidence to the likely cause or decision.

## Recommendation

State the next operational action supported by the evidence. Keep the recommendation within the HarborTech intern role.

## Escalation Notes
No issues were encountered during investigation, so no escalation is required for this task.

## Lessons Learned

Explain what the investigation taught you about cloud operations and the week's technical concepts.

## Professional Vocabulary

Define the important weekly terms in your own words and connect them to the work you completed.



# Week 1: Cloud Operations Onboarding

## HarborTech Ticket Summary
Ticket ONB-2026-0001 is for me as a new HarborTech intern to verify I have access to the Learner Lab environment, that I have an understanding of the lab's purpose and restrictions, and that I know where official AWS documentation can be found for reference.

## Client Impact
To be able to complete client support work, I must have access to the AWS environment. Ensuring environment readiness verifies necessary access and limitations.

## AWS Services Involved
This ticket involves Cengage.com/Canvas to access AWS Academy and the Learner Lab, labs.vocareum.com to access the Learner Lab's readme for information on IAM, region, and account restrictions, and docs.aws.amazon.com for access to all official AWS documentation.

## Virtualization Connection
Software-defined cloud infrastructure depends on account, Region, permission, cost, and platform boundaries to define by principle of least access what responsibilities I'm able to hold within the virtual environment.

## Evidence Reviewed
Document the evidence you reviewed, such as:
- I confirmed I have access to AWS Academy's Learner Lab and Cloud Operations courses
- I confirmed I'm able to access and start the Learner Lab
- The Learner Lab readme lists the normally accessible Regions as "us-east-1" and "us-west-2"
- The Learner Lab readme states that IAM is restricted to disallow creating users, groups, and any roles that aren't service-linked roles
- A role, "LabRole," and an instance profile, "LabInstanceProfile," have been pre-created for use in the Learner Lab
- Sessions end automatically once the lab timer reaches "0." No data associated with my profile is deleted and the session can be started and lab timer reset by clicking "Start Lab" again.
- The budget needs up to 8-12 hours to accurately reflect all incurred charges
- If the "Reset" button is clicked within Learner Lab, all changes made by me will be deleted and Learner Lab will be reverted to its initial state. The budget does not reset from this.
- The AWS Documentation site is located at "https://docs.aws.amazon.com/"
- A Playbook has been created on GitHub

## Operational Analysis
The evidence above shows that I am ready to begin HarborTech support work because I'm able to use the Learner Lab, that I am aware of its designed limitations and features, and that I know where to access the AWS Documentation for reference when needed. 

## Recommendation
My environment is ready for Week 2 support work and no additional steps are necessary at this time for that goal.

## Escalation Notes
No escalation is needed for this ticket.

## Lessons Learned
Week 1 has taught me:
- How to confirm my readiness in the Learner Lab environment
- That I must record exact actions and results as my evidence without treating assumption as fact
- Where to find official AWS documentation for learning anything in the AWS ecosystem
- That the boundaries imposed within a cloud environment are meant to be worked within for the sake of security and any task that cannot be fulfilled within those boundaries must be escalated to someone with higher access

## Professional Vocabulary
Define the important Week 1 terms in your own words.
Include terms such as:
- Virtualization - A form of abstraction where discreet pieces of hardware and wired connections are simulated in software to allow consolidation of computational power and greater flexibility
- Evidence - Facts that support the truthfulness of a given statement
- Finding - A factual observation of a given behavior, usually recorded as evidence of something
- Assumption - A guess; at best, a factually supported hypothesis. Distinctly not a fact or finding and cannot be used as evidence
- Escalation - Transferring a ticket that cannot be resolved within a given analyst's permitted access to another analyst that does have the required access
- Sandbox - A digital environment intended for testing and troubleshooting that is disconnected from Production to prevent unintended user impact
- Region - A virtual separation of computational resources based on the physical part of the world those computational resources are located in
- IAM - Identity and Access Management; AWS service to create and manage sets of permissions that users and services can be placed within to efficiently control what they're allowed to do on a very granular level 
- Operations Playbook - A diligently written and organized knowledge base of previous tickets including detailed troubleshooting steps, associated findings, root problems, and their specific resolutions
- 
