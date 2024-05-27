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
Summary Table
Data Type	Size	Range	Default Value
byte	8 bits	-128 to 127	0
short	16 bits	-32,768 to 32,767	0
int	32 bits 	-2^31 to 2^31-1	0
long	64 bits	-2^63 to 2^63-1	0L
float	32 bits	Approximately 1.4e-45 to 3.4e+38	0.0f
double	64 bits	Approximately 4.9e-324 to 1.8e+308	0.0d
boolean	1 bit*	true or false	false
char	16 bits	'\u0000' (0) to '\uffff' (65,535)	'\u0000'

