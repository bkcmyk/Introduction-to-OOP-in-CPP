#  Object-Oriented Programming in C++

## Aim
To study and implement the concepts of Object-Oriented Programming (OOP) in C++ using classes and objects

## Tools Used
VS Code
Other Online C++ Compilers (such as Programiz, Replit, or OnlineGDB)


## Theory
In C++, Object-Oriented Programming (OOP) allows us to represent real-world entities such as students, cars, calculators, and shapes as objects.
- An object is an instance of a class, which acts as a blueprint containing data members (variables) and member functions (methods).
-Objects give life to a class. While the class only describes what attributes and behaviors exist, the object stores the actual values and performs the actions. This enables the principles of OOP:
Abstraction → Hiding unnecessary details and showing only relevant features.
Encapsulation → Binding data and methods together to protect integrity.
Reusability → Defining a class once and using it to create multiple objects.

### Defining Objects and Accessing Attributes
Once a class is created, objects can be defined in the main program. Each object has its own copy of the class’s attributes and can call its functions.
#### Syntax:
```cpp
class ClassName {
public:
data_type attribute1;
data_type attribute2;


void method() {
// code
}
};


int main() {
ClassName obj;         // Defining object
obj.attribute1 = value;
obj.attribute2 = value;

obj.method();          // Accessing class function
}
```
### Defining Methods Inside a Class
Functions can be defined directly inside a class. Such methods are treated as inline by default.
#### Syntax:
```cpp
class Rectangle {

public:
float area(float l, float w) {
return l * w;
}
};
```
### Defining Methods Outside a Class
Functions can also be declared inside the class but defined outside using the scope resolution operator (::).
#### Syntax:
```cpp
class Cube {

public:
float side;

void calculateVolume();   // Declaration
};


void Cube::calculateVolume() {   // Definition

cout << "Volume: " << side * side * side;
}
```
### Public and Private Variables
Public members → Accessible anywhere in the program.
Private members → Hidden from outside; only accessible via public methods.
#### Syntax:
```cpp
class Student {

private:
float marks;

public:

void setMarks(float m) { marks = m; }
float getMarks() { return marks; }
};
```

## Algorithms
**1. Cube Volume (Method Defined Outside Class)**
1. Start
2. Create class Cube with member side.
3. Declare function calculateVolume() inside class.
4. Define function outside using Cube::.
5. Input side.
6. Calculate volume = side³.
7. Display volume.
8. End

**2. Rectangle Area (Method Inside Class)**
1. Start
2. Create class Rectangle with method area(l, w).
3. Input length and width.
4. Call method to compute area.
5. Display result.
6. End

**3. Printing Car Info**
1. Start
2. Define class Car with attributes name, year.
3. Create 3 objects c1, c2, c3.
4. Accept input for brand and year.
5. Display all details.
6. End

**4. Printing Student Info**
1. Start
2. Define class Student with attributes name, branch, year, result.
3. Create objects s1, s2.
4. Assign attributes.
5. Display details.
6. End

**5. Public vs Private Variables**
1. Start
2. Create class Student with private variable marks.
3. Provide public setMarks() and getMarks().
4. Create object.
5. Set marks using setter.
6. Access marks using getter.
7. Display result.
8. End

**6. Rectangle Area (OOP)**
1. Start
2. Define class Rectangle with attributes length, width.
3. Define method area().
4. Input values.
5. Calculate and display area.
6. End

**7. Simple Calculator**
1. Start
2. Define class Calculator with methods for sum, difference, product, division.
3. Input two numbers.
4. Display menu for operation.
5. Use switch to call correct method.
6. Display result.
7. Handle division by zero.
8. End

## Applications of OOP
#### 1. Software Development
Forms the foundation of programming languages like C++, Java, Python.
Used to design desktop apps, mobile apps, and enterprise systems.
#### 2. Database Management
Classes model entities such as students, employees, and customers.
Widely used in college databases and business CRMs.
#### 3. Game Development & Graphics
Objects represent players, shapes, or graphical components.
Used in 3D simulations and game engines.
#### 4. Banking & Finance
Classes model accounts, transactions, and customers.
Encapsulation ensures data security.
#### 5. Engineering Applications
Shapes and figures (rectangles, cubes, circles) are modeled as objects.
Useful in CAD, architecture, and simulation tools.
#### 5. Web Development
Backend frameworks apply OOP for modular and maintainable code.

## Outcomes of Using OOP

**Improved Problem Solving**  – Ability to model real-world scenarios into objects.

**Reusability** – Code can be reused across different projects via classes and methods.

**Data Security** – Encapsulation protects sensitive data.

**Flexibility & Modularity** – Programs become structured and easier to maintain.

**Scalability** – OOP-based software can be extended easily by adding new classes.

**Industry Relevance** – OOP is essential for careers in software development, AI, data science, and web systems.

**Strong Foundation** – Builds the base for advanced concepts like Design Patterns and Software Architecture.
