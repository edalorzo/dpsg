Design Patterns Study Group
===========================

.. contents:: 
  :local:
  :depth: 3
  :backlinks: top

Study Group Mechanics
-----------------------

The study group members gather regularly to improve their understanding of design patterns. The study group organizes and maintains an agenda of readings. Before each meeting,  participants must have read and reflected upon the suggested readings (and ideally read the alternative readings) and must come prepared with questions, ideas about, or explanations of the texts. 

One individual, the moderator, asks the opening question at the commencement of each meeting. This individual is charged with guiding the dialogue during the rest of the meeting, but this individual is not a teacher. He or she is simply considered to be the most advanced student with respect to a reading. If an individual is more advanced than others in the group, it makes sense for that individual to perform the role of moderator for serval meetings until others feel comfortable in that role. Should a debate get out of hand or a dialogue stray or lag, the moderator will help refocus the discussion, often asking if the opening questions have been answered or stepping in to make sure that statements are adequately validated.  

Individuals meet around a table or in a circle for 1 or 2 hours, and group size varies from 3 to as many as 10 individuals.

Study Group vs. Lectures
^^^^^^^^^^^^^^^^^^^^^^^^

It is important to note the difference between study groups and lectures. While there is nothing wrong with lectures, they tend to create a passive learning experience for attendees. If one is interested in simply gathering information, a lecture may be an excellent place to do it. But if one really wants to understand something (to "get your hands dirty"), there is nothing like a study group. While attendees of a lecture may seek information, attendees in a study group seek transformation; and want to make their subject study not only something they understand but something they may use in their everyday lives or work. The study group thus acts as a bridge, helping people move from passive to active learning.

While "experts" are often asked to give lectures, study groups prefer to invite experts to participate in a group, to ask opening questions and be an active member in a dialogue. The focus here is always on great literature, be it an important paper, article, or book. The group's dialogue revolves around getting to a better understanding of the issues.

Membership Rules
^^^^^^^^^^^^^^^^
The members of the study group must follow the next three simple rules:

* Do the readings!
* Come prepared or don't come at all!
* Participate: bring questions, answers, explanations, ideas, examples!

The second rule may sound harsh, but that's what guarantees the dynamics of the study group. Otherwise, the group quickly transforms into a lecture hall where the more advanced student becomes the lecturer.

Tips and Suggestions for Members
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

* If you really want to take advantage of your group membership, you must do the readings before the group meetings and reflect on their contents. Without an effort to understand the complex materials covered in the readings, there will be very little to discuss during the group sessions, and the learning transformation exercise all other members of the group are expecting gets severely handicapped.  
* Don't wait to a few hours before the meeting to start doing the readings, the concepts covered in them are not easy to digest and requires time and reflection to grasp them fully. Therefore, separate time for this purpose in such a way that you can thoroughly cover the material before the day of the meeting. 
* Since the group sessions are not lessons, but moderated discussions, it is of paramount importance that you come prepared to discuss the material. Passive members that don't do the work but come to the meetings to see what they can learn won't be tolerated in this type of group as they would be disastrous to the group dynamics. Additionally, this behavior would not be respectful for the rest of the group members who thoroughly prepared themselves to discuss their ideas during the group session. 
* Remember, you do the readings in your own time and come to the meetings to learn, discuss the material, ask questions, give explanations, or deepen your knowledge and understanding. The group is just a driving and guiding force to help you achieve the goal of becoming better at understanding using a set of design patterns.
* A right way to prepare for the sessions is to print the readings and then highlight points you would like to bring to discussion during the next meetings (e.g., those concepts that you did not fully understand or those ideas that you found particularly insightful). You may write side notes with questions, reflections, explanations, or opinions. Another great way to contribute is to bring your own examples of where the pattern has been used appropriately or pieces of code or examples of problems that could be solved with a given pattern.
* Also, take a look at the preliminary list of questions suggested in this site for every pattern and try to see if you can answer them after doing the readings. Most importantly, during the sessions, engage in conversations and discussions since this is the most enriching of all group activities. 

Suggested Books
---------------

The readings used by this study group are a careful selection of different chapter from the following books:

* `Design Patterns Elements of Reusable Object-Oriented Software`_
* `Head First Design Patterns`_
* `Design Patterns Explained`_
* `Holub on Patterns`_
* `Refactoring - Improving the Design of Existing Code`_
* `Refactoring to Patterns`_
* `Elemental Design Patterns`_
* `Object-Oriented Analysis and Design with Applications`_
* `Code Complete`_
* `Effective Java`_
* `Agile Principles, Patterns and Practices in C#`_

Official GoF Pattern Catalog
----------------------------

