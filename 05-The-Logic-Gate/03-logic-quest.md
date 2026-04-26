# 💎 Quest 05: The Security Gate
### *Coding a Password System*

In this quest, you will build a security system that checks a player's level and a secret code.

---

## 🎯 The Objective
1.  Check if `playerLevel` is 10 or higher.
2.  If they are level 10+, check if their `secretCode` is correct.
3.  Print different messages for "Access Granted," "Level Too Low," or "Wrong Code."

---

## 🛠️ Step 1: JavaScript Implementation
Create `SecurityGate.js` in your `/code` folder.

```javascript
let playerLevel = 12;
let secretCode = "Swordfish";

if (playerLevel >= 10) {
    if (secretCode == "Swordfish") {
        console.log("JS: Welcome, Master.");
    } else {
        console.log("JS: Correct Level, but Wrong Code!");
    }
} else {
    console.log("JS: You are too weak to enter!");
}
```

---

## 🛠️ Step 2: C# Implementation
Create `SecurityGate.cs` in your `/code` folder.

```csharp
using System;

class Program {
    static void Main() {
        int playerLevel = 12;
        string secretCode = "Swordfish";

        if (playerLevel >= 10) {
            if (secretCode == "Swordfish") {
                Console.WriteLine("C#: Welcome, Master.");
            } else {
                Console.WriteLine("C#: Correct Level, but Wrong Code!");
            }
        } else {
            Console.WriteLine("C#: You are too weak to enter!");
        }
    }
}
```

---

## 🏆 Quest Complete!
You have successfully created "Decision Trees." Your game can now tell the difference between a winner and a loser, a hero and a villain!

---
[Return to Main Menu](../README.md) | [Onward to Quest 06: The Switchboard](../06-The-Switchboard/switch-logic.md)
