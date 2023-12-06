# C++ Path


## Introduction 
In this path, you will understand the `C++` language and its concepts, we have divided these concepts into two parts.
**OOP and basics language** part, and related concepts of `C++` language or what we will call it later on the **extra topics** part.


### OOP and Language Basics Part
This part will cover the basics of `C++` as a language based on what we have covered earlier on the High-Level Language path.
Since most of the concepts in High-Level Languages are the same, we will show you a brief introduction to each concept and 
how to implement it using `C++`.

#### Example
A `class` is a collection of properties and methods to describe a new type in your program.

```c++
class Student {
  /* Student Properties/Data */ 
  /* Student Methods/Actions */ 
};
```

### Extra Topics
In this path, we will cover related `C++` topics that we have not covered in our High-Level Language path. 

#### Example
`Destructor` is a method in the class with the same name as the class but prefixed with the ~ (Tilda) symbol. It is used to clean up the memory from objects that are not in use or deleted.

```c++
class Student {
public:
  // Constructor for class Student
  Student();
  // Destructor for class Student
  ~Student();
};
```