Initially, the group will cover the basic GoF design patterns. However, there is no reason why the group cannot later work on other pattern catalogs from different domains (e.g. `JEE <https://www.amazon.com/Professional-Java-EE-Design-Patterns/dp/111884341X/ref=sr_1_1?s=books&ie=UTF8&qid=1422162198&sr=1-1&keywords=Java+EE+PAtterns>`_, `Enterprise Applications <https://www.amazon.com/Patterns-Enterprise-Application-Architecture-Martin/dp/0321127420/ref=sr_1_1?s=books&ie=UTF8&qid=1422162238&sr=1-1&keywords=patterns+of+enterprise+application+architecture>`_, `SOA <https://www.amazon.com/Design-Patterns-Prentice-Service-Oriented-Computing/dp/0136135161/ref=sr_1_2?s=books&ie=UTF8&qid=1422162269&sr=1-2&keywords=soa+patterns>`_, `Integration <https://www.amazon.com/Enterprise-Integration-Patterns-Designing-Deploying/dp/0321200683/ref=sr_1_1?s=books&ie=UTF8&qid=1422162295&sr=1-1&keywords=enterprise+integration+patterns>`_, `Functional <https://www.amazon.com/Functional-Programming-Patterns-Scala-Clojure/dp/1937785475/ref=sr_1_1?s=books&ie=UTF8&qid=1422162317&sr=1-1&keywords=Functional+Programming+patterns>`_, `Service <https://www.amazon.com/Service-Design-Patterns-Fundamental-Solutions/dp/032154420X/ref=sr_1_1?s=books&ie=UTF8&qid=1515981953&sr=1-1&keywords=Service+Design+Patterns>`_, etc.)

.. image:: resources/images/GoF_full_medium.png


GoF Patterns Study Guide
------------------------

Below you will find the recommended readings, optional readings, and the questions that can be covered for every one of the de GoF design patterns. Feel free to contribute your own readings and questions.

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

* Does an *adapter* always adapt only one class?
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

* What is an abstraction, and how is that different from an implementation? 
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
* Is it necessary to define an abstract implementation when there is one possible implementation?
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

* Single Responsibility Principle, `Agile Principles, Patterns and Practices in C#`_, p109-114.
* Extract Composite, `Refactoring to Patterns`_, p.214-223
* Replace Implicit Tree with Composite, `Refactoring to Patterns`_, p.178-190
* Replace One/Many Distinctions with Composite, `Refactoring to Patterns`_, p.224-235

Group Study Questions
*********************

* What is the difference between components, composites, and trees?
* How does *composite* makes clients simpler but the design overly general?
* If the *composite* needs to be traversed in both directions, what is the best place to put the parent reference?
* What problems can arise from sharing the same component with multiple parents?
* How does the *composite* conflicts with the principle of "class hierarchy design" that says that a class should only define operations that are meaningful to its subclasses?
* What should leaf classes do to implement operations that only pertain to the *composite*?
* How can leaves implement child management operations? Contrast/discuss transparency vs. safety.
* How does the *composite* pattern help to consolidate system-wide conditional logic?
* Where is the place to put the instance variable that will hold the child references for a *composite*?
* How can we deal with child ordering in the *composite*?
* How can *composite* traversal performance be improved?
* If children need to be deleted, which participant is responsible for doing the deletion and clean up? 

  - What problems can arise related to garbage collection? 
  - What about immutable components?
* What data structures can be used to implement the *composite*?
* Would you use the *composite* pattern if you did not have a part-whole hierarchy? In other words, if only a few objects have children and almost everything else in your collection is a leaf (a leaf can have no children), would you still use the *composite* pattern to model these objects? Defend position.
* Discuss the Brain Power on page 337 in `Head First Design Patterns`_.
* What is the *Single Responsibility Principle* (SRP)? 

  - How does it relate to the *composite* pattern?
  - How does it relate to the concept of cohesion?
  - What is considered a "responsibility" in the SRP?
  - How to decide when to separate responsibilities? Discuss rigidity vs. needless complexity.
  - How does the Single Responsibility principle relate to the other patterns?
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
* Open/Closed Principle, `Agile Principles, Patterns and Practices in C#`_, p121-133.

Group Study Questions
*********************

* What is the intent of the *decorator* pattern?
* When do we use a *decorator*?
* How does a *decorator* provide a flexible alternative to subclassing/class inheritance?
* How do *decorators* avoid the need to define an explosion of classes in a class hierarchy?
* How code relying on object identity fails to work with a *decorator*?
* How does the *decorator* make systems harder to learn and debug?
* Should we always define the abstract *decorator* interface? 

  - Can't it be defined directly in the concrete decorator?
* How could the *decorator* behavior be implemented with a *strategy* pattern?
* When is the *strategy* pattern a better choice than a *decorator*? 

  - Discuss the advantages/disadvantages of every case.
