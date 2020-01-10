# Clean Code Principle 
How to write clean and maintainable code ?
- Following the below rule will get your answer

# Naming Matter
 Class Naming
 
 - Should Be a noun 
 - Should be PascalCase => HttpClient
 - SRP Single Responsibility Principle 
 
 Method Naming
 - Should be Verb + Noun => getEmployee
 - Should do one action 
 - Shoudn't include [ And - OR ] expect in Java8 Stream and this called Antipattern
 
 Variable Naming
 - Shoud be Noun 
 - Use camelCase
 - Should be SNAKE_CASE for static or final variable
 - for boolean params it should start with is like isActive

# Class Constructor 
There are 3 methodology to write a constructor
- Static Method Factory
- Constructor Chain ( Dont DRY [ Don't Repeat yourself]
- Constructor Telescoping 
    For Example :
        if you develop a backend for a Restaurant and you create a class for Pizza
        this class will have a many parameters , so in this case we should use Builder pattern

