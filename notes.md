# html

## Basic HTML Tags

### Lists:
- `<ol>` : Ordered list
- `<ul>` : Unordered list
- `<li>` : Used to define list items
- `<dl>` : Used to create Definition list , with `<dh>` and `<dd>` being the data elmments

### Tables:
- `<table>` : Used to create a table.
- `<thead>` : Used to create the heading of the table.
- `<tbody>` : used to create the body of the table.
- `<tr>` : To create rows
- `<th>` : To create table headers
- `<td>` : To insert data into the table cells
- **Attributes** :
  - `border`: Adds borders to the table. CSS can also be used for styling.
  - `rowspan`, `colspan` : no of rows/cols need by a single td , th .

### containers:
- `<div>`
- `<section>`
- `<article>`

- `<iframe>` : contains the embbeded code of the web browser.

### form tag:
- `<form>`: main tag

- `<label>`: Used inside the form tag just tlike a container. gives the label inside the form tag.
- `<input>`: to add contents , we need a box like container . we use `<input>` for that purpose.
- *input type*:
  - text
  - password
  - number
  - email
  - address: (use textarea inseat of input ) textarea : but used insted of inputntag , we use `<texarea>`.
  - range : Gives a range to select just like the price range in flipkart.
  - radio : for genders( to selsect only one),we should use label just after the input.
  - checkbox : we should use label just after the input.
  - date

- `<button>`: To add an Button at the end of the form.

### icons
- `<i>`
- use Font Awesome to add an icon to the page
  - we should use font awesome cdn and copy the link to the head part
- Google Fonts - to add font to our html ( we should also link it to our head)

### semantics
- `<header>` : for header part of the body.
- `<nav>` : as the nav bar.
- `<section>` : divides the page into different section
- `<article>` : same as the section.
- `<aside>` : the part of the webpage which is on the left or the right side.
- `main` : Takes the main part of the body.
- `footer` : footer of the page.

# CSS   

## Ways to Apply
- Inline Css : should use style atribute, Syntax : `style= "Property:value;" `
- internal Css : should be used inside the html file itself , we use `<style>` tag. Syntax : `<style> selector { property: value;} </style>`
- External Css : Should be included to a html file, Syntax : `selectors { property : value }` , link the css in the head of the html using `<link rel="stylesheet href="filename.css>`

## CSS selectors
 - used to select a html element to a html file. 
    - tag name
    - id : #idname{...}
    - class : .classname{...}
    - Universal : *
    - CSS combinators
      - Grouping : , (comma seperated)
      - descendent : selector child{...}
      - child : >
      - sibling : ~ 
      - immedidate sibling : +

## CSS PROPERTIES
- float
- position
- absolute
- relative
- sticky

  - z-index : To override the content , over other elemnt

- flexbox : Flex box is used to arrange elemnts either in rows or coloums.
 - flex Container - All the child elemens should be included inside a Container tag.

- Grid: : Grid is used to arrange elemts in rows or Coloums, we also need to specify the width and height of each items.
  - display : grid;
  - grid-template-coloum/row : auto auto; (increasre the number of autos for how many coloums/rows needed.)
  - gap: used to give gap between the colums and rows

# Animate Libraries 

