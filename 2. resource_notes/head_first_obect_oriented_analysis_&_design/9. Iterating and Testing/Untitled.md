"We used Use Case Diagrams and a key feature list to turn a simple vision statement into an application architecture." (pg. 424)

"Our OO principles help us write well-designed, flexible OO software." (pg. 424)

"You're still writing your software for the customer." (pg. 426)

"None of the tools and techniques matter if you don't use them to produce great software that makes your customer happy." (pg. 426)

"Customers just want the software to work the way that it's supposed to." (pg. 426)

"Iterate deeper means we keep doing analysis and design, but now on each individual part of the system." (pg. 426)

"You write great software iteratively." (pg. 426)

"Work on the big picture, and then iterate over pieces of the app until it's complete." (pg. 426)

"You can choose to focus on specific features of the application. This approach is all about taking on piece of functionality that the customer wants, and working on that functionality until it's complete." (pg. 427)

"Feature Driven Development is when you pick a specific feature in your app, and plan, analyze, and develop that feature to completion." (pg. 427)

"Both approaches to iterating are driven by good requirements." (pg. 427)
 
"Because requirements come from the customer, both approaches focus on delivering what the customer wants." (pg. 427)

"You can also choose to focus on specific flows through the application. This approach takes a complete path through the application, with a clear start and end, and implements that path in your code." (pg. 427)

"Use case driven development is when you pick a scenario through a use case, and write code to support that complete scenario through the use case." (pg. 427)

"You'll often see the terms 'flow' and 'scenario' used interchangeably." (pg. 427)

"When you're using feature driven development, you work on a single feature at a time, and then iterate, knocking off features one at a time until you've finished up the functionality of an application." (pg. 428)

"With feature driven development, you pick a single feature, and the focus is on the feature list of your app." (pg. 428)

"All these other plans and diagrams are used, but your feature list is the focus." (pg. 428)

"With use case driven development, you work on completing a single scenario through a use case. Then you take another scenario and work through it, until all of the use case's scenarios are complete. Then you iterate to the next use case, until all your use cases are working." (pg. 429)

"With use case driven development, you work from the use case diagram, which lists the different use cases in your system." (pg. 429)

"Feature driven development is more granular." (pg. 430)

"A single feature is often pretty small, and every application has a lot of them." (pg. 430)

"Works well when you have a lot of different features that don't interconnect a whole lot." (pg. 430)

"Allows you to show the customer working code faster." (pg. 430)

"Is very functionality-driven. You're not going to forget about any features using feature driven development." (pg. 430)

"Works particularly well on systems with lots of disconnected pieces of functionality." (pg. 430)

"Use case driven development is more 'big picture'." (pg. 430)

"You'll be working on pretty major chunks of code at a time, since a single a scenario often involves a lot of functionality." (pg. 430)

"Works well when your app has lots of processes and scenarios rather than individual pieces of functionality." (pg. 430)

"Allows you to show the customer bigger pieces of functionality at each stage of development." (pg. 430)

"Is very user-centric. You'll code for all the different ways a user can use your system with use case driven development." (pg. 430)

"Works particularly well on transactional systems, where the system is largely defined by lengthy, complicated processes." (pg. 430)

"Anytime you've got a customer impatient to see results, you should consider feature driven development, and starting with a feature you've already done some work on." (pg. 433)

"Once you've decided on a feature to start with, you've got to do some more analysis." (pg. 434) 

"Your customers want to see something that makes sense to them." (pg. 436)

"You need to come up with some test scenarios that you can show to your customer, which will prove that your code works, and that it behaves like your customer expects it to." (pg. 436)

"Test cases don't have to be very complex; they just provide a way to show your customer that the functionality in your class is working correctly.-- Be careful... this 'scenario' isn't the same as the 'scenario' we've been talking about in a use case scenario." (pg. 437)

"Show the customer that you're not just dealing with happy paths... you're thinking about how to deal with uses of the software that are outside of the norm." (pg. 439)

"You should test your software for every possible usage you can think of. Be creative!" (pg. 439)

"Don't forget to test for incorrect usage of the software, too. You'll catch errors early, and make your customers very happy." (pg. 439)

"If you know what tests you're going to use before you write your code, it's easy to figure out what code you're going to need to pass those tests." (pg. 440)

"For the most part, this is just test driven development. Formally, test driven development focuses on automated tests, and usually involves a testing framework. But the idea of writing test cases, and then writing the code that will pass the test, is the core idea behind test driven development." (pg. 440)

"We are using both test driven development and feature driven development. Most good software analysis and design mixes lots of different approaches. You might start with a use case (use case driven development) and then choose just a small feature in that use case to start working on (which is really a form of feature driven development). Finally, you might use tests to figure out how to implement that feature (test driven development)." (pg. 440)