* How does the *decorator* fosters the *open/close* principle?
* What does it mean when they say the *decorator* "changes the skin of an object not its guts"?
* Why isn't the component the *decorator* itself? 

  - In other words, why the *decorator* interface must be separate from the component interface
* What does it mean that the *decorator* object’s interface must conform to the interface of the component it decorates? Why is that important? (e.g., transparency)
* Stage a debate about the *decorator*: one person should take the side of using the *decorator* pattern and argue the advantages, the other should take the side of using inheritance and discuss the benefits. 
  
  - See if the rest of the group can come up with examples of when one solution is better than the other.
* What are good examples of the decorator pattern in well-know APIS, e.g., JDK IO API?

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
* How complex must a sub-system be to justify using a *façade*?
* Does each subsystem only have one *façade*?
* What are the additional uses of a *façade* with respect to an organization of designers and developers with varying abilities? What are the political ramifications?
* Think of a complex system you have to use every day that you would like a *façade* for. How would you simplify the interface in the *façade*?
* How is a *façade* different from an *adapter*?
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
* What is intrinsic and extrinsic states, and why are they so important to this pattern?
* When do you have the better storage savings using *flyweight* pattern?
* What things you need to identify to apply the pattern correctly? (When makes sense to use it, when not)
* What is the importance of the `FlyweightFactory` in the pattern?
* How this pattern reduces object creation?
* How do you manage the extrinsic state? Where do you put it? Who is responsible for it?
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
* Is the *proxy* always responsible for creating the real subject?
* What are different types of *proxies* and what are they used for? 

  - Discuss the different types of proxy: remote proxy, virtual proxy, and protection proxy. 
  - Make sure everyone in the group understands each type of proxy, and come up with examples of each.
  - For every kind of proxy mentioned above, how does the proxy gets a reference to the real subject? 
* What are the main similitudes and differences between proxy and decorator?
* If a *proxy* is used to instantiate an object only when it is absolutely needed, does the *proxy* simplify code?
* Discuss the second Brain Power on page 435 in `Head First Design Patterns`_.
* Discuss the proxy zoo on page 488 in `Head First Design Patterns`_. Come up with at least one example habitat for each type of proxy–in other words, examples of when and where you might want to use that type of *proxy*.
* How does Spring uses Java *proxies* to provide additional functionality to components?
* How does AOP differ from the *proxy* pattern?

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

* Single Responsibility Principle, `Agile Principles, Patterns and Practices in C#`_, p109-114.
* `Apache Commons Chain of Responsibility <http://commons.apache.org/proper/commons-chain/>`_
* `Separation of Concerns <https://en.wikipedia.org/wiki/Separation_of_concerns>`_

Group Study Questions
*********************

* How does *chain of responsibility* reduces coupling between the sender of a request and its receiver?
* How does the *chain of responsibility* pattern differ from the *decorator* pattern or from a linked list?
* Is it helpful to look at patterns from a structural perspective? In other words, if you see how a set of patterns are the same in terms of how they are programmed, does that help you to understand when to apply them to a design?
* What are different ways to define the successor chain?
* What are various ways to represent a request?
* Can the *command* pattern be used to represent the requests?
* What happens if the request reaches the end of the chain without being properly handled?
* Does it make sense to use *chain of responsibility* when each request is only handled by one handler, or when the client object knows which service object should handle the request?
* Let's discuss how a programming language like Java or C# deals with exception handling and how this concept relates to the idea of how the chain of responsibility works. 

  - How about inheritance and dynamic dispatch?
* How can *chain of responsibility* be combined with a *composite* pattern?

  - If we use the *composite*, can successor actually be considered from the point of view of children's handlers?
* How does *chain of responsibility* implement the *single responsibility principle*?
* How does *chain of responsibility* implement the *separation of concerns principle*? 
* What other patterns decouple senders of requests from receivers?

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
* What is the intent of the *command* pattern?
* In the motivation section of the *command* pattern, an application’s menu system is described: an application has a menu, which in turn has menu items, which in turn execute commands when they are clicked. 
  
  - What happens if the *command* needs some information about the application to do its job? 
  - How would the *command* have access to such information such that new commands could easily be written that would also have access to the information they need?
* What is a *macro command*? Discuss how it could be designed.
* How does the *command* pattern decouple the object that invokes the operation from the one that has the knowledge to perform it? 
* Lead a group discussion on what it means to “encapsulate invocation” and how this relates to the *command* pattern.
* How does the *command* pattern compares to callbacks?
* Can you think of another real-world example of where you might want to use the *command* pattern?
* Put on a skit where each person in the group plays a role in the *command* pattern: the client, one or more commands, the invoker, and the receiver. 

  - Act out the ordering of a burger in the diner (`Head First Design Patterns`_ page 201). 
  - Act out the real-world example from the previous discussion.
