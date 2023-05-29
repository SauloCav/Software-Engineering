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
▸ Cohesion measures the degree to which elements of a given component (such as classes and methods) are related to each other.
▸ High cohesion means that all elements within a component are directed toward performing a single task;
▸ One of the best known metrics to calculate the "lack of cohesion" is called LCOM (Lack of Cohesion Between Methods).
- Coupling
▸ Coupling generally means the extent to which ("strength") two components depend ("relationship") on one another for successful execution;
▸ Coupling can be very useful, especially when it occurs with the interface of a stable class that provides a service relevant to the source class. Bad coupling, on the other hand, should be avoided, as it is a coupling not mediated by stable interfaces.
▸ Maximize cohesion (intra-module), minimize coupling (inter-module).
### SOLID
- SOLID is an acronym created by Michael Feathers after observing five principles of object orientation and code design — Created by Robert C. Martin (a.k.a. Uncle Bob). Used to make the software more change tolerant and easier to understand.

