"You want to keep your tests simple, and have them test just a small piece of functionality at a time. If you start testing multiple things at once, it's hard to tell what might have caused a particular test to fail. You may need a lot more tests, but keep each one focused on a very specific piece of functionality." (pg. 440)

"Each test does not make sure a single method in a class works correctly. Each test really focuses on a single piece of functionality. That might involve one method, or several methods. So it's one piece of functionality- setting a property- but it takes two methods." (pg. 440)

"Testing incorrect usage of your software is usually at least as important as testing it when it's used properly. Game designers could easily mistype a property name, or write code that expects some other piece of a game to set a property and asks for a property that doesn't exist. It's your job to know what will happen in these situations." (pg. 440)

"Test driven development focuses on getting the behavior of your classes right." (pg. 440)

"Analysis and design are all about making choices, and sometimes you're going to make a different choice than another programmer. There's nothing wrong with that, as long as you have a good, well thought out reason for the decision you made." (pg. 445)

"Different choices will result in different code and design implementations. OOA&D and software development aren't about making a particular decision, since many times there isn't an exactly 'right' or exactly 'wrong' choice. They're about writing well designed software, and that can happen in a lot of different ways." (pg. 445)

"In fact, even if two programmers made the same decision about commonality and variability in this exercise, it can lead to totally different design decisions when it comes to actually writing your classes." (pg. 445)

"Design decisions are always a tradeoff." (pg. 447)

"When you see the potential for duplicate code, you'll almost always find maintenance and flexibility issues, as well." (pg. 447)

"Both design choices have positives, and either one might work well. The only thing you cannot do is be unwilling to change your design- whichever one you start with- if it turns out to not work well down the line. At each stage of iterating through your app, you need to reevaluate your design decisions, and make sure they're still solid." (pg. 451)

"Iteration is really the key point here. Lots of design decisions look great at one stage of your development, but then turn out to be a problem as you get deeper into a particular part of your app. So once you make a decision, stick with it, and iterate deeper into your application. As long as your design is working, and you're able to use good OO principles and apply design patterns, you're in good shape. If you start running into trouble with a decision, though, don't ever be afraid to change designs and rework things." (pg. 451)

"You always have to make a choice, even if you're not 100% sure if it's the right one. It's always better to take your best guess, and see how things work out, rather than spend endless hours debating one choice or another. That's called analysis paralysis, and it's a sure way to not get anything done. It's much better to start down one path, even if you're not totally sure it's the right one, and get some work done, than to not make a choice at all." (pg. 451)

"Good software is built iteratively. Analyze, design, and then iterate again, working on smaller and smaller parts of your app." (pg. 451)

"Each time you iterate, reevaluate your design decisions, and don't be afraid to CHANGE something if it makes sense for your design." (pg. 451)

"What makes up a good test:
1. Each test case should have an ID and a name.-- The names of your test cases should describe what is being tested. You should also use a numeric ID, so you can easily list your tests out. Try not to refer to tests as test1, test2, etc. Use descriptive names whenever possible.
2. Each test case should have one specific thing that it tests.-- Each of your test cases should be atomic: each should test only one piece of functionality at a time. This allows you to isolate exactly what piece of functionality might not be working in your application. One piece of functionality may involve one method, two methods, or even multiple classes... but to start with focus on very complete pieces of functionality, one at a time.
3. Each test case should have an input you supply.-- You're going to give the test case a value, or a set of values, that it uses as the test data. This data is usually then used to execute some specific piece of functionality or behavior.
4. Each test case should have an output that you expect.-- Given your input, what should the program, class, or method output? You'll compare the actual output of the program with your expected output, and if they match, then you've got a successful test, and your software works. This is what you want the program to output.
5. Most test cases have a starting state.-- Do you need to open a database connection, or create a certain object, or set some values before running your test? If so, that's all part of the starting state of the test case, and needs to be handled before you run the actual test." (pg. 454)

"Remember, we started out writing the tests so that we could prove to the customer that the software we've been writing actually will work." (pg. 456)

"Our test cases let the customer see some code actually running, as well as help us find bugs in our code before we get too far along in our development cycle." (pg. 456)

"When you're writing software, you're also creating a contract between that software and the people that use it. The contract details how the software will work when certain actions are taken." (pg. 461)

"If the customer wants an action to result in different behavior, then you're changing the contract." (pg. 461)

"When you program by contract, you and your software's users are agreeing that your software will behave in a certain way." (pg. 461)

"Programming by contact is really about trust-- When you return null, you're trusting programmers to be able to deal with null return values. Programmers are basically saying that they've coded things well enough that they won't ask for non-existent properties, so their code doesn't worry about getting null values back."

"And we can always change the contract if we need to... " (pg. 463)

