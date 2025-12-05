---
marp: true
theme: default
class: lead
paginate: true
title: "Software Quality Documentation"
author: "Faiza Tasnim"
---
## Week-1
## Software Quality Introduction

---
# 🧠 Qualityful Software
Creating software is not just about writing code —  
it's about crafting a product that is **reliable**, **maintainable**, and **simple**.

---

## 🔑 The Key to Software Quality: Managing Complexity
> “Complexity is the enemy of reliability.”

- Great software engineers **manage complexity** rather than avoid it.  
- Simplicity makes the system **easier to understand, test, and improve**.  
- Each feature should have a **clear purpose** — unnecessary layers or logic lead to confusion.  

**Good design reduces complexity.**  
**Good progress keeps complexity in control.**

---

## 💡 Qualityful Software Principle: KISS
### *Keep It Simple, Stupid!*

The KISS principle reminds developers to:
- Build only what’s needed.
- Prefer **clarity over cleverness**.
- Use **simple architectures** and **straightforward logic**.
- Make sure anyone joining the project can **understand the code easily**.

**Simplicity = Quality + Maintainability**

---

## 🧩 Software Tools for Quality
Software quality depends on two main tools:

### 1️⃣ Design
- Good design ensures every component has a **defined role**.
- Focus on **modularity**, **reusability**, and **readability**.

### 2️⃣ Process
- Process means **structured and consistent steps** toward achieving quality.
- A clear process helps maintain **stability, discipline, and accountability**.
- Following a well-defined process prevents **confusion and major failures**.
- Continuous review and feedback within the process keep the project **aligned with its goals**.

---

## 👥 The Team Key: No Surprises
A qualityful software team follows the **“No Surprises”** rule:
- Everyone knows what’s happening.
- Communication is open and regular.
- No hidden changes, no secret assumptions.
- Transparency builds **trust** and **accountability**.

> A team without surprises is a team that delivers.

---

## 🌟 Conclusion
Building **qualityful software** means:
- Managing complexity with clear structure.  
- Keeping everything simple through KISS.  
- Using design and progress as tools for excellence.  
- Working as a transparent, surprise-free team.

---

## Week-2
## Software Process & Web Development


---

# ⚙️ PHP + REST API

- Built **11 REST APIs** for student management system project.
- Used **Bearer Token Authentication** for secure communication.
- **Database:** MySQL  
- **Tools:** Postman

---

# 🌐 NGINX Configuration

- **Nginx** used as a high-performance web server and reverse proxy.
- Configured to serve the API and frontend together.

- Hosted API endpoints and tested via browser.

---

# 🧭 Software Process Overview

Software process defines **how software is developed** systematically through a structured framework.

**Key Stages:**
1. Requirements
2. Design
3. Implementation
4. Testing
5. Deployment
6. Maintenance

---

# ⚡ Agile Model

- **Iterative and incremental** model.
- Emphasizes **customer collaboration** and **adaptive planning**.
- Short development cycles called **sprints**.
- Continuous feedback and improvement.


---

# 🔁 Spiral Model

- Combines **iterative development** with **risk analysis**.
- Each phase includes:
  - Planning
  - Risk assessment
  - Engineering
  - Evaluation
- Suitable for **large, high-risk projects**.

---

# 💧 Waterfall Model

- **Sequential development** process.
- Each phase must complete before the next begins.
- Ideal for **projects with well-defined requirements**.

**Phases:**
1. Requirements
2. Design
3. Implementation
4. Verification
5. Maintenance

---

# 🧠 Scrum Framework

- A subset of **Agile methodology**.
- Focused on small teams and sprints.
- Roles:
  - **Product Owner**
  - **Scrum Master**
  - **Development Team**
- Uses **daily standups** and **retrospectives**.

---

# ⚖️ Agile vs Scrum

Agile is a broad philosophy or mindset that emphasizes flexibility, collaboration, and customer satisfaction through continuous delivery of valuable software. Scrum, on the other hand, is a specific framework within Agile that provides a structured approach to implementing Agile principles. 

---

# 🧩 SE Rules Applied - Process

