# React_Questions
Q.1 
Ans.
Q.2 what is the current version of React (v18.0);
Ans.  Our latest major version includes out-of-the-box improvements like automatic batching, new APIs like startTransition, and streaming server-side .
Q.3 What are the advantages of using React?
Ans. Increases the application's performance with Virtual DOM
      - code easy to read and write
      - it renders both on client and server side (SSR).
      - Easy to integrate with frameworks (Angular, Backbone)
      -It is declarative,Write once, and learn anywhere,Fast, efficient, and easy to learn.
Q.4  What are the major features of React?
Ans.- It uses VirtualDOM instead of RealDOM considering that RealDOM manipulations are expensive.
    - Supports server-side rendering
    - Follows Unidirectional data flow or data binding
    - Uses reusable/composable UI components to develop the view.
    -Virtual DOM,One-way data binding,Performance,Components,Simplicity.
Q.5  What are the limitations of React? 
Ans. - Lack of Proper Documentation
    - Development Speed
    - JSX - JSX may be difficult for some devlopers to understand 
    - Problems With SEO
Q.6  Why we use react?
Ans. React can be used to build web, mobile, and desktop applications, making it a versatile framework for cross-platform development.
Q.7  Why is react fast?
Ans.React uses Virtual DOM, thereby creating web applications faster. Virtual DOM compares the components' previous states and updates only the items in the Real DOM that were changed, instead of updating all of the components again, as conventional web applications do.
Q.8 . what is a single page application?
Ans. A single page application is a website or web application that dynamically rewrites a current web page with new data from the web server, instead of the default method of a web browser loading entire new pages.
Q.9  React, is it framework or library?
Ans. React is merely a library that deals with views.
Q.10 Why we use redux? 
Ans.  Simply put, Redux is used to maintain and update data across your applications for multiple components to share, all while remaining independent of the components.
Q.11  What are diff key things of redux?
Ans.There are three core components in Redux — actions, store, and reducers.
Q.12 Why react is diff then other framework?
Ans. Compared to other frontend frameworks, the React code is easier to maintain and is flexible due to its modular structure. This flexibility, in turn, saves a huge amount of time and cost to businesses,Because of its component-based approach and virtual DOM, React is a lot faster than other frameworks.
Q.13  React, how different from plain js
Ans.  React has a steeper learning curve than vanilla javascript as it embraces component-based architecture and JSX syntax. Furthermore, React documentation and community support make it easier to learn and build complex applications once the basics are grasped.
Q.14  Why we use js?
Ans. JavaScript (JS) is a cross-platform, object-oriented programming language used by developers to make web pages interactive. It allows developers to create dynamically updating content, use animations, pop-up menus, clickable buttons, control multimedia, etc.
Q.15 What is JSX?
Ans. JSX stands for JavaScript XML. JSX allows us to write HTML in React. JSX makes it easier to write and add HTML in React.
Q.16  what is JSX in reactjs?
Ans.  JSX stands for JavaScript XML. JSX allows us to write HTML in React. JSX makes it easier to write and add HTML in React.
Q.17  Why we use jsx?  
Ans. JSX allows us to write HTML elements in JavaScript and place them in the DOM without any createElement() and/or appendChild() methods. JSX converts HTML tags into react elements. You are not required to use JSX, but JSX makes it easier to write React applications.
Q.18  Can I write if else condition in JSX?
Ans. if-else statements don't work inside JSX. This is because JSX is just syntactic sugar for function calls and object construction.
Q.19 . What is JSX and What is the relation of JSX with React.createElement ?
Ans.JSX allows us to write HTML elements in JavaScript and place them in the DOM without any createElement() and/or appendChild() methods.
Q.20  does the web browser understand JSX directly ?  
 Ans. No,Browsers can't read JSX because there is no inherent implementation for the browser engines to read and understand them.
