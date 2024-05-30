
# 🏁 The basics of React

## 🤓 Course overview and learning outcomes
The goal of this lesson is to provide you with a brief introduction to React. By the end of this course you should be able to explain what React is and how it works.

## ❓ What is react?
React is a web [framework](https://en.wikipedia.org/wiki/Web_framework) designed for building user-interfaces based on [components](#components). It is a popular choice for building web applications because it is fast, efficient, and easy to use. It is an open-source project that is maintained by Meta. 

## 🧩 Components
React is based on the concept of components. A component is a reusable piece of code that can be used to build user interfaces. Components can be nested inside other components to create complex user interfaces. React components can be written in JavaScript, TypeScript, or any other language that can be compiled to JavaScript. Here's an example of a simple React component:

```jsx
function Page() {
  return <h1>Home Page</h1>;
}
```

## 📦 Installation
To install React, you need to have [Node.js](https://nodejs.org/en/) installed on your computer. You can then install React using the following command:

```bash
npx create-react-app my-app
```

This will create a new React project in a folder called `my-app`.

## 🚀 Assignment
1) Create a new React project using the `create-react-app` command. Run the project using the following command

2) Create a folder in `src` called `components`. Inside this folder, create a new file called `HelloWorld.js`. In this file, create a simple React component that displays the text "Hello, World!".

3) Import the `HelloWorld` component into the `App.js` file and render it inside the `App` component.

4) Run the project with `npm run start` and verify that the "Hello, World!" text is displayed on the screen.

## 📚 Resources
- [React documentation](https://reactjs.org/docs/getting-started.html)
- [React tutorial](https://reactjs.org/tutorial/tutorial.html)
- [React components](https://reactjs.org/docs/components-and-props.html)
- [React hooks](https://reactjs.org/docs/hooks-intro.html)
