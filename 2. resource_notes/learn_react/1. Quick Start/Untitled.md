## Creating and nesting components
React apps are made out of Components, a piece of UI that has its own logic and appearance. A component can be as small as a button, or as large as an entire page. React component names must always start with a capital letter, while HTML tags must be lowercase.
## Writing markup with JSX
JSX is stricter than HTML. You have to close tags like `<br />`. Your component also can’t return multiple JSX tags. You have to wrap them into a shared parent, like a `<div>...</div>` or an empty `<>...</>` wrapper.
## Adding styles
In React, you specify a CSS class with `className`. Then you write the CSS rules for it in a separate CSS file. React does not prescribe how you add CSS files. In the simplest case, you’ll add a `<link>` tag to your HTML. If you use a build tool or a framework, consult its documentation to learn how to add a CSS file to your project.
## Displaying data
JSX lets you put markup into JavaScript. Curly braces let you “escape back” into JavaScript so that you can embed some variable from your code and display it to the user.
You can also “escape into JavaScript” from JSX attributes, but you have to use curly braces _instead of_ quotes.
You can put more complex expressions inside the JSX curly braces too.
In the above example, `style={{}}` is not a special syntax, but a regular `{}` object inside the `style={ }` JSX curly braces. You can use the `style` attribute when your styles depend on JavaScript variables.
## Conditional rendering
In React, there is no special syntax for writing conditions. Instead, you’ll use the same techniques as you use when writing regular JavaScript code.
- If and Else
- Conditional ? Operator
- Logical && Syntax
All of these approaches also work for conditionally specifying attributes.
## Rendering lists
You will rely on JavaScript features like `for` loop and the array `map()` function to render lists of components.
For each item in a list, you should pass a string or a number that uniquely identifies that item among its siblings. Usually, a key should be coming from your data, such as a database ID. React uses your keys to know what happened if you later insert, delete, or reorder the items.
## Responding to events
You can respond to events by declaring _event handler_ functions inside your components.
Do not _call_ the event handler function: you only need to _pass it down_. React will call your event handler when the user clicks the button.
## Updating the screen
Often, you’ll want your component to “remember” some information and display it. For example, maybe you want to count the number of times a button is clicked. To do this, add _state_ to your component.
First, import `useState` from React.
Now you can declare a _state variable_ inside your component.
You’ll get two things from `useState`: the current state (`count`), and the function that lets you update it (`setCount`). You can give them any names, but the convention is to write `[something, setSomething]`.
If you render the same component multiple times, each will get its own state.
## Using Hooks
Functions starting with `use` are called _Hooks_. `useState` is a built-in Hook provided by React.
You can also write your own Hooks by combining the existing ones.
Hooks are more restrictive than other functions. You can only call Hooks _at the top_ of your components (or other Hooks). If you want to use `useState` in a condition or a loop, extract a new component and put it there.
## Sharing data between components
However, often you’ll need components to _share data and always update together_.
To make both `MyButton` components display the same `count` and update together, you need to move the state from the individual buttons “upwards” to the closest component containing all of them.
You can pass information to `MyButton` using the JSX curly braces, just like you previously did with built-in tags like `<img>`
The information you pass down like this is called _props_.
This is called “lifting state up”. By moving state up, you’ve shared it between components.