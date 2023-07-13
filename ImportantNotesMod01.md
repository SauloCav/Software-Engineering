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


## Software modeling
- There is a gap between the following worlds: Requirements and code
- A model is an abstraction of the system being studied, not an alternative representation of it. That is, it is a simplification (focus on the useful and required) of reality.
- Models are cheaper to build than systems. Identified errors about models have a less disastrous impact.
- Systems modeling is the process of developing abstract models of a system, where each model presents a different view or perspective of the system.
- Software modeling runs through the entire software development lifecycle:
▸ Software process models: Examples of software process models, such as the waterfall model (Waterfall), the incremental model, the spiral model and the agile model;
▸ Requirement models: Requirements elicitation through user interviews, prototyping and group brainstorming;
▸ Software architecture models: Example of layered architecture, where the application is divided into layers, such as the presentation layer, the business layer and the data layer;
▸ Software Design Models: Using the UML to create class models, sequence diagrams, and activity diagrams to represent software design;
▸ Software Testing Templates: Example of automated unit tests, using tools like JUnit to test each unit of code separately;
▸ Software documentation templates: Source code documentation using tools like Javadoc and Doxygen to generate HTML documentation from code.
- Principles of modeling
1. The choice of model is important, including in terms of communication.
2. Each model can be expressed at different levels of accuracy.
3. The best models are connected to reality.
4. No model is enough, so focus on the essentials
### UML
- The UML is a visual language for modeling object-oriented systems;
- Each graphic element has a syntax and semantics;
- UML is independent of programming language and development process;
- UML can be used as:
1. Blueprint (detailed plan);
2. Programming language (automatic code generation, model-driven architecture)
3. Sketches (outlines, drafts)
- Templates are commonly used for:
1. Facilitate communication, visualization and discussion about the solution
2. As a way of documenting the system and the decisions made
3. Detailed guidance which can be used in implementation
4. Part-by-part complexity management
5. Reduction of development costs
6. Prediction of future system behavior
- EXISTING SYSTEMS: Clarifies what the system does and serves to identify strengths and weaknesses. Helps explain code that already exists. Also known as “Reverse Engineering”.
- NEW SYSTEM: Helps explain the requirements to other stakeholders. It helps to discuss alternative design proposals, before having any line of code implemented. Recognized as “Avante Engineering”.
- From different perspectives, we have different models to represent a system.
### External Perspective (CONTEXT MODELS)
- At an early stage of specifying a system, you must decide the boundaries of the system (context or environment);
- Boundary between the system and its environment;
- The definition of the system boundary is not free of value judgments.
- After defining the limits of the system, it is necessary to define the context and dependencies that the system has in its environment (simple architecture).
- The Activity Diagram aims to show activities that make up a system process and the flow of control.
### Interaction Perspective (INTERACTION MODELS)
- All systems involve some kind of interaction (between the system and the environment, or between components);
- System interaction modeling system highlights communication issues that may arise;
- Interaction modeling helps us understand whether the proposed structure for the system is likely to produce the required performance and reliability.
- Two approaches related to interaction modeling: <br>
▸ Use case modeling, used primarily to model interactions between a system and external actors; <br>
▸ Sequence diagrams, used to model interactions between system components, although external agents can also be included.
### Structural Perspective (STRUCTURAL MODELS)
- Models the organization of a system or the structure of the data that is processed;
- They can be static (project structure) or dynamic (in execution);
- You can create structural models when you are discussing and designing the system architecture.
- Class diagrams: <br>
▸ Shows the classes of a system and their associations; <br>
▸ Real-world object modeling; <br>
▸ Employs generalization, aggregation, and composition techniques. <br>
▸ Generalization is useful for keeping common information in one place. If there are changes, you don't need to query every class in the system. <br>
▸ Aggregation attempts to demonstrate that information from one object needs to be supplemented by information contained in one or more objects of another class. <br>
▸ Composition attempts to represent a stronger bond between whole-part objects to the point where one does not exist without the other 
### Behavioral Perspective (BEHAVIORAL MODELS)
- Models the dynamic behavior of the system while it is running;
- They show what happens or should happen when the system responds to a stimulus from its environment: <br>
▹ Data: Some incoming data needs to be processed by the system; <br>
▹ Events: Some events that happen trigger system processing.
- Data-driven programming is a programming model where the data itself controls the flow of the program. 
- In the case of event-driven programming, it is the event (not the data itself) that controls the flow of the program.


