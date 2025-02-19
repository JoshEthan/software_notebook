"UML class diagrams don't show constructors" (pg. 4)

"Great software always does what the customer wants it to. So even if customers think of new ways to use the software, it doesn't break or give them unexpected results. -- This approach is all about making sure the customer is happy with what their app does." (pg. 10)

"Great software is code that is object-oriented. So there's not a bunch of duplicate code, and each object pretty much controls its own behavior. It's also easy to extend because your design is really solid and flexible. --Good OO programmers are always looking for ways to make their code more flexible." (pg. 10)

"Great software is when you use tried-and-true design patterns and principles. You've kept your objects loosely coupled, and your code open for extension but closed for modification. That also helps make the code more reusable, so you don't have to rework everything to use parts of your application over and over again. --This design-focused approach optimizes code for extension and reuse, and takes advantages of design patterns and proven OO techniques." (pg. 10)

"Great software is more than just one thing. First, great software must satisfy the customer. The software must do what the customer wants it to do. Second, great software is well-designed, well-coded, and easy to maintain, reuse, and extend." (pg. 12)

"Great software in 3 easy steps.
1. Make sure your software does what the customer wants it to do. --This step focuses on the customer. Make sure the app does what it's supposed to do FIRST. This is where getting good requirements and doing some analysis comes in.
2. Apply basic OO principles to add flexibility. --Once your software works, you can look for any duplicate code that might have slipped in, and make sure you're using good OO programming techniques.
3. Strive for a maintainable, reusable design. --It's time to apply patterns and principles to make sure your software is ready to use for years to come." (pg. 13)

"Remember, we need to start out by making sure the app actually does what the customer wants... Don't worry too much about trying to apply patterns or other OO techniques to your app at this point... just get it to where it's working like it should." (pg. 14)

"Don't create problems to solve problems."(pg. 15)

"Enums, enumerated types, function sort of like constants. One of the big advantages of using enums is that it limits the possible values you can supply to a method... no more misspellings or case issues." (pg. 16)

"Enums are enumerated types. Enumerated types let you define a type name and then a set of values that are allowed for that type. Then, you refer to a specific value." (pg. 16)

"With enums, we don't have to worry about comparisons getting screwed up by misspellings or case issues." (pg. 17)

"The cool thing about enums is that methods or classes that use them are protected from any values not defined in the enum. So you can't misspell or mistype an enum without getting a compiler error. It's a great way to get not only type safety, but value safety; you can avoid getting bad data for anything that has a standard range or set of legal values." (pg. 17)

"The app is not going to break so easy, because we've added both type safety and value safety with enums. Less problems and less maintenance. --Code that is not fragile is generally referred to as robust code." (pg. 18)

"It's OK to do a little design when working on step 1, as long as your focus is still on the customer's needs. You want the basic features of your application in place before you start making big design changes. But while you're working on functionality, you can certainly use good OO principles and techniques to make sure your app is well designed from the start." (pg. 19)

"A single class diagram can have multiple classes in it." (pg. 19)

"Remember, our first job is to please the customer, and then we really focus on improving our OO design." (pg. 19)

"I'm not done with the first step until the app works like my customer wants it to. You want to make sure that the app works like it should before you dive into applying design patterns or trying to do any real restructuring of how the app is put together." (pg. 22)

"It's important to finish step 1 before going on to step 2, because you're going to makes lots of changes to your software when you're getting it to work right. Trying to do too much design before you've at least got the basic functionality down can end up being a waste, because a lot of the design will change as you're adding new pieces of functionality to your classes and methods." (pg. 22)

"You don't have to follow these steps exactly, but they do provide an easy path to follow to make sure your software does what it's supposed to, and is well-designed and easy to reuse. If you've got something similar that accomplishes the same goals, that's great!" (pg. 22)

"Step 2 is where you take software that works and make sure the way it's put together actually makes sense." (pg. 24)

"Use a textual description of the problem you're trying to solve to make sure that your design lines up with the intended functionality of your application." (pg. 26)

"Here are some helpful tips to find mismatched object types:
1. Objects should do what their names indicate.
2. Each object should represent a single concept. --You don't want objects serving double or triple duty.
3. Unused properties are a dead giveaway. --If you've got an object that is being used with no-value or null properties often, you've got an object doing more than one job. If you rarely have values for a certain property, why is that property part of the object? Would there be a better object to use with just a subset of those properties?" (pg. 27)

"Encapsulation allows you to group your application into logical parts." (pg. 28)

"Anytime you see duplicate code, look for a place to encapsulate!" (pg. 31)

"The idea behind encapsulation is to protect information in one part of your application from the other parts of your application. In its simplest form, you can protect the data in your class from the rest of your app by making that data private. But sometimes the information might be an entire set of properties (like details about a guitar) or even behavior (how a type of duck flies)." (pg. 31)

"When you break that behavior out from a class, you can change the behavior without the class having to change as well. So if you changed how properties were stored, you wouldn't have to change your class at all, because the properties are encapsulated away from the class." (pg. 31)

"That's the power of encapsulation; by breaking up the different parts of your app, you can change one part without having to change all the other parts. In general, you should encapsulate the parts of your app that might vary away from the parts that will stay the same." (pg. 31)

"Step 2 is where you look for big problems, especially related to things like duplicate code or bad class design." (pg. 31)

