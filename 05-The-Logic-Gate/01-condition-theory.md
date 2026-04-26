# 🚪 Quest 05: The Logic Gate (If/Else)
### *Teaching the Computer to Choose*

Logic is the "If/Then" of the world. 
* **If** the player touches the lava, **Then** they lose health.
* **If** the player has the golden key, **Then** the door opens.

---

## 📜 The 5-Year-Old Explanation
Imagine you are at a crossroad in a forest. 
There is a sign that says: "If you have a torch, go Left. Otherwise, go Right."

You check your bag. 
* Do you have a torch? **Yes (True)** -> You go Left.
* Do you have a torch? **No (False)** -> You go Right.

In coding, we call these **Booleans** (True/False) and **Conditions** (The Choice).

---

## 🛠️ The Dual-Language Side-by-Side

Both JavaScript and C# use the exact same "Grammar" for basic logic. 

### **The "If" Statement**
```javascript
// JS and C# look identical here!
if (playerHealth <= 0) {
    console.log("Game Over!"); // JS version
    // Console.WriteLine("Game Over!"); // C# version
}
```

### **The "Comparison" Symbols**
To make decisions, we compare numbers.

| Symbol | Meaning | Example |
| :--- | :--- | :--- |
| `==` | Is it Equal? | `score == 100` |
| `!=` | Is it NOT Equal? | `keyCount != 0` |
| `>` | Greater Than | `health > 50` |
| `<` | Less Than | `health < 10` |
| `>=` | Greater or Equal | `level >= 5` |
| `<=` | Less or Equal | `ammo <= 0` |

---

## ⚠️ The "Double Equals" Trap
One of the most common mistakes is using `=` when you mean `==`.
* `x = 10` -> This **gives** x the value of 10.
* `x == 10` -> This **asks** if x is 10.

If you use a single `=` inside an `if` statement, your game will do weird things!

---
[Next Lesson: The Else and Else-If Branches](./02-else-branches.md)
