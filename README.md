# Levels of Abstraction in Programming Languages:

Programming languages can be categorized based on their level of abstraction, which defines how closely the language aligns with machine code and hardware architecture. These levels of abstraction include:

**Low-Level Languages:**
These languages are closer to machine code and directly correspond to the hardware architecture.

**Examples include Assembly language.**

**Mid-Level Languages:**
Mid-level languages provide a balance between high-level and low-level languages.
They offer some level of abstraction from hardware specifics while still allowing fine-grained control over system resources.

**Examples include C and C++.**

**High-Level Languages:**
These languages provide a high level of abstraction from the hardware details, focusing more on problem-solving and algorithm implementation.
They are closer to human language and are easier to understand and use.

**Examples include Python, Java, JavaScript, and Ruby.**

Abstraction: Internal Working - how its done rather than what we do

  **eg:** saving a file with Notepad 
      Here we dont know how its saving the file in memory or what form will it be in inside memory etc.

**Compiler:** Completes the conversion to machine code.
        1. Converts the high level code into low level (0's and 1's)
        2. Its faster
        3. Collects the error and displays at the very end
        4. Memory requirement is more

    **Ex:** C Compiler
    
**Interpreter:** Converts line by line to machine code.
        1. Converts the high level code into low level (0's and 1's)
        2. Its slower comparitively
        3. If any error in instruction, it stops and displays then and there
        4. Memory requirement is less

   ** Ex:** BASIC

Programming Paradigms:

 * Imperative - ex: java, c#
 * Declarative - ex: Miranda, Erlang, Haskell, Prolog

` **refer:** https://media.licdn.com/dms/image/C4E12AQGFcNgWwdKEBw/article-inline_image-shrink_1500_2232/0/1583152646078?e=1715817600&v=beta&t=Ok6ZQ0GMadqUjQ7K0etsrM14ET3eu1o6-XNuGPyGljg `


**Object-Oriented:** Examples include Java, C#, etc.

  **Java:**  Not purely object-oriented due to usage of primitive data types (value types) such as int, float, char, boolean, etc. Example of objects: mobile - consisting of screen, buttons, IC chips with attributes.

**Pure object Oriented :**     ex: python

**Partially Object-Oriented:**  ex: C++

Can a C program run in a C++ environment? Yes.

**Reason:**
+ C++ was developed as an extension of C, adding object-oriented features while maintaining backward compatibility with C.
+ Because of this a c program can be saved in .cc extension and can run int C++ environment where it breaks the principle of Object Oriented Core Principles as everything must be in form of class and object only

**Class:**
* Collection of  objects.
* Blueprint.
* Collection common methods or behaviours and attributes shared by all objects
  
**Object: **Instance (representation/example) of a class. Real-world entity, tangible thing.

Example:

**Class Food**
**Objects:** biriyani, dosa.

**Class** : **Bird**
**Objects:** dove, peacock, pigeon, hummingbird.

**Methods/Functions/Behaviours (Actions):**
fly()
lands()

**Attributes/Properties/Variables:**
feathers
beak
eyes
legs


```
**EXAMPLE:**

class Student {
    // Properties/Attributes/Variables
    student ID
    student name
    course
    year
    
    // Methods/Behaviours
    Study()
    read()
    write()
    play()
}
```
### DAY 2

**Title**: Understanding Object-Oriented Concepts through Real-world Examples

**1. Introduction to Objects:**

Objects are real-world entities characterized by physical existence and tangibility.
Attributes define the characteristics of an object, with each attribute holding different values.
2. Understanding Objects through Examples:

**2.1. Student Object:**
**Attributes**: name, course, year, id.
The id uniquely identifies objects of the same class.
**Methods** (Behaviors): study(), writeExam().

Attributes are referred to as state due to their ability to change over time, akin to the change of state in matter.

**2.2. Book Object (Online Book Store):**

**Attributes**: name, no.of.pages, author, edition, qty, available.
**Methods**: purchase().

**2.2. Book Object (Online Book Store):**

**Attributes**:

