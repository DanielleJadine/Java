# Java
# What is Java?
-Java is a widely-used ,high-level programming language and computing platform developed by Sun Microsystems in 1995 ,which was later acquired by Oracle Corporation.
## Key points 
-Java is object oriented,meaning it organizes software design around data ,or objects rather than functions and logic.
-One of Javas key features is its platform independence ,achieved through the Java Virtual Machine(JVM),and this allows Java programs to run on any device or operating system that has JVM adhering to the "write once,run anywhere "(WORA) principle.
-Javas Syntax is similar to C++ which makes it relatively easy for programmers familiar with C-style languages to learn.
# Algorithms in Programming 
-In programming an algorithm is a step-by-step procedure or formula for solving a problem or performing task.
-An algorithm is a finite sequence of well-defomed instructions,typically to solve a class of problems or perform a computation.
# Getting Your Java Environment Ready
-The Java Development Kit (JDK) is required for developing Java applications. 
-It includes the Java Runtime Environment (JRE), an interpreter/loader (Java), a compiler (javac), an archiver (jar), a documentation generator (Javadoc), and other tools needed for Java development.
-Download and Install the JDK
-IntelliJ IDEA is a powerful, feature-rich Integrated Development Environment (IDE) for Java and other programming languages, developed by JetBrains. 
# Java Essentials
-Creating a Java package is an essential part of organizing your code and managing namespaces.
-A package is a namespace that organizes a set of related classes and interfaces. Here's a step-by-step guide on how to create and use packages in Java
## Define the Package
-When you create a package, you specify the package name at the top of your Java source file using the package keyword. This must be the first line in your Java file.
## Create the Directory Structure
-The package name corresponds to the directory structure where the class files are stored
## Create a Java Class in the Package
-Create a Java class within this directory structure and include the package statement at the top.
## Compile the Java Class
-To compile a class that is part of a package, you need to be in the root directory of your package structure. Navigate to the directory that contains the com directory and compile the Java file.
# Classes
-A class is a blueprint for objects. An object is an instance of a class.
# Java Reserved words
In Java, reserved words (also known as keywords) are predefined words that have a specific meaning to the Java compiler. These words cannot be used as identifiers (such as variable names, class names, or method names) in your programs because they are part of the syntax of the language.
 ## Variables
