## History
 >- 1995 couple of guy started company Netscape navigator 
 >- first browser in the market in that time Microsoft & apple in demand
 >- Netscape is very costly 
 >- Microsoft noticed as a Netscape becoming very big company they want to buy it but Netscape denied its offer
 >- Microsoft make the internet explorer and launch it as free to use
 >- sun microsystem and Netscape came together and deal to beat Microsoft 
 >- Netscape developer Brendan lee develop scripting language javascript firstly named mocha in the year 1992
 >- in the year 1996 Netscape bankrupt they decided to give ECMA 
 >- the javaScript official name is ECMA
 >- all companies collaborate and follow ECMA to get all unique features.
 >- ECMA 3 and ECMA 4 was developed in 8 years and having some political reasons they never     release 
 >- ECMA 3.1 decided it's ok  and its release as ECMA 5 in the year 2009
 >- in the year 2015 feature updated in ECMA 6

## Tech Debt(which never solve anymore)
  - `+` operator - concate and  addition 
  - `===` - equlity check
  - `null` - type of null is object 

### Control Statement 
  - if else
  - for loop
  - switch case 
  - while 
  - do while
### Operator 
  - Arithmatic (+,-,*,%,++,--,+=,-=,*=,/=,==,===)
  - Logical
  - Bitwise
  - Ternary
  - Relation

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

### Variable
 - JavaScript Variable is dynamic or  loose coupled  typed . it can hold any type of data.it is just placeholder.
`var`-
`let`-
`const`-


### Datatypes
 >datatypes are two types 
 > - Primitive data type
 > - Non-Primitive data type
 - Primitive data types:
     - null        code 
     - undefined   code
     - boolean     code 
     - number      code
     - string      code

- Non-Primitive data type
  - Object represent as [].
  - Array represent as {}.

## Falsy
 - false is always falsy value
 - 
## Truthy - non primitive is always truthy

## Scope 
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
### Function
- Introduction 
  > the function is a set of rules to perform some specific task
  > the function behaves exactly like variable behavior in ES5
  > you can override the same function 
  > the function can call before it declares 


                 
















        
