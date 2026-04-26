# 💎 Quest 04: The Combat Calculator
### *Calculating Damage and Loot*

In this quest, you will build a mini combat log that calculates a player's new health after an attack and their new gold after a bonus.

---

## 🎯 The Objective
1.  Start with `100` Health.
2.  Subtract `25` Damage.
3.  Double the remaining health (Power-up!).
4.  Calculate the remainder of `10 / 3` to find a "Hidden Seed."

---

## 🛠️ Step 1: JavaScript Implementation
Create `CombatMath.js` in your `/code` folder.

```javascript
let health = 100;
health -= 25;      // Health is now 75
health *= 2;       // Health is now 150
let seed = 10 % 3; // Seed is 1

console.log("JS Final Health: " + health);
console.log("JS Hidden Seed: " + seed);
```

---

## 🛠️ Step 2: C# Implementation
Create `CombatMath.cs` in your `/code` folder.

```csharp
using System;

class Program {
    static void Main() {
        int health = 100;
        health -= 25;      // Health is now 75
        health *= 2;       // Health is now 150
        int seed = 10 % 3; // Seed is 1

        Console.WriteLine("C# Final Health: " + health);
        Console.WriteLine("C# Hidden Seed: " + seed);
    }
}
```

---

## 🏆 Quest Complete!
You have mastered the basic physics of data! You can now move, hurt, heal, and reward your players using the power of math.

---
[Return to Main Menu](../README.md) | [Onward to Quest 05: The Logic Gate](../05-The-Logic-Gate/if-else-logic.md)
