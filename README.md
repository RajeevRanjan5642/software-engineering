# software-engineering

## What is Software Engineering ?
- Software engineering is the systematic approach to the design and development of s/w.
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

Requirement gathering includes:
- identifying stakeholders
- establishing goals and objectives
- eliciting requirements from the stakeholders
- documenting the requirements
- analyzing and confirming the requirements
- prioritizing
  
1. Identifying stakeholders:
   - Decision-makers
   - End-users
   - System administrators
   - Engineering
   - Marketing
   - Sales
   - Customer Support Personnel
It is good to have a representative from every group that the product affects.

2. Establishing goals and objectives:
   - Goals are broad, long-term achievable outcomes.
   - Goals can include customer outcomes and business goals.
   - Objectives are more specific than goals.
   - They are actionable and measurable actions that achieve the stated goals.

3. Eliciting requirements from the stakeholders:
   - Elicitation can be accomplished through surveys, questionnaires, and interviews.

4. Documenting the requirements:
   - As the requirements emerge, they should be documented and checked to ensure they align with the goals and objectives.
   - Documented requirements should be easily understood by stakeholders and the project team.
     
5. Analyzing and confirming the requirements:
   - In order to confirm the requirements, they should be analyzed to ensure consistency, clarity and completeness.
   - After analysis, the requirements should be shared with and approved by the stakeholders.

6. Prioritizing:
   - After confirmation, requirements should be prioritized. Labels such as "must-have", "highly desired", "nice to have" are helpful.
       
Typically, there may be three documents that result from the requirements gathering process:
1. Software Requirements Specification (SRS) : A document that captures the functionalities that the s/w should perform and also establishes benchmarks or service levels for its performance.
   - A purpose statement : who will have access to the SRS and how they should use it.
   - Scope : The scope describes the benefits of the s/w, its goals, and objectives.
   - Constraints : Constraints describe how the product must operate under given conditions that may limit options in the design phase such as conformation to standards or hardware limitations.
   - Assumptions : Assumptions may include things like operating system or hardware that is needed by the software to function.
   - Dependencies : Dependencies on other software products should also be noted.
   - Requirements : Requirements can be classified into four categories:
        1. Functional : Functional requirements are those that cover the functionalities of the software.
        2. External : External requirements are the requirements that address the behavior of the software in relation to external entities such as users and other h/w or s/w.
        3. system features : System features are a subset of functional requirements. These are the required features for the system to function
        4. non-functional : There are also non-functional requirements such as specifying performance, safety, security, and quality standards.
     
2. User Requirements Specification (URS) : use cases and user stories
3. System Requirements Specification (SysRS) : syatem capabilities and acceptance criteria, policy, regulation, personnel, performance, security and hardware requirements.

6. Design: In this phase, the requirements from the SRS are used to develop the s/w architecture.The architecture is reviewed by the stakeholder and the team. During this phase prototypes can be designed. A prototype is a small-scale replica of the end product that can be used for demonstration purposes. The document created in this phase is called a design document, and is used by the developers during the next phase, which is the development phase. Software Design is the process of transforming the requirements into a structure that is implementable using code. It transforms the requirements into a s/w solution. The technical lead breaks down requirements into sets of related components with clearly defined boundaries, and interactions. These components define the system architecture. The design communicates business rules and application logic.

7. Development: In this phase, the developers start the coding process once the design document is completed. The project planners use the design document to determine and assign coding tasks.This phase often requires the use of programming tools, different programming languages and s/w stacks. Organizations may also have standards or guidelines that need to be followed.

8. Testing: Code needs to be thoroughly tested to ensure it is stable, secure, and meets the requirements outlined in the SRS. Testing can be manual, automated or a hybrid of both. Product bugs are reported, tracked, and fixed, and retested until the software is stable. Some common levels of testing include unit testing, integration testing, system testing and acceptance testing.

9. Deployment: The deployment phase is where the application is released into the production environment and made available to the users. This approach can be used for making s/w available on a website, mobile device app store, or a s/w distribution server on a corporate n/w.

10. Maintenance: This phase happens once the code has been deployed into a production environment. This phase helps to find any other bugs, identify UI issues and identify other requirements that may not have been listed in the SRS. Code enhancements can also be identified at this stage. They are incorporated into the requirements as part of a future s/w release and the process can start over again.

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

## Software Development Methodologies

### Waterfall method
- It is a sequential method of s/w development where the o/p of one phase is the input for the next phase of the cycle.
- Development and work on the next phase start only after the completion of the previous phase.
- All planning such as defining requirements and architectural design, is done up front.
- The customer usually does not see the product until it is in the testing phase.
- For a major version release of the product, the same process is repeated resulting in long intervals such as years, between releases.
- plan -> design -> develop -> test -> deploy -> maintain

