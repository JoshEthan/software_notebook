"We have feature lists, individual modules to code, high-level views of what we need to build, the customer's vision, and even some design patterns to apply." (pg. 325)

"It's really not enough to just figure out the individual pieces of a big problem. You also need to know a little bit about how those pieces fit together, and which ones might be more important than others; that way, you'll know what you should work on first." (pg. 326)

"Architecture is you design structure, and highlights the most important parts of your app, and the relationships between those parts.-- Architecture helps us design the big systems. Our use case diagram was the start of the relationships, but it's still pretty unclear how all the modules interact." (pg. 326)

"Architecture is the organizational structure of a system, including its decomposition into parts, their connectivity, interaction mechanisms, and the guiding principles and decisions that you use in the design of a system." (pg. 326)

"Architecture takes a big chaotic mess and helps us turn it into a well-orded application." (pg. 327)

"We want to use all the information we have to create a nice, well-constructed application." (pg. 327)

"All the diagrams and patterns are used to build the customer exactly what they want, all within a flexible reusable design." (pg. 327)

"You write great software the same way, whether you're working on a small project, or a huge on. You can still apply the three steps we talked about." (pg. 328)

"The 3 steps apply to building great BIG software, too" (pg. 328)

"These three steps apply when you're working on really big applications, too. So we need to start with what the customer wants an app to do, before we get into details about the actual design of the app." (pg. 328)

"The first step is to make sure an application does what it's supposed to do. In small projects, we used a requirements list to write down functionality; in big projects, we've been using a feature list to figure those things out." (pg. 329)

"All of these features are about functionality... they focus on what the system has to do, not on what principles or patterns you use to build the system." (pg. 329)

"Even if we know to start by focusing on functionality, we still need to figure out which pieces are the most important. Those are the pieces we want to focus on first." (pg. 329)

"The things in your application that are really important are architecturally significant, and you should focus on them FIRST." (pg. 331)

"It's awfully hard to talk about the relationships between parts of a system if you don't have any of the parts themselves. To figure out how these modules interact, you'd need to have at least the basics of two modules in place first. So architecture isn't just about the relationship between parts of your app; it's also about figuring out which parts are the most important, so you can start building those parts first." (pg. 331)

"When figuring out if something is architecturally significant:
1. Is it part of the essence of the system?-- Is the feature really core to what a system actually is? Think about it this way: can you imagine the system without that feature? If not, then you've probably found a feature that is part of the essence of a system.
2. What the heck does it mean?-- If you're not sure what the description of a particular feature really means, it's probably pretty important that you pay attention to that feature. Anytime you're unsure about what something is, it could take lots of time, or create problems with the rest of the system. Spend time on these features early, rather than late.
3. How the heck do I do it?-- Another place to focus your attention early on is on features that seem really hard to implement, or are totally new programming tasks for you. If you have no idea how you're going to tackle a particular problem, you better spend some time up front looking at that feature, so it doesn't create lots problems down the road."  (pg. 332)

"The essence of a system is what it is at its most basic level. In other words, if you stripped away all the bells and whistles, all the 'neat' things that marketing threw  in, and all the cool ideas you had, what would the system really be about? That's the essence of a system."  (pg. 335)

"When you're looking at a feature, ask yourself: 'If this feature wasn't implemented, would the system still really be what it's supposed to be? If the answer is no, you've found yourself an 'essence feature'."  (pg. 335)

"Not knowing something isn't a bad requirement. It is a sign that you might need to get some additional requirements, or at least some clarification. In the early stages, you can leave some details out to get a basic sense of a system. But at this stage, it's time to fill in some of those details, and that's what the second Q of architecture is all about."  (pg. 335)

"Even if you've never written code specifically for a task before, it's just a few new details, really. But if you're new to threads, then that would be something you don't know how to do. Those are things to look out for: particularly hard tasks that you're unsure about how to handle."  (pg. 335)

