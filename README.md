# 🎮 Block Cascade - Demo Guide

Welcome to **Block Cascade**! This is an interactive puzzle game built with Unity. Here's what to expect and how to play.

---

## 📖 How to Play

### Objective
Collect as many blocks as possible within **5 moves** to maximize your score.

### Gameplay Mechanics

1. **Click a Block** – Tap or click on any colored block on the grid
2. **Match Connected Blocks** – All adjacent blocks of the **same color** are collected together
3. **Earn Points** – You get points equal to the number of blocks collected
4. **Grid Refills** – After 1 second, blocks fall down and new blocks fill empty spaces
5. **Chain Reactions** – If blocks match again after refill, they're automatically collected without using a move (bonus points!)
6. **Use a Move** – Each click costs 1 move (matching single blocks doesn't count)
7. **Game Over** – When you run out of moves, the game ends

### Scoring

- **Match 2 blocks** = 2 points
- **Match 3 blocks** = 3 points
- **Match 10 blocks** = 10 points
- **Chain Reactions** = Bonus points with no move cost!

### Win Strategy

- Look for large clusters of same-colored blocks
- Plan ahead for potential chain reactions
- Use all 5 moves wisely—once moves are gone, game over!

---

## 🎯 What to Expect

### The Grid
- **5 columns × 6 rows** of colored blocks
- 5 different colors randomly assigned
- Blocks fall naturally when others are removed

### Game Interface
- **Score Counter** (top) – Shows total points
- **Moves Counter** (top) – Shows remaining moves (starts at 5)
- **Replay Button** (bottom) – Restarts the game with fresh state

### Visual Feedback
- Blocks disappear immediately when matched
- 1-second pause before refill (so you can see the action)
- Grid slides down smoothly as blocks fall
- New blocks appear at the top

### Chain Reaction Example
1. You click a 5-block cluster → collect them, score 5 points
2. Blocks fall and reorganize
3. 3 red blocks now match at the original position → automatic collection!
4. You get 3 bonus points **without losing a move**

---

## 🎮 Controls

| Action | Input |
|--------|-------|
| Select Block | **Left Click** / **Tap** |
| Restart Game | Click **Replay** button |

---

## ⏱️ Demo Duration

A typical game takes **2–5 minutes** to complete (5 moves at varying speeds).

**Quick Test:** Click a few blocks to see the mechanic in action (takes ~30 seconds)

---

## 🐛 Known Behavior

- **Single block clicks do nothing** – You need at least 2 adjacent blocks of the same color
- **Grid must be full** – All 30 cells start with a block; refill is automatic
- **No undo** – Moves are permanent once made
- **Replay resets everything** – Score and moves restart at 0 and 5

---

## 💡 Tips for Best Experience

1. **Look for corners and edges** – Blocks there often create large clusters
2. **Think vertically** – Matching in one column can trigger cascades
3. **Watch the timer** – 1-second pause lets you see what happens after your move
4. **Try different colors** – Each color behaves the same, no special rules
5. **Test chain reactions** – Experiment with positions to trigger combos

---

## 🔄 Replay & Reset

Hit the **Replay** button anytime to:
- Reset score to 0
- Reset moves to 5
- Clear the grid and generate new blocks
- Start fresh

---

## 📝 Feedback

This demo showcases:
- ✅ Responsive grid-based mechanics
- ✅ Smooth block physics (gravity + refill)
- ✅ Real-time UI updates
- ✅ Chain reaction detection
- ✅ Game state management

Enjoy the puzzle!

---

**Built with:** Unity 6.0 | **Play Time:** 2–5 minutes | **Skill Level:** Casual
