Design Patterns Study Group
===========================

.. contents:: **Table of Contents**
  :local:
  :depth: 3
  :backlinks: top

Study Group Mechanics
-----------------------

The study group members gather regularly to improve their understanding of design patterns. The study group organizes and maintains an agenda of readings. Prior to each meeting, participants have read and reflected upon the readings and must come prepared with questions, ideas about, or explanations of the readings. 

One individual, the moderator, asks the opening question at the commencement of each meeting. This individual is charged with guiding the dialogue during the rest of the meeting, but this individual is not a teacher. He or she is simply considered to be the most advanced student with respect to a reading. If an individual is more advanced than others in the group, it makes sense for that individual to perform the role of moderator for serval meetings until others feel confortable in that role. Should a debate get out of hand or a dialogue stray or lag, the moderator will help refocus the discussion, often asking if the opening questions has been answered or stepping in to make sure that statements are properly validated.  

Individuals meet around a table or in a circle for 1 or 2 hours, and group size varies from 3 to as many as 10 individuals

Study Group vs. Lectures
^^^^^^^^^^^^^^^^^^^^^^^^

It is important to note the difference between study groups and lectures. While there is nothing wrong with lectures, they have a tendency to create a passive learning experience for attendees. If one is interested in simply gathering information, a lecture may be a fine place to do it. But if one really wants to understand something (to "get your hands dirty"), there is nothing like a study group. While attendees of a lecture may seek information, attendees in a study group seek transformation; they want to make what they study not only something they understand, but something they may use in their everyday lives or work. The study group thus acts as a bridge, helping people move from passive to active learning.

While "experts" are often asked to give lectures, study groups prefer to invite experts to participate in a group, to ask opening questions and be an active member in a dialogue. The focus here is always on great literature, be it an important paper, article, or book. The group's dialogue revolves around getting to a better understanding of the issues.

Membership Rules
^^^^^^^^^^^^^^^^
The members of the study group must follow the next three simple rules:

* Do the readings!
* Come prepared or don't come at all!
* Participate: bring questions, answers, explanations, ideas, examples!

The second rule may sound harsh, but that's what guarantees the dynamics of the study group. Otherwise the group quickly transforms into a lecture hall where the more advanced student becomes the lecturer.

Tips and Suggestions for Members
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

* If you really want to take advantage of your group membership, you must do the readings before the group meetings and reflect on their contents. Without an effort to understand the complex materials covered in the readings there will be very little to discuss during the group sessions and the learning transformation exercise all other members of the group are expecting gets seriously handicapped.  
* Don't wait to a few hours before the session to start doing the readings, the concepts covered in them are not easy to digest and requires time and reflection to fully grasp them. Therefore, separate time for this purpose in such a way that you can thoroughly cover the material before the day of the meeting. 
* Since the group sessions are not lessons, but moderated discussions, it is of paramount importance that you come prepared to discuss the material. Passive members that don't do the work but come to the meetings to see what they can learn won't be tolerated in this type of group as they would be disastrous to the group dynamics. Additionally, this behavior would not be respectful for the rest of group members who thoroughly prepared themselves to discuss their ideas during the group session. 
* Remember, you do the readings in your own time, and come to the sessions to learn, discuss the material, ask questions, give explanations or simply deepen your knowledge and understanding. The group is just a driving and guiding force to help you achieve the goal of becoming better at understanding using a set of design patterns.
* A good way to prepare for a sessions is to print the readings, and then highlight points you would like to bring to discussion during the next sessions (e.g.  those concepts that  you did not fully understand or those ideas that you found particularly insightful). You may write side notes with questions, reflections, explanations or ideas. Another great way to contribute is to bring your own examples of where the pattern has been used appropriately or pieces of code or examples of problems that could be solved with a given pattern.
* Also take a look at the preliminary list of  questions suggested in this site for every pattern and try to see if you can answer them after doing the readings. Most importantly, during the sessions, engage in conversations and discussions since this is the most enriching of all group activities. 

Suggested Books
---------------

The readings used by this study group are a careful selection of different chapter from the following books:

