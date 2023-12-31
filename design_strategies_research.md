# SOFTWARE DESIGN METHODOLOGIES

## Types of strateges 

### - Structured Design
### - Function Oriented Design
### - Object Oriented Programming

### Structured Design

#### 
This design strategy is top down in which a system is broken down
into functional modules where they each can be described as having 
inputs, processing and outputs.The main objective of structured 
design is to minimize the complexity and increase the modularity 
of a program.

### Function Oriented Design

####
Function oriented design is the result of focusing attention to 
the function of the program where the design is decomposed into 
a set of interacting units where each unit has a clearly defined 
function. These functions make up a system which can be 
considered to be the top view of all functions.

### Object Oriented Design

####
Object oriented programming works around the entities and their 
characteristics instead of functions involved in the software 
system. This design strategies focuses on entities and its 
characteristics. The whole concept of software solution 
revolves around the engaged entities.


## Task

####
1. What do we mean by coupling and cohesion when discussing structured design?

Cohesion is how related a module (such as a class) is with it's elements (methods).
High cohesion is ideal because all the elements in the class are tightly 
related which mean they strongly represent the behaviour of the class.
Coupling is the degree of interdependence between classes. Ideally, you would want
to have low coupling to reduce the risk of of errors when making changes.

2. What is the difference between top-down and bottom-up design? Which best describes a function oriented design?

The difference between top-down and bottom-up design is that top-down design focusses 
on breaking down a general system into smaller parts which work together to create functionality. 
Therefore, function oriented programming would be best desrcribed by a top-down design because it is 
a design which is decomposed into a set of interacting units where each unit has a clearly defined function. 
Whereas a bottom-up design starts with more specific and basic components which work together to create 
higher-level components to create one whole system. 

3. In which design methodology would a class diagram be most useful?

A class diagram would be most useful when using an object oriented design methodology. This is because
OOP focusses on classes, their characteristics and how each class interacts with other classes.

4. What are the four pillars of object oriented programming? Give a single-sentence description of each.

- Abstraction: the process of hiding internal details or processes from the user.
- Encapsulation: a way to keep code organized and separate from other codes in the system.
- Inheritance: when a class inherits the methods and properties of another class.
- Polymorphism: allows developers to create multiple methods with the same name, but with different implementations.

5. What is the strategy pattern? How would its implementation differ between a functional and object oriented system?

Objects are created which represent various strategies and a context object whose behavior varies as per its strategy object. The difference between strategy pattern and the other strategies is that a family of algorithms is defined first, each one is encapsulated and interchangeable. This means that the program can be flexible to chose any of the algorithms at runtime for specific task.


6. Imagine your is creating a new online payment system. In order to gain maximum market share it can't be tied to a particular sector - it needs to work just as well when ordering a takeaway as when buying a new coat. Which design methodology would you suggest following? Give some justification for your decision.

Object oriented programming would be best for a versatile payment system because you can have an organised set classes that represent real-world entities such as payments for takeaways and for buying a new coat. This is because OOP uses encapsulation and promotes modularity which means that you can have reusable methods/algorithms. This makes the system easy to maintain and extend. Therefore, new payment methods can be added without dirupting the existing code, which means less errors and bugs. Additionally, abstraction can be used which allows you to use the same methods for different scenarios.