Q.21 Can web browsers read JSX directly?
No,Browsers can't read JSX because there is no inherent implementation for the browser engines to read and understand them.
Q.22  What is Babel?
Ans.  Babel is transpiler[to translate the code] which convert the latest version of JavaScript code into the one that the browser understands.
Q.23 How do you create elements in React without JSX?
Ans. Yes, it is possible to use React without JSX,. So, anything you can do with JSX can also be done with just plain JavaScript.
Q.24 why do we use className instead of class keyword as an Attribute in jsx?
Ans.  The only reason behind the fact that it uses className over class is that the class is a reserved keyword in JavaScript and since we use JSX in React which itself is the extension of JavaScript, so we have to use className instead of class attribute.
the class is a reserved keyword in JavaScript and since we use JSX in React which itself is the extension of JavaScript
Q.25  DOM?
Ans.  Document Object Model 
DOM stands for Document Object Model. It is a programming interface that allows us to create, change, or remove elements from the document.
Q.26 what is virtualDOM? explain the same
Ans  React uses Virtual DOM which is like a lightweight copy of the actual DOM.
    - It is exactly the same as DOM, but it does not have the power to directly change the layout of the document.
    - Manipulating DOM is slow, but manipulating Virtual DOM is fast as nothing gets drawn on the screen
    - In virtual DOM, it first create the tree of components, and when we do changes in any component only that component is re-rendered.
Q.27  How Virtual DOM works?
Ans. In virtual DOM, it first create the tree of components, and when we do changes in any component only that component is re-rendered.
Q.28  Why react maintains virtual dom.
Ans React uses the virtual DOM as a strategy to compute minimal DOM operations when re-rendering the UI, React uses Virtual DOM exists which is like a lightweight copy of the actual DOM.
Q.29  Describe about Virtual Dom and real DOM?
Ans. A virtual DOM object is the same as a real DOM object, except that it is a lightweight copy. This means that it cannot manipulate on-screen elements. Moreover, upon any change of a property, it only updates the corresponding nodes and not the entire tree. That makes it a quick and efficient alternative.
-DOM is an interface that allows the script to update the content, style, and structure of the document. Virtual DOM is just like a blueprint of a machine, can do changes in the blueprint but those changes will not directly apply to the machine.
Q.30 shadow DOM?
Ans. Shadow DOM allows hidden DOM trees to be attached to elements in the regular DOM tree.
Q.31  What is diff between real vs virtual dom.
Ans.        Real DOM                                                                          Virtual DOM
           It allows us to directly target any specific node (HTML element)	    It can produce about 200,000 Virtual DOM Nodes / Second.
           It represents the Ul of your application	                                  It is only a virtual representation of the DOM
           The real DOM can directly update HTML. The virtual DOM cannot directly update HTML. The virtual DOM updates the JSX if the element updates. In real DOM, DOM 
            manipulation is very expensive.
Q.32 library vs framework
Ans.  A framework is a set of pre-written code that provides a structure for developing software applications. A library, on the other hand, is a collection of pre-written 
      code that can be used to perform specific tasks.