"Remember, we've got even more design work to do in step 3, so before you're done, you're software is really easy to extend and reuse." (pg. 31)

"There are other OO principles you can use at step 2. Other good OO principles you might want to think about at this stage are inheritance and polymorphism. Both of these relate to duplicate code and encapsulation though, so starting out by looking for places where you could use encapsulation to better your design is always a good idea." (pg. 34)

"Once you've gotten your software to work like it's supposed to, flexibility becomes a big deal. What if the customer wants to add new properties or features to the app? If you've got tons of duplicate code or confusing inheritance structures in your app, making changes is going to be a pain." (pg. 34)

"By introducing principles like encapsulation and good class design into your code, it's easier to make these changes, and your application becomes a lot more flexible." (pg. 34)

"Once you've taken a first pass over your software and applied some basic OO principles, you're ready to take another look, and this time make sure your software is not only flexible, but easily reused and extended." (pg. 36)

"Step 3 is when it is time to really think about reuse, and how easy it is to make changes to your software. Here's where you can take some well-designed classes and really turn them into a reusable, extensible piece of software."  (pg. 36)

"Once you've applied some basic OO principles, you're ready to apply some patterns and really focus on reuse."  (pg. 36)

"Delegation is when an object needs to perform a certain task, and instead of doing that task directly, it asks another object to handle the task (or sometimes just a part of the task)"  (pg. 43)

"The point of that is that delegation makes your code more reusable. It also lets each object worry about its own functionality, rather than spreading the code that handles a single object's behavior all throughout your application." (pg. 43)

"As for reusability, delegation lets each object worry about equality (or some other task) on its own. This means your objects are more independent of each other, or more loosely coupled. Loosely coupled objects can be taken form one app and easily reused in another, because they're not tightly tied to other objects' code." (pg. 43)

"Loosely coupled is when the objects in your application each have a specific job to do, and they do only that job. So the functionality of your app is spread out over lots of well-defined objects, which each do a single task really well." (pg. 43)

"The benefits of loosely coupled are that applications are usually more flexible, and easy to change. Since each object is pretty independent of the other objects, you can make a change to one object's behavior without having to change all the rest of your objects. So adding new features or functionality becomes a lot easier." (pg. 43)

"Delegation is the act of one object forwarding an operation to another object, to be performed on behalf of the first object." (pg. 43)

"To write great software consistently, you need a set of steps to follow that make sure your software works and is well designed. It can be as simple as the three steps; you just need something that works, and that you can use on all of your software projects." (pg. 48)

"Object-Oriented Analysis & Design (OOA&D) helps you write great software, every time. --The three steps you can follow to write great software is actually OOA&D." (pg. 48)

"OOA&D is really just an approach to writing software that focuses on making sure your code does what it's supposed to, and that it's well designed. That means your code is flexible, it's easy to make changes to it, and it's maintainable and reusable." (pg. 48)

"OOA&D is about writing great software, not doing a bunch of paperwork!" (pg. 49)

"Customers are satisfied when their apps WORK. --We can get requirements from the customer to make sure that we build them what they ask for. Use cases and diagrams are helpful ways to do that, but it's all about figuring out what the customer wants the app to do." (pg. 49)

"Customers are satisfied when their apps KEEP WORKING. --If we design our apps well, then they're going to be robust, and not break every time a customer uses them in unusual ways. Class and sequence diagrams can help show us design problems, but the point is to write well-designed and robust code." (pg. 49)

"Customers are satisfied when their apps can be UPGRADED.-- Using OO techniques like encapsulation, composition, and delegation will make your applications maintainable and extensible." (pg. 49)

"Programmers are satisfied when their apps can be REUSED.-- If you do just a little bit of analysis on your apps, you can make sure they're easily reused, by avoiding all sorts of nasty dependencies and associations that you don't really need. Concepts like the Open-Closed Principle (OCP) and the Single Responsible Principle (SRP) are big time in helping here." (pg. 49)

"Programmers are satisfied when their apps are FLEXIBLE.-- Sometimes just a little refactoring can take a good app and turn it into a nice framework that can be used for all sorts of different things. This is where you can begin to move from being a head-down coder and start thinking like a real architect." (pg. 49)

"This is ALL OOA&D! It's not about doing silly diagrams... it's about writing killer applications that leave your customer happy, and you feeling like you've kicked major ass." (pg. 49)

"It takes very little for something to go wrong with an application that is fragile." (pg. 50)

"You can use OO principles like encapsulation and delegation to build applications that are flexible." (pg. 50)

"Encapsulation is breaking your application up into logical parts." (pg. 50)

"Delegation is giving another object the responsibility of handling a particular task." (pg. 50)

"Always begin a project by figuring out what the customer wants." (pg. 50)

"Once you've got the basic functionality of an app in place, work on refining the design so it's flexible." (pg. 50)

"With a functional and flexible design, you can employ design patterns to improve your design further and make your app easier to reuse." (pg. 50)

"Find the parts of your application that change often, and try and separate them from the parts of your application that don't change." (pg. 50)

"Building an application that works well but is poorly designed satisfies the customer but will leave you with pain, suffering, and lots of late nights fixing problems." (pg. 50)

"Object oriented analysis and design (OOA&D) provides a way to produce well-designed applications that satisfy both the customer and the programmer." (pg. 50)