* Discuss how you might use the *command* pattern to implement a menu for a GUI.
* How can we use the *command* pattern to implement a design that supports an unlimited number of undos? 
* Should the client be blocked while the *command* is being executed? (consider asynchronous execution, NIO, JavaScript callbacks, etc.).
* What should happen if the *command* fails to leave the receiver in a possibly inconsistent state?
* What is a *smart command* pattern? 
* Do you think that supporting the *undo command* transforms the *command* into a state machine? Why, why not?
* Which are the major design principles that apply to this pattern?
* How can *command* pattern be used to create a transaction log and reapply operations in the case of a system crash (e.g. `System Prevalence <https://en.wikipedia.org/wiki/System_prevalence>`_ as implemented in `Prevayler <http://prevayler.org/>`_)
* How can the *command* pattern be used to model transactions?
* How can we combine the *command* pattern with the *composite* pattern? (e.g. MacroCommand).
* How can we combine the *command* pattern with the *memento* pattern to implement undo operations? 
  
  - Think about how to gradually restore the state of the receiver to a previous state in time by applying a historical, ordered, succession of undos. 
  - This is a discussion about one level undo vs. multiple level undos.
* How could the *command* pattern be combined with *prototype* pattern to create new commands based on existing ones easily?
* What happens if undo fails and application is now in an inconsistent state?
* How a framework like Spring offers command implementations to do things like programmatic transactions, retry support, database access layer impel rations (e.g., see Springs ``TransactionTemplate``, ``RetryTemplate`` and ``JdbcTemplate``)
* In a multithreaded application, what would be the risk of sharing the same *command* between multiple threads? In other words, are commands thread-safe?
* In Java 8, and in other OO languages with support for functional programming, how can we use functors (i.e., objects that are functions) to implement the command pattern?

  - Think, e.g. of Java 8 ``Function<T,R>`` or C# ``Func<T,R>``, combined with lambdas or method references (in Java) or delegates (in C#) that encapsulate the body of the command. 
  - There might be a discussion about the advantages of closures to accesses contextual data in the invoker that makes the commands simpler to implement
  - How is a *command* different than a closure or a "glorified function"?
* Bonus question: How could we define a command that could be interrupted?


Interpreter
~~~~~~~~~~~

TBD

Iterator
~~~~~~~~

TBD

Mediator
~~~~~~~~

Recommended Readings
********************

* Mediator, `Design Patterns`_, p.273-282
* Mediator, `Head First Design Patterns`_, p.622-623

Group Study Questions
*********************

* Since a Mediator becomes a repository for logic, can the code that implements this logic begin to get overly complicated, possible resembling spaghetti code? How could this potential problem be solved?
* WIP...

Memento
~~~~~~~

Recommended Readings
********************

* Memento, `Design Patterns`_, p.283-291
* Memento, `Head First Design Patterns`_, p.624-625

Alternative Readings
********************

* Single Resposibility Principle, `Agile Principles, Patterns and Practices in C#`_, p109-114.

Group Study Questions
*********************

* What is the intent of the *memento* Pattern?
* Which are the participants in the pattern?
* The authors write that the “Caretaker” participant never operates on or examines the contents of a *memento*. 

  - Can you consider a case where a Caretaker would, in fact, need to know the identity of a *memento* and thus require the ability to examine or query the contents of that memento? 
  - Would this break something in the pattern?
* How does *memento* protect the state of an object without exposing it to other classes? 
* Who is responsible for re-applying the state persisted in the *memento* object? 
* What is the difference between the Care Taker and the Originator's client? 

  - Could the same class implement these two roles?
* How is the *memento* pattern leveraging the "encapsulate what varies" principle?
* How does the *memento* pattern implement the "single responsibility" principle?
* What drawbacks could a *memento* implementation suffer if the originator's state or variation rate scales up?   
* How would you design narrow and wide interfaces in an implementation of the *memento* pattern so that the Care Taker does not have access to the wide interface?
* What conditions have to exist to be able to apply an incremental *memento*?
* How can *memento* be applied to other patterns such as *iterator* and *command*?
* If we leverage *memento* to implement the *iterator* pattern, how would it allow us to apply multiple iterators over the same collection at the same time?
* What kind of logic could you place inside the *memento* object to control how the state is re-applied?
* What important consideration about the persisted state (inside the *memento* object) should we contemplate if we are implementing *memento*? 

Observer
~~~~~~~~

Recommended Readings
********************

* Observer, `Design Patterns`_, p.293-303
* Keeping your Objects in the Know, `Head First Design Patterns`_, p.37-78

Alternative Readings
********************

