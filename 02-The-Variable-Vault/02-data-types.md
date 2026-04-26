# 🧪 The Shapes of Data (Data Types)
### *Knowing your Ints from your Strings*

To build a game, you need different types of boxes for different types of data. Here is how they look in both languages.

---

## 1. Whole Numbers (Integers)
Used for: HP, Level, Ammo, Enemies Killed.
* **JS:** `let health = 100;`
* **C#:** `int health = 100;`

## 2. Decimals (Floats)
Used for: Player Speed, Gravity, Time.
* **JS:** `let speed = 5.5;`
* **C#:** `float speed = 5.5f;`  
> **⚠️ C# Trap:** You MUST put an `f` after the number for a float. If you don't, C# thinks it is a "Double" (a much bigger, heavier number).

## 3. Text (Strings)
Used for: Character Name, Dialogue, Quests.
* **JS:** `let name = "Hero";`
* **C#:** `string name = "Hero";`

## 4. Yes/No (Booleans)
Used for: `isJumping`, `hasKey`, `isGameOver`.
* **JS:** `let isAlive = true;`
* **C#:** `bool isAlive = true;`

---

## 🛠️ How to Remember the Codes (The "Pattern" Method)

**JavaScript Pattern:**
`[Let/Const] [Name] = [Value];`

**C# Pattern:**
`[Type] [Name] = [Value];`

---

## ⚠️ Common Errors (The "Don'ts")

| Error | JavaScript Example | C# Example | The Fix |
| :--- | :--- | :--- | :--- |
| **Type Swap** | `let x = 5; x = "Hi";` | `int x = 5; x = "Hi";` | C# will crash. Keep your data types consistent! |
| **Missing 'f'** | *N/A* | `float x = 1.2;` | Add the `f`: `1.2f`. |
| **Numbers as Words**| `let x = "5";` | `int x = "5";` | `"5"` is text. `5` is a number. Don't mix them up! |

---
[Next Lesson: The Variable Quest](./03-variable-quest.md)
