# Interview-Questions
All the basics and advance questions of Frontend including HTML, CSS, JS and REACT 

## JAVASCRIPT: 

#### A Dynamically typed Language or a Statically typed language: 
  - JS is a dynamically typed language.
  - means all type checks are done at run time ( when program is executing).
  - So, we can just assign anything to the variable and it works fine.
    let a;
    a= 0;
    console.log(a); // 0
    a= "Hello"
    console.log(a) // "Hello"

    - TypeScript is a statically typed language. All checks are performed at compile time.
   
  #### Different datatypes in Javascript:
      - Primitive datatype : String, number,boolean, null, undefined, Bigint, symbol
      - Non-Primitive datatype : Object, Array, Date

  #### Hoisting: 
      - Scripting/Server side language, variables or functions must be declared beforeusing it. 
      - In javascript, variables and functions can be used before declaring it. The javascript             compiler moves all the declarations of variables and functions on top. so there will             not be any error. This is called hoisting. 

  #### Temporal dead zone : 
      - It is a specific time period in the execution of js code where the variables declared             with let and const exists but cannot be accessed until the value is assigned. 
      - Any attempt to access them result in reference errors. 

  #### Differences let, var and const : 
    SCOPE:
      - Variables declared with var are function scoped. ( available through out the function             where its declared ) or global scoped ( if defined outside the function). 
      - Variable declared with let and const are block scoped. 
    REASSIGNMENT : 
      - var and let can be reassigned. 
      - const cannot be reassigned. 

    HOISTING : 
      - var gets hoisted and initialized with undefined. 
      - let and const- get hoisted to the top of the scope but does not get assigned any value. 
      (temporal dead zone)

  #### FEATURES OF ES6 : 
      -  Arrow functions
      -  Let and Const declarations
      -  Destructuring assignment 
      -  Default parameters
      -  Template literals
      -  Spread and Rest operators
      -  Promises
      -  Modules
      -  Map, set, Weakmap, Weakset 

  ####  Limitations of Arrow functions in Javascription :
      -  Arrow functions cannot be accessed before initialization.
      -  Arrow function does not have access to arguments object. 
      -  Arrow function does not have their own this. instead, they inherit this from the                surroinding code at the time the function is defined.
      -  Arrow functions cannot be used as constructors. Using them with the new keyword to              create instances throws a TypeError.
      -  Arrow functions cannot be used as generator functions. 

      NOTE: Arrow functions + this combination  
    
   