## Software Project
- "The most fundamental problem in Computer Science is the task of problem decomposition: how to break a complex problem into parts that can be solved independently".
- Project: <br>
▹ Break a "big problem" into smaller parts; <br>
▹ Resolution (or implementation) of the smaller parts solve (or implement) the "big problem".
- Modularity is an organizing principle.
- Software engineers must be aware of how they modularize the design because this has important quality implications.
- Desirable properties in modularization: <br>
▹ Each module is a well-defined system that can be used with other applications; <br>
▹ Each module has specific objectives; <br>
▹ Modules can be compiled separately and saved in the library; <br>
▹ Modules should be easier to use than build; <br>
▹ Modules are simpler on the outside than on the inside.
- Design is the process of defining the architecture, components, interfaces and other characteristics of a system or component.
- Design and implementation activities are closely linked, and when designing a project, you should consider emerging implementation issues: <br>
▹ Use UML? <br>
▹ Which webservices? <br>
▹ Which APIs? <br>
▹ Which platform?
- Software design paves the way between requirements and implementation of a system.
- The software requirements are analyzed in order to produce a description of the internal structure of the software that will serve as a basis for its construction.
### Good design properties
- Conceptual integrity <br>
▸ Functionalities of a system must be coherent; <br>
▸ System cannot be a "heap" of functionalities without any coherence or consistency; <br>
▸ Conceptual integrity = coherence and standardization of functionalities, design and implementation to facilitate the use and understanding of the system.
- Hiding Information <br>
▸ Classes should hide internal implementation details (using the private modifier), especially those subject to change. <br>
▸ Additionally, the class interface must be stable from the syntactic and semantic point of view;
- Cohesion
▸ Cohesion measures the degree to which elements of a given component (such as classes and methods) are related to each other. <br>
▸ High cohesion means that all elements within a component are directed toward performing a single task; <br>
▸ One of the best known metrics to calculate the "lack of cohesion" is called LCOM (Lack of Cohesion Between Methods).
- Coupling
▸ Coupling generally means the extent to which ("strength") two components depend ("relationship") on one another for successful execution; <br>
▸ Coupling can be very useful, especially when it occurs with the interface of a stable class that provides a service relevant to the source class. Bad coupling, on the other hand, should be avoided, as it is a coupling not mediated by stable interfaces. <br>
▸ Maximize cohesion (intra-module), minimize coupling (inter-module).
### SOLID
- SOLID is an acronym created by Michael Feathers after observing five principles of object orientation and code design — Created by Robert C. Martin (a.k.a. Uncle Bob). Used to make the software more change tolerant and easier to understand.
### S — Single Responsibility
#### A class should have a single responsibility
If a Class has many responsibilities, it increases the possibility of bugs because making changes to one of its responsibilities, could affect the other ones without you knowing.
#### Goal
This principle aims to separate behaviours so that if bugs arise as a result of your change, it won’t affect other unrelated behaviours.
### O — Open-Closed
#### Classes should be open for extension, but closed for modification
Changing the current behaviour of a Class will affect all the systems using that Class.
If you want the Class to perform more functions, the ideal approach is to add to the functions that already exist NOT change them.
#### Goal
This principle aims to extend a Class’s behaviour without changing the existing behaviour of that Class. This is to avoid causing bugs wherever the Class is being used.
### L — Liskov Substitution
#### If S is a subtype of T, then objects of type T in a program may be replaced with objects of type S without altering any of the desirable properties of that program.
When a child Class cannot perform the same actions as its parent Class, this can cause bugs.
If you have a Class and create another Class from it, it becomes a parent and the new Class becomes a child. The child Class should be able to do everything the parent Class can do. This process is called Inheritance.
The child Class should be able to process the same requests and deliver the same result as the parent Class or it could deliver a result that is of the same type.
The picture shows that the parent Class delivers Coffee(it could be any type of coffee). It is acceptable for the child Class to deliver Cappucino because it is a specific type of Coffee, but it is NOT acceptable to deliver Water.
If the child Class doesn’t meet these requirements, it means the child Class is changed completely and violates this principle.
#### Goal
This principle aims to enforce consistency so that the parent Class or its child Class can be used in the same way without any errors.
### I — Interface Segregation
#### Clients should not be forced to depend on methods that they do not use.
When a Class is required to perform actions that are not useful, it is wasteful and may produce unexpected bugs if the Class does not have the ability to perform those actions.
A Class should perform only actions that are needed to fulfil its role. Any other action should be removed completely or moved somewhere else if it might be used by another Class in the future.
#### Goal
This principle aims at splitting a set of actions into smaller sets so that a Class executes ONLY the set of actions it requires.
### D — Dependency Inversion
#### High-level modules should not depend on low-level modules. Both should depend on the abstraction.
#### Abstractions should not depend on details. Details should depend on abstractions.
Firstly, let’s define the terms used here more simply
#### High-level Module(or Class): Class that executes an action with a tool.
#### Low-level Module (or Class): The tool that is needed to execute the action
#### Abstraction: Represents an interface that connects the two Classes.
#### Details: How the tool works
This principle says a Class should not be fused with the tool it uses to execute an action. Rather, it should be fused to the interface that will allow the tool to connect to the Class.
It also says that both the Class and the interface should not know how the tool works. However, the tool needs to meet the specification of the interface.
#### Goal
This principle aims at reducing the dependency of a high-level Class on the low-level Class by introducing an interface.
### Prefira Composição a Herança
- When a subclass inherits from a superclass, the subclass acquires all the behaviors of the subclass. Inheritance will make a hierarchy of classes. Relation "is a." The employee is a person.
- Composition contains instances of other classes that implement the desired functionality. "Has a" relationship The car has an engine.
- Inheritance exposes implementation details of parent classes to subclasses. Therefore, inheritance is often said to violate the encapsulation of parent classes. The implementation of the subclasses becomes so tightly coupled to the implementation of the parent class that any change in the latter can force modifications in the subclasses.
- Use inheritance when you really need it, not just to reuse some code. When you're thinking about using inheritance, ask yourself if the subclass really is a more specialized version of the superclass, otherwise in a few days you'll experience a mess.
### Demeter
- Demeter was the name of a research group at an American university (Northeastern University, in Boston, USA).
- Summary: avoid long "chains" of method calls ("don't talk to strangers").


