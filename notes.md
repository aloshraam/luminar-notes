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
  
 3) API call using axios Library :
  - Axios is a promise-based HTTP Client for node.js and the browser.
  

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
         - In JSX can directly pass JS code inside a curly braces, eg: `{js code}`

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
      - Tailwind-css : `npm install -D tailwindcss postcss autoprefixer`, `npx tailwindcss init -p` , have to do more steps , visit this page : https://tailwindcss.com/docs/guides/vite
  
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

          - `userRef(initial value)` : is a hook that lets you reference a value thats not needed fo rendering. Initialvalue is optional in useRef hook. It returns an objet with `current` key.
          - `useParams()` : hook will return dynamic value of route associated with component.

          - `useNavigate()` : hook used to navigate from one page to another 

        - `Custom hooks()` : create a js file to define a specific function for a special task. Then we can export the function from the file. The function name must start with `use` keyword.



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
     - `Dynammic Routing` : we can set up a dynamic / changing value in a url along `:` symbol, so react app will understand valur along with the `:`  is dynamic part of the url.
     - To set up `page not found` url use path `*`, its path mus t be set up at the end of all URL in react app.


       `<Link> </Link>` can be used to switch to different webpages within the webpage. (Anchor tag is used to move to a different website outside our project eg: youtuve video links)

  ## Higher Order COmponent(HOC)
      Components whose props are another component, eg : Route Component

  ## Axios in react
    - Using Axios Library : insall axios - `npm install axios`
    - To make a HTTP request using axios : axios(config)
      - config : is a predefined objext with keys (method, url, data, headers)
    - HTTP response will always return an object with predefined keys (data(//server response//), status)
    - Create a services folder inside src of your react app

  ## Data Sharing between components in react
    - `State Lifting` :  Data sharing is using props. We will create a state in common parent of data to be shared components, share state upadation function to one component and state to another component.
    - using `REDUX` Library
    - using `Context API`

# Content API
 Data sharing method in react
 - Avoid props drilling while sharing data between components
 - to share data it uses context of react, with the help of context we can share data inside 
 - Steps to perform data sharing using context API
  - Create  a contexy : use `contextMethod()` method in react
  - Use providers of contenxt to share data to the component, `provider` value key will help contenxt to share data, we can pass value as object
  - To access context from component : use  useContext Hook, `useContext(context-name)` we give data shared via context
- Create a `folder for context`
  - inside the folder creact a react component for perform data sharing using Context.
  - create context and export it 
  - use contenxt provider provide the state as its value to the component `children`
  - use the `children` props inside the component of react app inside `main.jsx` file


# JSON server Creation

1) Create a server folder to store json server
2) we have to create a package.json(npm configuration file) file inside server folder : use command -  `npm init -y `
3) Install json server package in server folder to run json file, use commmand to insall json-server : `npm i json-server` | to get a stable server use `npm i json-server@0.17.4`
4) Create json(db.json) file for storing project data
5) To run json file and available in browser port use command in server folder : `npx json-server db.json`


# JSON server Deployment using NODE.js

1) Create a index.js file inside the server folder
2) Update scripts key of `package.json` file with `{"start": "node index.js"}` and remove `test` key from it
3) Create a `.gitignore` File to add node_modules.
4) Define steps to run db.json file using json-server in index.js
    - import json-server
    - create a server for media player app inorder to run our server app
    - create a middleware to convert json data to js
    - create a port for executing our app
    - set up the path/route of db.json file so that client can make the request
    - use middleware, route inside the server
    - run the server using the given port
    - To execute our app we have to use `node index.js` in terminal, so that we can see the output in localhost:3000


# REDUX - State Management tool
 - Its a Javascript Library for predictable and maintanable global state management
 - Redux consist of 2 packagaes:
    - `React-Redux` : officially reat binding for redux, 
    - `Redux-toolkit` : The official, opinionated, batteries-included toolset for efficient Redux development
 - for installing the packages use these commands : `npm install @reduxjs/toolkit`, `npm install react-redux`

 ## Importanting API used in Redux   
  - `configureStore()` : used to create store for redux.
    - steps to create redux store in react app
       1) create a foldeer `redux`, to define logic in src folder.
       2) Inside redux folder create a `js file` for creating `redux store`
    - To provide store to our react app use `provider` component of react-redux. Give this in `main.jsx`
  -  `createReducer()`: used to create reducer, where we can store updated state inside store.
  - `createAction()` : used to create action where we can define the logic to update the state, output of action automatically return to its reducer
  - `createSlice()` : used to combine action and reducer in a single file. 
    - Steps to create slice for react:
      1) Create a js file for define slice
  - `createAsyncThunk()` : used to make asyncronous call in an action in redux. It accepts 2 arguments, first is ation string(`slicename/actionname`), 2nd argument us a callback function it can retuen promise. It output can be 3 different types.
      - `prending/fulfilled/rejected`
      - `extraReducers` in slice can handle promise return action, because it has designe differnet cases to update slice state, 

 ## Hooks used in component for managing state using redux
  - `useSelector(state=>state.reducer-name)` : used to select state from store in a component
  - `useDispatch()` : used to execute an `action` from a component, Hook will `return a function` that is dispatcing an action in its argument when we call the function
    - action without argument : `dispatch-funtion(actionName())`
    - action with argument : `dispatch-function(actionName(arg1, ar2, ...))`, to access the arguments of action in slice reduce function it uses its second argument which is an object with two keys, `payload` and `type`. payload will give the value from action dispatched by component

