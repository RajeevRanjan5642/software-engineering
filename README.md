# software-engineering

## What is Software Engineering ?
- s/w engineering is the systematic approach to the design and development of s/w.
- Responsibilities of a s/w engineer include:
    - Designing, building, and maintaining s/w systems.
    - Writing and testing code.
    - Consulting with stakeholders, third party vendors, security specialists, and other team members.
- s/w engineers build systems while s/w developers implement specific functionalitites.

## Software Development Life Cycle (SDLC)
- Systematic process to develop high-quality s/w.
- Its initial development in the 60s and 70s was driven by the need for a systematic approach because of the growing complexity of s/w.
- Aims to produce s/w that meets requirements.
- Defines phases with their own processes and deliverables.
- Cycle of planning, design, and development that can be implemented as an iterative approach.
- Minimizes risks and costs to the development of high-quality, deployable s/w.

## Advantages of the SDLC:
- It gives development teams a process to follow rather than using an adhoc approach to improve efficiency and reduce risks.
- There are discrete phases (the tasks from a previous phase don't ovelap with the tasks in the next phase) in the SDLC. Each phase is well defined so that team members know what they should be working on and when.
- Because of the well-defined phases, it facilitates communication b/w the customer, other stakeholders, and the development team.
- Since each phase is discrete, cross-domain teams know when they have completed their tasks and when development can move to the next phase.
- The SDLC provides room for iteration where at the end of a cycle the process can circle back to incorporate additional requirements as needed.
- Each team member has a well-defined role which reduces conflict and overlapping responsibilities.

## Phases of the SDLC
- There are generally 6 phases in s/w development process:
  1. Planning
  2. Design
  3. Development
  4. Testing
  5. Deployment
  6. Maintenance
 
1. Planning: In this phase, requirements are gathered, analyzed, documented and prioritized. As part of the planning process, labor and material costs are estimated and weighed against time constraints. Also, project teams are identified, and roles of each member are proposed. If the stakeholders are struggling to define requirements, a prototype can be produced by the development team to get stakeholder feedback and establish requirements.
After the requirements have been gathered, they are combined into a document called SRS (Software Requirements Specification). The SRS needs to be clearly understood and approved by all stakeholders.

Software requirements can be classified into four broad categories:
    1. functional
    2. external & UI
    3. system features
    4. non-functional

5. Design: In this phase, the requirements from the SRS are used to develop the s/w architecture.The architecture is reviewed by the stakeholder and the team. During this phase prototypes can be designed. A prototype is a small-scale replica of the end product that can be used for demonstration purposes. The document created in this phase is called a design document, and is used by the developers during the next phase, which is the development phase. Software Design is the process of transforming the requirements into a structure that is implementable using code. It transforms the requirements into a s/w solution. The technical lead breaks down requirements into sets of related components with clearly defined boundaries, and interactions. These components define the system architecture. The design communicates business rules and application logic.

6. Development: In this phase, the developers start the coding process once the design document is completed. The project planners use the design document to determine and assign coding tasks.This phase often requires the use of programming tools, different programming languages and s/w stacks. Organizations may also have standards or guidelines that need to be followed.

7. Testing: Code needs to be thoroughly tested to ensure it is stable, secure, and meets the requirements outlined in the SRS. Testing can be manual, automated or a hybrid of both. Product bugs are reported, tracked, and fixed, and retested until the software is stable. Some common levels of testing include unit testing, integration testing, system testing and acceptance testing.

8. Deployment: The deployment phase is where the application is released into the production environment and made available to the users. This approach can be used for making s/w available on a website, mobile device app store, or a s/w distribution server on a corporate n/w.

9. Maintenance: This phase happens once the code has been deployed into a production environment. This phase helps to find any other bugs, identify UI issues and identify other requirements that may not have been listed in the SRS. Code enhancements can also be identified at this stage. They are incorporated into the requirements as part of a future s/w release and the process can start over again.

### Summary:
The SDLC can be divided into six phases:
1. Planning: requirement gathering, create SRS
2. Design: develop architecture, create design document
3. Development: coding
4. Testing: identify and fix bugs
5. Deployment: code released to production environment
6. Maintenance: stakeholder feedback, issues

### Code Quality
Code quality refers to the characteristics of the code including attributes such as maintainability, readability, testability, and security. Quality code must fulfill the intended requirements of the s/w without defects. Additionally, it should be clean and consistent, easy to read and maintain, well documented, and efficient.

### Software Testing
The process of verifying that s/w matches established requirements and is free of bugs. Its purpose is to identify errors, gaps, or missing requirements when compared with stated requirements. Properly tested s/w ensures reliability, security, performance, and efficiency. S/w testing can often be automated or done manually. Levels of testing include unit, integration, system and user acceptance.

- Unit testing is often performed by the developer and tests the smallest component of code that can be isolated from the rest of the system.
- Once the components are integrated into the larger product, integration testing occurs.
- Then, after the larger product is deemed completed, system testing can take place.
- User Acceptance Testing (UAT) sometimes called beta testing, is when the s/w is tested by the intended end user.

### Software Release
When the newest version of the s/w is distributed, it is referred to as a "release". Different types of releases are intended for different audiences. There are generally three kinds of releases:
1. Alpha release : The alpha release is the first functioning version of the system released to a selected group of stakeholders. The alpha release likely contains errors and may not contain the full feature set but does contain most of the desired functionality.

2. Beta release : The beta release, also called a limited release, is given to the stakeholders outside of the developing organization. One of the intents of the beta release is to try out the s/w under real conditions, test the functionality, and identify any outstanding bugs or errors. The beta release should meet all the functional requirements.

3. GA release : After beta release changes are agreed upon, made, and tested, and a stable version is released. The audience for the GA release is all users.

### Software Documentation
- Software documentation should be provided to both non-technical end-users and technical users.
- System documentation is geared towards the technical user. Technical users may be other engineers, developers, or architects. System documentation explains how the s/w operates or how to use it. It consists of README files, inline comments, architecture and design documents, verification information and maintenance guides.
- User documentation is provided to the non-technical end-users to assist them in the use of the product. Generally user documentation is provided in the form of user guides, instructional videos, manuals and online help.