### 1️⃣ Divide and Conquer
- Break down complex systems into **manageable components**.
- Each module handles a **specific task**.

### 2️⃣ Single Responsibility Principle (SRP)
- Every class/module should have **only one reason to change**.
- Improves maintainability and reduces coupling.

---

# 🚧 Only Fools Rush In...

> "We don't construct unless we know what to construct."

### Meaning:
- Requirements and architecture/design must be clearly understood before coding begins.
- Prevents rework, cost overruns, and system inconsistencies.

**Key Practices:**
- Gather detailed **requirements**.
- Prepare **architecture diagrams**.
- Conduct **design reviews** before implementation.

---

# 🎯 Conclusion

- Successful software systems depend on **clear processes**.
- Applying **engineering principles** ensures quality and scalability.
- Combining **modern web technologies (PHP + REST + NGINX)** with **Agile frameworks** leads to efficient project delivery.

---


# WEEK-3
# 🚀 Laravel, Python, OOP & UML

---

# 🧩 What is Laravel?

**Laravel** is a PHP framework used for building web applications using the **MVC**  (Model-View-Controller) architecture.

### ✨ Features
- Elegant syntax
- Built-in authentication
- Routing and middleware
- ORM 
- Blade templating engine

---

# ⚙️ Laravel Installation Steps

