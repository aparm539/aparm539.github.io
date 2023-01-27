---
title: 'Creating Your First Java Program'
date: 2023-01-26
permalink: /posts/2023/01/Creating Your First Java Program/
tags:
  - Java
  - Introductory
---

## Why Is Java So Complicated?

Lets compare the classic programming practice of creating a "Hello World" program in Java and Python. The purpose of this program is simple: Output the text "Hello World" to the console.

### Steps For "Hello World" In Python 
1. Open Visual Studio Code.
   
2. Create a new file.
   
3. Write the following command: `print("Hello World")`. 
   
4. Save the file as "helloWorld.py".
   
5. Press f5 to run the program. 

5 steps for everything from creating the file to running the program. Now let's compare this to Java. 

### Steps for "Hello World" In Java

1. Open Eclispe.
   
2. Create a project.
   
3. Name the project HelloWorld.
   
4. Click Finish.
   
5. Select HelloWorld/src as the source folder.
   
6. Create a new class.
   
7. Name the class HelloWorld.
   
8. In the section "Which Method Stubs Would You Like to Create?", check the option for `public static void main(String[] args)`.
   
9.  Click Finish.
   
10. Under the main method write the following command: `System.out.println("Hello world!");`.
    
11. Save the file.
    
12. Right click the "HelloWorld" class and select Run As > Java Application. 


You can notice that it takes a few more steps in Java than in Python. We also have to do things that don't make much sense right now. Some question you might have at this point: 

- What does `public static void main(String[] args)` mean?
- Why did we have to create a folder first before making our file? 
- What is a class?

## The Anatomy of a Java Program

You might be able to see that a Java program has a different structure than a Python one. It has more parts than a Python program and that seems confusing at first. Let's break down why the file looks the way it does.

### The Organization of Files

#### Why Do We Create a Folder and a File?

Our project folder (in our case the HelloWorld folder) will contain everything we need to run our program. 

src contains all the java code we write which is organized into different packages

different packages are best used for large projects. Makes code easier to find and work on. 

Purpose of JRE system library allows us to use different functions and methods without importing them each time

When we run our program on different computers the JRE system library ensures that all the functions from the libraries included run properly.  

#### Why do we name our class the same things as our project? 

This is so the compiler knows which class file to run at the start rather than searching through all of them. 

#### What is the main method

The main method is the method where the program starts. Once the file is ran it reads the instructions from here first. 

#### Methods in Java