* `Design Patterns Elements of Reusable Object-Oriented Software`_
* `Head First Design Patterns`_
* `Design Patterns Explained`_
* `Holub on Patterns`_
* `Refactoring to Patterns`_
* `Elemental Design Patterns`_
* `Object-Oriented Analysis and Design with Applications`_
* `Code Complete`_
* `Effective Java`_
* `Agile Principles, Patterns and Practices in C#`_

Official GoF Pattern Catalog
----------------------------

Initially the group will cover the basic GoF design patterns. However there is no reason why the group cannot later work on other pattern catalogs from other domains (e.g. `JEE <https://www.amazon.com/Professional-Java-EE-Design-Patterns/dp/111884341X/ref=sr_1_1?s=books&ie=UTF8&qid=1422162198&sr=1-1&keywords=Java+EE+PAtterns>`_, `Enterprise Applications <https://www.amazon.com/Patterns-Enterprise-Application-Architecture-Martin/dp/0321127420/ref=sr_1_1?s=books&ie=UTF8&qid=1422162238&sr=1-1&keywords=patterns+of+enterprise+application+architecture>`_, `SOA <https://www.amazon.com/Design-Patterns-Prentice-Service-Oriented-Computing/dp/0136135161/ref=sr_1_2?s=books&ie=UTF8&qid=1422162269&sr=1-2&keywords=soa+patterns>`_, `Integration <https://www.amazon.com/Enterprise-Integration-Patterns-Designing-Deploying/dp/0321200683/ref=sr_1_1?s=books&ie=UTF8&qid=1422162295&sr=1-1&keywords=enterprise+integration+patterns>`_, `Functional <https://www.amazon.com/Functional-Programming-Patterns-Scala-Clojure/dp/1937785475/ref=sr_1_1?s=books&ie=UTF8&qid=1422162317&sr=1-1&keywords=Functional+Programming+patterns>`_, `Service <https://www.amazon.com/Service-Design-Patterns-Fundamental-Solutions/dp/032154420X/ref=sr_1_1?s=books&ie=UTF8&qid=1515981953&sr=1-1&keywords=Service+Design+Patterns>`_, etc.)

.. image:: resources/images/GoF_full_medium.png


GoF Patterns Study Guide
------------------------

Below you will find the recommended readings, optional readings and the questions that can be covered for everyone of the de GoF design patterns. Feel fre to contribute your own readings and questions.

Structural Patterns
^^^^^^^^^^^^^^^^^^^

Adapter
~~~~~~~

Recommended Readings
********************

* Adapter, `Design Patterns`_, p.139-150
* Being Adaptive, `Head First Design Patterns`_, p.235-254

Alternative Readings
********************

* Unify Interfaces with Adapter, `Refactoring to Patterns`_, p.247-257
* Extract Adapter, `Refactoring to Patterns`_, p.258-268
* `Law of Demeter <https://en.wikipedia.org/wiki/Law_of_Demeter>`_ (aka Principle of Least Knowledge)

Group Study Questions
*********************

* Does an *adapter* always adapts only one class?
* Since the *adapter* also wraps an object (the *adaptee*), how is it different from a *decorator* pattern?
* What are the two types of *adapters* and how do they differ in implementation?
* How is an *adapter* different from a *façade*?
* Would you ever create an *adapter* that has the same interface as the object which it adapts? 
  
  - Would your adapter then be a proxy?
* Stage a fireside chat between *adapter* and *proxy*. 

  - Discuss the similarities and differences in *adapter* and *proxy*. 
  - When would you use one vs. another? 
  - Under what conditions would an *adapter* look like *proxy*?
* Discuss the Brain Power on page 244 in `Head First Design Patterns`_.
* Discuss the `Principle of Least Knowledge <https://en.wikipedia.org/wiki/Law_of_Demeter>`_ on page 265 in `Head First Design Patterns`_. 

  - Take a small chunk of code you’ve written, and go through each line to see if it violates the Principle of Least Knowledge. Are there any cases in which you think you should change your code? If so, why?

Bridge
~~~~~~

Recommended Readings
********************

* Bridge, `Design Patterns`_, p.151-161
* The Bridge Pattern, `Design Patterns Explained`_, p.159-192