* Replace Hard-Coded Notification with Observer, `Refactoring to Patterns`_, p.236-246
* Keeping Coupling Loose, `Code Complete`_, p.100-102
* Move Accumulation to Collection Parameter, `Refactoring to Patterns`_, p.313-319
* `Reacting Programming with RxJava <http://reactivex.io/intro.html>`_
* `Deprecating the Observer Pattern <http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.186.8309&rep=rep1&type=pdf>`_

Group Study Questions
*********************

* What are other common names for the *observer* pattern?
* When is the *observer* pattern applicable?
* In Page 51 `Head First Design Patterns`_ describes how the *observer* pattern is like a newspaper subscription. 

  - Come up with several other real-world examples of the *observer* pattern.
* What is one of the most famous UI patterns that use the *observer* pattern?
* Which participant(s) can be responsible for triggering the update/notification mechanism? 

  - Should notification only be triggered by the subject?
* How does the *observer* pattern foster the design principle of "striving for loosely coupled designs"?
* How does the *observer* patterns foster the design principle of "program to an interface, not to an implementation"?
* How does the *observer* pattern foster the design principle of "favor composition over inheritance"?
* How can we control the number of updates the *observers* receive?
* How can the *observers* determine what changed in the subject? 
  
  - Discuss the two possible protocols for the notification (pull vs. push).
* What are the advantages and disadvantages of the pull/push notification protocols?
* How can subjects keep track of their *observers*?
* How can the *observers* determine from which subject they're being notified, in case they have subscribed with more than one subject?
* What should happen if an exception occurs while notifying one of the *observers*? 

  - Consider the same question in a scenario where *observers* are being notified asynchronously. Would the same strategy works?
* What should happen with transactions? Should it expand to all *observers*, or should we start a new transaction per *observer* notification?
* What happens if we want to delete a subject? 
  
  - How can we ensure there will be no dangling references to it from its *observers*? 
  - Why could it be wrong to keep these dangling references?
* Should *observers* keep a reference to their subject? Why/Why not?
* What is the importance to ensuring self-consistent state in the subject before notifying its *observers*?
* How can the *observer* pattern be combined with the *template method* pattern? 

  - How can this be used to avoid notifying *observers* in inconsistent state? 
* What can we do when we have *observers* interested only in certain types of events/aspects of the *observer*? 
* What is a change manager, and what are its responsibilities?
* When the dependency relationship between subject and *observer* is complicated, how can a change manager control the communication between subject and *observers*?
* When an *observer* observes more than one subject, how can we avoid redundant updates/notifications?
* The classic Model-View-Controller design is explained in GoF Implementation note #8: Encapsulating complex update semantics. 

  - Would it ever make sense for an *observer* (or view) to talk directly to the subject (or model)?
* How would you approach the task of debugging code in such a system?
* Is it clear to you how you would handle concurrency problems with this pattern? 

  - Consider an ``unregister()`` message being sent to a subject, just before the subject sends a ``notify()`` message to the ``ChangeManager`` (or Controller).
* What are the disadvantages of the Java implementation of the *observer* pattern in the `java.util` package?
* How is the observable pattern exploited in reactive programming? 
* Consider the case of remote observers (e.g., RMI). These can be destroyed without the subject being notified.

  - How should the subject deal with these? 
* What other known APIs use the *observer* pattern?

State
~~~~~

Recommended Readings
********************

* State, `Design Patterns`_, p.305-313
* The State of Things, `Head First Design Patterns`_, p.385-428

Alternative Readings
********************

* Replace State-Altering Conditionals with State, `Refactoring to Patterns`_, p.166-177
* Replace Type Code with State/Strategy, `Refactoring - Improving the Design of Existing Code`_, p.140-143 
* Replace Type Code with Class, `Refactoring - Improving the Design of Existing Code`_, p.134-137 
* Replace Type Code with Subclass, `Refactoring - Improving the Design of Existing Code`_, p.138-140
* Replace Conditional Logic with Polymorphism, `Refactoring - Improving the Design of Existing Code`_, p.19-26 
* Open/Closed Principle, `Agile Principles, Patterns and Practices in C#`_, p121-133.

Group Study Questions
*********************

* If something has only two to three states, is it overkill to use a *state* pattern?
* Continue the *state* vs. *strategy* discussion in `Head First Design Patterns` on page 411. 

  - Both patterns have the exact same class diagram, but they differ in intent. Debate on how they differ.
  - Compare how clients interact with them, e.g. who sets the strategy vs. who sets the state?
* How a given *state* can communicate with its context? (constructor delegation, parameter delegation, etc.)
* How are *states* initiated? (all at once vs. when needed).
* Where is the next *state* decided? (context vs. concrete classes).
* Discuss visibility of the concrete *state* classes.
* Discuss benefits/drawbacks of using an abstract class vs. an interface for states.

