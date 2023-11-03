# Software Design Methodologies

## Tasks

1. What do we mean by coupling and cohesion when discussing structured design?

Coupling is the measure of how dependent one module is with a another module within a program.Cohesion is how closely the responsibilites of elements within a single module are to each other. For a structured design to be considered good, a low coupling and high cohesion would be ideal.

2. What is the difference between top-down and bottom-up design? Which best describes a function oriented design?

The difference between both design is that the top-down design follows a decomposition approach, where the systems are broken down into smaller(sub)-systems where more detail are added until the design requirements are met, whereas a bottom-down design follows a composition appraoch, tackling the smalling systems first and then integrating them together. A top-down design would best describe a function oriented design.

3. In which design methodology would a class diagram be most useful?

Object oriented design as there is more of an emphasis on classes and objects

4. What are the four pillars of object oriented programming? Give a single-sentence description of each.

   - **Abstraction** - presenting the essential characteristics of an object and ignoring irrelevant details for simplified representation.
   - **Encapsulation**- hidng the complexity of the inner workings of an object from the programs and the programmers that make use of it can also often be referred to information hiding.
   - **Inheriatnce**- a class that derives  its methods and properties from another class i.e the hierachy of class based on a "is a " relationship.
   - **Polymorphism**- the ability of an object to act differently under different conditions


5.  What is the strategy pattern? How would its implementation differ between a functional and object oriented system?

The strategy pattern is a design pattern that allows for dynamic changes in the behaviour of an object by encapsulating it into diffrent strategies and have them called interchangeably at runtime from the client.

The way in which object oriented system implements this strategy pattern is using an interface, with this there will be multiple concrete implementations of the interface.

For functional system an interface and a different strategy class is not needed, functions are used to implement these different strategy. where functions can take in other functions as parameters using the idea of higher order functions.


6. Imagine your creating a new online payment system. In order to gain maximum market share it can't be tied to a particular sector - it needs to work just as well when ordering a takeaway as when buying a new coat. Which design methodology would you suggest following? Give some justification for your decision.

I think a Function-oriented design approach would be best suited in this scenario because this functional approach emphasises what the system will do, and since this is a payment system, this should be where our main focus should lie. Another benefit of using this approach is that we can divide these systems into sub-systems that will ensure that they can't be tied to a particular sector, with the help of the decomposition approach that the function-oriented design uses,so we get the bigger picture of the systems and then sub-divide them.










