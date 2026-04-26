# ➕ Math for Mortals: The Operators
### *The Engine of Game Logic*

In games, almost everything is a math problem. 
* *Damage:* `Health - AttackPower`
* *Loot:* `CurrentGold + Reward`
* *Speed:* `Position + Velocity`

---

## 📜 The 5-Year-Old Explanation
Imagine you have a magic calculator. 
* **`+`** adds a brick to your tower.
* **`-`** takes a brick away.
* **`*`** (Multiply) clones your tower.
* **`/`** (Divide) cuts your tower in half.
* **`%`** (Modulo) is the most special: it tells you what is **left over** after you try to share your bricks equally.

---

## 🛠️ The Dual-Language Side-by-Side

Both JavaScript and C# use the exact same symbols for basic math. This is one of the easiest parts of the "Bridge" between the two!

| Operation | Symbol | Example (JS) | Example (C#) |
| :--- | :--- | :--- | :--- |
| **Addition** | `+` | `10 + 5` (15) | `10 + 5` (15) |
| **Subtraction** | `-` | `10 - 5` (5) | `10 - 5` (5) |
| **Multiplication** | `*` | `10 * 2` (20) | `10 * 2` (20) |
| **Division** | `/` | `10 / 2` (5) | `10 / 2` (5) |
| **Remainder (Modulo)**| `%` | `10 % 3` (1) | `10 % 3` (1) |

---

## 🧬 The "Modulo" Secret (`%`)
In game dev, we use `%` constantly to see if a number is **Even or Odd**.
* If `number % 2` is `0`, the number is **Even**.
* If `number % 2` is `1`, the number is **Odd**.

**Use Case:** Making a character flash red every 2nd hit, or giving a bonus every 10th level.

---
[Next Lesson: Increments and Shorthand](./02-increment-shorthand.md)