- [animate.css] - We need to give a class = "animate__animated animate__"/ animation-name /".
- [https://michalsnik.github.io/aos/]

# WEB hosting Servers
- netlify
- github
- vercel


# GIT and GITHUB

- GIT : is ued to control version of a code
- GIT commands :
   - git status : use to check the status of the folder.
   - git init : used to create or initiate a git repository in a folder. // Just check the status after this, just to make sure we initialised.
   - git add . : used to track all untracked files to the git.
   - git commit -m "message" : used to save files to the git.
   - git remote add orgin "--link--" : this should be done to link the oru git with github
   - git push origin master : To push the code to the github 

# BOOTSTRAP

Bootstrap is used to create fast and resposive css
Some of the class and attributes of Bootstraps : 
- container , container-fluid : create a div and set the class as container to give it a margin 
- border
- border color attributes :
  - border-success : green
  - border-danger : red
  - border-warning : orange
  - border-dark : black
  - border-light : white
  - border-info : skyblue
   -primary -secondary

- m : use to set margin
  - mt : margin top
  - mb : margin bottom
  - ms : margin left
  - me : margin right
  - 1/2/3/4/5 : range

- p : for padding
  - same as margin 

- w : for width
  - w-25/50/75/100

- grid
  - rows : Can only be divided into total of 12 equal parts
  - coloums : 

# JAVASCRIPT

Javascript is a dynamic programing language because its datatypes change acoordingly at times.

Node Js : Its a collection of JS and Runtime Enviornment.
 we use ECMAscript version 6 

Basic Concepts of JS : 
 - Displaying Contents : console.log(contents) method.
 - Data Types :
   - Numbers
   - Text : Contents inside single or Double Quotes
   - Boolean : true / false
   - object : eg - array

 Combining different Types of datas : 
  - using comma's
  - using concatination : `+` Converts the contents to string (One of the side should also be string)
  - Template Literals : ` which combines different data suing the back tick symbol. 

 Variables : used to store Data.
 identifiers : set of rules to assign which defines what names should assign to a variable.

Creation of Variables :
 - Var : `var variableName = value`/ var variable_name (varable names should not have any space in Between )
 Hoisting : re-assing a variable on the top of code
 - Const : `const varableName = value`
 - let : `let varaiableName = value` 

Difference between different variables
var | const | let |
----|-------|-----|
use var keyword | use const keyword | use let keyword
can reassign | can't reassign | can reassgin inside its scope
Global Scope | Block Scope | Block Scope
Hoisting is possible with inital value | Hoisting is possible but without initial value | Hoisting is possible but without initial value

Spread Operator : which is used to spread an iterating variable to a single array which uses a simple -  `...`

## Operators in JS : 
 - assingment Operator : ` = `
 - Arthematic Operators : ` + - / * % ** `
 - Relational Operators : ` > < >= <= == === != !== `
 - Logical Operators : ` && || ! `
 - Increment Operators : ` ++ -- `
 - Short Hand Operators : ` += -= *= /= `
 - Spread operator : used ti spread an iterating varianble to a single array by using `...` symbol
 - rest operator : used to combine rest of the values to a single array, using `...` operators

## Looping Statements : 
 - while loop :
    ```
      while(condition){
        statements;
        increment; 
    }
    ```

  - for loop : 
    ```
      for(initialize variable,condition,increment){
        statements;
      }
    ```

break statemnts : used to brake the execution of the loop.
Continue statement : used to skip at certain values in loop.

Nested Loop : A loop within/inside a loop.
```
  for(initialize variable,condition,increment){
        for(initialize variable,condition,increment)
        {
          statements;
        }
      statements;
      }
```
Functions : Used to perform a paticular task, A funtion needs to declared and defined, The function should also be called to perform
 ```
  function function_name(args1, args2, ...){
    Funtion Body;
  }
  ...
  ...
  ...

  function_name(arg1, ...); // Funtion call
 ```
 - Function call : used to execute the function.
 - Hoisting is possible. 

## Types of Functions : 
  - Predefined Functions : eg - Number(), console.log(), Math.floor(), alert().
  - Arrow Functions : used as an alternative for normal function.
    - Syntax :  
      ```
        variableType Function_Name = (args1, args2, ...) => {
          Function body;
        }
      ```
  - Callback Function : A function defention which is written inside another function
    - Syntax :
      ```
        function_name( ()=>{statements})
      ```
   - Anonimous function : a function which are self executing
   - Recursive function / REpeating Function : used to perform repeatedly, calling inside its own definition.
    - Syntax : 
      ```
        function function_name(){
          ...... function_name();
        }
      ```
   - Nested Function : function which is declared inside another function.
    - closure property : In nested function when a child function access its parent data. 

## Array : used to save multiple variables.
 - Array methods :
   - push() : add elements to the end.
   - unshift() : to inseet value at the start.
   - pop() : used to remove item from the end.
   - shift() : to remove item fromt the front.

 - Accesing elements in array : 
   - displaying elements in an array using normal loop
     ```
      for (let i = 0; i < weekdays.length; i++) {
        console.log(weekdays[i]);
      }
      ```
   - displaying elements in an array using for-of loop
      ```
        for(let day of weekdays){
          console.log(day);
        }
      ```

   - displaying elements in an array using for-in loop.
    
      ```
       for(let day in weekdays){
         console.log(weekdays[day]);
       }
     ```
## Array Functions : 

 - sort(callback function) : The items can be sorted in accending or decending order.

   ```
    array_name.sort((a,b)=>a-b) - for accending order

    array_name.sort((a,b)=>b-a) - for decending order
    ```
 
 - forEach(callback function) : Its a alterantive for - for of loop

   ```
    array_name.forEach(array_Elem =>{
       statements;
    })
   ```

 - filter(callback function): which will filter values applied in the existing array based on the condition, the value RETURNED is ARRAY
   
    ```
      array_name.filter(element => statement)
    ```

 - find(callback function): which will return a particular value which satisfies conditions applied in excisting array , USED WHEN TO  RETURN A SINGLE ELEMENT

    ```
      array_name.find(element => statement)
    ```

 - map(callback function) : applies a certain mappin functions to all the elements in array elements , this method RETURNS a NEW ARRAY

 - reduce(callback function) : returns a SINGLE VALUE , either lowest/highest or total.

 - reduceRight( callback function) : return a FIRST single value , Based on the condition.

 - some( callback function ) : which returns a boolean value which satisy a condition in the applied array.

 - every( callback function )  : which returns a boolean value when all the values in array satisyies the condition.

 - flat(depth) : used to flatten the multi-dimentional array (which means it will make it a single array according to the dept), it RETURNS A ARRAY
   - array_name.flat(Infinity) : can be used when the array's dimention is not defined
   ```
      array_name.flat(depth);
   ```

 - include(array-item) : it return an boolean value if the item is present in the array.

 - indexOF(array-item) : gives the index of the given item.

 - Splice(index, delete count, replace) : Removes element or elements from an array and also to replace element in that position, returns an ARRAY of DELETED ELEMENTS.

 - `Use array.__proto__` : to get all the array methods , (can be runned on a browser inspect page).

## String
  
 ### String Methods : 
 - toLowerCase() : converts all elements to lower case

 - toUpperCase() : converts all the elements to upper case

 - substring(start-index,end-index) : creates a sub string of the given index

 - slice(start, end) : creates a sub string of the given index , slice can also give negative numbers to remove from the end.

 - startsWith(element) : will check if the array stats with the given element/input and returns an boolean output

 - endsWith(element) : will check if the array ends with the given element/input and returns an boolean output

 - split() : used to spilt the elements of a string and RETURNED as an ARRAY

 - includes(sunstring) : checks if the substring is present in the sting

 - trim() : removes all the unwanted spaces in an given array.

## Objects 
  
  Objects are just like an array which stores key-value pairs.

  Ways to Access values in Object : 
  - Bracket Notation : `objectName["key"]`
  - Dot Notation : `objectName.key`

  How to check whether a key is present in an object : 
  - using `in` operator : `"key" in objectName`, This will returns a Boolean Value.
  - using `hasOwnProperty()` : `object.hasOwnProperty(key)`, it returns a Boolean Value.

  Insert a value to an Exisiting Object : 
  - `objectName[key] = value`
  - `objectName.key = value`
  - `Object.assign(desigination,source)`

  `Object.keys(objectName)` : will return array of all the keys in tht exisiting Object
  `Object.values(objectName)` : will return array of all the values in the existing objects.
  `Object.entries(objectName)` : used to display as an array.

  `delete` keyword : used to remove an key/element from an object.  - `delete objectName.key`
  
  Destructurin of an object : uesd to access values without using notation
  `const {key1,key2,key3,....} = objectName`

## Exception / Run-time Errors  Handling
  -  We should use `try catch block` 
  
## OOPS
 - Object :  real world entites, Used to asses an class methods outside it. syntax : `new classname`
 - class : Blueprint of an object, can have some properties/funcition. `class` keyword is used to create these methods , pre-defined methods is called constructor and it can be initialized by class properties.
 - reference : linked the properties and function , keyword :  `this`

### Features of OOP
 - Inheritance : A class can extend/inherit functions defined in another class
   - Classical Inheritance : using keyword `extends`
      ```
      child_class extends parent_class{......}
      ```
   - Prototype Inheritance : using the keyword `__proto__`
      ```
        child_object.__proto__ = parent_object
      ```
 - Polymorphism : 
 - Abstraction : 
 - Encapusalation : class is an example

# Javascript in Front-end

Used to provide behaviours to HTML elements

## Applying JS to HTML

 - Internal JS : JS code in script tag in the HTML file
 - External JS : JS code in external file linked using script tag

## DOM (Document Object Model) 
 A tree structure using object corresponding to a webpage
 - Dom Methods : 
   - Using tag : `document.getElementByTagName("tag")`
   - using id :  `document.getElementById("tag")` / `id`
   - using class : `document.getElementByClassName("class")`
   - using querySelector : `document.querySelector("tag"/"#id"/".class")`
   - using querySelectorAll : `document.querySelectorAll("tag"/"#id"/".class")`

Events : Triggered by user action, Events may occur in HTML elements
 - Mouse related events : click, drag and drop, double click...
 - Keyboard related events : key-press, up and down arrow...
 - Touch related events 
 
Handling Events in HTML : event function call() inside HTML elements, Also the behaviour changes must be defined as a function defenitions.
Access / Update content of HTML element in JS : 
 - innerHTML / InnerText property

### PERMANTENTLY STORE DATA IN THE BROWSER :
 - Data will be stored permanently as key-value pairs, type of both key and value must be 'string', to convert value to string use -  `JSON.stringify(value)`,
To pass string to orginal form use - `JSON.parse(value)`

 - Local storage:
   - `setItem(key,value)` : used to store data to storage
   - `getItem(key)` : used to get value from storage
   - `removeItem(key)` : used to remove item from storage
   - `clear` : used to clear the storage
 - Session storage :

### WORKING OF BROWSER IN JS RUNTIME ENVIROMENT
  - JS engines : It handles JS execution and converts JS code into a code which is understable by the browser engines
    - Call stack : used to keep track of currently executing functions make sure each one finishes before moving to next, Only one call stack is in JS engine that is why it is known as single threaded programming.
        - can handle 2 types of functions : 
          - Synchronous Functions : Functions execution without a delay.
          - Asynchornous Functions : Functions execution with delay.
            - callback functions : The callback functions goes into the `task queue` or `Macro task queue`
            - web APIs : are stored in `micro tast queue`,Its a `Prrority queue`
    - Event Loop : manages the flow of the code, ensures the Asyncronous operations and user intraction smoothly.
    - Heap : storage for variables and objects in JS

### Asyncornous function call in JS : 
  - Call back function : Nested functions leads to call back hell.they dont give any response.
  - Promise :  Used to resolve an asynchronous function and it will definitly give a result/response
    - There are 2 states :
      - Resolved State : used to resolve asynchronous function call which will return a response then that state of promise is known as Resolves State, `then method`
      - Reject State : Used if asynchronous function call return nothing after making call that is known as reject state. `catch method`

      - Asycn-Await : To write promise much more eaiser, to avoid call back functions. if a function is asynchronous then only we can use await inside a function
       - Async : makes a function return a promise
       - Await : makes a function to wait for a promise
      

### API(Application Programming Interface)
 Used to communicate between applications through internet.
  - Socket (Web chatting)
  - REST/SOAP : Client-server communication
  - GRAPHQL
 API testing Tool
  - Postman
  - thunder Client : extention of VScode  

### URL(Universal Resourse Locator)
  - eg : https://getbootstrap.com/identifier
   - Base URL : https://getbootstrap.com
   - URI : Universal Resourse Identifier, eg : identifier
   - Path Parameter : Number associated with URI 
  - ex : https://www.google.com/search?q=luminar
   - Query Parameter : are values which comes after `?` in URL

### HTTP (Hyper Text Transfer Protocol)
 Used to allow application to make request-response via internet.
 - HTTP request : client application will make a request to server.
    - 2 parts : 
      - Header : used to keep secret data
      - Body : used to hold data (Binary/XML/JSON...) to be transfer from the client.
    - HTTp methods :
      - `GET` : get or read data
      - `POST` : create or store data
      - `PATCH` : used to update data partially
      - `PUT` : update data completely
      - `DELETE` : remove data
 - HTTP response : Upon the request the server application provide response to client.
  - HTTP status code : to get response status of request browser is using HTTP response status code
    - 1XX : Informational Error
    - 2XX : Success
    - 3XX : Redirecting Error
    - 4XX : Client Error
    - 5XX : server Error

### JSON (Java Script Object Notation)
  its a Data format used to transfer data from one application to another using internet.
   - Data are saved as Key - value pairs, The 'key' must be always be string
   - eg : "password" : "abc123", "age" : 32

### API call in JS
AJAX (Asyncronous Javascript and XML) : Method to make API calls using JS
 1) API call using `XMLHTTPrequest` or `XHR`
   - XMLHTTPrequest class has pre-defined methods and properties to make sending request and response between application in internet
   - Object of XMLHTTPrequest used to intract with server applications
   - XMLHTTPrequest Class property : 
     - Ready state : returns a number which indicate the state of a request, If the ready state == 4 then request recieve the response
     - responseText : Return a string that contain the response to the request as text.
     - status : which will return response code
   - XMLHTTPrequest Class Methods : 
     - open() :initialize/create APi request
     - sent() : sent an API request
   - Event : 
     - onreadystatechange : event to occur whenever the value of the ready state changes
   - Steps to make API call : 
     - create an object for XMLHTTPrequest class
     - Initiate the request using open method
     - send request
 2) API call using fetch API : 
  - fetch() returns a promise, the resolved response will get from `then method`, reject response get from `catch method`

  - JS module : used to transfer data from one js file to another 
    - Export statements : used to share data from a js file to another, can be used in 2 types.
      - using export default keyword : this keyword must be at the end of the file.
      - using export keyword : used to export multiple data from a js file to another. 
    - Import statements : used to use the exported data from another js file.
      - with curly braces : if data exported using `export keyword` 
      - without curly braces : If data exported using `export default keyword`


# React
 Its an Advanced Application Library
  ## Basic Concepts of React :
   - React app is a collection of different libraries
   - React app consist of different components, which are used to display contents in browser. In react app, all components are arranged in a tree structure.
   - Pure JS functions are used to build components, It returns how to display contents in browser. pure functions are functions which are capable of doing only  one task with help of its arguement. Functions without side effects.
   - Declarative approach
   - React uses `virtual DOM` : Light Weight memory representation of real DOM.
   - Babel Library : used to display contents in browser.

   - `JSX`(JavaScript XML) : JS extention for writing HTML code in JavaScript, Its used to display contents in browser.
      - JSX element : eg - `const heading = <h1> Heading1 </h1>`
      - Rules for using JSX
        - Every JSX element be inside a single Tag. Parent tag can only be a container tag (div, article, section) or react fragment (`<> </>`)
        - In JSX we use camelCase to write contents : eg - `fontSize`.
        - Every JSX tag must has a closing tag. If it has contents, then : `<starting tag>` content `</closing tag>`, If there is no content : `<starting tag> </closing tag>` or we can also use self closing tag (`<starting tags/>`) as well
         - Instead of atribute class we use `className` in JSX
         - Instead of attribute `for` we use `htmljsx` in JSX
         - In JSX can directly pass JS code inside a curly braces, eg: {js code}

  ## React app creation

   - CRA ( using create-react-app command)
   - Installing vite globally : tool for building web application.
    - `npm i -g create-vite`
    - React app creation using vite : `npm create vite@latest` or `npm create vite@latest reactAppName template react`
    - to generate `build` folder to deploy using netlify : `npm run build`

   - File and folder structure of react app using vite
     - package.json file : npm configuration file for the project
     - package-lock.json file : used to hold version of depended package of the project.
     - node_modules folder : used to locally store dependent package of project, we can generate node_modules folder with the help of npm install.
     - public folder :  used to hold data that can be acceses by any part of the project.
     - index.html :  which is an entry point of react application, react app will display in index.html file
     - src folder : logic of react app is defined.
       - main.jsx file : used to render (display in browser) react app in html element with id as `root`
         - createRoot() : lets the user to create root to display react component inside a browser DOM node. 
       - css file : used to define style for all components in react app.
       - App.jsx file : used to create react root component
       - assets folder : used to hold media files used in react project.
       
  ## Components 
   Used to display content in browser, to create a component js/jsx file with file name starts with capital letter.
   - There are 2 ways to create components
     - `Function based component/stateless components` : uses js pure function to build component, Function name must be similar to its file name, This function returns a jsx code.
     - `Class based components/stateful components`: Uses classes to create components, class inherit react component class. render method in class used to return jsx.
        - To create state it has to call super method in its constructor to get its parent features, this state is an object where we can store key-value pairs. To upadte the state use a pre-defined `setState()` which will pass its arguments as updated value of state.

  ### Life Cycle of Component 
    - Mounting Phase : putting jsx into DOM
      - `Constructor()`
      - `getDerivedStateFromProps()`
      - `render()`
      - `componentDidMount()`
    - Updating Phase : When component get updated
      - `getDerivedStateFromProps()`
      - `shouldComponentUpdate()` : This returns a boolean value
      - `render()`
      - `getSnapShotBeforeUpdate()`
      - `componentDidUpdate()`
    - Unmounting Phase : Removing a component from DOM
      - `componentWillUnmount()`

  ### Difference Class based and Function based components

  class based components                                                    Functional component
  using class to create, render method return jsx code.                     using js pure functions,returns jsx code.
  Stateful component.                                                       Stateless component.
  Hooks are not used                                                        Hooks are used.
  need Constructor to initialize a state.                                   No need of Constructor.
  Life Cycle methods are available in class componets.                      Life cycle methods are not available.

  ## Data sharing between React Components
   - Data can be shared from parent to child : use `props` object

  ## props
  - Its a property of a component. It is an `object` used to transfer data from parent component to child component, Parent data can be shared via child tag attribute. To access parent data in child we have to use `props` . `props` used in child component funtion argument.

  ## Conditional Rendering
    - Used based on certain condition. Rendering jsx element in browser, using `if-else` statement (Ternary Operator ?:) / `if` statment (Truthy Operator &&)

  ## List in React
    - Use map array method . set attribute to duplicate JSX element in a list 

  ## CSS styling in React

    - Different ways to apply css in jsx
      - Inline CSS : using style attribute to apply style to jsx element, style must be a js object
        - syntax : `style = {{css-property : value}}`
      - External CSS : Define css style in an external css file, link css file to component file using import statement. We cannot import css file into variable in component file
        - eg : `import "/file.css" `
      - CSS module file : File with extentsion ,module .css is known as  css `module file` , In this we have to define style in class. To use module css file we hae to import it to component file. 
        - import variableName from `module css file path`, apply style in component, we can use variableName.className

      - Important CSS styling react component Library
        - `Material UI` : `npm install @mui/material @emotion/react @emotion/styled`
      - React Bootstrap : `npm install react-bootstrap bootstrap`, Choose bootstrap theme inorder to apply bootstrap properly in react project. Use `https://bootswatch.com/` for selecting theme. Download `bootstrap.min.css` file of the theme and add that file inside project src folder. 
  
  ## Event Handling in React
    - syntax : event = {function call}
    - Binding function without argument : event = {functionName}
    - Binding function argumenets : event = {() => functionName(argument)}
    - Binding Function with arguments as events : event = {(event) => functioanName(event)}

  ## State in React 
   - Used to store data of a component. When state value changes component will rerender

  ## Hooks in React
   - Predefined Methods in react , Used to provide react component features to functional components
      - RULES to Call hooks in functional component
        - Import `hook` in component file.
        - To use hook component call the hook in top level of the component
        - Hook cannot be conditional
      - Based on features there are different hooks available.
        - `Build in hooks`
          - `useState(initial Value)` : used to craete state in functional component, This hook will return an array of 2 arguments, First one is state, Second argumenets is a function to update state, The state updating function name should start with `set`.

          - `useEffect()` : used to apply side-effect to the functional component. we can pass side-effect in its first arguments as call back function, we can also pass optional dependency argument to decide when to apply side-effects in component.Second Argument should be written inside `[]` (Mainly use to perform another task since Js is a pure fuction and cannot do other task)

          ```
            useEffect(()=>{
                setTimeout(()=>{
                setCount(count+1)
              },1000)
            },[count])
          
          ```

          - `userRef(initial value)` : is a hook that lets you reference a value thats not needed fo rendering. Initialvalue is optional in useRef hook. It returns an objet with `current` key 

        - `Custom hooks` : create a js file to define a specific function for a special task. Then we can export the function from the file. The function name must start with `use` keyword.

  ## Form Handling in React
    There are 2 ways to manage data inside the form by a component
    - Controlled Component :  components which store form data inside its own state
    - Uncontrolled Components : components who access form data using its DOM elements reference. 

  
  ## Set up path/url fr component in react
     Use package `react-router-dom`
     - install : `npm i react-router-dom`
     - steps to set up path/url for component
       1) Render the entire react app inside the `browserRouter` component of react-router-dom library, provide this step inside main.jsx file.
       2) Inorder to set up path for component, make sure each component must be inside `Routes` component of react-route-dom library, provide this step inside `App.jsx` file
       3) To set uop path for component, use `Route` component of react-route-dom library, route component has attribute like `path` adn `element` inorder to route for component. All route components must be inside `Route` component


       `<Link> </Link>` can be used to switch to different webpages within the webpage. (Anchor tag is used to move to a different website outside our project eg: youtuve video links)

  ## Higher Order COmponent(HOC)
      Components whose props are another component, eg : Route Component