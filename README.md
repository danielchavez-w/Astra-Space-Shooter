# 🚀 Astra: Space Shooter

> A retro-inspired 2D space shooter built with HTML5 Canvas. (WEB ONLY: PC & MAC)

### ⌨️ Controls
| Action | Key |
| :--- | :--- |
| **Move** | `W`, `A`, `S`, `D` or Arrow Keys |
| **Shoot** | `Spacebar` |

### 🕵️ Secret Commands
| Action | Key | Note |
| :--- | :--- | :--- |
| **Instant Win** | `K` | *I don't suggest it! Ruin the fun at your own risk.* ⚠️ |
| **Clear Leaderboard** | `Shift` + `Backspace` (PC) <br> `Shift` + `Delete` (Mac) | Wipes all local scores. |

### 🎮 Game

**Objective:** Pilot the Astra fighter and defend the sector against alien waves. 

* **🏆 Victory Condition:** Survive **3 Acts** (9 Rounds total).
* **💀 Game Over:** Three lives. No continues. Reboot system (Try again) when game is over. 

### 🔫 Systems & Combat
You are equipped with the **Triton-Class Starfighter**, featuring three distinct firing modes:
1.  **Blaster Tap (1st Firing Mode):** Tap spacebar. Reliable, no cooldown. Consistent firing. 
2.  **Blaster Continuous (2nd Firing Mode):** Hold down spacebar. 7-8 shots of firing then ship turns red and enters cooldown. 
3.  **Blaster Rapid (3rd Firing Mode):** Rapidly tap the spacebar and you get 5 shots at your speed. After 5 quick shots, the cooldown is engaged. 

### 📊 Leaderboard & Stats
The game features a persistent **Local Leaderboard** that tracks your combat efficiency.

**Your Pilot Profile tracks:**
* **High Score:** Total points from enemy kills. 
* **Accuracy:** Precision rating (Shots Hit / Shots Fired).
* **Kills Per Life:** Your average lethality before destruction.

> **Had a satisfying run? Post your stats on the leaderboard!** 

---

### 🛠 Developer Iteration Notes
> "During playtesting, I observed that players were repeatedly spamming the firing mechanic, which disrupted game balance. To address this, I implemented a firing cooldown system that limits consecutive shots and enforces pacing."

> "During testing, I observed that enemy explosion particles and player projectiles were being cleared immediately at the end of each round. This caused an abrupt visual cutoff before the victory state. I adjusted the round transition logic to allow active particles and projectiles to fade out naturally before displaying the “Victory!” message, improving visual continuity."

---
[**➡️ PLAY THE GAME HERE**](https://danielchavez-w.github.io/Astra-Space-Shooter/)
