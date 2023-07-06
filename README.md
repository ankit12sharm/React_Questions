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
    
  





























