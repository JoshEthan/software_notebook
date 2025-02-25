"For me, good design means when I make a change, it's as if the entire program was crafted in anticipation of it. I can solve a task with just a few choice function calls that slot in perfectly, leaving not the slightest ripple on the placid surface of the code." (What is good software architecture?)

"The first key piece is that architecture is about change." (What is good software architecture?)

"The measure of design is how easily it accommodates changes." (What is good software architecture?)

"Before you can change the code to add a new feature, to fix a bug, or for whatever reason caused you to fire up your editor, you have to understand what the existing code is doing." (How do you make a change?)

"If you do it right, the next person to come along won't be able to tell when any line of code was written." (How do you make a change?)

"In short, the flow chart for programming is something like: 
Get a Problem -> Learn Code -> Code Solution -> Clean Up -> Repeat" (How do you make a change?)

"While it isn't obvious, I think much of software architecture is about that learning phase." (How can decoupling help?)

"You can define 'decoupling' a bunch of ways, but I think if two pieces of code are coupled, it means you can't understand one without understanding the other." (How can decoupling help?)

"If you de-couple them, you can reason about either side independently." (How can decoupling help?)

"That's great because if only one of those pieces is relevant to your problem, you just need to load it into your monkey brain and not the other half too." (How can decoupling help?)

"To me, this is a key goal of software architecture: minimize the amount of knowledge you need to have in-cranium before you can make progress." (How can decoupling help?)

"Another definition of decoupling is that a change to one piece of code doesn't necessitate a change to another." (How can decoupling help?)

"We obviously need to change something, but the less coupling we have, the less that change ripples throughout the rest of the game." (How can decoupling help?)

"Good architecture makes a huge difference in productivity."

"You have to take great care to both organize the code well and keep it organized throughout the thousands of little changes that make up a development cycle."

"You have to think about which parts of the program should be decoupled and introduce abstractions at those points. Likewise, you have to determine where extensibility should be engineered in so future changes are easier to make."

"That effort pays off if you guess right and end up touching that code later. But predicting the future is hard, and when that modularity doesn't end up being helpful, it quickly becomes actively harmful."

THOUGHT: It almost feels like a game of Soduko. You scribble in a bunch of potentials. You want to leave things open. You just don't know what you need yet, you need to solve other problems first then circle back around. As you get the puzzle solved more and more, the easier it becomes to putting it all together. Software is just a puzzle.

"Some folks coined the term 'YAGNI'- You aren't gonna need it- as a mantra to use to fight this urge to speculate about what your future self may want."

"When people get overzealous about this, you get a codebase whose architecture has spiraled out of control."

"In theory, all of this decoupling means you have less code to understand before you can extend it, but the layers of abstraction themselves end up filling your mental scratch disk."

"Codebases like this are what turn people against software architecture, and design patterns in particular. It's so easy to get so wrapped up in the code itself that you lose sight of the fact that you're trying to ship a game."


