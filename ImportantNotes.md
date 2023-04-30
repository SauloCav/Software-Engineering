# Software Engineering


## Fundamentals
- Critical factors for software failures: <br>
▹ Increased demand: the techniques help us to build larger and more complex systems, demands change; <br>
▹ Low expectations: It is relatively easy to write computer programs without using techniques and methods of software engineering. We need education and training.
- Software engineering involves sociotechnical activities which aim to support professional software development (hard skills and soft skills), rather than individual programming.
- SOFTWARE: This is not just the program itself, but all associated documentation and configuration data needed to make this program operate correctly.
- Essential attributes of good software: maintainability; trust and protection; efficiency and acceptability.
- ES emerged in the context of the so-called Software Crisis during the 70s. <br>
▹ Term coined by Margareth Hamilton; <br>
▹ Meeting at a conference organized by the North Atlantic Treaty Organization in 1968; <br>
▹ High costs, delays in delivery, low reliability, high unmet demand, difficult maintenance, etc; <br>
▹ Too much emphasis on programming than principles and best practices; <br>
▹ Lack of a system in the development process.
- Software process is a sequence of activities leading to the production of a software product.
- The ability to solve problems effectively and efficiently is the goal of every engineer.


## Software Processes
- A traditional engineering process consists of a set of interrelated activities that transform one or more inputs into outputs while consuming resources to perform the transformation.
- A software process is a set of related activities that lead to the production of a software product.
- Software processes are specified for a number of reasons: <br>
▹ To facilitate human understanding, communication and coordination; <br>
▹ Assist in the management of software projects; <br>
▹ Measure and improve the quality of software products efficiently; <br>
▹ Support process improvement; <br>
▹ Provide a foundation for automated process execution support.
### Cascade model
- Proposed in the 70's and inspired by traditional engineering processes.
- Design with two features: <br>
▹ Detailed planning (big upfront design); <br>
▹ Activities sequentially in different phases.
- In principle, the result of each stage is the approval of one or more documents. The next stage should not be started until the previous stage is completed.
- Benefits:
1) Easy to understand, easy to use
2) Provide structure for inexperienced employees
3) Milestones are well understood
4) Defines the stability of the requirements
5) Good for management control (plan, team, follow-up)
6) Works well when quality is more important than cost or schedule.
- Difficulties
1) Customers don't know what they want (in a software).
2) It is no longer possible to spend “1 year” gathering requirements, 1 year designing, 1 year implementing, etc.
3) Excessively detailed documentation.
### Incremental model
- This approach merges requirements activities (plan driven or agile), construction and testing. The system is developed as a series of versions (increments), with each version adding functionality to the previous one.
- Benefits:
1) The cost of accommodating changes in customer requirements is reduced;
2) It's easier to get feedback from customers about the development that was done;
3) It is possible to achieve rapid delivery and implementation of useful customer software, even if all functionality is not included.
- Problems:
1) The process is not as visible. Managers need regular deliverables to measure progress;
2) The structure of the system tends to degrade with the addition of new increments.
### Boehm's spiral model
- Proposed by Barry Boehm in 1986, the spiral model is an example of an evolutionary software process model that couples the iterative nature of prototyping with the controlled and systematic aspects of the waterfall model.
- As software evolves cyclically as the process progresses, the developer and customer better understand and react to risks at each evolutionary level while risk is reduced.
- Each lap is divided into four sectors:
1) Definition of objectives: objectives, constraints and risks are identified. A management plan is developed;
2) Risk assessment and reduction: an analysis of the identified risks is carried out and measures are taken to reduce them;
3) Development and validation: the most appropriate development model is decided.
4) Planning: the project is reviewed and a decision is made about the continuity of the model in a new turn of the spiral.
- Advantages:
1) Provides an early indication of insurmountable risks without much cost;
2) Changes are accommodated;
3) The development phases can be determined by the project manager, according to the complexity of the project;
4) Users can be closely linked to all stages of the lifecycle and can see the system early because of rapid prototyping tools.
- Difficulties:
1) Time spent on very substantial risk assessment for small or low-risk projects;
2) The time spent planning, redefining objectives, doing risk analysis and prototyping can be excessive;
3) The model is complex;
4) Experience in risk assessment is required.
### Rational unified process
- The Unified Process (UP), proposed in the late 90s, is another example of an iterative development method.
- UP was proposed by professionals linked to a consulting and software development support tool company called Rational, which in 2003 would be bought by IBM. Therefore, the method is also called the Rational Unified Process (RUP);
- Benefits
1) Allows dealing with changing requirements, regardless of whether they come from the customer or the project itself;
2) Emphasizes the need for accurate documentation;
3) It forces integration to happen throughout software development, more specifically in the build phase.
- Difficulties
1) Depends on the ability of professionals to assign activities to individuals who then must produce pre-planned outputs in the form of artifacts;
2) Integration into the development process can have an adverse impact on some more fundamental activities during the testing stages;
3) Complex, especially for smaller companies, teams or projects.