Strategy
~~~~~~~~

Recommended Readings
********************

* Strategy, `Design Patterns`_, p.315-323
* Welcome to Design Patterns, `Head First Design Patterns`_, p.1-35

Alternative Readings
********************

* Favor Composition over Inheritance, `Effective Java`_, p.81-86
* `A Study of the Fragile Base Class Problem <https://drive.google.com/file/d/0Bxed3Yafe-7xTWc4ZnpKdUxpYnM/view>`_
* Replace Conditional Logic with Strategy, `Refactoring to Patterns`_, p.129-143
* Simplify Conditional Expressions, `Refactoring - Improving the Design of Existing Code`_, p.147-169
* Introduce parameter Object, `Refactoring - Improving the Design of Existing Code`_, p.185-188
* Strategy Pattern, `Design Patterns Explained`_, p.139-157

Group Study Questions
*********************

* What is the intent of the *strategy* pattern?
* What are the consequences of the *strategy* pattern?
* What are possible indications of the need to use a *strategy* pattern?
* How can the context and the concrete *strategy* share information?
* How can the behavior of the context be altered dynamically using a *strategy* pattern?
* How can conditional statements be eliminated using a *strategy* pattern?
* Why is it preferable to use composition over inheritance in a case like this? (See fragile base class issue)
* What are the advantages/disadvantages of parameter passing? (loose coupling vs unused info)
* What are the advantages/disadvantages of passing the context? (strong coupling vs require info only)
* Is there anything that can be done to make the design less coupled when the context is passed as a parameter?
* How can clients be exposed to implementation issues by having to instantiate a concrete *strategy*?
* What can be done to deal with an explosion of *strategy* objects? (See stateless *strategies*, *flyweight* pattern)
* Why is it said that 'using inheritance instead of *strategy* is harder to maintain, understand and extend? (see the Duck problem in `Head First Design Patterns`_)
* What are the main object-oriented principles enforced by the *strategy* pattern and how?
* How does the *strategy* pattern foster the idea of designing for change?
* Why is the object-aggregation approach to inheritance superior to direct class inheritance for handling variation?
* What is meant by "switch creep"?
* What is wrong with copy and paste?
* Have you ever been in a situation where you did not feel you could afford to anticipate change? What drove you that way? What was the result?
* Should you ever use switch statements? Why or why not?
* What does "interface" mean in the statement "program to an interface, not to an implementation"? Do you think it means we are supposed to use something like Java or C# interfaces, or something else?
* What are the advantages of composition over inheritance?

Template Method
~~~~~~~~~~~~~~~

Recommended Readings
********************

* Template Method, `Design Patterns`_, p.325-330
* Encapsulating Algorithms, `Head First Design Patterns`_, p.275-313


Alternative Readings
********************

* Form Template Method, `Refactoring to Patterns`_, p.205-213
* Design for Inheritance or else Prohibit it, `Code Complete`, p.87-92
* Open/Closed Principle, `Agile Principles, Patterns and Practices in C#`_, p121-133.
* Liskov Substitution Principle, `Agile Principles, Patterns and Practices in C#`_, p135-151

Group Study Questions
*********************

* What is the difference between a *strategy pattern* and a *template method* pattern?
* How could the *template method* pattern be combined with a *strategy* pattern?
* The Gang of Four calls this a “template method.” Why do they do this?
* According to the Gang of Four, the intent of the template method pattern is to “define the skeleton of an algorithm in an operation, deferring some steps to subclasses. Redefine the steps in an algorithm without changing the algorithm’s structure.”  What does this mean?
* How is the principle of "encapsulate what varies" implemented in the *template method* pattern? 
* What is the Hollywood Principle? How does the template method implement it?
* What is the importance of minimizing the number of primitive operations extending classes must implement?
* What is a hook method, and what are they used for?
* How do we know when to use hooks and when to use abstract methods?
* How can we avoid that the template method is overridden?
* How does the *template method* can be designed for inheritance as suggested by Bloch in Effective Java? 
* How do we know when to use abstract methods and when to use hooks?
* How does the *template method* provides reusability through inheritance?
* What can we do in terms of naming conventions to make clearer which operations need overriding?
* How does the *template method* fosters cohesion?
* What are the *template method* coupling points?
* How does the *template method* fosters the open/closed principle?
* The *template method* relies on inheritance. Would it be possible to get the same functionality of a *template method*, using object composition? What would some of the tradeoffs be?
* How does the *Hollywood Principle* relate to the *Dependency Inversion Principle*?
* Take a design that has a lot of lower- and higher-level components (see page 298 in `Head First Design Patterns`_). Now apply the Hollywood principle and clean up the design as a group.
* Lead a group discussion on the first Brain Power on page 305 in `Head First Design Patterns`_. 

  - Pick apart the implementation of Sun’s sort(), which uses static methods instead of inheritance. 
  - Did they do the right thing? 
  - Split into smaller groups if you like, and then come back together to discuss or debate as a large group.


