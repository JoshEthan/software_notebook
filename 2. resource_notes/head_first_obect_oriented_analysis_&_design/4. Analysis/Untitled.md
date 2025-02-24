"Your software has a context." (pg. 147)

"But our software has to work in the real world, not just in a perfect world. That means we have to think about our software in a different context." (pg. 147)

"The key to making sure things work and that the real world doesn't screw up your application is analysis: figuring out potential problems, and then solving those problems- before you release your app out into the real world." (pg. 147)

"Analysis helps you ensure your system works in a real-world context." (pg. 147)

"The first step in good analysis is figuring out potential problems." (pg. 148)

"Write your use cases in a way that makes sense to you, your boss, and your customers." (pg. 151)

"Analysis and your use cases let you show customers, managers, and other developers how your system works in a real world context." (pg. 151)

"Use cases are very precise. If your use case doesn't detail exactly what your system is supposed to do, then you could miss an important requirement or two and end up with unhappy customers." (pg. 151)

"But, use cases don't have to be very formal; in other words, your use case may not look like ours, and ours might not look like anyone else's. The important thing is that your use case makes sense to you, and that you can explain it to your co-workers, boss, and customers." (pg. 151)

"Since we changed our diagram, we need to go back to our use case, and update it with the new steps we've figured out." (pg. 152)

"Our analysis has made us realize we need to make some changes to our use case- and those changes mean that we need to make some additions to our system, too." (pg. 153)

"Since this is our second use case, let's label it according to what it describes." (pg. 153)

"Each use case should detail one particular user goal." (pg. 154)

"... that's what analysis is really about: making sure that you didn't forget anything that will help your software work in a real world context." (pg. 154)

"Class diagrams show the basic code-level constructs in your app." (pg. 155)

"Remember, these are the attributes of your class, which usually match up with the class's member variables and these are the class's operations, which are usually the class's public methods." (pg. 155)

"Delegation helps our applications stay loosely coupled. That means that your objects are independent of each other; in other words, changes to one object don't require you to make a bunch of changes to other objects." (pg. 162)

"So with delegation and a loosely coupled application, you can change the implementation of one object and you won't have to change all the other objects in your application. Your objects are shielded from implementation changes in other objects." (pg. 162)

"Delegation shields your objects from implementation changes to other objects in your software." (pg. 162)

"Anytime you see brackets, it indicates the multiplicity of an attribute: how many of a certain type that the attribute can hold." (pg. 165)

"Pay attention to the nouns in your use case.-- the nouns in a use case are usually the classes you need to write and focus on in your system." (pg. 167)

"Remember, you need classes only for the parts of your system you have to represent. We don't need a class for 'outside' or 'inside' or the 'owner' because our software doesn't have to represent those things." (pg. 169)

"Looking at the nouns (and verbs) in your use case to figure out classes and methods is called textual analysis." (pg. 169)

"Use cases are certainly a good start towards writing good software. But there's more to it than that. Remember, analysis helps you figure out the classes from your use case, and in the next chapter, we'll spend some time talking about good design principles in writing those classes." (pg. 173)

"You don't need to write use cases to create good software. There are plenty of programmers who are good at their jobs, and don't even know what a use case is. But if you want your software to satisfy the customer more often, and you want your code to work correctly with less rework, then use cases can really help you nail your requirements down... before you make embarrassing mistakes in front of your boss or a customer." (pg. 173)

"You really don't need to focus too much on grammar. Just write your use case in conversational English. Then figure out what the 'things' are in your use case- those are generally the nouns. For each noun, think about if you need a class to represent it, and you've got a good start on a real-world analysis of your system." (pg. 173)

"When you write your use case, reread it, and make sure that it makes sense to you. You might even want to let a couple of friends or co-workers read through it, too, and make sure it will work in the real world, not just in a controlled environment." (pg. 173)

"A good use case clearly and accurately explains what a system does, in language that's easily understood." (pg. 173)

"With a good use case complete, textual analysis is a quick and easy way to figure out the classes in your system." (pg. 173)

"Textual analysis tells you what to focus on, not just what classes you should create." (pg. 174)

"In other words, our analysis helped us understand what to focus on." (pg. 174)

"Remember, pay attention to those nouns!-- Even if the nouns in your use case don't get turned into classes in your system, they're always important to making your system work like it should." (pg. 175)

"The point is that the nouns are what you should focus on." (pg. 175)

