# Fluent Minesweeper

A Timeless Classic, recreated to match the design standards of today, inspired heavily by Microsoft Fluent Design System and macOS Sequoia (like my other projects). 

## How does it look?
### Light Mode:
<img width="791" height="819" alt="image" src="https://github.com/user-attachments/assets/31b17800-fd74-4597-b9f7-d74766059389" />

### Dark Mode:
<img width="657" height="743" alt="image" src="https://github.com/user-attachments/assets/85f3237b-438b-4d9c-bacf-c35e636348b7" />

[![Click here to play](https://img.shields.io/badge/Run-Game-brightgreen?style=for-the-badge)](https://tonystark965-404.github.io/Fluent-Minesweeper/)

## How to Play?
- Click on the Run Game link and play.
- Left clicking reveals a cell.
- Right clicking flags a cell.
- While revealing a cell, if you get a mine, it's game over, Restart by clicking the face emoji at the top.
- While revealing a cell, blank or numbered cells are safe.
- Find all of the numbered/empty cells while avoiding the cells with mines, or flag all the cells with mines to win. 

## What features does it have?
- A consistent design language, inspired by Windows 11 and MacOS Sequoia.
- Classic Minesweeper gameplay (including timer and mine flagging).
- Light and Dark modes.
- Three difficulty systems: Beginner (9x9 grid with 10 mines), Intermediate (16x16 grid with 40 mines) and Expert (22x22 grid with 80 mines).
  
## How can I run it locally and modify it?
   Easy, just do this:
   ```bash
   git clone https://github.com/TonyStark965-404/Fluent-Minesweeper.git
   cd fluent-minesweeper
```
Open index.html in your browser to play or
open in VS Code or a similar editor to modify.

## How does it work?
Fluent Minesweeper is built with HTML, CSS JavaScript, where the theme is stored locally using localStorage.
