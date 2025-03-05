"A design principle is a basic tool or technique that be applied to designing or writing code to make that code more maintainable, flexible, or extensible."  (pg. 376)

"Using proven OO design principles results in more maintainable, flexible, and extensible software." (pg. 376)

"Principle #1: The Open-Closed Principle (OCP)-- The OCPT is all about allowing change, but doing it without requiring you to modify existing code. Classes should be open for extension and closed for modification." (pg. 377)

"In other words, nobody can change the behavior, because you've locked it up in a class that you're sure won't change." (pg. 377)

"You close classes by not allowing anyone to touch your working code." (pg. 377)

"So you let them subclass your class, and then they can override your method to work like they want it to. So even though they didn't mess with your working code, you still left your class open for extension." (pg. 377)

"You open classes by allowing them to be subclassed and extended." (pg. 377)

"The OCP is about flexibility, and goes beyond just inheritance.-- It's certainly true that inheritance is a simple example of the open-closed principle, but there's a lot more to it than just subclassing and overriding a method. Anytime you write working code, you want to do your best to make sure that code stays working... and that means not letting other people change that code." (pg. 380)

"Rather than just diving into your code and making a bunch of changes, the OCP lets you extend your working code, without change that code." (pg. 380)

"Once you have a class that works, and is being used, you really don't want to make changes to it unless you have to. But remember, CHANGE is the great constant in software development. With the OCP, we allow for change through extension, rather than having to go back and modify your existing code. Subclasses can add and extend the base class's behavior, without messing around with code that you already know is working and making the customer happy." (pg. 381)

"OCP is really a combination of encapsulation. You're finding the behavior that stays the same, and abstracting that behavior away into a base class, and then locking that code up from modification. But then when you need new or different behavior, your subclasses handle the changes by extending the base class. That's where encapsulation comes in: you're encapsulating what varies (behavior in the subclasses) away from what stays the same (the common behavior in the base class)." (pg. 381)

"Anytime your code is closed for modification but open for extension, you're using the OCP. So for example, if you had several private methods in a class, those are closed for modification- no other code can mess with them. But then you could add several public methods that invoked those private methods in different ways. You're extending the behavior of the private methods, without changing them. That's another example of the OCP in action." (pg. 381)

"Principle #2: The Don't Repeat Yourself Principle (DRY)-- Avoid duplicate code by abstracting out things that are common and placing those things in a single location." (pg. 382)

"
1. Let's abstract out the common code.
2. Now remove the code from other locations...
3. ...and reference the code from Step #1" (pg. 383)

"DRY is really about ONE requirement in ONE place.-- Abstracting out duplicate code is a good start to using DRY, but there's more to it than just that. When you're trying to avoid duplicate code, you're really trying to make sure that you only implement each feature and requirement in your application one single time." (pg. 384)

"DRY is about having each piece of information and behavior in your system in a single, sensible place." (pg. 385)

"DRY is about avoiding duplicate code, but's also about doing it in a way that won't create more problems down the line. Rather than just tossing code that appears more than once into a single class, you need to make sure each piece of information and behavior in your system has a single, clear place where it exists. That way, your system always know exactly where to go when it needs that information." (pg. 385)

"Because DRY is related to our features and requirements, we should apply it to gathering those features and requirements as well as writing our code. Whether you're writing requirements, developing use cases, or coding, you want to be sure that you don't duplicate things in your system. A requirement should be implemented one time, use cases shouldn't have overlap, and your code shouldn't repeat itself. DRY is about a lot more than just code." (pg. 385)

"All of this is to avoid maintenance problems later. But it's more than just avoiding a need to update code in more than one place. Remember, DRY is about having a single source for a particular piece of information or behavior. But that single source has to make sense!" (pg. 385)

"So DRY is not just removing duplication, it's also about making good decisions about how to break up your system's functionality." (pg. 385)

"DRY is about having each piece of information and behavior in your system in a single, sensible place." (pg. 388)

"Principle #3: The Single Responsibility Principle (SRP)-- The SRP is all about responsibility, and which objects in your system do what. You want each object that you design to have just one responsibility to focus on- and when something about that responsibility changes, you'll know exactly where to look to make those changes in your code." (pg. 390)

"Every object in your system should have a single responsibility, and all the object's services should be focused on carrying out that single responsibility." (pg. 390)

"You've implemented Single Responsibility Principle correctly when each of your objects has only one reason to change." (pg. 390)

