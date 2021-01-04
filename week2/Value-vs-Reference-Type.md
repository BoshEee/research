# Value vs Reference Type

There is two data type groups in JavaScript, Primitives & Objects

### Primitives (Value Types) : 
    Number, String, Boolean, Symbol, Undefined and Null
    
### Objects (Reference Types) : 
    Object, Function and Array
    
    
# The Difference Between Them



| Primitive             | Object                    |
| --------------------- | ------------------------- |
| Copied by their value | Copied by their reference |

When we declare a variable let's say x = 10, that means x is a single variable not conected or linked to any other variable. 

To understand it even more let's consider the example below : 
```javascript=
let x = 10;
let y = x;

x++;

console.log(y); // y -> 10
```

We declared two variables X, Y . X = 10. then y = x .. after that we add 1 to x so now x = 11 but y still equals 10.

Because the variables are not linked or conected, any changes on x won't effect y.

    The variables only contain the value

### But Objects Are ...

When we deal with objects and assign values from a variable to another, it's effects the other like both of the variable are conected.

Let's change the example to object like the code below : 

```javascript=
let x = {value: 10};
let y = x;

x.value = 20;

console.log(y); // y -> 20
```

When we changed it to object, now anything we change in x will change y to because both of the variables pointing to the same value 

![](https://i.imgur.com/KLC6HT8.png)

    Declaring an Object creates it inside your computer memory
    
## *For better understanding watch this* [Video](https://https://www.youtube.com/watch?v=fD0t_DKREbE)


# Clean Code Concepts

    Clean code is code that is easy to understand and easy to change.
    
As a coder you need to keep your code clean and easy to read for other programmers. Because most of the time you will work with a team, means they will read your code and you will read thier code. So if your code is not clean that makes some issues

### HOW TO MAKE IT CLEAR?
---

By following some rules and using understandable names for IDs and CLASSES. Also, write the names in a way that explains what the variable contain or what the class does.

Don't forget to comment your code to make it easier for your mates to understand what this section of code does and why


## HERE ARE SOME TIPS TO CODE CLEAR

1. Keep it simple.
2. Don't repeat yourself.
3. Don't add functions you don't need.
4. Well-named constants.

```javascript=
let us = "John";  // No clue what the variable is...
let userName = "John"; // Now anyone read this knows it's a username Variable...
```

5. Keep Practicing.

    An Example ( left : Unclean code, Right : Clean Code )

![](https://i.imgur.com/YG4sJ46.jpg)


---

## Usefull links 
Read more about [Clean Code Concepts](https://https://x-team.com/blog/principles-clean-code/)
 What is Clean Code [Extended Explanation.](https://https://garywoodfine.com/what-is-clean-code/)
 
 
