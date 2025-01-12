## Game Name: **Code Knights**

### Overview

**Code Knights** is a tabletop strategy game for 2–4 players. Like chess, it’s played on a grid-based board, but instead of moving each piece manually, players **assemble ‘command blocks’** that dictate their pieces’ movements. Then they watch these commands execute step-by-step on the board, adjusting or “debugging” their strategy each turn.

### Components

1. **Game Board**  
   - An 8×8 or 10×10 grid (can be adjusted for shorter or longer play).  
   - Optionally include **obstacle tiles** (e.g., walls, water, or “fog”) that pieces can’t pass unless specifically instructed.

2. **Player Pieces**  
   - Each player starts with a set number of pieces (e.g., **1 King, 2 Knights, 2 Rooks**, or custom-coded “Code Knights”).  
   - For younger players, you might simplify the set (e.g., each has 1 King and 2 Knights).  

3. **Command Blocks (Cards or Tiles)**  
   - **Movement Blocks**: *Move forward*, *Move backward*, *Turn left/right*, *Jump*, etc.  
   - **Conditional Blocks**: *If (obstacle) ahead, do X; else do Y*, or *If (enemy piece) in range, do X; else do Y*.  
   - **Loop Blocks** (optional or advanced): *Repeat X times*, *Repeat until condition is met*.  
   - **Action Blocks**: *Capture piece*, *Toggle bridge*, *Build wall*, etc. (depending on the theme).  

4. **Programming Grid or Board Section**  
   - Each player has a small personal “command area” (like a mini board or “programming track”) where they line up the blocks that their piece(s) will execute when it’s their turn.

---

## Setup

1. **Arrange the Board**  
   - Place all players’ pieces in their designated start rows (similar to chess), or create a custom scenario (e.g., each player’s King in a corner, with obstacles in the middle).

2. **Deal Command Blocks**  
   - Each player gets a starting hand or set of command blocks (e.g., 3 Movement, 1 Conditional).  
   - Remaining blocks can form a shared “draw pile,” or you can allow trading/purchasing of additional blocks as the game progresses.

3. **Objective**  
   - **Classic**: Capture or corner the opponent’s King.  
   - **Alternate**: Accumulate points by capturing enemy pieces or reaching key squares.

---

## Gameplay

1. **Command Phase** (Programming)  
   - On a player’s turn, they **assemble or modify** the command sequence for **one** of their pieces.  
   - They lay down command blocks in a row (like Scratch’s code blocks) indicating a step-by-step program (e.g., *Move Forward* → *If obstacle ahead, Turn Right* → *Move Forward*).  
   - **Limit** the number of blocks per turn (e.g., max 3–5 commands in a single sequence) to keep it accessible and quick.

2. **Execution Phase**  
   - Once the player finalizes their block layout, they **execute** the commands in order:  
     1. **First** block triggers, the piece moves or acts.  
     2. **Check** for collisions, captures, or new conditions after each step.  
     3. Proceed to the **next** block, and so on, until the sequence is complete or the piece can no longer move (e.g., it’s blocked or captured).  
   - Other players watch and adapt their future strategies based on how the moves unfold.

3. **Capture & Conflict**  
   - If a piece moves onto a square occupied by an opposing piece, that piece is captured (removed from the board) just like in chess—unless your program instructs otherwise (e.g., a “skip capture” block might exist for advanced variants).  
   - Conditionals let you decide how to handle conflict (e.g., *If (enemy piece) in front, Capture; else Move Forward*).

4. **Scoring / Victory**  
   - In the **classic** victory condition, capturing the opponent’s King ends the game.  
   - Alternatively, award **points** for each enemy piece captured, plus a bonus for capturing or cornering the King.

---

## How This Encourages Algorithmic Thinking

1. **Scratch-Like Sequencing**  
   - Players literally line up **blocks** (movement, actions, conditions) to create short programs. They must think in terms of **step-by-step logic**, just like coding in Scratch.

2. **Conditionals and Branching**  
   - The availability of **if-then** blocks teaches players to consider branching logic. For example, *If there’s a piece ahead, capture it; else move forward* fosters an understanding of how programs react to changing conditions.

3. **Debugging**  
   - Seeing your piece crash into an obstacle or miss a capture because of the wrong block sequence mimics real programming: you’ll rearrange the “code” next turn to fix the mistake.

4. **Iteration and Loops** (for advanced play)  
   - Introducing **loop** blocks teaches iterative concepts. For instance, *Repeat ‘Move Forward’ until you hit an obstacle* is a direct parallel to while-loops in coding.

5. **Spatial Reasoning and Strategy**  
   - Like chess, you must **plan ahead** for your opponent’s potential moves. The presence of blocks, conditionals, and limited sequence length adds an extra layer of puzzle-solving.

---

## Possible Variations & Extensions

1. **Solo Puzzles**  
   - Provide puzzle boards with a fixed layout of obstacles and enemy “dummy” pieces. The goal is to capture or avoid them using minimal commands. Perfect for self-paced learning and challenge modes.

2. **Team Play**  
   - Split players into teams of 2–3. Each player programs one piece for the team. Communication and negotiation become key, teaching collaborative problem-solving.

3. **Varying Complexity**  
   - **Beginner**: Only allow Move Forward, Turn Left/Right blocks, and basic captures—no conditionals.  
   - **Intermediate**: Add If-Then blocks (obstacle detection, enemy detection).  
   - **Advanced**: Introduce loops, multiple condition checks, special terrain interactions (bridges, teleporters, rotating tiles, etc.).

4. **Digital Companion App**  
   - For even more accessibility, a free app can illustrate how block sequences transform into piece movements. This can be especially helpful for younger players or visually simulating complex paths.

---

## Summary

**Code Knights** merges the strategic depth of a **chess-like** board game with the **visual, block-based programming** style of Scratch. By assembling command blocks, players learn critical coding ideas—sequencing, conditionals, loops, and debugging—while competing in a fun, social environment. The game can be simplified for beginners or ramped up for advanced learners, making it an **accessible** yet **deep** introduction to **algorithmic thinking**.
