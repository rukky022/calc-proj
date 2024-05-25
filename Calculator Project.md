# Calculator Project
**Language:** Java
**IDE:** whichever (I use IntelliJ at work, but VS Code is also pretty popular)
**Version Control:** GitHub
**Project description:**
The client needs a Terminal-based calculator that can solve all basic operations, as well as geometric problems such as finding the area, volume, and sqft of standard objects. The list of required functions is below.

When the user first starts the application, there should be a menu with all the functions the calculator can do. For instance:

```
Welcome to the Calculator. This calculator can solve basic arithmetic expressions, square root, exponents, and geometric equations such as the area, surface area, volume, and circumference of certain shapes.

To get started, please enter the corresponding letter in the brackets for the type of expression you want to solve:

-   [A] for Arithmetic (addition, subtraction, division, multiplication)
    
-   [S] for Square Root
    
-   [E] for Exponents
    
-   [G] for Geometric equations
```

**Basic functions:**

-   Addition
-   Subtraction
-   Division
-   Multiplication
-   Square Root of a single number
-   Exponents (ex. 2^3^ etc)

**Examples:**
```
Input: 5 + 8
Output: 13

Input: 9 + 6 + 3
Output: 18

Input: Sqrt of 9
Output: 3
```
Input: 2^3^
Output: 8

Input: 9^1/2^
Output: 3

**Geometric functions** for the following shapes (if you need ideas on how to do this, ask for *Hint 1*):

-   **Shapes:** Circle, Square, Rectangle, Triangle, Trapezoid, Rectangular Prism, Cylinder, Cube, Sphere
-   **Area** of Circle, Square, Rectangle, Triangle, and Trapezoid
-   **Surface Area** of Rectangular Prism, Cylinder, Cube, and Sphere  
-   **Volume** of Rectangular Prism, Cylinder, Cube, and Sphere
- **Circumference** of a Circle

**Bonus 1:** This calculator can use PEMDAS on longer expressions, such as
```
Input: (2 + 4) * (4 - 5)
Output: -6

Input: 5 * (3 / 2)
Output: 54
```
**Bonus 2:** This calculator should also be able to solve fraction equations with only two operands, or with the Square Root and Exponent functions (if you need ideas on how to do this, ask for Hint 2) and return the value rounded to the last 4 digits, such as
```
Input: ⅔ * ⅕
Output: 0.1333

Input: ¼ + ⅔
Output: 0.9166

Input: Sqrt of ¼
Output: 0.5000
```
Input: ⅝^1^
Output: 0.6250
