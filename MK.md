# React
React is a JavaScript library for building user interfaces.
* Declarative: React makes it painless to create interactive UIs. Design simple views for each state in your application, and React will efficiently update and render just the right components when your data changes. Declarative views make your code more predictable, simpler to understand, and easier to debug."

* Component-Based: Build encapsulated components that manage their own state, then compose them to make complex UIs. Since component logic is written in JavaScript instead of templates, you can easily pass rich data through your app and keep the state out of the DOM.
* Learn Once, Write Anywhere: We don't make assumptions about the rest of your technology stack, so you can develop new features in React without rewriting existing code. React can also render on the server using [<u>Node</u>](https://nodejs.org/en) and power mobile apps using [<u>React Native</u>](https://reactnative.dev/).

[<u>Learn how to use React in your project</u>.](sdfdd)

## Installation
React has been designed for gradual adoption from the start, and you can use as little or as much React as you need:

* Use [<u>Quick Start</u>]() to get a taste of React.
* Add React to an Existing Project to use as little or as much React as you need.
* Create a New React App if you're looking for a powerful JavaScript toolchain.
## Documentation
You can find the React documentation on the website.

Check out the Getting Started page for a quick overview.

The documentation is divided into several sections:

* Quick Start
* Tutorial
* Thinking in React
* Installation
* Describing the UI
* Adding Interactivity
* Managing State
* Advanced Guides
* API Reference
* Where to Get Support
* Contributing Guide

You can improve it by sending pull requests to this repository.
## Examples
We have several examples on the website. Here is the first one to get you started:

```
import { createRoot } from 'react-dom/client';

function HelloMessage({ name }) {
  return <div>Hello {name}</div>;
}

const root = createRoot(document.getElementById('container'));
root.render(<HelloMessage name="Taylor" />);
```
