[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/-AeYBdka)
[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-2972f46106e565e64193e422d61a12cf1da4916b45550586e14ef0a7c637dd04.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=19647863)
# COMP 271 SU25 WEEK 00

A simple discussion on realistic data structures.

Your assignment for the first week has two parts.

# Explain
Explain in your own words how the loops in lines 40-45 in class [Realistic.java](./Realistic.java) work. Specifically discuss 

* the range of the first loop (ie, the values variable `i` takes), 
* the range of the second loop, 
* the index positions for the arrays inside both loops. In the first loop the assignment is
`temporary[i] = arr[i];` and in the second loop we have `temporary[i-1] = arr[i];`. Why?

You may type your answers in a **block comment** at the top of class `Realistic.java` or as a new markdown file in this repository -- in this case, the new file should be name `explain.md`. This is a good opportunity to familiarize yourself with [MarkDown](https://www.markdownguide.org/basic-syntax/).

# Code
Add a method with the following header to class `Realistic`:
```java
public static void add(int value)
```
This method should increase the size of the array `arr` by one element and insert the given `value` into the last position of the enlarged array. Ensure the rest of the original array remains intact.
