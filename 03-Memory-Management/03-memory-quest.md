# 💎 Quest 03: The Memory Test
### *Visualizing the Stack and Heap*

In this quest, we won't just write code; we will track *where* that code lives in the computer's brain.

---

## 🎯 The Objective
Write a script that creates a **Value Type** (Stack) and a **Reference Type** (Heap), and understand why they behave differently.

---

## 🛠️ Step 1: JavaScript Implementation
Create `MemoryTest.js` in your `/code` folder.

```javascript
// STACK: Simple number
let score = 10; 

// HEAP: An array (list) is an object, so it goes to the Heap
let enemyNames = ["Goblin", "Troll", "Dragon"]; 

console.log("Score is on the Stack: " + score);
console.log("Enemies are on the Heap: " + enemyNames);
```

---

## 🛠️ Step 2: C# Implementation
Create `MemoryTest.cs` in your `/code` folder.

```csharp
using System;

class Program {
    static void Main() {
        // STACK: int is a Value Type
        int playerAge = 25; 

        // HEAP: string is a Reference Type in C#
        string dialogue = "Welcome to the Great Valley!";

        Console.WriteLine("Age (Stack): " + playerAge);
        Console.WriteLine("Dialogue (Heap): " + dialogue);
    }
}
```

---

## 🏆 Quest Complete!
You now understand the "Physical" side of code. You know that simple numbers are fast and "in your hands" (Stack), while complex text and lists are in the "warehouse" (Heap).

---
[Return to Main Menu](../README.md) | [Onward to Quest 04: Math for Mortals](../04-Math-for-Mortals/operators.md)