Q.33  What is web development?
 Ans. Web development is the building and maintenance of websites,
 Q.34 How will you implement lazy loading in react?
 Ans.You need to provide a single input parameter to call React. lazy().
     Code-splitting and lazy loading is a way to decreasing initial loading time to clients.
    - Call const LazyLoadedComponent = React.lazy(() => import(‘./custom-component.js’)
    - Use <LazyLoadedComponent />
 Q.35  How to pass data from parent component to child component ? 
   Ans.      The most basic and commonly used way to pass data from a parent component to a child component is through [props]. Props, 
               short for properties, are read-only values that are passed from a parent component to a child component
 Q.36  How can we pass data from component A to component C with no child sibling
       relationship? 
   Ans. Props are used for passing data between the components. We usually use it to pass data from the parent component to the child component.
Q.37 . How do we create react apps?
 Ans. If you have npx and Node.js installed, you can create a React application by using create-react-app.
Q.38  How do we create react apps in local?  
Ans. cd ReactProjects .
    -Install React using create-react-app, a tool that installs all of the dependencies to build and run a full React.js application.
Q.39 How to create components in React?
Ans. create a new file with a .js 
Q.40  react element?
Ans.React Element: It is the basic building block in a react application, it is an object representation of a virtual DOM node. 
Q.41  Explain the default keyword in React.
   Ans. when you export a symbol as default, you don't need to specify its name
Q.42  What is the difference between Element and Component?
Ans. There is certainly a difference between elements and components. Furthermore, a component refers to a small part of a larger entity that mostly is a manufactured object. In contrast, an element is one the simplest parts of which anything consists of.
Q.43  what is React Api used under the hood?
Ans. React must now compare these two trees and provide ReactDOM with instructions to sync anything that has changed.
Q.44 What are callback functions?
Ans. A callback function is a function passed into another function as an argument, which is then invoked inside the outer function to complete some kind of routine or action
Q.45  Inline Conditional Expression - Example ?
Ans. An expression a ? b : c evaluates to b if the value of a is true, and otherwise to c . One can read it aloud as "if a then b otherwise c".
Q.46 npm vs npx ?
Ans. NPM is a package manager used to install, update or remove packages and dependencies your project requires. NPX is an NPM package used to execute any package on the NPM registry directly without installing it. This is just a starting point in the world of Javascript and NodeJS
Q.47 What is default in export statement?
Ans.  Default export - is the value that will be imported from the module, if you use the simple import statement import X from 'module'.
Q.48   What is meant by data flow is unidirectional in react?
Ans.Unidirectional data flow is a technique that is mainly found in functional reactive programming. It is also known as one-way data flow, which means the data has one, and only one way to be transferred to other parts of the application.
Q.49 What is the use of keys in react?
Ans. Keys help React identify which items have changed, are added, or are removed.
Q.50 diffing algorithm?
Ans.Elements of different types will produce different trees. We can set which elements are static and do not need to be checked.
Q.51 Reconciliation process
Ans. Reconciliation is the process of comparing transactions and activity to supporting documentation. Further, reconciliation involves resolving any discrepancies that may have been discovered.
Q.52 what is state?
Ans.The state is a built-in React object that is used to contain data or information about the component. A component's state can change over time; whenever it changes, the component re-renders
Q.53 what is useState().?
Ans useState is React Hook that allows you to add state to a functional component.
Q.54  setState() is async or sync in nature?
Ans.setState is an Asynchronous Function.
Q.55 useEffect in react?
Ans. The useEffect Hook allows you to perform side effects in your components,
If we need to perform a side effect, it should strictly be done after our component renders.
Q.56 What is state lifting?
Ans. We lift the state up to make the parent state a single shared state and a sole "source of truth" and pass the parent's data to its children. This concept is called lifting state up. It is of great use to maintain data consistency in our react applications.
Q.57  lifting state up?
Ans.In React, sharing state is accomplished by moving it up to the closest common ancestor of the components that need it. This is called “lifting state up”. We will remove the local state from the TemperatureInput and move it into the Calculator instead.
Q.58  What is the purpose of callback function as an argument of setState()?
Ans. The setState function takes an optional callback parameter that can be used to make updates after the state is changed. This function will get called once the state has been updated, and the callback will receive the updated value of the state.
Q.59  what is state and props in react application?
Ans.                     State                                                                         Props
      -State changes can be asynchronous                                                      -	Props are read only
      -State is controlled by react components                                                - Props are controlled by whoever renders the components
      -State can used to display changes with the component                                   - Props are used to communicate between components
Q.60 Explain state management with state and props?
Ans. Props are used to pass data, whereas state is for managing data. Data from props is read-only, and cannot be modified by a component that is receiving it from outside. State data can be modified by its own component, but is private (cannot be accessed from outside)
Q.61  What is prop drilling? 
Ans_1.Prop drilling occurs when a parent component passes data down to its children and then those children pass the same data down to their own children. This process can continue indefinitely. At the end, it's a long chain of component dependencies that can be difficult to manage and maintain.
Ans_2.- Prop drilling is basically a situation when the same data is being sent at almost every level due to requirements in the final level.
Q.62 Prop drilling and its disadvantage and how we can get rid of this?
Ans. Using the useContext hook is one of the better solutions to this.
Q.63  what are differences between state and props?
Ans. Props are used to pass data from one component to another. The state is local data storage that is local to the component only and cannot be passed to other components.
Q.64  How does it(props and state) helps to improve performance? 
Ans nhi mila muje answer khud dekh lo sub me hi krdu kya
Q.65 pass props b/w the component?
Ans. React components use props to communicate with each other. Every parent component can pass some information to its child components by giving them props. Props might remind you of HTML attributes, but you can pass any JavaScript value through them, including objects, arrays, and functions.
Q.66 Can we pass the state also as a props to the children components?
Ans. The Parent component has a name state, when it renders the Child component it passes the state variable as a prop named name.
Q.67  How to pass props from children to parent?
Ans. Create a callback method.
Q.68  What is the difference between state and props?
Ans.The difference comes in which component the data are owned. State is owned locally and the component itself updates it. Props are owned and read-only by a parent. Props can be changed only if an upstream shift is caused by a callback function passed on to the child.
Q.69  can we update the state directly
Ans. No, Updating the state of a component directly can have unintended consequences that can be difficult to debug.
Q.70 Why should we not update the state directly?
Ans.can have unintended consequences that can be difficult to debug
Q.71 What is use of key property in react?
Ans.React's key prop gives you the ability to control component instances.
Q.72  What are key props in react?
Ans. React's key prop gives you the ability to control component instances.
Q.73 why is the "key" prop used in lists in react js?
Ans. Keys are used in React to identify which items in the list are changed, updated, or deleted.
Q.74 What is the significance of keys props in React ?
Ans. React's key prop gives you the ability to control component instances.
Q.75  What is ""key"" prop and what is the benefit of using it in
   arrays of elements?
Ans.  A key is a special string attribute you should include when creating arrays of elements. Key prop helps React identify which items have changed, are added, or are removed.
Q.76 Explain about Components in React ? 
Ans. Components are independent and reusable bits of code.
Q.77 What are the types of components in React? 
Ans. React supports two types of components, class components and functional components.
Q.78 What are controlled components?
Ans.In React, a controlled component is a component that is controlled by React state.
Q.79  What are uncontrolled components?
Ans.Uncontrolled components refer to components that manage their own state internally.
Q.80  difference between a Controlled and an Uncontrolled one in React?
Ans.In React, a controlled component is a component that is controlled by React state, while an uncontrolled component is a component that maintains its own internal state.
  In a controlled component react, state handles all the form data, whereas, in an uncontrolled component, the HTML form element data is managed by only the DOM.
Q.81  What are Pure Components?
Ans. A React component is considered pure if it renders the same output for the same state and props.
Q.82  What is diff between pure and impure component?
Ans.In React, components are pure if their output is only determined by their inputs ( props ), and are impure if their output is determined by something other than the inputs, namely their state .
Q.83 What is a higher-order component(HOCs) in React?  when it is used ?
Ans. A higher-order component (HOC) is an advanced technique in React for reusing component logic. HOCs are not part of the React API, per se. They are a pattern that emerges from React's compositional nature. Concretely, a higher-order component is a function that takes a component and returns a new component.
Q.84  What are higher-order components (HOCs) used for?
Ans.This is where HOCs come in. Here, higher-order components allow developers to reuse code logic in their project. As a result, this means less repetition and more optimized, readable code.
Q.85 How do you create HOC?
Ans.e can invoke the HOC as follows: const SimpleHOC = higherOrderComponent(MyComponent);.
Q.86 How can you embed two or more components into one?
Ans.create the parent-child relationship between the 2 or more components.
Q.87 What are the different ways to style a React component?
Ans.Inline CSS.
Normal CSS.
CSS in JS.
Styled Components.
CSS module.
Sass & SCSS.
Less.
Stylable.
Q.88 What are the differences between class and functional components?
Ans.A functional component is just a plain JavaScript pure function that accepts props as an argument and returns a React element(JSX). A class component requires you to extend from React. Component and create a render function that returns a React element.
Q.89  How we update state in class components ?
Ans. To change a value in the state object, use the this. setState() method. When a value in the state object changes, the component will re-render, meaning that the output will change according to the new value(s).
Q.90  What are different phases of lifecycle in class component? 
Ans.Lifecycle of Components
The three phases are: Mounting, Updating, and Unmounting.
Q.91  Explain the usage of componentWillUnmount() lifecycle method?
Ans.The componentWillUnmount() method allows us to execute the React code when the component gets destroyed or unmounted from the DOM (Document Object Model). This method is called during the Unmounting phase of the React Life-cycle i.e before the component gets unmounted.
Q.92  Why React uses className over class attribute?
Ans.the class is a reserved keyword in JavaScript 
Q.93 How to perform unmounting in functional component?
Ans.This method is called during the unmounting phase of the React Lifecycle, i.e., before the component is destroyed or unmounted from the DOM tree. This method is majorly used to cancel all the subscriptions that were previously created in the componentWillMount method.  [maybe].
Q.94 Create a simple class and function based component.
Ans.To develop class-based components in React, we can use JavaScript ES6 classes. To define a React component class, you need to extend React. Component. You must develop a render method that returns a React element by extending from React.
Q.95  When to use a Class Component over a Function Component?
Ans.  If you want consistency between all components in your codebase, go with classes.
Q.96  why do we use className instead of class in react js?
Ans.The only reason behind the fact that it uses className over class is that the class is a reserved keyword in JavaScript and since we use JSX in React which itself is the extension of JavaScript, so we have to use className instead of class attribute.
Q.97  What are fragments in react?
Ans. React Fragment is a feature in React that allows you to return multiple elements from a React component by allowing you to group a list of children without adding extra nodes to the DOM.
Q.98  What do you mean by unidirectional?
Ans.Unidirectional data flow describes a one-way data flow where the data can move in only one pathway when being transferred between different parts of the program.
Q.99  What are the features of React?
Ans.Virtual DOM,One-way data binding,Performance,Components,Simplicity.
Q.100 What is the difference between the ES5 and ES6 standards?
Ans. ES5 supports primitive data types that are string, number, boolean, null, and undefined. In ES6, there are some additions to JavaScript data types. 
Q.101  what do you mean by rendering?
Ans. In React, Render is the technique that can redirect a page with the help of function render().
Q.102 what do you mean by re-rendering?
Ans. A second or subsequent render to update the state is called as re-rendering. React components automatically re-render whenever there is a change in their state or props.
Q.103 What are the things that can cause re-render of your state
Ans.React components automatically re-render whenever there is a change in their state or props. A simple update of the state, from anywhere in the code, causes all the User Interface (UI) elements to be re-rendered automatically. 
Q.104  what is conditional rendering in react js? 
Ans.In React, conditional rendering is the process of displaying different content based on certain conditions or states.
Q.105 What is the use of render() in React?
Ans.In React, Render is the technique that can redirect a page with the help of function render(). Most importantly, render a function we can use to define the HTML code within the HTML element. It helps to display certain views in the UI using certain logic defined in the render function and returns the output.
Q.106  What is the difference between server side render and client side render?
Ans. The main difference between these two rendering approaches is in the algorithms of their operation. CSR shows an empty page before loading, while SSR displays a fully-rendered HTML page on the first load.
Q.107 Write a class based component and asked to convert into function component
        class Fun(){
        componentDidMount(){
        function doSomething(){
        console.log(4);
        }
        fun();
        }

        render(){
        return <>Fun</>
        }
        }
Q.108 What would you do if your React application is rendering slowly?
Ans.Remember re-render happens whenever there is a change in a state component. It causes the render method to call again and then react updates only a portion that needs to be updated by comparing copies of Virtual DOM.
Q.109  Explain the lifecycle methods of components?[12]
Ans. - Each component in React has a lifecycle which you can monitor and manipulate during its three main phases.
    - The three phases are: Mounting, Updating, and Unmounting.
Q.110 life cycle component Phases?
Ans.. The three phases are: Mounting, Updating, and Unmounting.
Q.111 methods inside mounting phase?
Ans.-constructor()
    - getDerivedStateFromProps()
    - render()
    - componentDidMount()
Q.112 What are the different lifecycle methods in React?
Ans. The three phases are: Mounting, Updating, and Unmounting.
Q.113 what is meant by when I say *componentDidMount* is a lifecycle method? 
Ans. The componentDidMount() method is called after the component is rendered. This is where you run statements that requires that the component is already placed in the DOM.
Q.114   Basically what are lifecycle methods?
Ans. Mounting, Updating, and Unmounting.
Q.115  What is use of shouldComponentUpdate?
Ans.The shouldComponentUpdate is a lifecycle method in React. This method makes the component to re-render only when there is a change in state or props of a component and that change will affect the output.
Q.116 What is Difference between componentWillMount and componentDidMount? 
Ans.The main distinction lies in the invocation timing of componentDidMount() and the deprecated componentWillMount().
Q.117 Difference between shouldComponentUpdate and componentDidMount?
Ans.componentWillMount gets called when rendering React on the server and on the client, but componentDidMount is only called on the client.
Q.118 Lifecycle methods in react. Best lifecycle method for making API calls?
Ans.componentDidMount() method
For example, we are going to fetch any data from an API then API call should be placed in this lifecycle method, and then we get the response, we can call the setState() method and render the element with updated data.
Q.119  Can we use lifecycle methods in functional component?
Ans. Yes, you can use the life cycle method in the functional component with help of useEffect hooks.
Q.120 What are hooks in react? Can you name any hook that we frequently use ? [13]
Ans. Hooks are the functions which "hook into" React state and lifecycle features from function components.
Q.121  What are the rules of using hooks?
Ans -Hooks can only be called inside React function components.
    -Hooks can only be called at the top level of a component.
    -Hooks cannot be conditional.
Q.122  Have you worked with Hooks, different type of hooks?
Ans.useState Hook. useState to Create State Variables. ...
useEffect Hook. useEffect to Perform Side Effects. ...
useRef Hook. useRef to Reference React Elements. ...
useCallback Hook. useCallback Prevents Callbacks from Being Recreated. ...
useMemo Hook. useMemo Can Improve Expensive Operations. ...
useContext Hook. ...
useReducer Hook.
Q.123 name 2 hooks and explain ?
Ans. useState Hook.useState is React Hook that allows you to add state to a functional component
useEffect Hook.The useEffect Hook allows you to perform side effects in your components. Some examples of side effects are: fetching data,
useRef Hook.
useCallback Hook.
useMemo Hook.
useContext Hook.
useReducer Hook.
Q.124 What is the need of useState() hook? Can you initialise the ?
Ans. The React useState Hook allows you to have state variables in functional components. 
Q.125  useState() hook with null value? [2]
Ans.the state can be true or null, with the init value of null.
Q.126  useEffect hook (2)
Ans.The useEffect Hook allows you to perform side effects in your components.
Q127.Write syntax for useEffect hook.
Ans.No dependency passed: useEffect(() => { //Runs on every render }); Example.
An empty array: useEffect(() => { //Runs only on the first render }, []); Example.
Q.128 Implement the useState and useEffect hooks?
Ans.Application constant = () => {
const [counter, setCounter] = React.useState(0);
const handleClick = () => setCounter(counter + 1);
return (
<>
<h1>Counter: {counter}</h1>
<button onClick={handleClick}>Increase</button>
</>
Q.129 What is dependency array in useEffect() hook?
Ans.
  





