Alternative Readings
********************

* The Meaning of Abstraction, `Object-Oriented Analysis and Design with Applications`_, p.44-50
* Form Consistent Abstractions, `Code Complete`_, p.89-90.
* Bridge, `Holub on Patterns`_, p.364-365.
* `Head First Design Patterns`_, p.612-613
* `Opaque Pointer <https://en.wikipedia.org/wiki/Opaque_pointer>`_

Group Study Questions
*********************

* What is an abstraction and how is that different from an implementation? 
* How does the *bridge* prevents class explosion?
* How does the *bridge* differ from a *strategy* and a *strategy's* context?
* What is the basic problem being solved by the *bridge* pattern?
* How is implementation defined in the context of the *bridge* pattern?
* Should the implementor share the same interface as the abstraction?
* What does it mean when the Gang of Four says that the intent of the *bridge* pattern is to "decouple an abstraction from its implementations so that the two can vary independently"?.
* Why can tight coupling lead to an explosion in the number of classes?
* How, when, and where do you decide which implementor class to instantiate when there's more than one?
* Why do you think the Gang of Four call this pattern "Bridge"? 
 
  - Is it an appropriate name for what it is doing? Why or why not? 
* Is it necessary to define an abstract implementation when there is one one possible implementation?
* How does the bridge pattern foster the principles of "encapsulate what varies" and "favor composition over inheritance"?
* Bonus question: Why do you think Carolan called this technique 'a `Cheshire Cat <https://www.youtube.com/watch?v=2ueZo5i6GPg>`_ Idiom'? (Only for `Lewis Caroll <https://en.wikipedia.org/wiki/Lewis_Carroll>`_ fans:-) )


Composite
~~~~~~~~~

Recommended Readings
********************

* Composite, `Design Patterns`_, p.163-173
* Well-Managed Collections, `Head First Design Patterns`_, p.315-384

Alternative Readings
********************

* Single Resposibility Principle, `Agile Principles, Patterns and Practices in C#`_, p109-114.
* Extract Composite, `Refactoring to Patterns`_, p.214-223
* Replce Implicit Tree with Composite, `Refactoring to Patterns`_, p.178-190
* Replace One/Many Distinctions with Composite, `Refactoring to Patterns`_, p.224-235

Group Study Questions
*********************

* What is the difference between components, composites and trees?
* How does *composite* makes clients simpler but the design overly general?
* If the *composite* needs to be traversed in both directions what is the best place to put the parent reference?
* What problems can arise from sharing the same component with multiple parents?
* How does the *composite* conflicts with the principle of "class hierarchy design" that says that a class should only define operations that are meaningful to its subclasses?
* What should leaf classes do to implement operations that only pertain to the *composite*?
* How can leaves implement child management operations? Contrast/discuss transparency vs safety.
* How does the *composite* pattern help to consolidate system-wide conditional logic?
* Where is the place to put the instance variable that will hold the child references for a *composite*?
* How can we deal with child ordering in the *composite*?
* How can *composite* traversal performance be improved?
* If children need to be deleted, which participant is responsible of doing the deletion and clean up? 

  - What problems can arise related to garbage collection? 
  - What about immutable components?
* What data structures can be used to implement the *composite*?
* Would you use the *composite* pattern if you did not have a part-whole hierarchy? In other words, if only a few objects have children and almost everything else in your collection is a leaf (a leaf can have no children), would you still use the *composite* pattern to model these objects? Defend position.
* Discuss the Brain Power on page 337 in `Head First Design Patterns`_.
* What is the *Single Responsibility Principle* (SRP)? 

  - How does it relate to the *composite* pattern?
  - How does it relate to the concept of cohesion?
  - What is consider a "responsibility" in the SRP?
  - How to decide when to separate responsibilities? Discuss rigidity vs needless complexity.
  - How does the Single Responsibility principle relate to the other patterns you know?
* What are the differences between the relationships of components, composites, trees, etc. 


Decorator
~~~~~~~~~

Recommended Readings
********************

* Decorator, `Design Patterns`_, p.175-184
* Decorating Objects, `Head First Design Patterns`_, p.79-107

