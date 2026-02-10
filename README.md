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
    


   ## HTML AND CSS: 

   #### Semantic Elements : 
       - Semantic element : 
       <header> -> important top content
       <footer> -> supporting inforation
       <section> -> used to group related content together that forms a logical section on page.
       <article> -> main independent content 
       <nav> -> navigation link 
       <main> -> tells users where main content starts
       - they improve **SEO, accessibility, and code readability.**
       - SEO ( Search Engine Optimization) 
       - Semantic elements help search engines understand the structure and importance of content on a page. 
       - It make website more usable for screen reader and assistive technologies
       - code self - explanatory and easier to understand for developers. 

  #### Session Storage : 
        - Stores data temporarily in the browser **for a single tab/ session.**
        - Data is stored as **key value pairs**
        - Data is available **only in the current browser tab**
        - Data is cleared **automatically when the tab is closed**
        - Maximum size is around **5-10 MB**
        - Example: sessionStorage.setItem("user", "me");
                  sessionStorage.getItem("user");
                  sessionStorage.removeItem("user");

  #### Comparison Local vs Session Storage: 
                                      **localStorage**                **sessionStorage**
        - Lifetime :                    Permanent                          Temporary
        - Scope :                  All Tabs, Shared btw windows     current tab, per-tab isolation
        - Size limit:                    5-10 MB                            5-10 MB
        - Data format :                 String(key value pairs)          String(key value pairs)
        - Page Refresh :               DAta Stays                        DAta Stays
        - accessible via JS:           yes                                  yes
        - Performance:               block operation, snyc              block operation, snyc

  ####  Inline vs Inline Block vs Block : 

          - Inline: No width/ height ( <span>)
          -  Block : Takes full width ( <div> ) 
          -  Inline- block : Width/ height allowed but stays inline 

  ####  Positioning : 

          - position: relative -> element stay in normal document flow. moves top/ right/ bottom/ left. spac is still reserved for the element. ex: small shifts, container setup. 
          - position: absolute -> Element is removed from normal document flow. positioned relative to the nearest positioned ancestor. if no ancestor means positioned relative to the viewport.  ex: tooltips, dropdowns, icons/badges inside cards. 
          
                  
       
       