# MONGODB - DATABASE
  1) Database used to store and manage data permanently (MySQL, SQL, MsAccess, MongoDB, Oracle,...)
  2) MongoDB : Is a NOSQL Database, data stores as JSON document `({"key" ; value})`, To store multiple json document is known as `collection` 
  3) Difference bewtween SQL and MongoDB 

                                    SQL                                                    MONGODB

                                - Relational SQL DBMS                                  - Document Oriented NoSQL DB

                                - Data Stored in table, every table must have rows     - Data Stored in Collections as JSON document
                                and fixed colums

                                - Uses fixed `schema`                                  - uses dynamic `schema`

                                - Support rich set of data type                        - limited set of datatypes

                                - Uses in traditional buisness app                     - Used in bigdata and real-time Apps

                                - Optimised for complex join and transaction           - Optimized for scalability and performance

  4) MongoDB in the following enviorment
    - MongoDB Atlas : The fully managed service for MongoDB deployments in the cloud
    - MongoDB Enterprice : The subscription-based, self-managed version of MongoDB. 
    - MongoDB Community : The source-available, free-to-use, and self-managed version of MongoDB

  5) MongoDB, mongosh :is a terminal used to write mongodb codes.
  6) `Collection` : used to store JSON documents, to name a collection use small letter in its `plural form`.
  7) MongoDB generate a unique value to identify each document in a collection using` _id `key its value is a `hexadecimal number`
  8) `CRUD Operation performed in MongoDB`
    - TO `get/read single document `from mongoDB collection : use `findOne({key:"value})`
     which return the "entire document" when the key and value is present otherwise , a `null` 
    - To `get/read all documents` from mongoDB collection : use `find()` which returns the all document present in the collection
    - To insert a single document to MongoDB collection : use `insertOne({key : "value"})` 
    - To insert multiple document to MongoDB collection : use `insertMany([{key:value}])`
    - To get the total count of document in a collection : use `countDocuments()`
    - To limit document while getting from a collectio n : use `limit(count)` // use `db.users.find().limit(count)`
    - To skip documents while getting from a collection : use `skip(count)`
    - To sort data while getting from a collection : use `sort({key : 1 : -1})`
    - To get document after applying different query statements use `$` symbol : `$gt`/ `$gte` / `$lt` / `$lte` / `$eq` / `$neq` / `$exists`/ `$regex`
    - To update a single document : `updateOne({key : value}, {$set : {key : value}})` , we can also update statements : `$set , $inc , $push, $pull`
    - To update more than one document : use `updateMany()`
    - To delete one document : `deleteOne : ({key : value})`
    - To delete multiple values : use `deleteMany([key : value])`
  9) `Aggregation` : used to combine/join two collection in mongoDb
     - `$lookup`
        
        - ```{
            $lookup:
              {
                from: <collection to join>,
                localField: <field from the input documents>,
                foreignField: <field from the documents of the "from" collection>,
                as: <output array field>
              }
          }
          ```
  
# SERVER SIDE / BAACK-END 
  Used to resolve client or front end request

  ## Node.js

  - provides aa runtime environment for js outside the browser
   1) its a free open source, open-platform runtime envornment that lets us to create server ( used to resolve ,ultiple client request ), wed apps, command line tools or script.
   2) Features : 
      - Extremly Fast
      - Aynchronous function
      - Highly Scalable
   3) Node js `Global objects` : objects can be shared throughout without importing it, eg : `process` object. `environmental variable` in process used to store system configuration or secret data of an application.
   4) Node js module system : used to share data from one file to another using `CommonJsModule` system.
    - `require(packagename/ filepath)` : to import data from a file/package.
    - `module.exports` / `export keyword` to export data from a file
    - Predefined / build-in modules in node js
      - fs module : To handle file system of a computer
      - HTTP module : used to create HTTP server
      - HTTPS module : used to create HTTPS server 
      - Events Module : used to manage user-defined events
      - crypto module : 
      
   5) `Exection Model` : `Event driven`,` non blockung I/O model`, `optimized asyncronous task`
   6) API Access : System has access to system level API (file system, network, process)
   7) Working of Node.js : used to resolve client resquest and send the response while working single thread.
      - non blocking I/O
      - Asynchronous function 