Visitor
~~~~~~~

Recommended Readings
********************

* Visitor, `Design Patterns`_, p.331-349
* Visitor, `Head First Design Patterns`_, p.628-629

Alternative Readings
********************

* Move Accumulation to Visitor, `Refactoring to Patterns`_, p.320-338
* `Double Dispatch <https://en.wikipedia.org/wiki/Double_dispatch>`_
* `Visitor in Java: Double dispatch (within a single hierarchy) <https://sourcemaking.com/design_patterns/visitor/java/2>`_

Group Study Questions
*********************

* One issue with the Visitor pattern involves cyclicality. When you add a new Visitor, you must make changes to the existing code. How would you work around this possible problem?
* How can the visitor be used to implement multiple-dispatch?
* WIP....

Creational Patterns
^^^^^^^^^^^^^^^^^^^

Abstract Factory
~~~~~~~~~~~~~~~~

Recommended Readings
********************

* Abstract Factory, `Design Patterns`_, p.87-95
* The Abstract Factory Pattern, `Design Patterns Explained`_, p.193-213

Alternative Readings
********************

* Baking with OO Goodness, `Head First Design Patterns`_, p109-168
* Dependency Inversion Principle, `Agile Principles, Patterns and Practices in C#`_, p153-162
* `Inversion of Control Containers and the Dependency Injection Pattern <https://www.martinfowler.com/articles/injection.html>`_

Group Study Questions
*********************

* Although using “switches” can be a reasonable solution to a problem that requires choosing among alternatives, it caused problems design. Can you tell what kind of problems those would be?
* What might a switch indicate the need for?
* Why is this pattern named “Abstract Factory”?
* What are the three key strategies in the *abstract factory*?
* What are the consequences of the *abstract factory* pattern?
* Why do you think the Gang of Four calls this pattern “Abstract Factory”? 

  - Is it an appropriate name for what it is doing? Why or why not?
* How do you know when to use the *abstract factory* pattern?
* What design principles can you name for this pattern?
* Where to put the concrete factory instantiation and how to decide which concrete factory to use?
* Why could you need to use an adapter to make *abstract factory* work?

Builder
~~~~~~~

Recommended Readings
********************

* Builder, `Design Patterns`_, p.97-106
* Builder, `Head First Design Patterns`_, p.614-615

Alterntive Readings
*******************

* Encapsulate Composite with Builder, `Refactoring to Patterns`_, p.96-113
* Consider a Builder when Faced with Many Constructor Parameters, `Effective Java`_, p.11-16

Group Study Questions
*********************

* What’s the intent of the *builder* pattern?
* List scenarios where you can use this pattern.
* Do you think that necessarily all these scenarios should happen to use this pattern or are they all independent.
* Which are the participants of this design pattern?
* What’s the main difference between the *builder* and the other creational patterns?
* Which are the benefits of using the *builder* pattern?
* Which are the downsides of the *builder* pattern?
* Who is responsible for memory handling in this pattern?
* Can the constructor of the *builder* pattern set or create values by default?
* Can the operations/methods of the *builder* pattern set or create values by default?
* Why is there no abstract/parent class for any of the products?
* Should the *builder* operations be overridable? How could you prevent this from happening?
* Which is the difference between fluent and non-fluent *builder* pattern?
* If the building process is abstracted into a class or method, does it continue being a *builder* pattern?
* Does this pattern implies mutability? i.e. ``StringBuilder`` class in Java 
* Can we assume that as the *builder* classes grow horizontally, fewer and fewer methods are going to be shared between *builders*?
* Which could be the motivation to use a *builder* pattern instead of a *composite*? 
  
  - What advantages could it have to refactor the code?
  - Why the refactoring from *composite* to builder promotes a loosely coupled design and scalability?
* Which design principles are related to this design pattern?
* Like the *abstract factory* pattern, the *builder* pattern requires that you define an interface, which will be used by clients to create complex objects in pieces. In the MazeBuilder example, there are BuildMaze(), BuildRoom() and BuildDoor() methods, along with a GetMaze() method. How could the *builder* pattern allow me to add new methods to the *builder’s* interface, without having to change each and every sub-class of the *builder*?

Factory Method
~~~~~~~~~~~~~~

Recommended Readings
********************

* Factory Method, `Design Patterns`_, p.107-116
* Factory Method, `Design Patterns Explained`_, p.385-391