## Software Architecture
- Architecture is always design. Design is not always architecture.
- Software architecture design (sometimes called high-level design): Develops the top-level structure and organization of the software and identifies the various components.
- Detailed software design: specify each component in sufficient detail to facilitate its construction
- Focus is no longer on small units (eg classes and interfaces):
- But larger and more relevant units;
- Packages, modules, subsystems, layers, services, etc.
- Definition of relevance depends on the system.
- Software architecture is the fundamental organization of a system, embodied in its components, their relationships with each other and with the environment, and the principles that govern their design and evolution.
- Software architecture is the structure or structures of the system, comprising software elements, the externally visible properties of those elements, and the relationships between them.
- Bases for understanding software architecture
1) Captures the structure of the system in relation to its components and how they are related;
2) Defines the design rules of the whole system, considering how a system can change;
3) Makes explicit the role of abstraction (externally visible properties) and various architectural views (system structures).
- The software architecture goes beyond the calculation algorithms and data structures; designing and specifying the general structure of the system emerges as a new type of problem. Structural issues include overall organization and control structure; communication, synchronization and data access protocols; assignment of functionality to design elements; physical distribution; composition of design elements; sizing and performance; and selection among design alternatives.
- Architectural design is concerned with understanding how a system should be organized and with the overall structure of that system. Ensuring that business objectives, quality attributes and constraints are met.
- Software Architecture
1) Components
2) Responsibilities
3) Relationships
4) Strategies
- Software architecture is important as it affects the performance and robustness as well as the deployability and maintainability of a system. Individual components implement functional requirements, while non-functional requirements depend on the architecture.
- Therefore, the architectural model can serve: <br>
▹ As a document of what was designed; <br>
▹ To facilitate discussion and negotiation with customers, developers and managers; <br>
▹ Complexity management tool;
- System architects need to make a series of structural decisions:
1. Is there a generic application architecture that can be reused?
2. How will the system be distributed over a number of processors?
3. What architectural patterns or styles can be used?
4. What will be the fundamental approach to structuring the system?
5. How will the structural components of the system be decomposed?
6. How will the architectural project be evaluated?
7. How should the system architecture be documented?
- The architecture of a software system can be based on a certain pattern or style of architecture.
- An architectural pattern proposes a higher-level organization for software systems, including their main modules and the relationships between them.
- Architectural patterns or styles: catalog of a series of successfully used structures that facilitate certain types of component communication.
- These patterns are reusable blueprints that describe the structure and interaction between collections of components.
- An architectural pattern expresses a fundamental structural organization scheme for software. It provides a set of predefined subsystems and specifies their responsibilities, and includes rules and guidelines for organizing the relationship between them.
- You can use architectural patterns in a number of ways:
1. As the starting point for the architectural design process;
2. As a project checklist;
3. As a way to organize the work of the development team;
4. As a way to evaluate components for reuse;
5. As a vocabulary to talk about types of applications.
6. How will the architectural project be evaluated?
7. How should the system architecture be documented?
8. To avoid the Big Ball of Mud.
- Try to avoid the Big Ball of Mud (architectural anti-pattern), that is, a module can use practically any other module in the system; i.e. system is a "mess".
### Client-Server Architecture:
- The client-server architecture illustrates an organization widely used for distributed systems, at runtime;
- A client-server system is organized as a set of services and associated servers and clients that access and use the services.
- Examples: Print Service, File Service, Web Service.
- Considered architecture of distributed systems, but the logical model of services can be implemented in a single computer;
- Services and servers can be modified without affecting other parts of the system;
- The client makes a request to a server and waits until it receives a response.
- Most systems that use large amounts of data are organized around a shared database or repository.
- Suitable for applications where data is generated by one component and used by another.
- It is a client-server architecture that allows services to store/access data.
### Layered Architecture:
- System functionality is organized hierarchically into separate layers, and each layer only depends on the features and services offered by the layer immediately below it.
- Promotes separation of concerns and makes the system modular and scalable;
- Each layer can be developed and tested independently of the others, facilitating the maintenance and development of new features;
- Allows you to replace or update a layer without affecting the others, as long as the interface between them is preserved.
### MVC architecture:
- Originally, the Model-View-Controller (MVC) architecture emerged in the late 70's with the Smalltalk language.
- View: layer of interaction with the user and graphical presentation. It just displays the data, through html or xml;
- Controller: responsible for receiving all user requests. Classes that handle and interpret events generated by input devices, such as mouse and keyboard. Requests changes to the Model.
- Model: whenever you think about data manipulation. Responsible for reading and writing data, as well as its validations.
- Conceptual organization that favors work specialization, multi-use of the model and testability.
### Architecture with Microservices:
- Monoliths: at runtime, system is a single process (process here is operating system process).
- Modules (or sets of modules) become independent processes at runtime.
- These modules are smaller than a monolith: Hence the name microservice.
- Microservices are not a silver bullet. There are high quality monoliths (see StackOverflow).
- Migration can be gradual (microservices gradually extracted from the monolith).
- Microservices are an example of applying Conway's Law, which states that companies tend to adopt software architectures that are copies of their organizational structures.
### Message Oriented Architecture:
- Object orientation is about passing messages. Messaging is about communication.
- Architecture for distributed applications.
- Clients do not communicate directly with servers.
- But with an intermediary: message queue (or message broker).
- Message Oriented Architecture enables loose coupling between clients and servers.
- In Message Driven systems, each component sends items to a fixed recipient. In Event Driven systems, on the other hand, each component produces data items with a fixed sender and shares them with any consumer.
### Event Driven Architecture:
- An event-driven architecture consists of Event Producers that generate a stream of events and Event Consumers that "listen" to the events. Producers and Consumers do not know each other.
- In Event Sourcing, events are recorded in a log. Consumers are not required to subscribe to an event stream.
- Publish-Subscribe model (pub/sub): systems can: (1) publish events (publishers); (2) subscribe to events (subscribers); (3) be notified of the occurrence of events.
### Duct and Filter architecture:
- Provides a framework for systems that process a stream of data, ie data-driven modeling.
- Data flows from one to another and transforms as it moves through the sequence. Each processing step is implemented as a transformation: <br>
▹ Pipes: connector that transmits data between filters. Pipes are used to store the output of one filter while it is not read by the next filter in the sequence; <br>
▹ Filters: component that transforms the data. Each filter (filter) works independently, which expects a given input to produce a given output; <br>


