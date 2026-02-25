# UseCase9 – Recursive Palindrome Checker

## 🧠 Objective
Validate whether a given string is a palindrome using recursion.

---

## 🎯 Goal
Use a recursive method to compare characters from the start and end of the string, moving inward until a base condition is reached.

---

## 🔄 Flow of Execution

1. Define the input string  
2. Call a recursive method with start and end indices  
3. Compare characters at both positions  
4. If mismatch → return false  
5. If start ≥ end → base condition → return true  
6. Continue recursive calls shrinking the range  
7. Display result  

---

## 📚 Key Concepts Used

### Recursion
A technique where a method calls itself to solve smaller instances of the same problem.

### Base Condition
Stops recursive calls and prevents infinite recursion.

### Call Stack
The memory structure used by the JVM to manage recursive method calls.

### Divide and Conquer
Each recursive call reduces the problem size until the base condition is reached.

---

## 🛠 Data Structure Used
- Call Stack

---

## ⚙️ How to Run

### Compile:
```
javac UseCase9PalindromeCheckerApp.java
```

### Run:
```
java UseCase9PalindromeCheckerApp
```

---

## 📌 Example

### Input
```
madam
```

### Output
```
Input : madam
Is Palindrome? : true
```

---

## 🚀 Learning Outcome

This implementation demonstrates:

- Recursive problem solving  
- Proper base condition handling  
- Understanding of call stack behavior  
- Clean divide-and-conquer logic  

---

## 👨‍💻 Author

Dito Dileep  
B.Tech Computer Science (AI & ML)  
SRM Institute of Science and Technology
