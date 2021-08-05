## History
 >- In year 1995
 >- Designed by Brendon in 3 weaks
 >- Earlier named as Mocha
 >- the javaScript official name is ECMA
 >- all companies collaborate and follow ECMA to get all unique features.
 >- ECMA 3 and ECMA 4 was developed in 8 years and having some political reasons they never  release 
 >- ECMA 3.1 decided it's ok  and its release as ECMA 5 in the year 2009
 >- in the year 2015 feature updated in ECMA 6

## Tech Debt(which never solve anymore)
  - `+` 
    >- Acts as concat and add depending on variable type
    >- Always do concat when the one of the variable is string type
  - `===` - equlity check/type check
  - `null` - Missed if check for null type ,returns a type of object 

### Control Statement 
  - if else
  - for loop
  - switch case 
  - while 
  - do while
### Operator 
  - Arithmatic (+,-,*,%,++,--,+=,-=,*=,/=,==,===)
  - Logical (&& , || ,!)
  - Bitwise(&,|,^,~,>>,<<,>>>)
  - Ternary(?,:)
  - Relational(<=,>=,==,!=)

### Logical Operator 
  - `&&` 
    - true && false =false
    - false && false =false
    - false && true =false
    - true && true  =true       
        
  - `||`
    - false || true = true
    - true || false = true
    - true || true = true
    - false || false = false

## Variable
 - JavaScript Variable is dynamic or  loose coupled  typed . it can hold any type of data.it is just placeholder.
 - ES5-
    - var
      - re-declare 
      - re-initialize
      - hoisted
      - local variable overrides the global declara
      - tion 
        - functional scope 
        - global scope 
  - ES6
   - `let`
     - > can not be re-declared but can be re-assigned
   - `const`
     - > can not be re-declared but can not be re-assigned
   - `featurs`
     - >lexical /block scope 
     - >no hoisting 
     - >lexical scope variable overrides the parents lexical,functional local or global.



### Datatypes
 >datatypes are two types 
 > - Primitive data type
 > - Non-Primitive data type
 - Primitive data types:
     - null        
     - undefined   
     - boolean      
     - number      
     - string      

- Non-Primitive data type
  - Object represent as [].
  - Array represent as {}.

### Scope 
  - local scope -
  - global scope -
  - Functional scope - limits to the function
  - Lexical scope - starts with curly bracase 

>Diference between lexical scope & function scope
 - lexical scope is always part of functional scope.
 - both functional & lexical have there own local and global scope 

Copy By Value(primitive) 
copy by value best example is `xerox copy`
```    
    var local=14;
    remote=local;
    local=20;
    console.log(local);
    o/p
    14
```
 

### Copy By Reference(non-primitive)
> copy by reference exaple is Debit card,googl doc
> means when the any reference changes all one changed

  

- var a=5
- var b={}         
  ```                
         var a-----[5 ][ ][  ][ *  ][ ][ ] 
                                |
                               b|---[ ][ ][ ][ ][ ]```
 
if we storing in variable in non primitive they make second memory location
 
## Function
- Introduction 
  > the function is a set of rules to perform some specific task
  > the function behaves exactly like variable behavior in ES5
  > you can override the same function 
  > the function can call before it declares 

### Features
 > function is kind of object 
 > function is first class citizen in javaScript
 > function can use in two way
   - Assignment
      ``` 
      var doask =function(){
         console.log("print");
         
   - Declaration
      ```
      function doask(){
         console.log("print");
         
 > it can assign variable
 > function can pass array 
 > function act as a object 
 > function can scope another function
 > function can return another function
 > it can act as constructor
 > in other language we can say class
 > it can hoisted

### Higher Order function
 - Funtion returning a funtion 
 - Function passess a parameter
 > any function which takes function as a parameter and returns function from a function
 ``` 
      function add(a,b){
      const c=a+b;
        return c;
          }
       function operate(operation){
        let localfn;
       if (operation && (typeof operation ==="function")){
          localfn=operation;
               }
       else
          localfn=function()
          {
          }
       console.log("operate=>" typeof localfn,location);
          return localfn;
            }
           const executefn=operate(print);
           console.log("executefn=>" typeof executefn,executefn);
           var d=executefn(1,3);
           console.log(d);
   ```
    
### Pure function
 - > it is a function where i pass value it returns always same values.
 
### IIFE(Immediately Invoked Function Expression )
 - > second name "self executing function expression(SEF)
 - > JavaScript does not have any private method like other languages
 - > JavaScript by default started
 `
 so they created a new way so function can act as a priavte method that way they
 implemented function called IIFE
 
 var outside =(function(userid){
               console.log("initialization");
               function hello(value){
               console.log("print" value,userid);
               }
               return hello
               })(30)
  
 ` 
### Arrow function 
 - > it is always function expression or function assignment .
   > it can't be function declaration because function declaration always need a function keyword it can't be hoisted
 `
 var b=()=>{
 console.log("hii");
 }
 b();
 
 `
## Arrays 
- > arrays are special varaible .which having capacity to different values
- Length of array
  - last index plus one 
-### crreate an array
- `
     var name =["sushil","arun","jyoti","shiv"]
 `
 - built-in functions
   - push
     `
        adds end of an  array
     `
   - pop
      `
        removes items from an aaray
     `
   - unShift
       `
        adds items beginning of an array
       `
   - shift
        `
        remove item beginning of an array
     `
   - concat 
       `
          for add two different array
       `
   - 
     
## Object
- object is non primitive data type 
- creating object
  -1 `
      key-value pair
      var a={first:"sushil",secong:"arun",third:"jyoti"};

     `
  - 2 `
          new
          
          var n1=new object();
       `





                 
















        
