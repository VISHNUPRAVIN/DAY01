Difference between HTTP/1.1 and HTTP/2 are:

         HTTP/1.1                                                  HTTP/2

* Ithe usest works on the textual format.                    * It works on the binary protocol.

* There is head of line blocking that blocks all             * It allows multiplexing so one TCP connection       
  the requests behind it until it doesn’t get its              is required for multiple requests.              
  all resources.                                            

* It uses requests resource Inlining for use                 * It uses PUSH frame by server that collects all multiple pages.
  getting multiple pages.

* It compresses data by itself.                              * It uses HPACK for data compression.    


Objects and its internal representation in Javascript

Object:
 In JavaScript, an object is a standalone entity, with properties and type.
 Compare it with a cup, for example. A cup is an object, with properties.
 A cup has a color, a design, weight, a material it is made of, etc. The same way, 
 JavaScript objects can have properties, which define their characteristics.

Creating Objects in JavaScript:
By object literal
By creating instance of Object directly (using new keyword)
By object literal:

The syntax of creating object using object literal is given below:

object={property1:value1,property2:value2,propertyN:valueN}

Property and value is separated by colon(:).

Example:
   
   var person={
 
    firstname="xxxx";
     lastname="yyyy";
          age=25
,
     };
 By creating instance of Object directly (using new keyword):
 The syntax of creating object directly is given below:
            
           var objectname=new object();

Here, new keyword is used to create object.
 
      Example:
      var emp=new object()

          emp.id="xxx";

          emp.name="yyyy";
   
       emp.salary=50000,
       
Accessing JavaScript Objects:
The syntax for accessing the property of an object is:

objectName.property

or

objectName[“property”]

Accessing ‘fname’ from example 1 using dot operator,