Alterntive Readings
*******************

* Baking with OO Godness, `Head First Design Patterns`_, p.109-168
* Introduce Polymorphic Creation with Factory Method, `Refactoring to Patterns`_, p.88-95
* Move Creation Knowledge to Factory, `Refactoring to Patterns`_, p.68-79
* Encapsulate Classes with Factory, `Refactoring to Patterns`_, p.80-87


Group Study Questions
*********************

* TDB

Prototype
~~~~~~~~~

Recommended Readings
********************

* Prototype, `Design Patterns`_, p.117-126
* Prototype, `Head First Design Patterns`_, p.626-627

Alterntive Readings
*******************

* Override clone judiciously, `Effective Java`_, p.54-61.
* `Deep vs Shallow vs Lazy Copy <https://sites.google.com/a/backcountry.com/tico-coding/dpsg/pattern-catalog/creational/prototype>`_


Group Study Questions
*********************

* When should this creational pattern be used over the other creational patterns?
* Explain the difference between deep vs. shallow copy.
* WIP...

Singleton
~~~~~~~~~

Recommended Readings
********************

* Singleton, `Design Patterns`_, p.127-134
* One of a Kind Objects, `Head First Design Patterns`_, p.169-190

Alterntive Readings
*******************

* Inline Singleton, `Refactoring to Patterns`_, p.114-120

Group Study Questions
*********************

* Discuss how and why you would use the *singleton* pattern with the *factory* pattern to create objects.
* What are some disadvantages to the *singleton* pattern?
* Discuss how you would implement a *singleton* that limited the number of instances to, say, five objects. 
  - How would you change the code on page 180 of `Head First Design Patterns`_ to do this?
* The *singleton* pattern is often paired with the *abstract factory* pattern. What other creational or non-creational patterns would you use with the *singleton* pattern?
* How does a Spring *singleton* differs from a Java *singleton*?

Further Readings
----------------

A selection of web sites where members of the group can continue their learning journey.

Design Patterns Catalogs
^^^^^^^^^^^^^^^^^^^^^^^^

`SourceMaking`_:
 Website specialized in design patterns, anti-patterns, refactoring, and UML.

`Catalog of Patterns of Enterprise Application Architecture`_:
 Martin Fowler's awesome catalog of enterprise application patterns.

`Enterprise Integration Patterns`_:
 Great catalog of patterns to create messaged-based systems.

`Workflow Patterns`_:
 A catalog of workflow orchestration patterns.

Object-Oriented Programming 101: Must Reads
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

`Principles of Object-Oriented Design`_:
 Website containing dozens of references to other excellent papers on well-known design techniques, principles, and patterns.

`Type, Data Abstraction and Polymorphism`_:
 Best explanation ever on polymorphism and type systems by the great type theorist Luca Cardelli.

`Encapsulation and Inheritance`_:
 Best explanation ever on the true meaning of encapsulation by the great Alan Snyder.

`Abstraction vs. Information Hiding vs Encapsulation`_:
 Great article that delves into the semantic similarities and differences of these three fundamental concepts.

`Design by Contract`_:
 A coherent set of methodological principles helping to produce correct and robust software.


Other Interesting Readings
^^^^^^^^^^^^^^^^^^^^^^^^^^

`Teach Yourself Programming in Ten Years`_:
 Peter Norvig with a compelling argument about how it takes time and effort to become really good at programming.

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
.. _Principles of Object-Oriented Design: http://www.butunclebob.com/ArticleS.UncleBob.PrinciplesOfOod
.. _Type, Data Abstraction and Polymorphism: https://drive.google.com/file/d/0Bxed3Yafe-7xRkJMOGR3UGdIZG8/view
.. _Encapsulation and Inheritance: https://drive.google.com/file/d/0Bxed3Yafe-7xeWFqeEZXNHljM1U/view
.. _Abstraction vs. Information Hiding vs Encapsulation: http://www.tonymarston.co.uk/php-mysql/abstraction.txt
.. _Teach Yourself Programming in Ten Years: https://norvig.com/21-days.html 
.. _Non-software Examples of Design Patterns: http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.106.8473&rep=rep1&type=pdf
.. _A Study of The Fragile Base Class Problem: http://www.cas.mcmaster.ca/~emil/Publications_files/MikhajlovSekerinski98FragileBaseClassProblem.pdf
.. _Design by Contract: http://se.inf.ethz.ch/~meyer/publications/computer/contract.pdf
.. _Agile Principles, Patterns and Practices in C#: http://www.informit.com/store/agile-principles-patterns-and-practices-in-c-sharp-9780131857254
.. _Refactoring - Improving the Design of Existing Code: http://www.informit.com/store/refactoring-improving-the-design-of-existing-code-9780201485677
