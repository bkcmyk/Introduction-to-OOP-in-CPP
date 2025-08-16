#  Object-Oriented Programming in C++

##  Aim
To study and implement the concepts of **Object-Oriented Programming (OOP)** in C++ using classes and objects.

## Tools Used
- **VS Code**
- **Other Online C++ Compilers** (such as Programiz, Replit, or OnlineGDB)

---

##  Theory

In C++, **Object-Oriented Programming (OOP)** allows us to represent real-world entities such as students, cars, calculators, and shapes as **objects**.  
An **object** is an instance of a **class**, which acts as a blueprint containing **data members (variables)** and **member functions (methods)**.

Objects give life to a class. While the class only describes what attributes and behaviors exist, the object stores the actual values and performs the actions.  
This enables the principles of OOP:

- **Abstraction** → Hiding unnecessary details and showing only relevant features.  
- **Encapsulation** → Binding data and methods together to protect integrity.  
- **Reusability** → Defining a class once and using it to create multiple objects.  

---

###  Defining Objects and Accessing Attributes
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

---

###  Defining Methods Inside a Class
```cpp
class Rectangle {
public:
    float area(float l, float w) {
        return l * w;
    }
};
```

---

###  Defining Methods Outside a Class
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

---

###  Public and Private Variables
```cpp
class Student {
private:
    float marks;

public:
    void setMarks(float m) { marks = m; }
    float getMarks() { return marks; }
};
```

---

##  Algorithms

### 1. Cube Volume (Method Defined Outside Class)
1. Start  
2. Create class `Cube` with member `side`.  
3. Declare function `calculateVolume()` inside class.  
4. Define function outside using `Cube::`.  
5. Input side.  
6. Calculate volume = side³.  
7. Display volume.  
8. End  

---

### 2. Rectangle Area (Method Inside Class)
1. Start  
2. Create class `Rectangle` with method `area(l, w)`.  
3. Input length and width.  
4. Call method to compute area.  
5. Display result.  
6. End  

---

### 3. Printing Car Info
1. Start  
2. Define class `Car` with attributes `name`, `year`.  
3. Create 3 objects `c1, c2, c3`.  
4. Accept input for brand and year.  
5. Display all details.  
6. End  

---

### 4. Printing Student Info
1. Start  
2. Define class `Student` with attributes `name`, `branch`, `year`, `result`.  
3. Create objects `s1, s2`.  
4. Assign attributes.  
5. Display details.  
6. End  

---

### 5. Public vs Private Variables
1. Start  
2. Create class `Student` with private variable `marks`.  
3. Provide public `setMarks()` and `getMarks()`.  
4. Create object.  
5. Set marks using setter.  
6. Access marks using getter.  
7. Display result.  
8. End  

---

### 6. Rectangle Area (OOP)
1. Start  
2. Define class `Rectangle` with attributes `length`, `width`.  
3. Define method `area()`.  
4. Input values.  
5. Calculate and display area.  
6. End  

---

### 7. Simple Calculator
1. Start  
2. Define class `Calculator` with methods for `sum, difference, product, division`.  
3. Input two numbers.  
4. Display menu for operation.  
5. Use switch to call correct method.  
6. Display result.  
7. Handle division by zero.  
8. End  

---

##  Applications of OOP

- **Software Development** → Foundation for C++, Java, Python, etc. Used in desktop apps, mobile apps, enterprise systems.  
- **Database Management** → Models entities like students, employees, customers. Widely used in CRMs.  
- **Game Development & Graphics** → Objects as characters, shapes, 3D components in simulations and gaming engines.  
- **Banking & Finance** → Accounts and transactions modeled as classes. Ensures data security.  
- **Engineering Applications** → Shapes modeled as objects in CAD, architecture, simulations.  
- **Web Development** → OOP frameworks ensure modular and maintainable backend code.  

---

##  Outcomes of Using OOP

- **Improved Problem Solving** – Ability to model real-world scenarios into objects.  
- **Reusability** – Code reuse across projects via classes and methods.  
- **Data Security** – Encapsulation ensures protection of sensitive data.  
- **Flexibility & Modularity** – Programs are structured and maintainable.  
- **Scalability** – Easy extension by adding/modifying classes.  
- **Industry Relevance** – Required skill in software dev, AI, web systems.  
- **Strong Foundation** – Prepares for advanced topics like Design Patterns & Software Architecture.  

---
