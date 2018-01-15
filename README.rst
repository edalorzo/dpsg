Design Patterns Study Group
===========================

.. contents:: Table of Contents
  :local:

The Books
---------

The readings used by this study group are a careful selection of different chapter from the following books:

* `Design Patterns Elements of Reusable Object-Oriented Software`_
* `Head First Design Patterns`_
* `Design Patterns Explained`_
* `Holub on Patterns`_
* `Refactoring to Pattern`_
* `Elemental Design Patterns`_
* `Object-Oriented Analysis and Design with Applications`_
* `Code Complete`_
* `Effective Java`_

Official Pattern Catalog
------------------------

Initially the group will cover the basic GoF design patterns. However there is no reason why the group cannot later work on other pattern catalogs from other domains (e.g. `JEE <https://www.amazon.com/Professional-Java-EE-Design-Patterns/dp/111884341X/ref=sr_1_1?s=books&ie=UTF8&qid=1422162198&sr=1-1&keywords=Java+EE+PAtterns>`_, `Enterprise Applications <https://www.amazon.com/Patterns-Enterprise-Application-Architecture-Martin/dp/0321127420/ref=sr_1_1?s=books&ie=UTF8&qid=1422162238&sr=1-1&keywords=patterns+of+enterprise+application+architecture>`_, `SOA <https://www.amazon.com/Design-Patterns-Prentice-Service-Oriented-Computing/dp/0136135161/ref=sr_1_2?s=books&ie=UTF8&qid=1422162269&sr=1-2&keywords=soa+patterns>`_, `Integration <https://www.amazon.com/Enterprise-Integration-Patterns-Designing-Deploying/dp/0321200683/ref=sr_1_1?s=books&ie=UTF8&qid=1422162295&sr=1-1&keywords=enterprise+integration+patterns>`_, `Functional <https://www.amazon.com/Functional-Programming-Patterns-Scala-Clojure/dp/1937785475/ref=sr_1_1?s=books&ie=UTF8&qid=1422162317&sr=1-1&keywords=Functional+Programming+patterns>`_, `Service <https://www.amazon.com/Service-Design-Patterns-Fundamental-Solutions/dp/032154420X/ref=sr_1_1?s=books&ie=UTF8&qid=1515981953&sr=1-1&keywords=Service+Design+Patterns>`_, etc.)

.. image:: src/main/resources/static/images/GoF_full_medium.png

Further Readings
----------------

A selection of web sites where members of the group can continue their learning journey.

Design Patterns Catalogs
^^^^^^^^^^^^^^^^^^^^^^^^

`SourceMaking`_:
 Website specialized in design patterns, anti-patterns, refactoring and UML.

`Catalog of Patterns of Enterprise Application Architecture`_:
 Martin Fowler awesome catalog of enterprise application patterns.

`Enterprise Integration Patterns`_:
 Great catalog of patterns to create messaged-based systems.

`Workflow Patterns`_:
 A catalog of workflow orchestration patterns.

Object-Oriented Programming 101: Must Reads
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

`Principles of Object Oriented Design`_:
 Website containing dozens of references to other excellent papers on well known design techniques, principles and patterns.

`Type, Data Abstraction and Polymorphism`_:
 Best explanation ever on polymorphism and type systems by the great type theorist Luca Cardeli.

`Encapsulation and Inheritance`_:
 Best explanation ever on the true meaning of encapsulation by the great Alan Snyder.

`Abstraction vs Information Hiding vs Encapsulation`_:
 Great article that delves into the semantic similarities and differences of these three fundamental concepts.

Other Interesting Readings
^^^^^^^^^^^^^^^^^^^^^^^^^^

`Teach Yourself Programming in Ten Years`_:
 Peter Norving with a compelling argument about how it takes time and effort to become really good at programming.

`Non-software Examples of Design Patterns`_:
 Interesting examples of design patterns used in ordinary, real life situations.

The Patterns
------------


Behavioral
^^^^^^^^^^

Strategy
********

Defines a family of algorithms, encapsulates each one, and make them interchangeable. Strategy lets algorithms vary independently from clients that use it.

**Readings**

* `Head First Design Patterns`_, Welcome to Design Patterns, page 1-35.
* `Design Patterns Elements of Reusable Object-Oriented Software`_, Strategy Pattern, page 315-323.

**Questions**

