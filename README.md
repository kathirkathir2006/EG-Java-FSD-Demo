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