"SRP and DRY are related, and often appear together. DRY is about putting a piece of functionality in a single place, such as a class; SRP is about making sure that a class does only one thing, and that it does it well." (pg. 391)

"In good applications, one class does one thing, and does it well, and no other classes share that behavior." (pg. 391)

"Having each class do only one thing is not limiting, when you realize that the one thing a class does can be a pretty big thing." (pg. 391)

"SRP will often make your classes bigger. Since you're not spreading out functionality over a lot of classes- which is what many programmers not familiar with the SRP will do- you're often putting more things into a class." (pg. 391)

"But using the SRP will usually result in less classes, and that generally makes your overall application a lot simpler to manage and maintain." (pg. 391)

"Cohesion is actually just another name for SRP. If you're writing highly cohesive software, then that means that you're correctly applying the SRP." (pg. 391)

"If what you've said doesn't make sense, then you're probably violating the SRP with that method. The method might belong on a different class... think about moving it.-- The (class name) (method) itself." (pg. 392)

"Cases like getVariable are why SRP analysis is just a guideline. You still are going to have to make some judgement calls using common sense and your own experience." (pg. 394)

"Once you've done an analysis, you can take all the methods that don't make sense on a class, and move those methods that don't make sense on a class, and move those methods to classes that do make sense for that particular responsibility." (pg. 395)

"If a parameter that might cause a method to make sense is passed into a class's constructor, your SRP analysis might be misleading. But that's why you always need to apply a good amount of your own common sense and knowledge of the system in addition to what you learn from the SRP analysis." (pg. 396)

"Principle #4: The Liskov Substitution Principle (LSP)-- Subtypes must be substitutable for their base types." (pg. 400)

"The LSP is all about well-designed inheritance. When you inherit from a base class, you must be able to substitute your subclass for that base class without things going terribly wrong. Otherwise you've used inheritance incorrectly!" (pg. 400)

"LSP states that a subtype must be substitutable for its base type." (pg. 403)

"It might seem like this isn't such a big deal, but code that violates LSP can be confusing and a real nightmare to debug." (pg. 404)

"It's hard to understand code that misuses inheritance.-- When you use inheritance, your subclass gets all the methods from its superclass, even if you don't want those methods. And if you've used inheritance badly, then you're going to end up with a lot of methods that you don't want, because they probably don't make sense on your subclass." (pg. 404)

"First, be sure your subclasses can be substitute for their base types, which is just following the LSP. Second, learn about some alternatives to using inheritance in your code..." (pg. 404)

"Delegation is when one class hands off the task of doing something to another class. It's also just one of several alternatives to inheritance." (pg. 406)

"Delegation is when you hand over the responsibility for a particular task to another class or method." (pg. 406)

"If you need to use functionality in another class, but you don't want to change that functionality, consider using delegation instead of inheritance." (pg. 407)

"Use composition to assemble behaviors from other classes." (pg. 408)

"Sometimes delegation isn't quite what you need; in delegation, the behavior of the object you're delegating behavior to never changes." (pg. 408)

"In some cases, you need to have more than one single behavior to choose from." (pg. 408)

"When we reference a whole family of behaviors we're using composition." (pg. 409)

"The closed-in diamond at the end of a line means composition." (pg. 409)

"Composition is most powerful when you want to use behavior defined in an interface, and then choose from a variety of implementations of that interface, at both compile time and run time." (pg. 409)

"Composition allows you to use behavior from a family of other classes, and to change that behavior at runtime." (pg. 409)

"Pizza is actually a great example of composition: it's composed of different ingredients, but you can swap out different ingredients without affecting the overall pizza slice." (pg. 409)

"When an object is composed of other objects, and the owning object is destroyed, the objects that are part of the composition go away too." (pg. 410)

"In composition, the object composed of other behaviors owns those behaviors. When the object is destroyed, so are all of its behaviors." (pg. 411)

"The behaviors in a composition do not exist outside of the composition itself." (pg. 411)

"Composition is really about ownership. The main object owns the composed behavior, so if that objects goes away, all the behavior does, too." (pg. 411)

"Aggregation is when you want all the benefits of composition- flexibility in choosing a behavior, and adhering to the LSP- but your composed objects need to exist outside of your main object." (pg. 412)

"Aggregation is when one class is used as part of another class, but still exists outside of that other class." (pg. 412)

"A line with an open diamond at the end means aggregation." (pg. 412)

"To figure out when to use composition or aggregation is to ask: Does this object whose behavior I want to use exist outside of the object that uses its behavior." (pg. 413)

"If the object does make sense existing on its own, then you should use aggregation; if not, then go with composition." (pg. 413)

