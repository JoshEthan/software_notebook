"A design principle is a basic tool or technique that be applied to designing or writing code to make that code more maintainable, flexible, or extensible."  (pg. 376)

"Using proven OO design principles results in more maintainable, flexible, and extensible software." (pg. 376)

"Principle #1: The Open-Closed Principle (OCP)-- The OCPT is all about allowing change, but doing it without requiring you to modify existing code. Classes should be open for extension and closed for modification." (pg. 377)

"In other words, nobody can change the behavior, because you've locked it up in a class that you're sure won't change." (pg. 377)

"You close classes by not allowing anyone to touch your working code." (pg. 377)

"So you let them subclass your class, and then they can override your method to work like they want it to. So even though they didn't mess with your working code, you still left your class open for extension." (pg. 377)

"You open classes by allowing them to be subclassed and extended." (pg. 377)

"The OCP is about flexibility, and goes beyond just inheritance.-- It's certainly true that inheritance is a simple example of the open-closed principle, but there's a lot more to it than just subclassing and overriding a method. Anytime you write working code, you want to do your best to make sure that code stays working... and that means not letting other people change that code." (pg. 380)

"Rather than just diving into your code and making a bunch of changes, the OCP lets you extend your working code, without change that code." (pg. 380)

"Once you have a class that works, and is being used, you really don't want to make changes to it unless you have to. But remember, CHANGE is the great constant in software development. With the OCP, we allow for change through extension, rather than having to go back and modify your existing code. Subclasses can add and extend the base class's behavior, without messing around with code that you already know is working and making the customer happy."

"OCP is really a combination of encapsulation"

""