* What is the intent of the strategy pattern?
* What are the consequences of the strategy pattern?
* What are possible indications of the need to use a strategy pattern?
* How can the context and the concrete strategy share information?
* How can the behavior of the context be altered dynamically using a strategy pattern?
* How can conditional statements be eliminated using a strategy pattern?
* Why is it preferable to use composition over inheritance in a case like this? (See fragile base class issue)
* What are the advantages/disadvantages of parameter passing? (loose coupling vs unused info)
* What are the advantages/disadvantages of passing the context? (strong coupling vs require info only)
* Is there anything that can be done to make the design less coupled when the context is passed as parameter?
* How can clients be exposed to implementation issue by having to instantiate a concrete strategy?
* What can be done to deal with an explosion of strategy objects? (See stateless strategies, flyweight pattern)
* Why is it said that 'using inheritance instead of strategy is harder to maintain, understand and extend? (see Duck problem)
* What are the main OO principles enforced by the strategy pattern and how?
* How does the strategy pattern foster the idea of designing for change?
* Why is the object-aggregation approach to inheritance superior to direct class inheritance for handling variation?
* What is meant by "switch creep"?
* What is wrong with copy and paste?
* Have you ever been in a situation where you did not feel you could afford to anticipate change? What drove you that way? What was the result?
* Should you ever use switch statements? Why or why not?
* What does "interface" mean in the statement "program to an interface, not to an implementation"? Do you think it means we are supposed to use something like Java interfaces?
* What are advantages of composition over inheritance?
* How can the strategy pattern be implemented with a functional programming pattern?

**Optional Readings**

* `Effective Java`_, Item 18: Favor Composition over Inheritance, page 87-92.
* `Refactoring to Pattern`_, Replace Conditional Logic with Strategy, page 129-143.
* `Design Patterns Explained`_, Chapter 9: The Strategy Pattern, page 139-157.
* `Refactoring Improving the Design of Existing Code`_, Chapter 9: Simplify Conditional Expressions, page 237-239.
* `Refactoring Improving the Design of Existing Code`_, Introduce Parameter Object, page 295-299.
* `A Study of The Fragile Base Class Problem`_.

.. _Design Patterns Elements of Reusable Object-Oriented Software: http://www.informit.com/store/design-patterns-elements-of-reusable-object-oriented-9780201633610
.. _Head First Design Patterns: https://www.amazon.com/Head-First-Design-Patterns-Brain-Friendly-ebook/dp/B00AA36RZY
.. _Design Patterns Explained: http://www.informit.com/store/design-patterns-explained-a-new-perspective-on-object-9780321247148
.. _Holub on Patterns: https://www.apress.com/la/book/9781590593882#otherversion=9781430253617
.. _Refactoring to Pattern: http://www.informit.com/store/refactoring-to-patterns-9780321213358
.. _Object-Oriented Analysis and Design with Applications: http://www.informit.com/store/object-oriented-analysis-and-design-with-applications-9780201895513
.. _Elemental Design Patterns: http://www.informit.com/store/elemental-design-patterns-9780321711922
.. _Code Complete: http://www.informit.com/store/code-complete-9780735619678
.. _Effective Java: http://www.informit.com/store/effective-java-9780134685991
.. _Refactoring Improving the Design of Existing Code: http://www.informit.com/store/refactoring-improving-the-design-of-existing-code-9780201485677
.. _SourceMaking: https://sourcemaking.com
.. _Catalog of Patterns of Enterprise Application Architecture: https://martinfowler.com/eaaCatalog/
.. _Enterprise Integration Patterns: http://www.enterpriseintegrationpatterns.com/patterns/messaging/
.. _Workflow Patterns: http://workflowpatterns.com
.. _Principles of Object Oriented Design: http://www.butunclebob.com/ArticleS.UncleBob.PrinciplesOfOod
.. _Type, Data Abstraction and Polymorphism: https://drive.google.com/file/d/0Bxed3Yafe-7xRkJMOGR3UGdIZG8/view
.. _Encapsulation and Inheritance: https://drive.google.com/file/d/0Bxed3Yafe-7xeWFqeEZXNHljM1U/view
.. _Abstraction vs Information Hiding vs Encapsulation: http://www.tonymarston.co.uk/php-mysql/abstraction.txt
.. _Teach Yourself Programming in Ten Years: https://drive.google.com/file/d/0Bxed3Yafe-7xQ05oNDVBX0ZTQms/view
.. _Non-software Examples of Design Patterns: http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.106.8473&rep=rep1&type=pdf
.. _A Study of The Fragile Base Class Problem: http://www.cas.mcmaster.ca/~emil/Publications_files/MikhajlovSekerinski98FragileBaseClassProblem.pdf
