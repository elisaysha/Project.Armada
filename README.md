# 🚢 ARMADA – A Military Strategy Game

**Armada** is a Python turn-based strategy game inspired by Battleship. It’s designed to be more challenging and engaging, with special ship abilities, simplified ship placement, and a future plan to add smarter AI and graphics.

---

## 🎯 Why This Game?

I wanted to reimagine Battleship to make it harder and more exciting. Armada is text-based, but includes new mechanics like one-tile ships, special abilities, and resource-based decision making — all coded from scratch.

---

## 👥 Who It’s For

- Players aged 10–16
- People who enjoy thinking games
- Anyone interested in coding or game logic

---

## 🕹️ How to Play

- The game uses an 8×8 board.
- Place your ships by typing in coordinates (e.g. `4 0`).
- Take turns with a bot to guess the enemy’s ship positions.
- You can use ship abilities if that ship is still alive.
- First to sink all enemy ships wins.

---

## 🔫 Ship Abilities

| Ship (Letter) | Ability                                |
|---------------|-----------------------------------------|
| A – Aircraft Carrier | Sends 5 random air strikes         |
| M – Missile Cruiser  | Does area damage                   |
| R – Radar           | Reveals and optionally attacks a ship |
| S – Submarine       | Dives to avoid attacks for one turn |
| D – Destroyer       | Fires 3 extra shots in one turn     |

If a ship is destroyed, its ability is disabled.

---

## 🔄 Gameplay Differences

- All ships only take up **one space** — making them harder to find.
- Abilities require “resources” earned each turn.
- You can only use an ability if that ship is still alive.

---

## 🧠 Code Info

- ~730 lines of Python
- Uses lists, loops, and functions to manage the board and gameplay
- Heavy use of logic and conditions
- Includes comments to explain major sections

---

## 🚧 Things to Improve

- Replace the random bot with a smarter AI that learns patterns
- Add a proper interface or graphics
- Port to other platforms like mobile or Discord
- Make the code more readable and modular

---

## ✅ What Went Well

- The game works as planned and is fun to play
- Got positive feedback from testers
- Almost no major bugs after testing

---

## 💬 What Could Be Better

- The code is long and complex
- Might be confusing for someone reading it for the first time

---

## 🙏 Thanks

Thanks to my teachers and friends who helped test the game and gave suggestions. This took over 100 hours of coding and testing, and I'm proud of how it turned out.

---
