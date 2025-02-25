"An abstract class defines some basic behavior, but it's really the subclasses of the abstract class that add the implementation of those behaviors. " (pg. 201)

"Abstract classes are placeholders for actual implementation classes." (pg. 201)

"The abstract class defines behavior, and the subclasses implement that behavior." (pg. 201)

"Whenever you find common behavior in two or more places, look to abstract that behavior into a class, and then reuse that behavior in the common classes." (pg. 205)

"When the name of a class is in italics, the class is abstract." (pg. 206)

"The line with a diamond means aggregation. Aggregation is a special form of association, and means that one thing is made up (in part) of another thing." (pg. 206)

"A line with an arrow that isn't colored means generalization. You use a generalization to show that a class extends and inherits behavior from a more generalized class." (pg. 206)

"Many people use just the basics you've already learned, and are happy... It's really up to you; as long as you can communicate your design, you've used UML the way it's intended." (pg. 207)

"These are little indicators that we may have a design problem. When things just don't seem to make sense in your application, you may want to investigate further...-- Subclass for each type just for a constructor; Extra code from abstract class; function for each type" (pg. 213)

"Along with some major design improvements, we've uncovered a few problems with the search tool. That's OK... you're almost always going to fund a few new problems when you make big changes to your design." (pg. 214)

"One of the best ways to see if software is well-designed is to try and CHANGE it.-- If your software is hard to change, there's probably something you can improve about the design." (pg. 217)

"Inheritance has the dual role of defining behavior that applies to multiple types, and also being the preferred focus of classes that use those types." (pg. 223)

"When choosing between writing code that interacts directly with a subclass or with the interface, you should always favor coding to the interface, not the implementation. This adds flexibility to your app." (pg. 224)

"Coding to an interface, rather than to an implementation makes your software easier to extend." (pg. 224)

"By coding to an interface, your code will work with all of the interface's subclasses- even ones that haven't been created yet." (pg. 224)

"Encapsulation has been responsible for preventing more maintenance problems than any other OO principle in history, by localizing the changes required for the behavior of an object to vary." (pg. 225)

"But there's more to encapsulation then just avoiding lots of copy-and-paste. Encapsulation also helps you protect your classes from unnecessary changes." (pg. 226)

"Anytime you have behavior in an application that you think is likely to change, you want to move that behavior away from parts of your application that probably won't change very frequently. In other words, you should always try to encapsulate what varies." (pg. 226)

"Software that isn't well-designed falls apart at the first sign of change, but great software can change easily." (pg. 228)

"The easier way to make your software resilient to change is to make sure each class has only one reason to change. In other words, you're minimizing the chances that a class is going to have to change by reducing the number of things in that class that can cause it to change." (pg. 228)

"When you see a class that has more than one reason to change, it is probably trying to do too many things. See if you can break up the functionality into multiple classes, where each individual class does only one thing- and therefore has only one reason to change." (pg. 228)

"When you see a potential for duplicate code, you should look to encapsulate." (pg. 230)

"Most of the time abstracting out common properties leads you to encapsulation." (pg. 231)

"Encapsulate what varies." (pg. 232)

"Code to an interface rather than to an implementation." (pg. 232)

"Each class in your application should have only one reason to change." (pg. 232)