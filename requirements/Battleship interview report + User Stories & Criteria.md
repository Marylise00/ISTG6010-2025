 Battleship Requirements Interview Report

**Interviewer:** Marylise Iris  
**Interviewee:** Battleship Game Enthusiast (Simulated)  
**Date:** March 20, 2025  

---

## Interview Transcript

**Q1: Can you explain the basic rules of Battleship?**  
**A:** Sure! Battleship is a 2-player guessing game. Each player places a fleet of ships on their grid without the other seeing. Players then take turns guessing coordinates on the opponent's grid, trying to locate and sink their ships. The first player to sink all of the opponent’s ships wins.

---

**Q2: What kinds of ships are typically used in the game?**  
**A:** There are 5 ships per player:  
- Carrier (5 spaces)  
- Battleship (4 spaces)  
- Cruiser (3 spaces)  
- Submarine (3 spaces)  
- Destroyer (2 spaces)  

Each ship takes up a specific number of grid squares and can be placed either horizontally or vertically.

---

**Q3: What are the most important gameplay actions?**  
**A:** The main actions include:  
- Placing ships on the grid  
- Calling out a coordinate on the opponent’s grid  
- Marking hits or misses  
- Tracking the status of your own ships  
- Winning the game when all enemy ships are sunk

---

**Q4: What features would make the game more user-friendly as a software version?**  
**A:** A clean grid layout, color indicators for hits/misses, simple drag-and-drop for placing ships, turn indicators, and maybe even a "fog of war" style animation would all improve the experience.

---

**Q5: What are some common challenges or frustrations players face?**  
**A:** Sometimes players forget where they've already guessed. Also, it can be tricky to track which ships are left. If the grid is too cluttered or the interface isn't responsive, it ruins the strategic feel.

---

•	**Q6: What would improve the digital experience of Battleship?**
**A:** Visual feedback, automatic ship tracking, and an onboarding tutorial would help.

User Stories and with Acceptance Criteria

1. Player Setup
**User Story:**
As a player, I want to place my ships on a grid so that I can prepare for the game.
**Acceptance Criteria:**
•	- I can drag or click to position 5 ships of various sizes.
•	- Ships cannot overlap or be placed off-grid.
•	- I can confirm or reset my setup before starting.
•	- I can choose a random auto-placement option to set ships quickly.

2. Taking a Turn
**User Story:**
As a player, I want to call out a grid coordinate on my opponent’s board so I can try to hit their ships.
**Acceptance Criteria:**
•	- I can click on a coordinate once per turn.
•	- My turn ends after I fire a shot.

3. Shot Feedback
**User Story:**
As a player, I want to get immediate feedback after I take a shot so that I know the result.
**Acceptance Criteria:**
•	- I receive a message saying whether the shot was a hit, miss, or if a ship was sunk.
•	- The feedback is visual and/or audio (e.g., sound or highlight).

4. Tracking My Moves
**User Story:**
As a player, I want to track which coordinates I’ve guessed so that I don’t repeat moves.
**Acceptance Criteria:**
•	- Misses are marked with one icon/color.
•	- Hits are marked differently.
•	- I cannot re-guess the same spot.

5. Winning the Game
**User Story:**
As a player, I want to be notified when I win or lose so that I know the game has ended.
**Acceptance Criteria:**
•	- The system announces the winner.
•	- All ship locations are revealed at the end.
•	- I have the option to restart the game or exit.

6. Tutorial for New Players
**User Story:**
As a new player, I want a guided tutorial so that I can learn how to play before starting a real game.
**Acceptance Criteria:**
•	- A tutorial explains ship placement, taking turns, and tracking moves.
•	- I can choose to skip or repeat the tutorial.


