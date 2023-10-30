#  Software Methodologies

**What is Software Design Stratgeies**

Software design is a process to conceptualize the software requirements into software implementation. It does so by taking the user requirements and finding the optimum solution. A good software design strategy identifies these requirements as challenges and provides the most optimal solutions.

**1.What do we mean by coupling and cohesion when discussing structured design?**

Coupling is communicating between different modules whereas, cohesion is the measure of how closely the compoments within a module. 
In Structured Design the goal is to minimize coupling between modules. This is because low coupling makes the system more modular and easier to read, maintain and modify. Structured design promotes the use of well defined interfaces.

**2.What is the difference between top-down and bottom-up design? Which best describes a function oriented design?**

**Top-down design** 
Top-down design is a design approach where the design starts from the system as a whole and then the complete system is then divided into smaller sub-applications with more details. 

Each part again goes through the top-down approach till the complete system is designed with all the minute details. TopDown approach is also termed as breaking a bigger problem into smaller problems and solving them individually in recursive manner.

Top-Down Model is followed by structural programming languages like C, Fortran, etc.

**Bottom-down design** 
Bottom down focusses on identifying and resolving smallest problems and then integrating them together to solve the bigger problem, assembling them into a complete system.

Bottom-Up Model is mainly used by object oriented programming languages like Java, C++, etc.


In terms of Function Oriented Design a bottom up design will be more suited on the basis that based that  it aligns with the principles of modularity(class), incremental development, readability, and code reusability.

**3.In which design methodology would a class diagram be most useful?**
In Design Methodology, a class diagram would provide more of a benefit with OOP (Object Oriented Design) as it illustrates the classes and interfaces. This is particulary good for software applications and databases.


**4.What are the four pillars of object oriented programming? Give a single-sentence description of each.**


The foundations of Object-Oriented Programming (OOP) consist of four key principles:

**Encapsulation:**
Encapsulation involves cbonding both data and the methods that manipulate that data into a class. This restricts access to some of the object's components while exposing others, providing data protection and a clear interface for interacting with the object.

**Inheritance:**
Inheritance allows a new class (subclass or derived class) to inherit attributes and behaviors from an existing class (known as the superclass or base class). This promotes the reuse of code and establishes an "is-a" relationship between classes.

**Polymorphism:**
Polymorphism enables objects from distinct classes to be treated as instances of a shared superclass. This concept facilitates method overriding, permitting different classes to offer their own implementations of methods, thereby enhancing flexibility and extensibility.

**Abstraction:**
Abstraction involves simplifying the intricacies of reality by modeling classes based on their fundamental characteristics and disregarding irrelevant details. This process offers a clear, high-level perspective on an object's behavior and attributes

**5.What is the strategy pattern? How would its implementation differ between a functional and object oriented system?**

A behavioural design pattern called the Strategy Pattern encompasses a collection of algorithms and defines them so they can be used interchangeably. Without changing its structure, it enables the client to select an algorithm at runtime from a family of algorithms.

The Strategy Pattern would be implemented in a functional system by designating procedures or functions as strategies. Depending on the chosen approach, the client code would call these functions, causing behaviour to change dynamically.

The Strategy Pattern is usually implemented with classes and interfaces in an object-oriented system. Every tactic is contained within a distinct class that carries out a shared interface. By switching objects that implement the same interface, the client code can transition between different strategies.

**6 Imagine you is creating a new online payment system. In order to gain maximum market share it can't be tied to a particular sector - it needs to work just as well when ordering a takeaway as when buying a new coat. Which design methodology would you suggest following? Give some justification for your decision.**

To develop an online payment system applicable to diverse sectors such as ordering takeaways or purchasing clothing, I believe it is best adopt an Agile Design Methodology, specifically a version that incorporates Iterative and Incremental Development.

Adaptability: Agile methodologies tend to excel in adapting to changing requirements, a crucial quality in a dynamic market where the payment system must cater to various sectors. 

Continuous Feedback: Agile methodologies foster continuous feedback from stakeholders, allowing the system to evolve based on real user requirements and experiences ensuring a high degree of alignment with market needs.

Incremental Delivery: Breaking the project into smaller increments or iterations enables the swift delivery of a functional product. Additional features can then be added incrementally, simplifying the process of entering diverse sectors without the need for an exhaustive upfront design.

Cross-Functional Teams: Agile emphasizes the use of cross-functional teams capable of collaborating on various aspects of the system. This collaborative approach is particularly beneficial for a system intended to serve multiple sectors effectively.

User-Centric Design: Agile places a strong emphasis on user-centric design and engagement. This approach is instrumental in creating a user-friendly payment system that is adaptable across different sectors.

By adhering to Agile principles, the development team ensures flexibility, responsiveness, and a customer-oriented approach, making it the optimal choice for a payment system targeting widespread market adoption across diverse sectors.