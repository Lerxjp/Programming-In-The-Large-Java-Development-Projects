# Programming-In-The-Large-Java-Development-Projects
## Overview
Project Learnings & Course AimsObject-Oriented Implementation: Implemented object-oriented programs precisely according to detailed Javadoc specifications. This involved building a comprehensive simulation of a cargo port system from a provided template.  
Software Testing: Tested components of the object-oriented programs using the JUnit 4 testing framework. This required writing test suites capable of distinguishing between correct and incorrect class implementations.
Advanced Java Concepts: Wrote and documented code utilizing key language features, including inheritance for classifying various ship types and statistics evaluators. Implemented specific interfaces such as Tickable for time simulation and Encodable for saving states.
Applied exception handling and utilized File I/O to decode the port simulation state from machine-readable string representations. 
GUI Development: Applied object-oriented concepts to connect a core system model to a Graphical User Interface (GUI) built with JavaFX. 
Software Maintainability: Practiced the disciplined individual habits required to ensure large, complex software systems remain maintainable. This included strict adherence to a style guide, passing Checkstyle automated formatting, and undergoing manual design reviews.
Code Quality and Best Practices: Analyzed code to judge whether it follows established good practices for object-oriented design. This process involved identifying and resolving issues such as magic numbers, duplicated code, poor variable naming, and insufficient inline or Javadoc commenting.
Specification Analysis: Interpreted specifications for program modules to ensure classes, methods, member variables, and access modifiers were implemented exactly as required, without adding unrequested public methods or fields.  

## P1 and P2: Cargo Port System Simulation
This project is a simple simulation of a cargo port system. It manages the movement of ships around a port, including loading and unloading ships at quays, storing cargo at the port temporarily, and managing a queue of ships waiting offshore to dock at the port. The system also keeps track of statistics relating to the port's operations.
