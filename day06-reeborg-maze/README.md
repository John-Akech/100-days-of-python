# Maze Solver

Day 6 of #100DaysOfCode

A Python solution for navigating Reeborg’s World **Maze Challenge**.  
The robot follows the "right-hand rule" to explore and find the path to the goal.

---

## How It Works
- Define a `turn_right()` function using repeated left turns.
- Move forward while possible, otherwise:
  - If the path to the right is clear → turn right and move.
  - If the path ahead is clear → move forward.
  - Otherwise → turn left.

This ensures the robot keeps exploring until it reaches the goal.


## Example World
You can test the code here:  
👉 [Reeborg’s Maze Challenge](https://reeborg.ca/reeborg.html?lang=en&mode=python&menu=worlds%2Fmenus%2Freeborg_intro_en.json&name=Maze&url=worlds%2Ftutorial_en%2Fmaze1.json)

---

## Project Info
- **Day:** 6  
- **Topic:** Problem Solving with Loops and Conditionals  
- **Concepts Used:** Functions, While Loops, If/Else Logic  