"But if you don't trust your users...-- But what happens if you don't think your code will be used correctly? Or if you think that certain actions are such a bad idea that you don't want to let users deal with them in their own way? In these cases, you may wan to consider defensive programming." (pg. 464)

"Defensive programming assumes the worst, and tries to protect itself (and you) against misuse or bad data." (pg. 464)

"...or if they don't trust you...-- they can program defensively too." (pg. 465)

"It's really not important what kind of exception is thrown. What's important is how your customers and clients are involved in that decision. In programming by contract, you work with the client to agree on how you're going to handle problems; in defensive programming, you make that decision in a way that ensures your code doesn't crash, regardless of what the client wants to have happen." (pg. 465)

"When we decided to switch from returning null to throwing an exception, we did that by listening to the client, and agreeing on that particular action as a response to a request for non-existent properties." (pg. 465)

"We made the exception a RuntimeException, again because the client didn't want to add lots of try/catch blocks to their code. They could have just as easily asked for a checked exception, and we could have agreed- and still been programming by contract." (pg. 465)

"Compare that to defensive programming, where we're not really that interested in what the client wants. In defensive programming, we're making sure that we aren't responsible for crashing a program, and we even go out of our way to try and prevent the client from crashing their program." (pg. 465)

"When you are programming by contract, you're working with client code to agree on how you'll handle problem situations." (pg. 471)

"When you're programming defensively, you're making sure the client gets a 'safe' response, no matter what the client wants to have happen." (pg. 471)

"It's not a matter of being better or worse; it's a matter of what your customer wants. In fact, you'll rarely decide on your own if you want to do programming by contract or defensive programming. That's something that's usually determined by what your customer wants, and the types of users that will be using the software that you're writing." (pg. 471)

"Break your apps into smaller chunks of functionality.-- So you're taking each problem, and then breaking it up (either into use cases or features), and then solving a part of the problem, over and over. Take a single feature and working on that feature until it's complete." (pg. 473)

"But you can still break things up further...-- But once you choose a single feature or use case, you can usually break that feature up into even smaller pieces of behavior. Just like when you broke your app up and began to iterate, you'll have to do more analysis and design at each step. Always make sure your earlier decisions make sense, and change or rework those decisions if they don't." (pg. 473)

"Your decisions can iterate down, too-- Lots of times you'll find that decisions you made earlier save you work down the line." (pg. 473)

"The first step in writing good software is to make sure your application works like the customer expects and wants it to." (pg. 475)

"Customers don't usually care about diagrams and lists; they want to see your software actually do something." (pg. 475)

"Use case driven development focuses on one scenario in a use case in your application at a time." (pg. 475)

"In use case driven development, you focus on a single scenario at a time, but you also usually code all the scenarios in a single use case before moving on to any other scenarios, in other use cases." (pg. 475)

"Feature driven development allows you to code a complete feature before moving on to anything else." (pg. 475)

"You can choose to work on either big or small features in feature-driven development, as long as you take each feature one at a time." (pg. 475)

"Software development is always iterative. You look at the big picture, and then iterate down to smaller pieces of functionality." (pg. 475)

"You have to do analysis and design at each step of your development cycle, including when you start working on a new feature or use case." (pg. 475)

"Tests allow you to make sure your software doesn't have any bugs, and let you prove to your customer that your software works." (pg. 475)

"A good test case only tests one specific piece of functionality." (pg. 475)

"Test cases may involve only one, or several, methods in a single class, or may involve multiple classes." (pg. 475)

"Test driven development is based on the idea that you write your tests first, and then develop software that passes those tests. The result is fully functional, working software." (pg. 475)

"Programming by contract assumes both sides in a transaction understand what actions generate what behavior, and will abide by that contract." (pg. 475)

"Methods usually return null or unchecked exceptions when errors occur in programming by contract environments." (pg. 475)

"Defensive programming looks for things to go wrong, and tests extensively to avoid problem situations." (pg. 475)

"Methods usually return 'empty' objects or throw checked exceptions in defensive programming environments." (pg. 475)

"Programming by contract sets up an agreement about how your software behaves that you and users of your software agree to abide by." (pg. 478)

"Defensive programming doesn't trust other software, and does extensive error and data checking to ensure the other software doesn't give you bad or unsafe information." (pg. 478)

"Use case driven development takes a single use case in your system, and focuses on completing the code to implement that entire use case, including all of its scenarios, before moving on to anything else in the application." (pg. 478)

"Feature driven development focuses on a single feature, and codes all the behavior of that feature, before moving on to anything else in the application." (pg. 478)

"Test driven development writes test scenarios for a piece of functionality before writing the code for that functionality. Then you write software to pass all the tests." (pg. 478)

"Good software development usually incorporates all of these development models at different stages of the development cycle." (pg. 478)