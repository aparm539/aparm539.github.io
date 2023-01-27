---
title: 'Method Overloading in Java'
date: 2023-01-24
permalink: /posts/2023/01/Method-Overloading-in-Java/
tags:
  - Java
  - Introductory
---

Method overloading allows for two methods to have the same name, as long as their parameters are different. 

## Why would you want to overload a method? 

Overloading a method allows you to call the same method for different types of data. Imagine you have a method that multiplies two numbers: 

```java
class Product{

  static int multiply(int a, int b){
    return a*b;
  }
}
```

This method can only accept integers, but what if we wanted to multiply two doubles? That is where overloading becomes useful. We can create a second method with the same name and different data types for our parameters. 

```java
class Product{

    static int multiply(int a, int b){
    return a*b;
  }

  static int multiply(double a, double b){
    return a*b;
  }
}
```

Now we have overloaded our method! We can do this by adding a different number of arugments as well. 

```java
class Product{

    static int multiply(int a, int b){
    return a*b;
  }

  static int multiply(double a, double b){
    return a*b;
  }
  static int multiply(double a, double b, double c){
    return a*b*c;
  }
}
```
All three of our methods have the same name and will still work without throwing any errors. 