Variables are used to store data that can be referenced and manipulated in a program.
e.g int number = 10;
double price = 19.99;
char letter = 'A';
boolean isJavaFun = true;
## Dynamically Typed vs Statically Typed Programming Languages
-Dynamically typed and statically typed programming languages are two different approaches to type checking and type safety in programming
## Statically Typed Programming Languages
-Definition
-In statically typed languages, type checking is performed at compile time. This means that the type of each variable is known and checked before the program is run.
## Dynamically Typed Programming Languages
-Definition
-In dynamically typed languages, type checking is performed at runtime. The type of a variable can change during the execution of the program.
# Primitive Data Types 
-Primitive data types are the most basic data types available in a programming language. 
-They serve as the building blocks for data manipulation in programs. In Java, there are eight primitive data types, each of which represents a different kind of data.
## Summary Table
Data Type	Size	Range	Default Value
byte	8 bits	-128 to 127	0
short	16 bits	-32,768 to 32,767	0
int	32 bits 	-2^31 to 2^31-1	0
long	64 bits	-2^63 to 2^63-1	0L
float	32 bits	Approximately 1.4e-45 to 3.4e+38	0.0f
double	64 bits	Approximately 4.9e-324 to 1.8e+308	0.0d
boolean	1 bit*	true or false	false
char	16 bits	'\u0000' (0) to '\uffff' (65,535)	'\u0000'
# Local Variable Type Inference
-Local Variable Type Inference (LVT) is a feature introduced in Java 10 that allows the compiler to infer the type of local variables automatically, making the code more concise and readable. 
-This feature uses the var keyword to let the compiler determine the type based on the assigned value
## Declaration and Initialization:
-When you declare a local variable and initialize it at the same time, you can use the var keyword.
-The compiler infers the type of the variable from the type of the expression on the right-hand side of the assignment.
## Rules and Restrictions:
-The variable must be initialized at the time of declaration; you cannot use var without initialization.
-The inferred type must be a valid, concrete type; it cannot be null or involve wildcard types directly.
# Variable type interface
-Variable type inference is a programming language feature that allows the compiler to automatically deduce the type of a -variable at compile time, based on the value assigned to the variable. This feature enhances code readability and conciseness by eliminating the need for explicit type declarations.
# Naming Variables
-Naming variables is a crucial aspect of writing clean and understandable code. 
## Use Descriptive Names
Choose names that clearly convey the purpose or meaning of the variable.
Avoid single-letter or ambiguous names like x, y, or temp.
## Be Consistent
Maintain consistency in naming style throughout your codebase.
Choose a naming convention (e.g., camelCase, snake_case, PascalCase) and stick to it.
## Follow Conventions
Adhere to the naming conventions of the programming language or framework you're using.
For example, in Java, variables typically start with a lowercase letter, while classes start with an uppercase letter.
## Use Intention-Revealing Names
Opt for names that reveal the intention behind the variable.
Instead of result, consider totalRevenue or averageScore.
## Avoid Abbreviations (Except Common Ones)
Abbreviations can make code harder to understand, especially for newcomers.
Use full words unless the abbreviation is widely understood (e.g., num for "number").
## Be Mindful of Scope
Choose variable names appropriate to their scope (e.g., local variables, instance variables, constants).
Shorter names may be acceptable for loop counters or temporary variables with limited scope.
## Use Singular Nouns for Single Values
Use singular nouns for variables representing single values.
For example, user, customer, product, etc.
## Use Plural Nouns for Collections
Use plural nouns for variables representing collections or arrays.
For example, users, customers, products, etc.
## Avoid Reserved Words and Keywords
Do not use language keywords or reserved words as variable names.
If a reserved word accurately describes the variable's purpose, consider using a synonym or prefixing/suffixing it.
## Make Names Pronounceable
Choose names that are easy to pronounce and understand when read aloud.
Pronounceability aids in team communication and code review discussions.
# Modifying Variables
-Modifying variables involves changing their values during the execution of a program. 
-Depending on the programming language and the type of variable, there are various ways to modify variables
## Hard coded variables
-"Hard-coded variables" refer to values that are explicitly written into the source code rather than being obtained from external sources or calculated dynamically during runtime. 
-These values are typically literals and are directly embedded into the code.
## Dynamic variables
-In dynamically typed languages, variables are not bound to a specific data type at compile time.
-Instead, their type is determined dynamically at runtime based on the value assigned to them. 
-This contrasts with statically typed languages, where variable types are explicitly declared and enforced by the compiler.
# Arithmetic Operators
-Arithmetic operators are symbols or functions in programming languages used to perform mathematical calculations on numerical values. 
-These operators allow you to perform basic arithmetic operations like addition, subtraction, multiplication, division, and modulus.
## Addition +
Adds two operands.
Can also be used for string concatenation in some languages
## Subtraction -
Subtracts the right operand from the left operand.
## Multiplication *
Multiplies two operands.
## Division /
Divides the left operand by the right operand.
## Modulus %
Returns the remainder of the division of the left operand by the right operand.
# Decision Structures in Java
-Decision structures in Java allow you to control the flow of your program based on certain conditions. 
-Java provides several constructs for decision-making, including if, if-else, if-else-if, switch, and the ternary operator (? :).
## if Statement:
The if statement executes a block of code if a specified condition is true. It is the most basic decision-making statement.
## if-else Statement:
The if-else statement allows you to execute one block of code if the condition is true and another block of code if the condition is false.
## if-else-if Statement:
The if-else-if statement allows you to check multiple conditions and execute different blocks of code based on the first condition that is true.
## switch Statement:
The switch statement allows you to select one of many code blocks to be executed based on a given expression. It's useful when you have multiple conditions to check against the same variable.
## Ternary Operator (? :):
The ternary operator is a shorthand way of writing an if-else statement. It returns one of two values depending on the value of a Boolean expression.
# Relational Operators
-Relational operators in Java are used to compare two values or expressions. 
-The result of a relational operation is always a boolean value: true or false. 
-These operators are essential in control flow statements such as if, while, and for loops, allowing the program to make decisions and iterate over data based on certain conditions.
## Equal to (==):
Compares two values for equality.
Example: if (a == b)
Not equal to (!=):
Compares two values for inequality.
Example: if (a != b)
## Greater than (>):
Checks if the value on the left is greater than the value on the right.
Example: if (a > b)
## Less than (<):
Checks if the value on the left is less than the value on the right.
Example: if (a < b)
## Greater than or equal to (>=):
Checks if the value on the left is greater than or equal to the value on the right.
Example: if (a >= b)
## Less than or equal to (<=):
Checks if the value on the left is less than or equal to the value on the right.
Example: if (a <= b)
# Logical Operators 
-Logical operators in Java are used to combine multiple boolean expressions and return a boolean result. 
-These operators are particularly useful in control flow statements to create more complex conditions. Java provides three logical operators:
## Logical AND (&&):
Returns true if both operands are true.
Example: if (a && b)
## Logical OR (||):
Returns true if at least one of the operands is true.
Example: if (a || b)
## Logical NOT (!):
Inverts the value of its operand.
Example: if (!a)
# Short Circuit Logic
-Short-circuit logic in Java refers to the evaluation behavior of the logical AND (&&) and logical OR (||) operators.
-In short-circuit evaluation, the second operand is evaluated only if the first operand does not determine the result of the operation. 
-This can prevent unnecessary computations and avoid potential errors such as null pointer exceptions.
# Short-Circuit AND (&&)
-The logical AND (&&) operator uses short-circuit evaluation.
-If the first operand is false, the overall result is false, and the second operand is not evaluated. This is because the AND operation requires both operands to be true to result in true. 
-If the first operand is already false, evaluating the second operand is unnecessary.
# Short-Circuit OR (||)
The logical OR (||) operator also uses short-circuit evaluation. If the first operand is true, the overall result is true, and the second operand is not evaluated. This is because the OR operation requires only one operand to be true to result in true. If the first operand is already true, evaluating the second operand is unnecessary.
# Repetition Structures in Java
-Repetition structures, also known as loops, in Java are used to execute a block of code repeatedly as long as a specified condition is true. Java provides several types of loops to handle different scenarios:
-while Loop
-do-while Loop
-for Loop
-enhanced for Loop (for-each Loop)
1. while Loop
The while loop repeats a block of code as long as a specified condition is true. The condition is checked before the loop body is executed.
2.do-while Loop
The do-while loop is similar to the while loop, but it checks the condition after executing the loop body. This ensures that the loop body is executed at least once.
3. for Loop
The for loop is used when you know in advance how many times you want to execute a statement or a block of statements. It consists of three parts: initialization, condition, and update.
4. Enhanced for Loop (for-each Loop)
The enhanced for loop, also known as the for-each loop, is used to iterate over elements in an array or a collection. It simplifies the syntax and makes the code more readable.
# Controlling Loop Execution
-Java provides several statements to control the execution of loops:
-break Statement: Exits the loop immediately.
-continue Statement: Skips the current iteration and proceeds with the next iteration.
-return Statement: Exits the loop and the method in which it is used.
# Methods in Java
-Methods in Java are blocks of code that perform specific tasks and can be called upon to execute those tasks whenever needed. 
-They help in organizing code, making it reusable, and improving readability and maintainability.
## Types of Methods
1. Instance Methods
Instance methods are associated with an instance of a class. They can access instance variables and other instance methods directly.
2.Static Methods
Static methods belong to the class rather than an instance. They can be called without creating an instance of the class and can only access static variables and other static methods directly.
# Method Overloading
Method overloading allows multiple methods in the same class to have the same name but different parameters (different type, number, or both). This is useful for creating methods that perform similar functions but with different inputs.
# Pass by Value
In Java, method parameters are passed by value, meaning that a copy of the actual parameter is passed to the method. Changes to the parameter within the method do not affect the original value.
# Returning Values
Methods can return values of any data type, including objects. Use the return statement to return a value from a method.
# Variable Scope
Variable scope in Java refers to the region of the program where a variable is accessible. Understanding the scope of variables is crucial for writing correct and maintainable code. In Java, variable scope is categorized into several types based on where and how variables are declared:
-Local Scope
-Instance Scope (Fields)
-Class Scope (Static Fields)
-Block Scope
1. Local Scope
Local variables are declared inside a method, constructor, or block and are only accessible within that specific method, constructor, or block. They are created when the block is entered and destroyed when the block is exited.
2. Instance Scope (Fields)
Instance variables, also known as fields, are declared inside a class but outside any method, constructor, or block. They are accessible to all non-static methods and constructors of the class and represent the state of an instance of the class. Each instance of the class has its own copy of instance variables.
3. Class Scope (Static Fields)
Static variables, also known as class variables, are declared with the static keyword inside a class but outside any method, constructor, or block. They are shared among all instances of the class and are accessible through the class name as well as instances of the class.
4. Block Scope
Block scope refers to variables declared inside any pair of curly braces {} such as loops, if statements, and blocks within methods. These variables are only accessible within that block.
# Passing Data to Methods
-In Java, you can pass data to methods through parameters. Methods can accept input in the form of parameters, process the data, and return a result. 
## Method Parameters
When defining a method, you specify parameters in the method's signature. These parameters act as placeholders for the actual values (arguments) you pass when calling the method.
# Returning Data from Methods
-Returning data from methods in Java involves specifying a return type in the method signature and using the return statement to return a value from the method.
## Method Return Types
The return type of a method is specified in the method declaration. It indicates the type of value the method will return. If a method does not return any value, its return type is void.
# Overloading Methods
-Method overloading in Java allows a class to have more than one method with the same name, provided their parameter lists are different.
-Overloading increases the readability of the program by allowing methods that perform similar operations to be called by the same name.
## Key Points
-Different Parameter Lists: Methods can be overloaded if they have different parameter lists, which means the number of parameters, the type of parameters, or the order of parameters must differ.
-Return Type and Access Modifiers: Changing the return type or access modifier alone does not constitute overloading; the parameter list must change.
-Compile-Time Polymorphism: Method overloading is an example of compile-time polymorphism because the method call is resolved at compile time based on the method signature.
# Objects in Java
-In Java, objects are the fundamental building blocks for creating complex applications.
-An object is an instance of a class, which is a blueprint defining the data and behavior (methods) the object will have. Understanding objects is crucial for mastering object-oriented programming (OOP) in Java.
## Key Concepts
-Class: A blueprint for creating objects. It defines fields (attributes) and methods (behaviors) that the objects created from the class will have.
-Object: An instance of a class. It is created from a class and can have state and behavior as defined by the class.
-Instantiation: The process of creating an object from a class.
## Defining a Class
A class is defined using the class keyword. 
## Creating an Object
To create an object, you use the new keyword followed by the class constructor.
# Java Constructors
Constructors are special methods used to initialize objects. They have the same name as the class and do not have a return type.
## Object State and Behavior
State: Represented by the fields (attributes) of the object. Each object has its own set of values for these fields.
Behavior: Represented by the methods (functions) of the object. Methods define what operations can be performed on the object’s data.
## Encapsulation
Encapsulation is an OOP principle where the data (fields) and code (methods) that manipulates the data are bundled together. It restricts direct access to some of the object's components, which is achieved using access modifiers.
# Method Parameters as Objects
-In Java, method parameters can be of primitive types or objects. When you pass an object as a parameter to a method, you are actually passing a reference to the object, not a copy of the object itself.
-This means any changes made to the object inside the method will affect the original object outside the method. 
# Method Return Types
-In Java, methods can have different return types, including primitive types, objects, arrays, or even void. The return type of a method determines what type of data it can return to the caller. 
# Wrapper Classes
Wrapper classes in Java provide a way to treat primitive data types as objects. Each primitive data type has a corresponding wrapper class in Java, which allows you to perform operations on them like objects.
Wrapper classes are useful when working with collections, generics, or methods that require objects instead of primitives.
## Converting Primitive Types to Wrapper Objects
You can create wrapper objects using constructors or static methods provided by the wrapper classes.
## Converting Wrapper Objects to Primitive Types
You can extract the primitive value from wrapper objects using methods provided by the wrapper classes.
# Records
Records are a new feature introduced in Java starting from version 14. They provide a concise syntax for declaring classes that are meant to be simple data carriers. Records can help reduce boilerplate code in 
Java by automatically generating standard methods such as constructors, accessors, equals(), hashCode(), and toString().
# Inheritance
-Inheritance is a fundamental concept in object-oriented programming (OOP) that allows a class to inherit properties and behaviors (fields and methods) from another class.
-In Java, inheritance is achieved using the extends keyword.
## Superclass and Subclass:
-Superclass: The class whose properties and methods are inherited.
-Subclass: The class that inherits from the superclass.
## Types of Inheritance
-Single Inheritance: A class can inherit from only one superclass.
-Multilevel Inheritance: A class can inherit from a superclass, and another class can inherit from this subclass, forming a chain.
-Hierarchical Inheritance: Multiple classes inherit from a single superclass.
## Constructors in Inheritance:
-The constructor of the superclass is called when an object of the subclass is created.
-You can call the superclass constructor explicitly using super().
## Method Overriding:
-A subclass can provide a specific implementation of a method that is already defined in its superclass.
## Access Modifiers:
-public, protected, and private keywords control the visibility of fields and methods in the superclass to the subclass.
## Chain of Inheritance
-Chain of inheritance, also known as multilevel inheritance, is a type of inheritance in which a class is derived from another derived class.
-This forms a hierarchy where each class inherits from the preceding class, creating a chain of classes.
-In Java, this is accomplished by having a subclass extend a superclass, and then another subclass extend that subclass, and so on.
## Limiting Access in Inheritance
-Limiting access in inheritance is crucial to maintaining encapsulation and ensuring that only necessary parts of a class's implementation are exposed to other classes, including subclasses.
-Java provides several mechanisms to control the access of fields, methods, and constructors through access modifiers.
## Sealed Classes
-Sealed classes are a feature introduced in Java 17 to provide more control over the inheritance hierarchy of classes. 
-They allow you to define a class and explicitly specify which classes are permitted to extend it. 
-This helps in creating a more predictable and controlled inheritance structure, improving the safety and maintainability of the code.
## Sealed Class: A class that restricts which other classes can inherit from it.
## Permitted Subclasses: The specific classes that are allowed to extend the sealed class.
# Polymorphism
-Polymorphism is one of the core concepts of object-oriented programming (OOP) that allows objects of different classes to be treated as objects of a common superclass.
-It enables a single interface to be used for different underlying data types. 
-Polymorphism can be achieved through method overriding (runtime polymorphism) and method overloading (compile-time polymorphism).