![image](https://github.com/user-attachments/assets/3fcebf18-595f-4ea5-9f1b-a3d093f8b282)

#### Pros:
1. Easy to understand and follow.
2. Each stage/phase is discrete and well-defined, making it easy for all team members to understand their roles.
3. Since planning is done upfront, it is easier to estimate a budget and allocate resources.

#### Cons:
1. Waterfall lacks flexibility. Since all planning is done upfront if a requirement is changed that change can be hard to incorporate at a later date.

### V-shape model
- The V-shape model is named as such because the phases form the shape of a V.
- The phases going down the left side of the V are called 'verification' and going up the right are called 'validation'.
- Each phase in verification corresponds with a validation phase.
- There are 4 stages that occur on each side of the V. Going down the V are planning, system design, architecture design, and then module design. The bottom of the V is the coding phase. And going up the V are 4 phases that correspond to the phases going down the V: unit testing, integration testing, system testing and acceptance testing.
- The tests are written during the verification phases on the left and executed during the validation stages on the right.
  
![image](https://github.com/user-attachments/assets/d09a4727-72cb-49b1-801b-93eec32b699d)

#### Pros:
- Simple and easy to use.
- Designing test plans during the verification phases saves considerable time during coding and validation phases.

#### Cons :
1. It does not readily accomodate changing requirements.

### Agile model
- It focuses on a collaborative s/w development process over multiple short cycles rather than a strictly top-down linear process.
- It is an iterative approach to development.
- It aligns with the SDLC, but each phase is short.
- Teams work in cycles, or sprints, which are usually one to four weeks long.
- Unit testing happens in each sprint to minimize the risk of failure.
- Rather than the 'maintenance' stage of the SDLC, the final stage of the sprint is a feedback stage.
- At the end of each sprint, a chunk of working code is released at a meeting called the 'sprint demo' where stakeholders can see the new functionality and provide feedback.
- After the sprint demo, the entire process is repeated for every sprint cycle.
- After several sprint cycles, a minimum viable product, or MVP, is developed so stakeholders can provide feedback on the basic feature set.
- The 4 core values of Agile developemnt outlined in what is known as the 'Agile manifesto' are:
  1. individuals and interactions over processes and tools
  2. working s/w over comprehensive documentation
  3. customer collaboration over contract negotiation
  4. responding to change over following a plan.

#### Pros :
1. With Agile, new, and changing requirements are handled quickly and easily because planning is initiated at the beginning of each sprint cycle.
2. At the end of each cycle, the QA team, stakeholders, and the customer have some piece of working code to test against requirements and are encouraged to provide feedback.

#### Cons :
1. Budgeting and sceduling can be challenging because the overall scope of the product is not clearly defined.

### Difference b/w traditional SDLC methods and the agile method
- Traditional SDLC methods are sequential whereas agile is cyclical.
- Traditional SDLC methods center around the whole product being developed before soliciting customer feedback whereas agile focuses on quick and short bursts of development.

### Software Versions
- Version numbers indicate the history of changes, updates, and patches to software,
- Some version numbers follow the semantic numbering system and have 4 parts separated by a period.
  - The first number indicates major changes to the software, such as a new release.
  - The second number indicates minor changes to the software.
  - The third number indicates patches or minor bug fixes.
  - The fourth number indicates a build number or a build date, and it can indicate less significant changes made.
- Lack of compatibility between old and new versions of s/w is a common problem.
- Sometimes updating s/w to a newer version will resolve compatibility issues.
- Some s/w is backwards compatible. If a program or application is backwards compatible, then the older versions of files, programs, and systems will work properly with newer versions.

### Software Testing
- Software Testing is the practice of integrating quality checks throughout the s/w development cycle.
- The purpose of testing is to check whether the s/w matches expected requirements and ensure error-free s/w.
- In order to test s/w the team writes "test cases". These test cases are written to verify the functionality of a s/w application and ensure requirements have been satisfied.
- A test case contains : steps, inputs, data and the expected corresponding outputs.
- Regardless of the test type or development method, test cases should always be written after requirements are finalized.
  
- Testing can be broadly classified into three categories:
  1. Functional Testing : Functional testing usually involves black box testing which is a method of testing without looking at source code or internal structure. Functional testing is only concerned with inputs and corresponding outputs of the system under test. It is entirely based on testing functional requirements. The goal is to test the functionality of the application making sure the application is usabl and accessible. Functional testing makes sure that when user errors or input edge cases do occur, the s/w handles those exceptions seamlessly by displaying appropriate error messages.
  2. Non-Functional Testing : Non-functional testing includes testing the application for attributes like performance, security, scalability, and availability.
  3. Regression Testing : Also called maintenance testing, confirms that a recent change to the application, such as a bug fix, does not adversely affect already existing functionality. Regression testing should occur when there has been a change in requirements or defects have been fixed.

- There are four testing levels :
  1. Unit Testing : Unit testing refers to tests that verify the functionality of a specific section of code, usually at the function level. It is performed by the s/w developer or engineer during the development phase of the SDLC. Unit testing aims to eliminate construction errors before code is integrated with other modules.
  2. Integration Testing : Prior to integration testing, smaller, independent code modules that passed unit testing are incorporated into the larger s/w application. After modules are integrated together, then integration testing can occur. Integration testing exposes bugs that occur when those smaller units of code interact with each other.
  3. System Testing : System Testing occurs after integration testing and is consucted on a complete, integrated system to evaluate the system's compliance with its specified requirements.
  4. Acceptance Testing : It is a formal testing w.r.t user needs, requirements, and business processes. It determines whether a system satisfies the needs of the users, customers, and other stakeholders. Acceptance testing is usually done by the customer or the stakeholders during the maintenance stage of the SDLC.















