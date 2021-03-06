## Java Resources for Beginner

### Basics

>Java is one of the most popular programming languages in the world. With Java you can build various types of applications such as desktop, web, mobile apps and distributed systems. 
Java Development Kit 
>We use Java Development Kit (JDK) to build Java applications. JDK contains a compiler, the Java Runtime Environment (JRE) and a library of classes that we use to build applications.  
Java Editions.

>We have four editions of Java, each used for building a different type of application:  
•Java Standard Edition (SE): the core Java platform. It contains all of the libraries that every Java developer must learn.  
•Java Enterprise Edition (EE): used for building very large scale, distributed systems. It’s built on top of Java SE and provides additional libraries for building fault-tolerant, distributed, multi-tier software.  
•Java Micro Edition (ME): a subset of Java SE, designed for mobile devices. It also has libraries specific to mobile devices. 
•Java Card: used in smart cards.

### How Java Code Gets Executed 
>The Java compiler takes Java code and compiles it down to Java Bytecode which is a cross-platform format. When we run Java applications, Java Virtual Machine (JVM) gets loaded in the memory. It takes our bytecode as the input and translates it to the native code for the underlying operating system. There are various implementations of Java Virtual Machine for almost all operating systems.  
Architecture of Java Applications  
>The smallest building blocks in Java programs are methods (also called functions in other programming languages). We combine related methods in classes, and related classes in packages. This modularity in Java allows us to break down large programs into smaller building blocks that are easier to understand and re-use. 

### Types 
### Variables 
> We use variables to temporarily store data in computer’s memory. In Java, the type of a variable should be specified at the time of declaration.  
> In Java, we have two categories of types:  
•Primitives: for storing simple values like numbers, strings and booleans.  
•Reference Types: for storing complex objects like email messages. 

### Primitive Types  
|Type	|Bytes	|Range|
|------|------|---------|
|byte		|1 |[-128, 127]|
|short		|2 |[-32K, 32K]|
|int	|4 |[-2B, 2B]|
|long	|8 |
|float	|4|
|double	|8|
|char		|2 |A, B, C, …|
|boolean		|1 |true / false|

## Reference Types 
> In Java we have 8 primitive types. All the other types are reference types. These types don’t store the actual objects in memory. They store the reference (or the address of) an object in memory. 
> To use reference types, we need to allocate memory using the new operator. The memory gets automatically released when no longer used.
```
Date now = new Date();
```

## Strings 
> Strings are reference types but we don’t need to use the new operator to allocate memory to them. We can declare string variables like the primitives since we use them a lot.
```
String name = “Mosh”;
```

## Useful String Methods  
> The String class in Java provides a number of useful methods:  
•startsWith(“a”) 
•endsWith(“a”)  
•length() 
•indexOf(“a”) 
•replace(“a”, “b”) 
•toUpperCase() 
•toLowerCase()

> Strings are immutable, which means once we initialize them, their value cannot be changed. All methods that modify a string (like toUpperCase) return a new string object. The original string remains unaffected.

## Escape Sequences

> If you need to use a backslash or a double quotation mark in a string, you need to prefix it with a backslash. This is called escaping.  
## Common escape sequences:  
•\\ 
•\” 
•\n (new line) 
•\t (tab) 

![image](https://user-images.githubusercontent.com/11692119/121558618-716c5500-ca33-11eb-91a8-c6965ae509e2.png)


