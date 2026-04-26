# ♻️ The Garbage Collector (GC)
### *The Janitor of your Game*

If you keep putting toys (data) in the Toy Chest (Heap) and never take them out, the chest gets full and the game crashes. This is called a **Memory Leak**.

---

## 📜 The 5-Year-Old Explanation
Imagine you have a robot janitor. Every few minutes, he walks around the room. If he sees a toy that nobody is playing with, he throws it in the bin to make room for new toys. 

In coding, this janitor is called the **Garbage Collector**.

---

## 🛠️ JS vs C# Janitors

### **JavaScript (The Invisible Janitor)**
In JS, the janitor is very active. Since JS was made for browsers, it tries to clean up constantly so your browser tab doesn't freeze. You don't have much control over him.

### **C# (The Professional Janitor)**
In C# (and Unity), the Garbage Collector is a big deal. If the janitor starts cleaning while your player is in the middle of a boss fight, the game might "stutter" for a millisecond. 
* **Pro Tip:** Pro game devs try to create as little "garbage" as possible so the janitor never has to work during gameplay!

---

## ⚠️ The "Memory Leak" Trap
A memory leak happens when you tell the computer to remember something, but you forget to tell it you're done with it. The janitor thinks you're still playing with it, so he never cleans it up.

**How to avoid it:**
1. **JS:** Don't create global variables if you don't need them.
2. **C#:** Be careful with `static` variables that live forever.

---
[Next Lesson: The Memory Quest](./03-memory-quest.md)