# Express JS 
 Express is a node js framework used for server creation.
 1) Used in client server application , to create server with node.js features
 2) Steps to create an express server for resolving client request.
  - Create a server folder for server application
  - create `package.json` file inside server folder, use command : `npm init -y`
  - `update` package.json file `script` key value as the following opject, `{"start" : node index.js}` and remove its test key value and from it.
  - install packages needed to create node server app
    - express package: used to create the server - `npm i express`
    - `cors` package : used to enable `cross origin REsource sharing` - `npm i cors`
    - `dotenv` package : used to load content `.env` file into process object - `npm i dotenv`
    - `mongoose` package : used to communicate between node.js app and mongoDB.
    - `jsonwebtoken` : used for authorization.
    - `multer`  : used for handling form-data/multi part data
  - create a `.env` file in server folder, which used to store enviromental variables of a project
  - create a `.gitignore` file in server which is used to store file/folder to be ignored while adding to git
  - Create `index.js` file to define express server for `resolving client request` from browser
      - import express, dotenv, cors in `index.js` file
      - create `express server` using express package
      - use cors in our server-app to enable data sharing between different application.
      - use `express.json()` in server app for passing json data from client request
      - create a port for server app
      - run the server app in specified port 
      - run server application using command : `node index.js`
      - To resolve HTTP request using ` express-server-name.httprequest('path',(req, res)=>{response object share server response to client})` 
    - How to set up path/url for resolving client request in server
      - Create a routes folder in `server folder` and create a `js file` inside routes folder for defing path / route corresponding  to client request.
        - Steps to define path in js file
          - import `express`
          - Create an object for express Router class which is capable of routes in server.
          - export object of express of router class
          - import object of express router class and use router in server application
          - to set up the route syntax  : 
            - `RouterObject.httpRequestMethod("path",controller name)`
    - To set up controller for server app : used to define the logic to resolve client request
      - Create a controller folder in server app, and create a js file inside it for defining logic to resolve client request
      - export rach controller logic from js file
      - import controller in router.js file and use the controller in corresponding request
      - syntax of controller:
        - 
        ```
          controllerName = (request,response) =>{
            using response object share server reponse to client
          }
        ```
    - To set up database connection from nodejs server
       - create a folder for define db connection in server folder
       - inside the folder create js file to define connection steps
         - import mongoose
         - get the db connetion string
         - To connect with MongoDB use connect method of mongoose pass connection string as argument it will return promise
         - import connection js file in index.js
    - To setup model fro communication for communicating node js and mongoDB
      - create model folder in server folder
      - create js file inside the folder for creating model
        - import the mongoose 
        - create schema for model
        - create model using that schema
        - export model
    - To set up Authorization using `Middleware`
      - Create a folder for middleware in that create a js file
      - use middleware in route before controller
    - To handle multipart form data requst using multer
      - create js file inside middleware folder
      - import multer
      - create `upload` folder in server folder fr storing uploadded files.
      - define storage object using diskstorage method of in js file
      - created multer instance using the storage and export it from that file, use it in route.
    - Server has to use `express.static(stattic file / folder path)` to export the static file or folder from server




# MONGOOSE 

Node js package for mongo DB data modelling
1) Mongoose is an ODM(Object Data Modelling) library for MongoDB which helps to create and manage mongoDB documents with nodeJS
2) Install Mongoose in nodeJS app: `npm i mongoose`
3) Schema : A schema defines the structure of your collection documents. A mongoose schema maps directly to a mongoDB collection. To create a scheme  we have to create an object for mongoose `schema` class
4) Models takes our schema and apply it to each docuements in its collection. Create model in mongoose , use model method, syntax : `model("modelName",schema)`
5) In node js application controller will communicate with inorder to manage data in mongoDB.
6) CRUD operations in Mongoose
  - To create a document using mongoose in mongoDB, create an object of model with same order of schema, after that we have to save the object inorder to apprear changes in mongoDB using `save()` method.
  - `GET / read` : `find()` , `findOne()` , `findById()`
  - `Update` a Document : `updateOne()` , `updateMany()`, `findByIdandUpdate(_id of document, update querry)`
  - Delete a document : `deleteOne()` , `deleteMany()` , `findByIdandDelete(_id of document)`
7) `Mongoose query helpers` : `skip()` , `sort()` , `limit()`...

# JSON WEBTOKEN
NodeJS package for autherization (learn autheration and authentication)
1) install jsonWebToken library : `npm i jsonwebtoken`
2) Token generation using jwt : `sign(payload, password)`
    - `payload` : used to store data inside token creation.
3) `Token verify using JWT` : verify(token, password) `return a response if token is verfied else error`

# MIDDLEWARE
 Node js library for authorization
 - Used to controll request: response cycle in server, before resolving a request server can perform any task using (authorization, data fromat changing etc....) using mmiddleware
 - Middleware are function with 3 arguments, they are `request, response, next` . Here request will give you client request, response object will give response from server to client, `next method` used to comtrol the request
 - Middleware can be of `2 types`: 
    - `Application Specific middleware` : middleware will active for all client request.
    - `Router specific middleware` : middleware will active for only selected route/path.

# Multer
Node js middleware for handling multipart/form-data
- Multer is a node.js middleware for handling multipart/form-data, which is primarily used for uploading files.
- Multer adds a body object and a file or files object to the request object. The body object contains the values of the text fields of the form, the file or files object contains the files uploaded via the form.
- intall the `multer` : `npm i multer`
- multer can used to define storage space for uploaded file



