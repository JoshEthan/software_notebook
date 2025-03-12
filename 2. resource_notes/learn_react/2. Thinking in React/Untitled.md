When you build a user interface with React, you will first break it apart into pieces called _components_.

Then, you will describe the different visual states for each of your components.

Finally, you will connect your components together so that the data flows through them.

## Start with the mockup
Imagine that you already have a JSON API and a mockup from a designer.
To implement a UI in React, you will usually follow the same five steps.

## Step 1: Break the UI into a component hierarchy
Start by drawing boxes around every component and subcomponent in the mockup and naming them.
Depending on your background, you can think about splitting up a design into components in different ways:
- **Programming**—use the same techniques for deciding if you should create a new function or object.
- **CSS**—consider what you would make class selectors for. (However, components are a bit less granular.)
- **Design**—consider how you would organize the design’s layers.

If your JSON is well-structured, you’ll often find that it naturally maps to the component structure of your UI. That’s because UI and data models often have the same information architecture—that is, the same shape. Separate your UI into components, where each component matches one piece of your data model.