"In a lot of cases, this all ends up just being a judgement call. But as long as you choose to start working on things that seem the most important to the system, you're going to get off to a good start. What you don't want to do is see some things that look familiar- perhaps you've solved the same problem in another project- and start there. Start with the core pieces of the system, and the things that look like they might be particularly hard, and you'll be on the road to success."  (pg. 335)

"The essence of a system is what that system is at its most basic level."  (pg. 335)

"Using the three Qs of architecture, we've started to add some order to all that confusion we started out with.-- Start with a mess, then focused on making the system do what it is supposed to do, finally, we've narrowed that down to just a few key features to focus on."  (pg. 336)

"The reason that these features are architecturally significant is that they all introduce RISK to your project. It doesn't matter which on you start with- as long as you are working towards reducing the RISKS in succeeding."  (pg. 338)

"Since we don't know what this means, it could be a ton of work, and that's a RISK in meeting schedules and deadlines. This is something we're not sure how to do, so there's RISK that we won't figure it out, or it will take a really long time. If the core features of the system aren't in place, there's a serious RISK that the customer won't like the system."  (pg. 338)

"The point here is to REDUCE RISK, not to argue over which key feature you should start with first. You can start with ANY of these, as long as you're focused on building what you're supposed to be building."  (pg. 338)

"You should still write use cases whenever possible. Scenarios are helpful for quick problems, and to find thee most common requirements. Remember, scenarios are only one path through a use case. If there are lots of alternate paths, you might miss some important requirements if you used just a scenario for your requirements."  (pg. 343)

"If you're just getting started, and a use case seems like it might be premature, just using scenario is a good way to get started." (pg. 343)

"Remember, when you're figuring out requirements, whether you're using a use case, a use case diagram, or a scenario, you're trying to make sure you are building just what the customer wants. Without good requirements, the risk is letting down or upsetting the customer by building the wrong thing." (pg. 343)

"During the requirement phase is when you're writing use cases, putting together a requirements list, and using lots of scenarios to chart out all the paths through a use case." (pg. 343)

"Sometimes you don't have a complete requirements list and a bunch of use cases, but you still need to get some basic work done to see how a system is going to work. …using a scenario to get the basics of a module or piece of code down, so you can get the basic building blocks of your application in place." (pg. 343)

"Scenarios help in gathering requirements, in being sure your use cases are complete, but also in architecture, helping you reduce the chaos and confusion around what a particular module or piece of code does." (pg. 343)

"We could have used a use case to figure out the requirements, but remember, we're not trying to complete the module, as much as get the basic pieces together" (pg. 345)

"If we got into too much detail, we might actually add risk to the project, by working on details that really aren't important at this stage of things." (pg. 345)

"Use cases don't add risk when used at the right time. Right now, we've come up with some key features that could cause us headaches if we don't figure them out. We don't need anything perfect, we just need to get an understanding of how things work, so if there are any potential problem spots, we can catch them and avoid problems down the line." (pg. 345)

"So at this point, the details you'd need to write a good use case are a bit of over kill." (pg. 345)

"But once we've got the key features sketched out, and handled the major risks, we'll go back to each module and really start to add detail in. At that point, a use case is very helpful." (pg. 345)

"We use a scenario to avoid getting into lots of unnecessary details. A scenario gives us lots of the advantages of a use case, without forcing us to get into lots of detail that we don't need to worry about right now." (pg. 345)

"Focus on one feature at a time to reduce risk in your project." (pg. 349)

"Don't get distracted with features that won't help reduce risk." (pg. 349)

"Once you've handled your key features, and reduced or eliminated the big risks to your project, then you'll have plenty of time to work on other features. At this stage, though, you're trying to avoid spending time on anything that doesn't help you reduce the risks to your project succeeding." (pg. 349)

"Build on what you've already got done whenever possible.-- When you've got nothing but requirements and diagrams, you've got to pick a place to start. But now that we do have some code and classes, it's easiest to pick another key feature that relates to what we've already built." (pg. 351)

"Architecture is your design structure, and highlights the most important parts of your app, and the relationships between those parts.-- You really can't talk about the relationships between parts if you don't have at least two parts that have a relationship." (pg. 351)