## Agile Development 
- In the 1980s and early 1990s, there was a widespread view that the best way to get the best software was through careful project planning. 
- During the 1990s, there was dissatisfaction with these heavy-handed approaches to software engineering;
- Allow the development team to focus on the software itself, and not on its design and documentation;
- Reduce process bureaucracy.
- While there are many approaches to agile software development, they share some key characteristics:
1) The specification, implementation and testing processes are interspersed in an iterative manner;
2) The system is developed in a series of versions (increments);
3) Good practices emerge to deliver value.
- Important points: <br>
▸ They present processes, but “light”; <br>
▸ Less emphasis on documentation; <br>
▸ Less emphasis on big upfront design; <br>
▸ Constant customer involvement; <br>
▸ New practices (refactoring, code review, continuous integration); <br>
▸ No method is a silver bullet; <br>
▸ Processes are adaptable.
- Difficulties:
1) Success depends on a willing customer;
2) Members may not have the personality for the intense involvement required;
3) Prioritizing changes can be difficult;
4) Keeping it simple takes extra work;
5) Many organizations are very attached to established processes;
6) Definition of contracts due to their dynamic nature.
### Extreme programming
- Extreme Programming (XP) was coined by Kent Beck (2000), as the approach was developed to boost known good practices, such as iterative development, to “extreme” levels.
- Based on Values, Principles and Practices.
- Pair programming: To develop the software, programmers work in pairs. Pairs are dynamically created so that all team members work with each other.
- User Stories: Requirements are expressed as scenarios (called user stories), which are implemented directly as a series of tasks.
- Test Driven Development: Programmers work in pairs and develop tests for each task before writing code.
- When new code is integrated into the system, all tests should run successfully. There is a short gap between system releases.
- XP takes an extreme approach to incremental development: <br>
▹ New versions of the software can be built several times a day and releases are delivered to customers periodically; <br>
▹ Release deadlines are never disrespected; <br>
▹ When a developer creates a new version, he must run all existing automated tests, as well as tests for the new functionality; <br>
▹ Accept that changes will happen and reorganize the software when those changes actually happen; <br>
▹ Software must be constantly refactored to alleviate architectural degradation.
### Scrum
- Scrum is a lightweight framework that helps people, teams and organizations generate value through adaptive solutions for complex problems.
- Fundamentals of Scrum: <br>
▹ Transparency <br>
▹ Inspection <br>
▹ Adaptation 
- Roles of the Scrum Team (All have the same hierarchical level): <br>
▹ Product Owner (PO) <br>
▹ Developers <br>
▹ Scrum Master
- Scrum artifacts represent work or value. They are designed to maximize transparency of key information. Thus, all who inspect them have the same basis for adaptation: <br>
▹ Product Backlog (Product Goal) <br>
▹ Sprint Backlog (Sprint Goal) <br>
▹ Increment (Definition of Done) 
- The objective of the product backlog is to generate more transparency during the development of a project, to level the understanding of all those involved about what needs to be done and, especially, to maximize the possibility of constant evaluations and adaptations of tasks throughout the process.
- For each story there is an estimate of difficulty defined through story points.
- Planning Poker: brings together the opinion of several specialists, for a quick estimate of the project.
- Events are used in Scrum to create regularity and minimize the need for undefined meetings.
- Criteria for story completion: <br>
▸ External quality: <br>
▹ Acceptance tests (black box or functional) <br>
▹ Non-functional tests (eg performance, usability) <br>
▸ Internal quality: <br>
▹ Unit tests; <br>
▹ Code review. <br>
- Agile Scrum methodology phases: <br>
▸ Step 1:  Product Backlog Creation <br>
▸ Step 2: Sprint planning and creating backlog <br>
▸ Step 3: Working on sprint <br>
▸ Step 4: Testing and Product Demonstration <br>
▸ Step 5: Retrospective and the next sprint planning


