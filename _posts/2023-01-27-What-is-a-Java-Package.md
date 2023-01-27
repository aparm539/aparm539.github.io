---
title: 'What is a Java Package?'
date: 2023-01-24
permalink: /posts/2023/01/What-is-a-Java-Package/
tags:
  - Java
  - Introductory
---

Packages in Java group related classes. It may be easier to think of a package as a folder.

## Why do we group related classes? 

- Doing this makes our code easier to work on. It can be hard to understand the need for this while you are still making small programs with just a few classes, but imagine if you were creating a large program with 300 classes. It's much easier to find the classes when they are grouped like this.

- Prevents naming conflicts. You can have two classes in different packages that have the same name. 

- Controls access to the class. Protected members are accessable by classes in the same package and its subclass. Default members are accessible by members of the same class only.  