"Commonality also applies to smaller problems." (pg. 355)

"Commonality is about more than just the names of properties... you need to look a little deeper.-- Let's take a step back from focusing on the actual names of the properties." (pg. 359)

"Good design will always reduce risk. We can get it right the first time. We don't have to worry about the design drastically changing in the middle or near the end of the project's development cycle." (pg. 362)

"We're focusing on doing just the things that reduce risk.-- Remember, the point of architecture is to reduce risk, and to create order. There are plenty of other things to work on in your application, but those are for after you've got a handle on how your application will be structured, and have the major risks reduced to the point where they are manageable." (pg. 363)

"The question you need to be always asking at this stage of a project is, 'Will this reduce the risk to my project succeeding?' If the answer is yes, you should go ahead; if it's no, you probably can leave the task for a later stage of the project." (pg. 364)

"You could just do a class diagram for all implementations. It's really a judgement call, and as long as you feel you're focusing on reducing the risk in your project, it's OK to stop with a class diagram, or take things a level or two deeper." (pg. 364)

"It is good to ask the customer and users of a system about what it should do. It's usually a good idea to ask the customer, because it is their system that you're building. And really, the customer is only going to confuse you, or get you working on the wrong thing, if you're unsure of what you're supposed to be working on. As long as you go into a conversation clear on what your goals are, and you're listening for something specific, you should be able to filter out anything that might confuse or distract you." (pg. 364)

"Tools like commonality and the three Qs of architecture are for you to come up with stuff like using a Map for storing properties. They help you get to solutions that you might not think of on your own, in a way that works on any type of project." (pg. 364)

"OOA&D is all about code- it's about writing great software, every time. But the way you get to good code isn't always by siting down and writing it right away. Sometimes the best way to write great code is to hold off on writing code as long as you can. Plan, organize, architect, understand requirements, reduce risk... all these make the job of actually writing your code very simple." (pg. 364)

"When you're not sure what a feature really means, one of the best things you can do is ask the customer." (pg. 366)

"You can use these three basic steps anytime you're unsure about what a feature means, and how you need to implement that feature in your system.-- 1. Ask the customer: What does the feature mean? 2. Commonality analysis: How do I realize that feature in my system? 3. Implementation plan"(pg. 367)

"When you find more things that are different about a feature than things that are the same, there may not be a good generic solution." (pg. 369)

"You're job is to reduce risk and complexity, not increase it." (pg. 369)

"Customers don't pay you for great code, they pay you for great software." (pg. 370)

"Great software is more than just great code.-- Great code is well-designed, and generally functions like it's supposed to. But great software not only is well-designed, it comes in on time and does what the customer really wants it to do." (pg. 370)

"That's what architecture is about: reducing risk of you delivering your software late, or having it not work like the customer wants it to. Our key feature list, class diagrams, and those partially done classes all help make sure we're not just developing great code, but that we're developing great software." (pg. 370)

"Reducing risk helps you write great software." (pg. 371)

"We don't have a lot of code, but we do have a project that we're confident we can deliver on time, with the right functionality." (pg. 371)

"Architecture helps you turn all your diagrams, plans, and feature lists into a well-ordered application." (pg. 372)

"The features in your system that are most important to the project are architecturally significant." (pg. 372)

"Focus on features that are the essence of your system, that you're unsure about the meaning of, or unclear about how to implement first." (pg. 372)

"Everything you do in the architectural stages of a project should reduce the risks of your project failing." (pg. 372)

"If you don't need all the details of a use case, writing a scenario detailing how your software could be used can help you gather requirements quickly." (pg. 372)

"When you're not sure what a feature is, you should ask the customer, and then try and generalize the answers you get into a good understanding of the feature." (pg. 372)

"Use commonality analysis to build software solutions that are flexible." (pg. 372)

"Customers are a lot more interested in software that does what they want, and comes in on time, than they are in code that you think is really cool." (pg. 372)