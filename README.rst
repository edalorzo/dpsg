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

Creational
^^^^^^^^^^

Creational design patterns abstract the instantiation process. They help make a system independent of how its objects are created, composed, and represented. A class cre- ational pattern uses inheritance to vary the class that's instantiated, whereas an object creational pattern will delegate instantiation to another object.

Creational patterns become important as systems evolve to depend more on object composition than class inheritance. As that happens, emphasis shifts away from hard- coding a fixed set of behaviors toward defining a smaller set of fundamental behaviors that can be composed into any number of more complex ones. Thus creating objects with particular behaviors requires more than simply instantiating a class.

There are two recurring themes in these patterns. First, they all encapsulate knowledge about which concrete classes the system uses. Second, they hide how instances of these classes are created and put together. All the system at large knows about the objects is their interfaces as defined by abstract classes. Consequently, the creational patterns give you a lot of flexibility in what gets created, who creates it, how it gets created, and when. They let you configure a system with "product" objects that vary widely in structure and functionality. Configuration can be static (that is, specified at compile-time) or dynamic (at run-time).

Sometimes creational patterns are competitors. For example, there are cases when either Prototype or Abstract Factory could be used profitably. At other times they are complementary: Builder can use one of the other patterns to implement which components get built. Prototype can use Singleton in its implementation.

Abstract Factory
****************

TBD

Builder
*******

TBD

Factory Method
**************

TBD

Prototype
*********

TBD

Singleton
*********

TBD

Structural
^^^^^^^^^^

Structural patterns are concerned with how classes and objects are composed to form larger structures. Structural class patterns use inheritance to compose interfaces or implementations.  As a simple example, consider how multiple inheritance mixes two or more classes into one. The result is a class that combines the properties of its parent classes. This pattern is particularly useful for making independently developed class libraries work together. Another example is the class form of the Adapter  pattern. In general, an adapter makes one interface (the adaptee's) conform to another, thereby providing a uniform abstraction of different interfaces. A class adapter accomplishes this by inheriting privately from an adaptee class. The adapter then expresses its interface in terms of the adaptee's.

Rather than composing interfaces or implementations, structural object patterns describe ways to compose objects to realize new functionality. The added flexibility of object composition comes from the ability to change the composition at run-time, which is impossible with static class composition.

Composite is an example of a structural object pattern. It describes how to build a class hierarchy made up of classes for two kinds of objects: primitive and composite. The composite objects let you compose primitive and other composite objects into arbitrarily complex structures. In the Proxy pattern, a proxy acts as a convenient surrogate or placeholder for another object. A proxy can be used in many ways. It can act as a local representative for an object in a remote address space. It can represent a large object that should be loaded on demand. It might protect access to a sensitive object. Proxies provide a level of indirection to specific properties of objects. Hence they can restrict, enhance, or alter these properties.

The Flyweight pattern defines a structure for sharing objects. Objects are shared for at least two reasons: efficiency and consistency. Flyweight focuses on sharing for space efficiency. Applications that use lots of objects must pay careful attention to the cost of each object. Substantial savings can be had by sharing objects instead of replicating them. But objects can be shared only if they don't define context-dependent state. Flyweight objects have no such state. Any additional information they need to perform their task is passed to them when needed. With no context-dependent state, Flyweight objects may be shared freely.

Whereas Flyweight shows how to make lots of little objects, Facade shows how to make a single object represent an entire subsystem. A facade is a representative for a set of objects. The facade carries out its responsibilities by forwarding messages to the objects it represents. The Bridge pattern separates an object's abstraction from its implementation so that you can vary them independently.

Decorator describes how to add responsibilities to objects dynamically. Decorator is a structural pattern that composes objects recursively to allow an open-ended number of additional responsibilities. For example, a Decorator object containing a user interface component can add a decoration like a border or shadow to the component, or it can add functionality like scrolling and zooming. We can add two decorations simply by nesting one Decorator object within another, and so on for additional decorations. To accomplish this, each Decorator object must conform to the interface of its component and must forward messages to it. The Decorator can do its job (such as drawing a border around the component) either before or after forwarding a message.

Behavioral
^^^^^^^^^^

Behavioral patterns are concerned with algorithms and the assignment of responsibilities between objects. Behavioral patterns describe not just patterns of objects or classes but also the patterns of communication between them. These patterns characterize complex control flow that's difficult to follow at run-time. They shift your focus away from flow of control to let you concentrate just on the way objects are interconnected.

Behavioral class patterns use inheritance to distribute behavior between classes. This section includes two such patterns. Template Method is the simpler and more common of the two. A template method is an abstract definition of an algorithm. It defines the algorithm step by step. Each step invokes either an abstract operation or a primitive operation. A subclass fleshes out the algorithm by defining the abstract operations. The other behavioral class pattern is Interpreter, which represents a grammar as a class hierarchy and implements an interpreter as an operation on instances of these classes.

Behavioral object patterns use object composition rather than inheritance. Some describe how a group of peer objects cooperate to perform a task that no single object can carry out by itself. An important issue here is how peer objects know about each other. Peers could maintain explicit references to each other, but that would increase their coupling. In the extreme, every object would know about every other. The Mediator pattern avoids this by introducing a mediator object between peers. The mediator provides the indirection needed for loose coupling.

Chain of Responsibility provides even looser coupling. It lets you send requests to an object implicitly through a chain of candidate objects. Any candidate may fulfill the request depending on run-time conditions. The number of candidates is open-ended, and you can select which candidates participate in the chain at run-time.

The Observer pattern defines and maintains a dependency between objects. The classic example of Observer is in Smalltalk Model/View/Controller, where all views of the model are notified whenever the model's state changes.

Other behavioral object patterns are concerned with encapsulating behavior in an object and delegating requests to it. The Strategy pattern encapsulates an algorithm in an object. Strategy makes it easy to specify and change the algorithm an object uses. The Command pattern encapsulates a request in an object so that it can be passed as a parameter, stored on a history list, or manipulated in other ways. The State pattern encapsulates the states of an object so that the object can change its behavior when its state object changes. Visitor encapsulates behavior that would otherwise be distributed across classes, and Iterator abstracts the way you access and traverse objects in an aggregate.


.. _Design Patterns Elements of Reusable Object-Oriented Software: http://www.informit.com/store/design-patterns-elements-of-reusable-object-oriented-9780201633610
.. _Head First Design Patterns: https://www.amazon.com/Head-First-Design-Patterns-Brain-Friendly-ebook/dp/B00AA36RZY
.. _Design Patterns Explained: http://www.informit.com/store/design-patterns-explained-a-new-perspective-on-object-9780321247148
.. _Holub on Patterns: https://www.apress.com/la/book/9781590593882#otherversion=9781430253617
.. _Refactoring to Pattern: http://www.informit.com/store/refactoring-to-patterns-9780321213358
.. _Object-Oriented Analysis and Design with Applications: http://www.informit.com/store/object-oriented-analysis-and-design-with-applications-9780201895513
.. _Elemental Design Patterns: http://www.informit.com/store/elemental-design-patterns-9780321711922
.. _Code Complete: http://www.informit.com/store/code-complete-9780735619678
.. _Effective Java: http://www.informit.com/store/effective-java-9780134685991
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