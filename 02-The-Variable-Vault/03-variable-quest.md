# 💎 Quest 02: The Variable Vault
### *Creating your Character Sheet*

In this quest, you will build a mini "Character Sheet" in the computer's memory using both languages.

---

## 🎯 The Objective
Create 4 variables in both JS and C# to represent a player:
1.  **Name** (Text)
2.  **Level** (Whole Number)
3.  **Gold** (Decimal Number)
4.  **HasSword** (Yes/No)

---

## 🛠️ Step 1: JavaScript Implementation
Create a file in your `/code` folder named `Variables.js`. Paste and run:

```javascript
let playerName = "Aria";
let playerLevel = 15;
let goldCount = 150.25;
let hasSword = true;

console.log("--- Player Stats (JS) ---");
console.log("Name: " + playerName);
console.log("Level: " + playerLevel);
console.log("Gold: " + goldCount);
console.log("Sword: " + hasSword);
```

---

## 🛠️ Step 2: C# Implementation
Create a file in your `/code` folder named `Variables.cs`. Paste and run:

```csharp
using System;

class Program {
    static void Main() {
        string playerName = "Aria";
        int playerLevel = 15;
        float goldCount = 150.25f;
        bool hasSword = true;

        Console.WriteLine("--- Player Stats (C#) ---");
        Console.WriteLine("Name: " + playerName);
        Console.WriteLine("Level: " + playerLevel);
        Console.WriteLine("Gold: " + goldCount);
        Console.WriteLine("Sword: " + hasSword);
    }
}
```

---

## 🏆 Quest Complete!
You have successfully taught the computer how to "remember" game data. This is the foundation of every inventory system, health bar, and score counter ever made!

---
[Return to Main Menu](../README.md) | [Onward to Quest 03: Memory Management](../03-Memory-Management/stack-vs-heap.md)
