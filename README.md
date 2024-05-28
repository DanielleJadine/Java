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



