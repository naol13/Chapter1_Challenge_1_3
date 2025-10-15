
# Chapter1_Challenge_1_3 – The Dungeon Game 

## 🧩 Project Overview
This project is a simple **text-based dungeon adventure game** written in Java.  
The player explores **five rooms**, each containing a random event that affects their health.  
The challenge demonstrates Java concepts from Chapter 1, such as **loops, conditionals, switch statements, random number generation, and user input**.

---

## 🎯 Objective
Your mission is to:
1. Set the player's starting health to **100**.
2. Use a **for loop** to simulate 5 rooms.
3. Randomly determine events using a number between 1 and 3:
   - **1 → Trap:** health -= 20  
   - **2 → Healing potion:** health += 15 (capped at 100)  
   - **3 → Monster battle:** player must guess a number (1–5) using a **do-while loop** until correct.
4. Use a **switch statement** to handle each event.
5. Use a **break statement** if the player’s health reaches 0 or below (defeat).
6. If the player survives all rooms, announce victory and remaining health.

---

## 🧠 Concepts Demonstrated
- **for loop** – iterates through 5 rooms  
- **do-while loop** – keeps asking for guesses until the correct number is entered  
- **switch statement** – determines which event happens in each room  
- **Random class** – generates random numbers for events and monsters  
- **Scanner class** – handles user input  
- **if / break logic** – ends the game when health reaches 0  

---

## 🕹️ How to Play
1. Run the program in **NetBeans IDE** (Project: `Chapter1_Challenge_1_3`).  
2. Follow the text prompts in the console.
3. In each room:
   - You may trigger a **trap**, **find a potion**, or **encounter a monster**.
   - If you face a monster, guess numbers between 1–5 until you win.
4. Survive all 5 rooms to win the game!

---

---

## ⚙️ Technologies Used
- **Language:** Java  
- **IDE:** Apache NetBeans  
- **JDK:** 17 or higher  
- **Classes Used:** `Scanner`, `Random`

**Most challenging part:**  
Implementing the monster guessing logic and ensuring proper loop termination.

**What I enjoyed:**  
Simulating random game events and seeing the outcomes change each time I run the program.

---

## 🗂️ GitHub Repository
You can find this project here:  
`https://github.com/naol13/Chapter1_Challenge_1_3`