Alternative Readings
********************

* Move Embellishment to Decorator, `Refactoring to Patterns`_, p.144-165
* Open/Close Principle, `Agile Principles, Patterns and Practices in C#`_, p121-133.

Group Study Questions
*********************

* What is the intent of the *decorator* pattern?
* When do we use a *decorator*?
* How does a *decorator* provide a flexible alternative to subclassing/class inheritance?
* How do *decorators* avoid the need to define an explosion of classes in a class hierarchy?
* How code relying on object identity fail to work with a *decorator*?
* How does the *decorator* makes systems harder to learn and debug?
* Should we always define the abstract *decorator* interface? 

  - Can't it be defined directly in the concrete decorator?
* How could the *decorator* behavior be implemented with a *strategy* pattern?
* When is the *strategy* pattern a better choice than a *decorator*? 

  - Discuss advantages/disadvantages of every case.
* How does the *decorator* fosters the *open/close* principle?
* What does it mean when they say the *decorator* "changes the skin of an object not its guts"?
* Why isn't the component the *decorator* itself? 

  - In other words, why the *decorator* interface must be separate from the component interface
* What does it mean that the *decorator* object’s interface must conform to the interface of the component it decorates? Why is that important? (e.g. transparency)
* Stage a debate about the *decorator*: one person should take the side of using the *decorator* pattern and argue the advantages, the other should take the side of using inheritance and argue the advantages. 
  
  - See if the rest of the group can come up with examples of when one solution is better than the other.
* What are good examples of the decorator pattern in well know APIS, e.g. JDK IO API?

Façade
~~~~~~

Recommended Readings
********************

* Façade, `Design Patterns`_, p.185-193
* Being Adaptive, `Head First Design Patterns`_, p.254-274

Alternative Readings
********************

* `Law of Demeter <https://en.wikipedia.org/wiki/Law_of_Demeter>`_ (aka Principle of Least Knowledge).

Group Study Questions
*********************

* In the *façade* pattern, what is considered a subsystem?
* What is the public interface of a subsystem?
* How does a *façade* make subsystems easier to use?
* How does the *façade* promotes weak coupling between the clients and the subsystems?
* Can clients only access the subsystem through the *façade*?
* Can the *façade* add functionality to a request, or is it just supposed to pass it to the subsystem?
* How complex must a sub-system be in order to justify using a *façade*?
* Does each subsystem only have one *façade*?
* What are the additional uses of a *façade* with respect to an organization of designers and developers with varying abilities? What are the political ramifications?
* Think of a complex system you have to use every day that you would like a *façade* for. How would you simplify the interface in the *façade*?
* How is a *façade* different from a *adapter*?
* Discuss the `Principle of Least Knowledge <https://en.wikipedia.org/wiki/Law_of_Demeter>`_ on page 265. 

  - Take a small chunk of code you’ve written, and go through each line to see if it violates the Principle of Least Knowledge. 
  - Are there any cases in which you think you should change your code? If so, why?

Flyweight
~~~~~~~~~

Recommended Readings
********************

* Flyweight, `Design Patterns`_, p.195-206
* Flyweight, `Head First Design Patterns`_, p.618-619

Group Study Questions
*********************

* What is a non-GUI example of a *flyweight*?
* What is the minimum configuration for using *flyweight*? 

  - Do you need to be working with thousands of objects, hundreds, tens?
* When to use the *flyweight* pattern?
* What is intrinsic and extrinsic states and why are they so important to this pattern?
* When do you have the better storage savings using *flyweight* pattern?
* What things you need to identify to apply the pattern correctly? (When makes sense to use it, when not)
* What is the importance of the `FlyweightFactory` in the pattern?
* How this pattern reduces objects creation?
* How do you manage the extrinsic state? where do you put it? who is responsible for it?
* What downsides can you determine for this pattern?

Proxy
~~~~~

Recommended Readings
********************

* Proxy, `Design Patterns`_, p.207-217
* Controlling Object Access, `Head First Design Patterns`_, p.429-497

Alternative Readings
********************

