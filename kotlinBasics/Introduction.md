# Kotlin Basics 
## 1. Introduction to Kotlin 
Kotlin is a modern programming language developed by JetBrains.
It is used for Android development, backend, web, and desktop applications.
Kotlin is known for its simplicity, null safety, and full interoperability with Java.

## 2. Setting Up the Environment
You can start working with Kotlin in several ways:

- Install IntelliJ IDEA (recommended for Kotlin)
- Use Android Studio (if you plan to develop Android apps)
## 3. Your First Kotlin Program (Hello World)
Let's print a simple message:
```
fun main() {
    println("Hello, World!")
}
```
- fun is used to define a function.
- main is the entry point of the program.
- println prints a message to the output.
## 4. Variables and Data Types
In Kotlin, you can define variables in two ways:

- val for immutable variables (cannot be changed)
- var for mutable variables (can be changed)
Example:
```
val name = "Sarina"    // Immutable
var age = 28           // Mutable
 ```
Common data types:

- Int (Integer)
- Double (Decimal number)
- String (Text)
- Boolean (True or False)
## 5. Operators
Arithmetic Operators:

- +Addition
- -Subtraction
- *Multiplication
- /Division
- % Modulus (remainder)
### Comparison Operators:

- == Equal to
- != Not equal to
- > Greater than
- < Less than
- >= Greater than or equal to
- <= Less than or equal to
## 6. Conditional Statements (if, when)
if statement:
```
val number = 10
if (number > 5) {
    println("Number is greater than 5")
}
```
when expression (similar to switch in other languages):
```
val day = 3
when (day) {
    1 -> println("Monday")
    2 -> println("Tuesday")
    3 -> println("Wednesday")
    else -> println("Invalid day")
}
```
## 7. Loops (for, while, do-while)
### for loop:
```
for (i in 1..5) {
    println(i)
}
```
### while loop:
```
var i = 1
while (i <= 5) {
    println(i)
    i++
}
```
### do-while loop:
```
var i = 1
do {
    println(i)
    i++
} while (i <= 5)
```

