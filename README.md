# 📖 LeetBook

### Turn your LeetCode grind into a revision book.

> 💡 **Status:** Idea / Planning stage. Development has not started yet.

## 🧠 The Idea

**LeetBook** is a **Chrome extension** that will let anyone export **all the LeetCode problems they have solved**,
along with **all their accepted solutions**, into a clean **PDF document** in **one click**.

## ❓ The Problem

- LeetCode has **no option to download** your solved problems or your code.
- If you have solved 100+ problems, revising them before interviews means opening each problem one by one.
- Many problems are solved in more than one way (brute force, then optimized), but there is no easy way to see all your approaches together.
- There is no simple way to keep a **backup** of all your work or to **print** it for offline revision.

## ✅ What LeetBook will do

1. The user logs in to LeetCode and clicks the LeetBook button.
2. LeetBook finds **every problem the user has solved**.
3. For each problem, it collects **all the different accepted solutions** (for example,
   brute force and optimized), not just the latest one.
   - Duplicate submissions (the same code submitted again) will be removed automatically.
   - Each approach will show its language, runtime, memory and date, so you can compare them.
   - If you wrote a **note** on a submission in LeetCode, it will be used as the approach name.
   - Users can choose between **"Latest solution only"** and **"All approaches"**.
4. It puts everything into a **PDF document**: a clean revision book with every problem,
   its difficulty, topics and link, and all your approaches.

### 📄 Example: how a problem will look in your LeetBook

    1. Two Sum  (Easy)  ·  Array, Hash Table
       ├── Approach 1 (Brute Force): C++ · Runtime 120 ms · 12 Mar 2026
       └── Approach 2 (Hash Map):    C++ · Runtime 4 ms   · 15 Mar 2026

## 🌟 Why LeetBook will be useful

- 📚 **Easy revision:** all your solutions in one place before interviews or placements
- 🧩 **See your growth:** compare your brute-force and optimized solutions side by side
- 💾 **Backup:** your work stays safe outside LeetCode
- 📈 **Track progress:** see how many Easy / Medium / Hard problems you solved, and in which topics
- 🔒 **Private:** everything will run in the user's own browser. No server, and no passwords shared.
- 🖱️ **Simple:** no coding or setup needed, just one click

## 🧰 Planned Tech Stack

- JavaScript
- Chrome Extensions (Manifest V3)
- LeetCode's GraphQL API
- Hashing (to detect and remove duplicate solutions)

## ⚠️ Disclaimer

LeetBook is not affiliated with LeetCode. It will use LeetCode's unofficial internal API,
which may change at any time.