* `Java Proxies <https://docs.oracle.com/javase/8/docs/api/java/lang/reflect/Proxy.html>`_.
* `Java Remote Method Invocation API <https://docs.oracle.com/javase/8/docs/technotes/guides/rmi/index.html>`_

Group Study Questions
*********************

* What is the intent of the *proxy* pattern?
* Is the *proxy* always responsible of creating the real subject?
* What are different types of *proxies* and what are they used for? 

  - Discuss the different types of proxy: remote proxy, virtual proxy, and protection proxy. 
  - Make sure everyone in the group understands each type of proxy, and come up with examples of each.
  - In every type of proxy mentioned above, how does the proxy gets a reference to the real subject? 
* What are the main similitudes and differences between proxy and decorator?
* If a *proxy* is used to instantiate an object only when it is absolutely needed, does the *proxy* simplify code?
* Discuss the second Brain Power on page 435 in `Head First Design Patterns`_.
* Discuss the proxy zoo on page 488 in `Head First Design Patterns`_. Come up with at least one example habitat for each type of proxy–in other words, examples of when and where you might want to use that type of *proxy*.
* How does Spring uses Java *proxies* to provide additional functionality to components?
* How does AOP differers from the *proxy* pattern?

Behavioral Patterns
^^^^^^^^^^^^^^^^^^^

Chain of Responsibility
~~~~~~~~~~~~~~~~~~~~~~~

Recommended Readings
********************

* Chain of Responsibility, `Design Patterns`_, p.223-232
* Being Adaptive, `Head First Design Patterns`_, p.617

Alternative Readings
********************

* Single Resposibility Principle, `Agile Principles, Patterns and Practices in C#`_, p109-114.
* `Apache Commons Chain of Responsibility <http://commons.apache.org/proper/commons-chain/>`_
* `Separation of Concerns <https://en.wikipedia.org/wiki/Separation_of_concerns>`_

Group Study Questions
*********************

* How does *chain of responsibility* reduces coupling between the sender of a request and its receiver?
* How does the *chain of responsibility* pattern differ from the *decorator* pattern or from a linked list?
* Is it helpful to look at patterns from a structural perspective? In other words, if you see how a set of patterns are the same in terms of how they are programmed, does that help you to understand when to apply them to a design?
* What are different ways to define the successor chain?
* What are different ways to represent a request?
* Can the *command* pattern be used to represent the requests?
* What happens if the request reaches the end of the chain without being properly handled?
* Does it make sense to use *chain of responsibility* when each request is only handled by one handler, or, when the client object knows which service object should handle the request?
* Let's discuss how a programming language like Java or C# deals with exception handling and how this concept relates to the idea of how the chain of responsibility works. 

  - How about inheritance and dynamic dispatch?
* How can *chain of responsibility* be combined with a *composite* pattern?

  - If we use the *composite*, can successor actually be considered from the point of view of children handlers?
* How does *chain of responsibility* implements the *single responsibility principle*?
* How does *chain of responsibility* implements the *separation of concerns principle*? 
* What other patterns decouples senders of requests from receivers?

Command
~~~~~~~

Recommended Readings
********************

* Command, `Design Patterns`_, p.233-242
* Encapsulating Invocation, `Head First Design Patterns`_, p.191-233

Alternative Readings
********************

* Replace Conditional Dispatcher with Command, `Refactoring to Patterns`_, p.191-201
* `The Command Pattern <http://wiki.c2.com/?CommandPattern>`_
* `Uses of Command Pattern <https://en.wikipedia.org/wiki/Command_pattern#Uses>`_

Group Study Questions
*********************

* What are other names of the *command* pattern?
* What are the participants of the *command* pattern?
* What is the intend of the *command* pattern?
* In the motivation section of the *command* pattern, an application’s menu system is described: an application has a menu, which in turn has menu items, which in turn execute commands when they are clicked. 
  
  - What happens if the *command* needs some information about the application in order to do its job? 
  - How would the *command* have access to such information such that new commands could easily be written that would also have access to the information they need?
