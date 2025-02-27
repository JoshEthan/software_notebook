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

"Good architecture makes a huge difference in productivity." (At What Cost?)

"You have to take great care to both organize the code well and keep it organized throughout the thousands of little changes that make up a development cycle." (At What Cost?)

"You have to think about which parts of the program should be decoupled and introduce abstractions at those points. Likewise, you have to determine where extensibility should be engineered in so future changes are easier to make." (At What Cost?)

"That effort pays off if you guess right and end up touching that code later. But predicting the future is hard, and when that modularity doesn't end up being helpful, it quickly becomes actively harmful." (At What Cost?)

THOUGHT: It almost feels like a game of Sudoku. You scribble in a bunch of potentials. You want to leave things open. You just don't know what you need yet, you need to solve other problems first then circle back around. As you get the puzzle solved more and more, the easier it becomes to putting it all together. Software is just a puzzle. (At What Cost?)

"Some folks coined the term 'YAGNI'- You aren't gonna need it- as a mantra to use to fight this urge to speculate about what your future self may want." (At What Cost?)

"When people get overzealous about this, you get a codebase whose architecture has spiraled out of control." (At What Cost?)

"In theory, all of this decoupling means you have less code to understand before you can extend it, but the layers of abstraction themselves end up filling your mental scratch disk." (At What Cost?)

"Codebases like this are what turn people against software architecture, and design patterns in particular. It's so easy to get so wrapped up in the code itself that you lose sight of the fact that you're trying to ship a game." (At What Cost?)

"There's another critique of software architecture and abstraction that you hear sometimes, especially in game development: that it hurts your game's performance." (Performance and Speed)

"Many patterns that make your code more flexible rely on virtual dispatch, interfaces, pointers, messages, and other mechanisms that all have at least some runtime cost." (Performance and Speed)

"A lot of software architecture is about making your program more flexible. It's about making it take less effort to change it. That means encoding fewer assumptions in the program." (Performance and Speed)

"But performance is all about assumptions. The practice of optimization thrives on concrete limitations." (Performance and Speed)

"This doesn't mean flexibility is bad, though! It lets us change our game quickly, and development speed is absolutely vital for getting to a fun experience." (Performance and Speed)

"Balanced game design demands iteration and experimentation." (Performance and Speed)

"The faster you can try out ideas and see how they feel, the more you can try and the more likely you are to find something great. Even after you've found the right mechanics, you need plenty of time for tuning." (Performance and Speed)

"Making your program more flexible so you can prototype faster will have some performance cost. Likewise, optimizing your code will make it less flexible." (Performance and Speed)

"It's easier to make a fun game fast than it is to make a fast game fun." (Performance and Speed)

"One compromise is to keep the code flexible until the design settles down and then tear out some of the abstraction later to improve your performance." (Performance and Speed)

"...there's a time and place for different styles of coding." (The Good in Bad Code)

"Writing well-architected code takes careful thought, and that translate to time." (The Good in Bad Code)

"...maintaining a good architecture over the life of a project takes a lot of effort." (The Good in Bad Code)

"You have to treat your code-base like a good camper does their campsite: always try to leave it a little better than you found it." (The Good in Bad Code)

"...game design requires a lot of experimentation and exploration." (The Good in Bad Code)

"Especially early on, it's common to write code that you know you'll throw away." (The Good in Bad Code)

"If you just want to find out if some game-play idea plays right at all, architecting it beautifully means burning more time before you actually get it on screen and get some feedback." (The Good in Bad Code)

"Prototyping- slapping together code that's barely functional enough to answer a design question- is perfectly legitimate programming practice." (The Good in Bad Code)

"If you write throwaway code, you must ensure you're able to throw it away." (The Good in Bad Code)

"You need to make sure the people using the throwaway code understand that even though it kind of looks like it works, it cannot be maintained and must be rewritten. If there's a chance you'll end up having to keep it around, you may have to defensively write it well." (The Good in Bad Code)

"One trick to ensuring your prototype code isn't obliged to become real code is to write it in a language different from the one your game uses. That way, you have to rewrite it before it can end up in your actual game." (The Good in Bad Code)

"...forces in play:
1. We want nice architecture so the code is easier to understand over the lifetime of the project.
2. We want fast runtime performance.
3. We want to get today's features done quickly.
"

"...these are all about some kind of speed: our long-term development speed, the game's execution speed, and our short-term development speed."

"Good architecture improves productivity over the long term, but maintaining it means every change requires a little more effort to keep things clean."

"The implementation that's quickest to write is rarely the quickest to run. Instead, optimization takes significant engineering time. Once it's done, it tends to calcify the codebase: highly optimized code in inflexible and very difficult to change."

"There's no simple answer here, just trade-offs."

"But, to me, this is exciting! Look at any field that people dedicate careers to mastering, and in the center you will always find a set of intertwined constraints."

"To me, this has much in common with games themselves. A game like chess can never be mastered because of all of the pieces are so perfectly balanced against one another. This means you can spend your life exploring the vast space of viable strategies."