## Requirements Engineering
- Functional requirements are statements of services the system should provide, how the system should react, and how the system should behave.
- Non-functional requirements are restrictions on the services or functions offered by the system. They apply to the system as a whole.
- Product requirements: Need or restriction in the software to be developed
- Process requirements: Restriction on software development.
- System requirements: Requirements for the system as a whole. It encompasses user requirements, requirements from other interested parties (such as regulatory authorities and software architects), and requirements without an identifiable human source (hardware, firmware, etc).
- Software requirements: Software requirements are derived from system requirements. Restricted to end user and customer requirements.
- Requirements Engineering is the name given to the set of activities related to the elicitation, analysis, specification and validation of requirements.
### Elicitation and analysis
- Elicitar (or elicitate): "make come out, expel, expel".
- Objective requirements analysis:
1) Classification of requirements (type, priority, scope, etc);
2) Conceptual modeling to understand the problem and solution;
3) Conflict resolution (incompatibilities, disagreements, etc).
- Difficulties in elicitation: <br>
▸ Stakeholders often do not know what they want from a system; <br>
▸ Stakeholders express requirements in their own terms and with implicit knowledge of their own work; <br>
▸ Different stakeholders have different requirements and may express these differences in different ways; <br>
▸ Political factors can influence the requirements of a system; <br>
▸ The economic and business environment in which the analysis takes place is dynamic.
- User Stories = 3C’s (Card + Conversations + Confirmation): <br>
▹ Card: used by the PO to write a feature to be implemented; <br>
▹ Conversation: verbal communication between the client and the team to understand each card; <br>
▹ Confirmation: scenarios that will be used by the PO to accept the implementation of the story (written on the back of the card), ie “acceptance tests”.
- How to write a user story? <br>
▹ As a... (role or actor) (Who) <br>
▹ I want to... (capacity or functionalities required) (What) <br>
▹ So that... (why is it of business value or benefit) (why)
- Characteristics of good user stories: <br>
▹ Independent <br>
▹ Open for Negotiation <br>
▹ Add Value <br>
▹ Estimables <br>
▹ Brief <br>
▹ Testable
- Formal or informal INTERVIEWS are part of most requirements engineering processes: <br>
▹ Structured interviews, in which the stakeholder responds to a predefined set of questions; <br>
▹ Semi-structured interviews, in which the stakeholder responds to a predefined set of questions, but there is still room for other questions that arise; <br>
▹ Open interviews, in which there is no predefined agenda.
- Effective interviewers have two characteristics:
1) Are open to new ideas, avoid preconceived ideas about requirements and are willing to listen to stakeholders;
2) They encourage the interviewee to participate in discussions with a springboard question, a requirements proposal or working together on a prototype of the system.
- USE CASES are a requirements discovery technique which identifies actors in an interaction, this being supplemented by other graphical models.
- More detailed requirements specification document;
- Use Case is not so common with agile methods;
- An actor performing some operation with the system;
- Include normal flow and extensions;
- However, use cases cannot portray all the subtleties of how the business is run. For this, you need business rules, that is, written and unwritten rules that dictate how a company or agency conducts its business.
- ETHNOGRAPHY is an observation technique that can be used to understand operational processes which helps to extract support requirements.
- Ethnography helps uncover implicit requirements that reflect the real ways people work.
- People find it very difficult to express the details of their work.
- Social and organizational factors can become clear only when analyzed by an impartial observer.
### Requirements specification
- Requirements specification refers to the production of a software requirements document (DRS) that can be systematically reviewed, evaluated and approved.
- The DRS lays the groundwork for agreement between customers and contractors on what the software product should do, as well as what it is not expected to do;
- DRS:
1) Commitment to communicating requirements to customers;
2) Define requirements in detail for developers and testers;
3) Inclusion of information on system evolution;
4) Information on anticipated changes;
5) No need to present details of architecture or project;
- Requirements specification refers to the production of a software requirements document (DRS) that can be systematically reviewed, evaluated and approved.
- The DRS lays the groundwork for agreement between customers and contractors on what the software product should do, as well as what it is not expected to do;
- DRS:
1) Commitment to communicating requirements to customers;
2) Define requirements in detail for developers and testers;
3) Inclusion of information on system evolution;
4) Information on anticipated changes;
5) No need to present details of architecture or project;
- In the context of agile methodologies, it uses user stories that form the product backlog.
- The imprecision in the specification of requirements is the cause of many problems in software engineering;
- The specification of the functional requirements of a system must be complete and consistent;
- Common causes of errors: system complexity and number of stakeholders.
- Software requirements are often written in natural language, but in software requirements specification this can be supplemented by formal or semi-formal descriptions.
- Analyze the system and develop a set of graphical system models, such as use-case models, which then serve as a system specification.
- For complex systems, you can demand in addition to the software requirements document: <br>
▹ System definition document: Lists system requirements along with background information about the overall goals of the system, its target environment, and a statement of constraints, assumptions, and requirements. <br>
▹ System requirements document: System requirements specification is a systems engineering activity and is outside the scope of ES.
According to IEEE 830, the most common quality criteria for a good requirements specification are: <br>
▹ Correct; <br>
▹ Complete; <br>
▹ Clara; <br>
▹ Consistent; <br>
▹ Modifiable; <br>
▹ Prioritized; <br>
▹ Verifiable; <br>
▹ Traceable.
### Requirements validation
- Requirements documents may be subject to verification and validation procedures.
- It is important to verify that a requirements document complies with company standards and that it is understandable, consistent and complete;
- The requirements can be validated to ensure that the software engineer understood the requirements;
- A prototype is an early version of a software system, used to demonstrate concepts, try out design options, and find out more about the problem and its possible solutions.
- An MVP is the version of a new product that allows a team to collect as much information and learning about customers as possible with the least amount of effort and time.
- In an MVP, you decide what is minimal, but it is the customer who decides whether the product is viable. Love the problem not the solution or technology you are using.
- In short, prototyping helps us understand the viability of an idea and MVP is more about validated learning, which is one of the principles of Lean Startup.
### Requirements management
- Change is inevitable in all major software projects. Requirements change as the business responds to external pressures and priorities change.
- Change increases costs because it usually means that work must be redone. Approaches to cost reduction:
1) Change prevention, includes activities capable of anticipating possible changes before any rework is necessary;
2) Change tolerance, where the process is designed so that changes can be accommodated at relatively low cost.
- Planning: Essential stage in the requirements management process. Determines the level of detail required in requirements management.
- Change management: Decides whether the benefits of implementing new requirements justify the implementation costs. All proposed changes are handled formally.