"Be careful! Sometimes the slightest change in the usage of your objects can make all the difference." (pg. 413)

"Inheritance is just one option." (pg. 414)

"If you favor delegation, composition, and aggregation over inheritance, your software will usually be more flexible, and easier to maintain, extend, and reuse." (pg. 414)

"Delegate behavior to another class when you don't want to change the behavior, but it's not your object's responsibility to implement that behavior on its own." (pg. 414)

"You can reuse behavior from one or more classes, and in particular from a family of classes, with composition. Your object completely owns the composed objects, and they do not exist outside of their usage in your object." (pg. 414)

"When you want the benefits of composition, but you're using behavior from an object that does exist outside of your object, use aggregation." (pg. 414)

"Subclassing and inheritance are key to any good OO programming language. The LSP is not about subclassing, though; it's about when to subclass. If your subclass really is substitutable for its base type, then you've probably done a good job using inheritance. If your subclass is not substitutable for its base type, then you might look at other OO solutions like aggregation or delegation." (pg. 415)

"It is OK to use delegation, composition, or aggregation in a class that really shouldn't extend another class. In fact, the LSP doesn't apply at all to aggregate or delegate classes, because those are two great ways to fix an inheritance tree that doesn't conform to the LSP. You might even say that good use of the LSP goes hand-in-hand with more delegation, composition, and aggregation." (pg. 415)

"Lots of times, you don't need to worry about the formal name of design principle to write good code. For example, to make a child extend the parent, all methods need to be changed. That should be a real tip-off that you've got some inheritance problems." (pg. 415)

"You really don't need to memorize these symbols at all. While UML provides specific notation for aggregation and composition, they are all just different forms of association. So just like we did with delegation, you can use a normal line with an arrow, a normal association, for composition and aggregation." (pg. 415)

"It's possible that could be confusing to developers, but it also allows for a lot more flexibility." (pg. 415)

"If you're using a basic association arrow, you won't need to change your class diagram at all. It also gives the developer freedom to come up with their own ideas about how to implement the association." (pg. 415)

"There's nothing wrong with using the aggregation and composition symbols, but you shouldn't get too hung up on it, especially if you're early on in the development cycle. You never know what might change later, and flexibility is always better than rigidity in your design." (pg. 415)

"The Open-Closed Principle keeps your software reusable, but still flexible, by keeping classes open for extension, but closed for modification." (pg. 417)

"With classes doing one single thing through the Single Responsibility Principle, it's even easier to apply the OCP to your code." (pg. 417)

"When you're trying to determine if a method is the responsibility of a class, ask yourself, Is it this class's job to do this particular thing? If not, move the method to another class." (pg. 417)

"Once you have your OO code nearly complete, be sure that you Don't Repeat Yourself. You'll avoid duplicate code, and ensure that each behavior in your code is in a single place." (pg. 417)

"DRY applies to requirements as well as your code: you should have each feature and requirement in your software implemented in a single place." (pg. 417)

"The Liskov Substitution Principle ensures that you use inheritance correctly, by requiring that subtypes be substitutable for their base types." (pg. 417)

"When you find code that violates the LSP, consider using delegation, composition, or aggregation to use behavior from other classes without resorting to inheritance." (pg. 417)

"If you need behavior from another class but don't need to change or modify that behavior, you can simply delegate to that class to use the desired behavior." (pg. 417)

"Composition lets you choose a behavior from a family of behaviors, often via several implementations of an interface." (pg. 417)

"When you use composition, the composing object owns the behavior it uses, and they stop existing as soon as the composing object does." (pg. 417)

"Aggregation allows you to use behaviors from another class without limiting the lifetime of those behaviors." (pg. 417)

"Aggregated behaviors continue to exist even after the aggregating object is destroyed." (pg. 417)

"Classes should be open for extension, but closed for modification (the OCP)" (pg. 418)

"Avoid duplicate code by abstracting out things that are common and placing them in a single location (the DRY principle)" (pg. 418)

"Every object in your system should have a single responsibility, and all the object's services should be focused on carrying out that single responsibility (the SRP)" (pg. 418)

"Subclasses should be suitable for their base classes (the LSP)" (pg. 418)

"I let someone else do things for me: is a basic delegation definition, but a class that uses composition uses other classes for behavior, also." (pg. 420)

"A subclass is the only class that changes another class's behavior." (pg. 420)

"In aggregation and delegation, object instances are tied together, but not dependent on each other for their existence." (pg. 420)