"Pay attention to the nouns in your use case, even when they aren't classes in your system." (pg. 175)

"Think about how the classes you do have can support the behavior your use case describes." (pg. 175)

"It seems like if the nouns in the use case are usually the classes in my system, then the verbs in my use case are my methods." (pg. 176)

"The verbs in your use case are (usually) the methods of the objects in your system." (pg. 176)

"You've already seen how the nouns in your use case usually are a good starting point for figuring out what classes you might need in your system. If you look at the verbs in your use case, you can usually figure out what methods you'll need for the objects that those classes represent." (pg. 176)

"There are times when you might represent things external to the system, but usually only when you need to interact with those external things." (pg. 179)

"Remember, what works in software doesn't always work in real life. Make sure your applications are real-world compatible." (pg. 179)

"You don't usually represent living things with a class unless the system is going to store long-term information about that thing.-- You'll often see classes like user or Manager, but these represent roles in a system, or store credit cards or addresses." (pg. 179)

"The nouns are candidates for classes... not every noun will be a class." (pg. 179)

"The verbs are candidates for operations." (pg. 179)

"Textual analysis is a really good start to figuring out the classes and methods you'll need in your system." (pg. 179)

"Most of the time, nouns that are outside the system don't get turned into classes. The only exception is when you have to interact with something outside of the system- like when there's some state or behavior that the system needs to work with on a recurring basis." (pg. 179)

"A solid line from one class to another is called an association. It means that one class is associated with another class, by reference, extension, inheritance, etc." (pg. 182)

"This line goes from the source class to the target class. This means that the source class has an attribute of a certain type, the target class." (pg. 182)

"When you're using associations to represent attributes, you usually do not write the attribute that the associate represents in the class's attribute section." (pg. 182)

"The multiplicity an attribute is unlimited." (pg. 182)

"The name of the attribute in the source class is written here, at the target end of the line." (pg. 183)

"The number is the multiplicity of this association. It's how many of the target type is stored in the attribute of the source class." (pg. 183)

"Once I had my class diagram, I had a pretty good idea about how my whole system was going to work." (pg. 186)

"Once you've got the use case, it's pretty natural to do some analysis, and turn the nouns into classes. It seems like you wouldn't have to spend as much time worrying about what should be a class and what shouldn't." (pg. 186)

"With use cases and class diagrams, if I make a mistake, I can just scribble things out and redraw my diagram.-- Remember how we said OA&D helps you write great software every time? OOA&D can help you avoid making mistakes in your code." (pg. 186)

"Class diagrams provide limited type information."

"Class diagrams don't tell you how to code your methods."

"Class diagrams only give you a 10,000 foot view of your system."

"Class diagrams are great for modeling the classes you need to create, but they don't provide all the answers you'll need in programming your system." (pg. 188)

"Analysis helps you ensure that your software works in the real world context, and not just in a perfect environment." (pg. 191)

"Use cases are meant to be understood by you, your managers, your customers, and other programmers." (pg. 191)

"You should write your use cases in whatever format makes them most usable to you and the other people who are looking at them." (pg. 191)

"A good use case precisely lays out what a system does, but does not indicate how the system accomplishes that task." (pg. 191)

"Each use case should focus on only one customer goal. If you have multiple goals, you need to write multiple use cases." (pg. 191)

"Class diagrams give you an easy way to show your system and its code constructs at a 10,000-foot view." (pg. 191)

"The attributes in a class diagram usually map to the member variables of your classes." (pg. 191)

"The operations in a class diagram usually represent the methods of your classes." (pg. 191)

"Class diagram leave out lots of detail out, such as class constructors, some type information, and the purpose of operations on your classes." (pg. 191)

"Textual analysis helps you translate a use case into code-level classes, attributes, and operations." (pg. 191)

"The nouns of a use case are candidates for classes in your system, and the verbs are candidates for methods on your system's classes." (pg. 191)

"Noun Analysis is done to your use case to figure out what classes you need in your system." (pg. 196)

"Multiplicity describes how many of a specific type can be stored in an attribute of a class." (pg. 196)

"Attribute is the UML term that usually represents a method in one of your classes." (pg. 196)

"Class Diagram lists all the code-level constructs along with their attributes and operations." (pg. 196)

"Operation is equivalent to a member variable in a class." (pg. 196)

"Association visually shows that one class has a relation to another class, usually through an attribute." (pg. 196)

"Verb Analysis helps you figure out the candidates for methods on the objects in your system." (pg. 196)