**Name: "Java 8"
Number of Pages: 300
Author: "ABC"
Edition: 2nd
Quantity: 3
Availability: Yes**

**Methods:**

purchase():
Action: Represents the process of buying a book from the online store.

**Functionality:**
Decreases the quantity of the book by 1.
Updates the availability status accordingly.

**Illustration of Purchase Transactions:**

Initial State:

Quantity: 3
Availability: Yes
User A Buys 1 Book:

Action: User A purchases 1 copy of the book.
Result:
Quantity Decreased: 2
Availability: Yes (Still available)
User B Buys 1 Book:

Action: User B purchases 1 copy of the book.

Result:
Quantity Decreased: 1
Availability: Yes (Still available)

**User C Buys Last Book:**

Action: User C purchases the last available copy of the book.
Result:
**Quantity Decreased: 0
Availability: No (Book out of stock)**

**Conclusion:**
Through the process of purchasing, the quantity of the book decreases until it is no longer available for purchase, demonstrating the change in state of the book object.

**2.3. TV Object:**

Attributes: LED, status, volume, channelNum, ChName, input mode.
Methods: on(), off(), incVol(), decVol(), idle().
Demonstrating state changes through TV operations.

**3. Object-Oriented Principles:**

**3.1. Encapsulation:**

Hiding internal state and requiring all interaction to be performed through an object's methods.
Example: Private class encapsulating variables and methods, objects 

**3.2. Abstraction:**
Presenting only the essential features of an object to the outside world, hiding implementation details.
Example: Abstraction in file content through interfaces like NotePad.

**4. Application of Object-Oriented Concepts:**
**4.1. ATM Machine:**

Logic for withdraw() and deposit() hidden, while user interacts through UI buttons.

**4.2. Notepad Interface:**
Interface providing a view with methods like save(), open(), new().
 Windows OS:
Complex logic encapsulated within the operating system, abstracting details from users.

**5. Conclusion:**
Understanding objects through real-world examples helps grasp fundamental object-oriented concepts.
Encapsulation and abstraction play pivotal roles in organizing and managing complex systems effectively.


**Day3**

**Day 4**

### Java Source Code Standardization

**1. Naming Conventions:**

**Class Name and File Name:** Should be identical.
**Class Naming**: Capitalize the first letter, follow Upper Camel Case (for multi-word class names).
**Variables**: Lowercase, follow Lower Camel Case (for multi-word variable names).
**Constants**: Completely uppercase, separated by underscores for readability.

**2. Single Class per File:**
Keep only one class per Java file to maintain clarity and organization.
Every change in the source code should reflect in the output, necessitating recompilation.

**3. Variables:**
**Definition:** Variables represent data that can vary during program execution.
**Naming:** Use meaningful names reflecting the data they hold.
**Convention:** Lowercase for variables, with multi-word names following lower camel case.
**Example:** int age;
**Example:** String employeeName;

**4. Constants:**
**Definition:** Constants are values that do not change during program execution.
Naming: Completely uppercase, with underscores separating words for clarity.
Example: final double PI = 3.14159;
Example: final int NO_DAYS = 7;
5. Data Types:

**Definition:** Data types specify the type of data a variable can hold and the operations that can be performed on it.
Examples of Data Types:
Integer: int, short, byte, long
Floating-point: float, double
Character: char
Boolean: boolean

