# ☕ Java Fundamentals

![Java](https://img.shields.io/badge/Java-17%2B-orange?style=for-the-badge&logo=java)
![Status](https://img.shields.io/badge/Status-Active-brightgreen?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)

A comprehensive collection of Java programs covering core concepts — from basics to object-oriented programming. Perfect for beginners and anyone looking to strengthen their Java skills.

---

## 📁 Project Structure

```
java-fundamentals/
│
├── src/
│   ├── 01_basics/
│   │   ├── HelloWorld.java
│   │   ├── DataTypes.java
│   │   └── Variables.java
│   │
│   ├── 02_control_flow/
│   │   ├── IfElse.java
│   │   ├── SwitchCase.java
│   │   └── Loops.java
│   │
│   ├── 03_arrays/
│   │   ├── ArrayBasics.java
│   │   └── MultiDimensional.java
│   │
│   ├── 04_methods/
│   │   ├── MethodBasics.java
│   │   └── Recursion.java
│   │
│   ├── 05_oop/
│   │   ├── Classes.java
│   │   ├── Inheritance.java
│   │   ├── Polymorphism.java
│   │   ├── Encapsulation.java
│   │   └── Abstraction.java
│   │
│   ├── 06_collections/
│   │   ├── ArrayListDemo.java
│   │   ├── HashMapDemo.java
│   │   └── LinkedListDemo.java
│   │
│   └── 07_exception_handling/
│       ├── TryCatch.java
│       └── CustomException.java
│
└── README.md
```

---

## 🧠 Topics Covered

### 1️⃣ Java Basics
- Hello World & program structure
- Data types (int, float, char, boolean, String)
- Variables and constants
- Operators (arithmetic, logical, relational)
- Type casting

### 2️⃣ Control Flow
- `if`, `else if`, `else` statements
- `switch` and `switch` expressions
- `for`, `while`, `do-while` loops
- `break` and `continue`

### 3️⃣ Arrays
- Single-dimensional arrays
- Multi-dimensional arrays
- Array sorting and searching

### 4️⃣ Methods & Functions
- Method declaration and calling
- Method overloading
- Recursion

### 5️⃣ Object-Oriented Programming (OOP)
- **Classes & Objects**
- **Inheritance** – extending classes
- **Polymorphism** – method overriding
- **Encapsulation** – getters & setters
- **Abstraction** – abstract classes & interfaces

### 6️⃣ Collections Framework
- `ArrayList`, `LinkedList`
- `HashMap`, `HashSet`
- Iterating collections

### 7️⃣ Exception Handling
- `try`, `catch`, `finally`
- Multiple catch blocks
- Custom exceptions

---

## 🚀 Getting Started

### Prerequisites
- Java JDK 17 or higher → [Download here](https://www.oracle.com/java/technologies/downloads/)
- Any IDE: **IntelliJ IDEA**, **VS Code**, or **Eclipse**

### Clone the Repository
```bash
git clone https://github.com/kota64453/java-fundamentals.git
cd java-fundamentals
```

### Run a Program
```bash
# Compile
javac src/01_basics/HelloWorld.java

# Run
java -cp src 01_basics.HelloWorld
```

### Run in VS Code
1. Install the **Extension Pack for Java** in VS Code
2. Open the project folder
3. Click the ▶️ **Run** button on any `.java` file

### Run in IntelliJ IDEA
1. Open IntelliJ → `File` → `Open` → select the project folder
2. Right-click any `.java` file → `Run`

---

## 💡 Sample Code

```java
// Hello World
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, World!");
    }
}
```

```java
// OOP Example - Class & Object
public class Car {
    private String brand;
    private int speed;

    public Car(String brand, int speed) {
        this.brand = brand;
        this.speed = speed;
    }

    public void display() {
        System.out.println(brand + " runs at " + speed + " km/h");
    }

    public static void main(String[] args) {
        Car car = new Car("Toyota", 120);
        car.display();
    }
}
```

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| Java 17+ | Programming Language |
| IntelliJ IDEA / VS Code | IDE |
| Git | Version Control |
| GitHub | Code Hosting |

---

## 📚 Learning Resources

- [Official Java Documentation](https://docs.oracle.com/en/java/)
- [W3Schools Java Tutorial](https://www.w3schools.com/java/)
- [GeeksForGeeks Java](https://www.geeksforgeeks.org/java/)
- [Programiz Java](https://www.programiz.com/java-programming)

---

## 🤝 Contributing

Contributions are welcome! Here's how:

1. Fork the repository
2. Create a new branch → `git checkout -b feature/your-topic`
3. Add your Java program
4. Commit → `git commit -m "Add: topic name"`
5. Push → `git push origin feature/your-topic`
6. Open a Pull Request

---

## 👨‍💻 Author

**kota64453**  
GitHub: [@kota64453](https://github.com/kota64453)

---

## 📄 License

This project is licensed under the **MIT License** — feel free to use and share!

---

⭐ **If this helped you, give it a star!** ⭐