* What is a *macro command*? Discuss how it could be designed.
* How does the *command* pattern decouples the object that invokes the operation from the one that has the knowledge to perform it? 
* Lead a group discussion on what it means to “encapsulate invocation” and how this relates to the *command* pattern.
* How does the *command* pattern compares to callbacks?
* Can you think of another real-world example of where you might want to use the *command* pattern?
* Put on a skit where each person in the group plays a role in the *command* pattern: the client, one or more commands, the invoker, and the receiver. 

  - Act out the ordering of a burger in the diner (`Head First Design Patterns`_ page 201). 
  - Act out the real-world example from the previous discussion.
* Discuss how you might use the *command* pattern to implement a menu for a GUI.
* How can we use the *command* pattern to implement a design that supports a unlimited number of undos? 
* Should the client be blocked while the *command* is being executed? (consider asynchronous execution, NIO, JavaScript callbacks, etc).
* What should happen if the *command* fails leaving the receiver in a possibly inconsistent state?
* What is a *smart command* pattern? 
* Do you think that supporting the *undo command* transforms the *command* into a state machine? Why, why not?
* Which are the major design principles that apply to this pattern?
* How can *command* pattern be used to create a transaction log and reapply operations in the case of a system crash (e.g. `System Prevalence <https://en.wikipedia.org/wiki/System_prevalence>`_ as implemented in `Prevayler <http://prevayler.org/>`_)
* How can the *command* pattern be used to model transactions?
* How can we combine the *command* pattern with the *composite* pattern? (e.g. MacroCommand).
* How can we combine the *command* pattern with the *memento* pattern to implement undo operations? 
  
  - Think about how to gradually restore the state of the receiver to a previous state in time by applying a historical, ordered, succession of undos. 
  - This is a discussion about one level undo vs multiple level undos.
* How could the *command* pattern be combined with *prototype* pattern to easily create new commands based on existing ones?
* What happens if undo fails and application is now in a inconsistent state?
* How a framework like Spring offers command implementations to do do things like programatic transactions, retry support, database access layer impel rations (e.g. see Springs TransactionTemplate, RetryTemplate and JdbcTemplate)
* In multithreaded application, what would be the risk of sharing the same *command* between multiple threads? In other words, are commands thread-safe?
* In Java 8, and in other OO languages with support for functional programming, how can we use functors (i.e. objects that are functions) to implement the command pattern?

  - Think, for e.g. of Java 8 `Function<T,R>` or C# `Func<T,R>`, combined with lambdas or method references (in Java) or delegates (in C#) that encapsulate the body of the command. 
  - There might be a discussion about the advantages of closures to accesses contextual data in the invoker that makes the commands simpler to implement
  - How is a *command* different than a lambda or a "glorified function"?
* Bonus question: How could we define a command that could be interrupted?

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

`Design by Contract`_:
 A coherent set of methodological principles helping to produce correct and robust software.


Other Interesting Readings
^^^^^^^^^^^^^^^^^^^^^^^^^^

`Teach Yourself Programming in Ten Years`_:
 Peter Norving with a compelling argument about how it takes time and effort to become really good at programming.

`Non-software Examples of Design Patterns`_:
 Interesting examples of design patterns used in ordinary, real life situations.

.. _Design Patterns: http://www.informit.com/store/design-patterns-elements-of-reusable-object-oriented-9780201633610
.. _Design Patterns Elements of Reusable Object-Oriented Software: http://www.informit.com/store/design-patterns-elements-of-reusable-object-oriented-9780201633610
.. _Head First Design Patterns: https://www.amazon.com/Head-First-Design-Patterns-Brain-Friendly-ebook/dp/B00AA36RZY
.. _Design Patterns Explained: http://www.informit.com/store/design-patterns-explained-a-new-perspective-on-object-9780321247148
.. _Holub on Patterns: https://www.apress.com/la/book/9781590593882#otherversion=9781430253617
.. _Refactoring to Patterns: http://www.informit.com/store/refactoring-to-patterns-9780321213358
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
.. _Design by Contract: http://se.inf.ethz.ch/~meyer/publications/computer/contract.pdf
.. _Agile Principles, Patterns and Practices in C#: http://www.informit.com/store/agile-principles-patterns-and-practices-in-c-sharp-9780131857254