### 🪄 Step-by-Step
1. **Install Composer**  
   Download and install Composer 
   👉 [https://getcomposer.org](https://getcomposer.org)
2. **Install Laravel via Composer**  
   ```bash
   composer create-project laravel/laravel student-management
   ```
3. **Run the Development Server**
   ```bash
   cd student-management
   php artisan serve
   ```
   Visit → `http://127.0.0.1:8000`

---

# 🧠 What is ORM?

**ORM** (Object Relational Mapping) allows developers to interact with databases using objects instead of SQL queries.

In Laravel, this is done using Eloquent ORM.

### 🔹 Example
```php
// Model: App\Models\Admin
$user = Admin::find(1);
echo $admin->name;
```

---

# 🛢️ Database Setup in Laravel

### ⚙️ Configuration
1. Open `.env` file
2. Set database credentials:
   ```bash
   DB_CONNECTION=mysql
   DB_HOST=127.0.0.1
   DB_PORT=3306
   DB_DATABASE=student_db
   DB_USERNAME=root
   DB_PASSWORD=
   ```

3. Run migrations:
   ```bash
   php artisan migrate
   ```

---

# 🐍 What is Python?

Python is a high-level, interpreted, and versatile programming language known for its simplicity and readability.

### ✅ Features
- Open-source
- Object-oriented
- Large library support
- Cross-platform

---

# 💻 Python Basic Example

```python
# Simple Python Example
def greet(name):
    print(f"Hello, {name}!")

greet("Faiza")
```

### 🧠 Output:
```
Hello, Faiza!
```

---

# 🧱 OOP – Object-Oriented Programming

OOP organizes code into classes and objects.

### 🔹 Core Concepts
- **Class** – Blueprint for objects  
- **Object** – Instance of a class  
- **Encapsulation** – Hiding internal details  
- **Inheritance** – Reuse behavior from parent classes  
- **Polymorphism** – Same interface, different behavior  
- **Abstraction** – Simplify complex systems  

---

# 🧩 OOP Example in Python

```python
class Car:
    def __init__(self, brand, color):
        self.brand = brand
        self.color = color

    def drive(self):
        print(f"The {self.color} {self.brand} is driving!")

my_car = Car("Toyota", "Red")
my_car.drive()
```

---

# 🔶 UML – Unified Modeling Language

UML is a standardized visual language used to model software systems.

### 🧩 Common UML Diagrams
- **Use Case Diagram** → shows system interactions  
- **Class Diagram** → defines classes and relationships  
- **Sequence Diagram** → shows message flow  
- **Activity Diagram** → models workflow or process  

---

# 🎯 Conclusion

✅ **Laravel** – Web framework for PHP  
✅ **ORM** – Database interaction via objects  
✅ **Database Setup** – Configure `.env` and run migrations  
✅ **Python** – Simple, powerful programming language  
✅ **OOP** – Organize code into reusable classes  
✅ **UML** – Visual modeling tool for system design  

---
# Week-4
# Software Design and OOP Concepts

---

## 1. Object-Oriented Programming (OOP) for Software Design

Object-Oriented Programming (OOP) is a programming paradigm based on the concept of objects. The key principles of OOP—Abstraction, Encapsulation, Inheritance, Polymorphism, and Composition—help structure complex systems effectively and align software design with real-world problems.

---

## 2. Requirements

Software requirements specify what the system should do. They include:

- **Functional Requirements:** Specific behavior or functions of the system (e.g., login, data processing).
- **Non-Functional Requirements:** Constraints or quality attributes (e.g., performance, security, scalability).
- **User Stories / Use Cases:** Requirements in the "Actor-Goal" format to capture how users interact with the system.


---

## 3. Abstraction and Inheritance

**Abstraction:**  
- Hides internal implementation details and exposes only necessary interfaces.  
- Helps reduce complexity and focus on essential features.  

**Example:**  
```python
class Vehicle:
    def start(self):
        pass  # Abstract method
```

---

**Inheritance:**  
- Allows a class (subclass) to inherit attributes and methods from another class (superclass).  
- Promotes code reuse and hierarchical relationships.

**Example:**  
```python
class Car(Vehicle):
    def start(self):
        print("Car engine started")
```

---

## 4. Encapsulation and Dependency Injection

**Encapsulation:**  
- Restricts direct access to object data and exposes functionality via methods.  
- Enhances security, maintainability, and reduces errors.

**Example:**  
```python
class BankAccount:
    def __init__(self, balance):
        self._balance = balance  # Protected attribute
    
    def get_balance(self):
        return self._balance
```
---

**Dependency Injection:**  
- Technique where dependencies are provided to a class rather than created inside it.  
- Reduces tight coupling and improves testability.

**Example:**  
```python
class Service:
    def __init__(self, repository):
        self.repository = repository  # Injected dependency
```

---

## 5. Polymorphism and Composition

**Polymorphism:**  
- Allows objects of different classes to be treated as objects of a common superclass.  
- Supports method overriding and dynamic behavior.

---

**Example:**  
```python
class Dog:
    def speak(self):
        return "Woof!"

class Cat:
    def speak(self):
        return "Meow!"

animals = [Dog(), Cat()]
for animal in animals:
    print(animal.speak())
```
---

**Composition:**  
- Models "has-a" relationships where objects contain other objects.  
- Promotes flexible design over inheritance when appropriate.

**Example:**  
```python
class Engine:
    pass

class Car:
    def __init__(self):
        self.engine = Engine()  # Composition
```

---

## 6. Software Requirements

- Define what system must do and its constraints.
- Serve as a guide for design, implementation, and testing.
- Can be documented as **user stories**, **use case diagrams**, or **requirement specifications**.

---

## 7. Software Testing

Software testing ensures that the system behaves as expected. Key points:

- **Unit Testing:** Tests individual functions or modules.
- **Integration Testing:** Ensures modules work together correctly.
- **System Testing:** Validates the entire system’s functionality.
- **Regression Testing:** Ensures new changes do not break existing functionality.
- **Importance:** Catch bugs early, provide confidence in refactoring, and improve software reliability.

---

## 8. SOLID Principles

**S** - **Single Responsibility Principle (SRP):**  
- A class should have only one reason to change.  
- Improves maintainability and reduces complexity.

**O** - **Open/Closed Principle (OCP):**  
- Classes should be open for extension but closed for modification.  
- Enables adding new functionality without changing existing code.

**L** - **Liskov Substitution Principle (LSP):**  
- Subclasses must be substitutable for their base class.  
- Ensures consistent behavior and reduces bugs when using polymorphism.

---

**I** - **Interface Segregation Principle (ISP):**  
- Clients should not be forced to depend on methods they do not use.  
- Promotes focused, smaller interfaces.

**D** - **Dependency Inversion Principle (DIP):**  
- High-level modules should not depend on low-level modules; both should depend on abstractions.  
- Reduces tight coupling and increases flexibility.

---

## 9. Conclusion

OOP combined with proper requirements and testing ensures robust software design.  
- **Abstraction & Inheritance:** Simplify and reuse code.  
- **Encapsulation & DI:** Protect data and improve testability.  
- **Polymorphism & Composition:** Enable flexible and dynamic behavior.  
- **SOLID Principles:** Promote maintainable, scalable, and high-quality code.  
- **Testing:** Validates that design and implementation meet the requirements.

---
# Week-5
# High-Level Programming, JavaScript & TypeScript

---

# What Is a High-Level Programming Language?
- A high-level programming language is easy for humans to read and write.
- It hides complex machine-level details.
- Focus on *logic* rather than hardware.
- Examples: **Python, JavaScript, TypeScript, React**.

---

# JavaScript (JS)

- JavaScript is a high-level, dynamic, interpreted language.
- Runs in all web browsers.
- Used to make webpages interactive.
- Used in frontend & backend (Node.js).

---
# Pros & Cons: JavaScript
### ✔ Pros
- Easy to learn
- Works in every browser
- Huge community
- Fast development

### ✘ Cons
- No type safety
- Runtime errors
- Hard to maintain large projects

---

# JavaScript Examples
### 1. Print a Message
```js
console.log("Hello World!");
```
### 2. Add Two Numbers
```js
let a = 5;
let b = 10;
console.log(a + b); // 15
```
### 3. Change HTML Text
```js
document.getElementById("title").innerText = "Welcome!";
```

---

# Build a To-Do App Using JavaScript
### Basic Structure
HTML:
```html
<input id="taskInput" placeholder="Add new task" />
<button onclick="addTask()">Add</button>
<ul id="taskList"></ul>
```
---

JavaScript:
```js
function addTask() {
  const input = document.getElementById("taskInput");
  const task = input.value.trim();
  if (!task) return;

  const li = document.createElement("li");
  li.textContent = task;

  document.getElementById("taskList").appendChild(li);
  input.value = "";
}
```

---

# TypeScript (TS)

- TypeScript is JavaScript with types.
- Created by Microsoft.
- Compiles to JavaScript.
- Helps catch errors early with type checking.

---

# Pros & Cons: TypeScript
### ✔ Pros
- Type safety
- Cleaner, scalable code
- Better IDE support
- Great for large projects

### ✘ Cons
- Requires compilation
- Slightly harder to learn
- Extra setup needed

---

# TypeScript Examples
### 1. Add Numbers with Types
```ts
function add(a: number, b: number): number {
  return a + b;
}
```

### 2. Define an Interface
```ts
interface User {
  name: string;
  age: number;
}

const person: User = {
  name: "Faiza",
  age: 25
};
```

---

# Build a To-Do App Using TypeScript
HTML:
```html
<input id="taskInput" placeholder="Add new task" />
<button id="addBtn">Add</button>
<ul id="taskList"></ul>
```
---

TypeScript (compile to JS):
```ts
const input = document.getElementById("taskInput") as HTMLInputElement;
const addBtn = document.getElementById("addBtn") as HTMLButtonElement;
const list = document.getElementById("taskList") as HTMLUListElement;

function addTask(): void {
  const task: string = input.value.trim();
  if (!task) return;

  const li = document.createElement("li");
  li.textContent = task;

  list.appendChild(li);
  input.value = "";
}

addBtn.addEventListener("click", addTask);
```

---

# JavaScript vs TypeScript

JavaScript → Dynamic typing
TypeScript → Static typing with defined types
JavaScript → Errors found at runtime
TypeScript → Errors caught during development/compilation
JavaScript → Easier for beginners
TypeScript → Moderate learning curve due to type system
JavaScript → Basic tools
TypeScript → Advanced IDE support and better developer tools
JavaScript → No compilation required
TypeScript → Must be compiled into JavaScript before running


---

# Conclusion
- High-level languages make development easier.
- JavaScript is simple and flexible, great for beginners.
- TypeScript adds types for safer, scalable code.
- Both can build powerful apps like To-Do lists.

---

# Week-6
# React

---

## What Is React?

- React is a JavaScript library for building user interfaces.

- Developed by Facebook (Meta).

- Based on components.

- Uses a virtual DOM to efficiently update UI.

- Allows fast, interactive web apps.

---

## Why React? (Advantages)

### ✅ Pros

- Component reusability

- Fast rendering (Virtual DOM)

- Strong community & ecosystem

- Easy integration with APIs

- Great for scalable apps

---

## React Disadvantages

### ❌ Cons

- JSX learning curve

- Frequent library updates

- Not a full framework (needs external libraries)

- Setup can be complex for beginners

---

## JavaScript vs TypeScript vs React
Key Differences:

### 1. JavaScript

- A programming language

- Dynamic typing

- Runs in browser directly

### 2. TypeScript

- Superset of JS

- Static typing

- Must compile to JS

---

### 3. React

- A UI library

- Uses JS/TS

- Builds interactive web apps

---

## Simple React ToDo App Example

```react
import { useState } from "react";

function App() {
  const [task, setTask] = useState("");
  const [list, setList] = useState([]);

  const addTask = () => {
    if (task.trim() === "") return;
    setList([...list, task]);
    setTask("");
  };

```
---

```
  return (
    <div>
      <h2>React ToDo App</h2>
      <input
        value={task}
        onChange={(e) => setTask(e.target.value)}
        placeholder="Enter task"
      />
      <button onClick={addTask}>Add</button>

      <ul>
        {list.map((item, i) => (
          <li key={i}>{item}</li>
        ))}
      </ul>
    </div>
  );
}

export default App;
```
---

## Conclusion

- JavaScript = programming language

- TypeScript = JavaScript + types

- React = library for building UI

- React + JS/TS → powerful way to create modern web apps

---

# Week-7
## 🌐 GitHub, GitHub.io, Docker, and Hugo


---

## 💻 What is GitHub?

A cloud-based platform for version control using **Git**

**Purpose:**  
- Track changes  
- Collaborate with developers  
- Manage code repositories

**Key Features:**  
- Repositories (projects)  
- Branching & merging  
- Pull requests & code reviews  
- Issue tracking


---

## 🌐 What is GitHub.io?

**Definition:**  
GitHub Pages – free hosting for static websites

**URL Format:** `username.github.io`

**Purpose:**  
- Deploy websites directly from GitHub repositories

**Use Cases:**  
- Personal portfolio  
- Project documentation  
- Blogs

---

## 🐳 What is Docker?

**Definition:**  
A platform to build, ship, and run applications in **containers**

**Key Concept:**  
Containers package the app + dependencies → run anywhere

**Benefits:**  
- Consistency across environments  
- Lightweight vs virtual machines  
- Easy scaling & deployment



---

## ⚡ What is Hugo?

**Definition:**  
A fast static site generator written in **Go**

**Purpose:**  
- Converts Markdown content → HTML websites

**Benefits:**  
- Blazing fast builds  
- Easy theming & templates  
- Works well with GitHub Pages



---

## 🔄 How These Work Together

1. **Development:** Write content in Markdown, build site with Hugo  
2. **Version Control:** Store code & content on GitHub  
3. **Hosting:** Deploy generated site on GitHub Pages (GitHub.io)  
4. **Containerization (Optional):** Docker to test Hugo site locally

  
```
[Markdown + Hugo] --build--> [Static HTML] --push--> [GitHub Repo] --deploy--> [GitHub.io]
                                         \
                                          \
                                          [Docker Container for Testing]
```

---

## ✅ Benefits of Using These Together

- **Fast Deployment:** Hugo + GitHub Pages → instant publishing  
- **Collaboration:** Multiple contributors on GitHub  
- **Portability:** Docker ensures consistent environments  
- **Automation:** CI/CD pipelines can rebuild & deploy automatically

---

## 🏁 Conclusion

- **GitHub:** Code management & collaboration  
- **GitHub.io:** Free static website hosting  
- **Docker:** Containerized app environment  
- **Hugo:** Fast static site generator  

