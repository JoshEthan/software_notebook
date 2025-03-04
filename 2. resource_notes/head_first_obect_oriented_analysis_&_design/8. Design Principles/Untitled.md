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