**6. Literals:**
![image](https://github.com/kathirkathir2006/EG-Java-FSD-Demo/assets/17041355/7c9ba6d8-0e43-4948-a6a0-5e341225a2aa)

**Definition:** Literals are constant values assigned to variables directly in the code.
**Examples of Literals:**
**Integer Literal:** int x = 10;
**Floating-point Literal:** double y = 3.14;
**Character Literal:** char ch = 'A';
**String Literal:** String name = "John";
**Boolean Literal:** boolean flag = true;

**7. Memory Management:**

**Memory Address:** Each variable is stored in a memory location identified by its memory address.
**Variable Name:** Assigned to memory addresses to facilitate easy data retrieval.
**Example:** int age; - Here, age is the variable name assigned to hold an integer value.

**Conclusion:**
Adhering to standardized naming conventions and coding practices ensures readability, maintainability, and consistency across Java source code files. Following these conventions also aids in efficient memory management and reduces the likelihood of errors during compilation and execution. Additionally, understanding literals facilitates direct assignment of values to variables, enhancing code clarity and conciseness.

**Day 5:**

### Operators:

 Operators are fundamental elements in programming languages, serving to manipulate data in various ways. Here's an organized overview:

**Operand**: The data on which operators act.
**Operators**: Symbols that perform operations on operands.

**Operands and Operators:**
int operand1 = 10; // Operand
int operand2 = 5; // Operand
int result = operand1 + operand2; // Operator (+) acting on operands
System.out.println("Result of addition: " + result); // Output: Result of addition: 15

**Arithmetic Operators:**

**+: Addition.**

String-> not a datatype => its an Object
String str="hello"; //will be converted to object (implicitly)
//because of internal architecture

**Example**: 10 + 10 = 20
"hi" + " world" concatenates strings: "hi world"
10 + 8 + "hi" + 9 results in "18hi9" due to string concatenation.

**-:** **Subtraction**,  **'*': Multiplication.**

**/: Division.**

**Example**: 9 / 3 = 3 (quotient)
2.5 / 2 = 1.25

**%: Modulus (remainder).**

**Example** : 9 % 3 = 0
2.5 % 2 = 0

		
**assignment optr : '='**
	is to assign value to a variable which is 	declared/defined
	always declare/define variables which will be used 	intside the code
	
**declaration:** 
		int a,b,c; 
**initialization:**
		int a=90; //90 is assign(=)ed to variable a
	
**+= -> compound assignment optr** => 	more than one optr is compound
	*=
	/=
 
**eg:**
	int a=0;
	a+=2   //a=a+2;
	sop(a); //2 

	int b=2;
	b*=2  //b=b*2;
	sop(b) //4

**increment/ decrement optr**
	
	++ means = > add 1 => +1
	a++ => post-incr => a=a+1
	
	++a => pre-incr=> a=a+1

int i=1;
sop(i);
i++;
sop(i);
 ===============================================
**NOTE :** refer demo for remaining

**Seminar**
logical optr - 5 min
======================
&& - and - madan
! - not - sai
|| - or  - venkat
===============================================
**Day 5:**

sequence Structures
repetition Structures
selection Structures

control - condition/criteria

if
if..else
else..if
nested if

Looping:

arduino
Copy code
for
while
do...while
enhanced for loop
selection
switch

unconditional statements:

continue;
break;
return;

if:
if(condn) //outcome of condn => T or F
{
//grp stmts
}

scss
Copy code
if(condn)
	//one stmt alone
condn can be T or F, if True below block of code or statement will get executed

you can't write integer value in the place of condition, it requires only boolean value or expression that gives boolean as o/p

if true and u need group of statements to be executed use block - {} -in the if part or inthe else part

else will never ever have (), only if has
in else if() - here only if has it

System.out.println(2>1); // True
System.out.println(4<10); // True
System.out.println(4+10); // 14 // here expression gives int value, not boolean

As much as possible use conditional optrs to get boolean outcomes in if

logical optr -

r
Copy code
&& - and
	a>b && a>c  ----- T and T = T
			  T and F = F
			  F and T = F	 
			  F and F = F
|| - or
	a>b || a>c  ----- T or T = T
			  T or F = T
			  F or T = T
			  F or F = F
Looping:
int keys=10; // how many times u ll test --->10

vbnet
Copy code
how many times - finite times -

when we know no of execution - finite loops

	eg: for loop or enhanced for

when we know don't know no of execution - infinite loops

	eg: while or do while loop
for loop:

sql
Copy code
for(initilization;test/condn;incr or decr)
{
	//block of statements	
}

//10 times - start=0  end point =9
//10 times - start=1  end point =10
	for(int i=0;i<10;i++)
{
	System.out.println("hi");
}

i++ will not be executed for the 1st time
initialization and condn will be executed for the first time


