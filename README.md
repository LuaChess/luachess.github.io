<div align="center">

<img src="https://luachess.github.io/assets/luachess.png" alt="LuaChess logo" width="160">

# LuaChess

### Play chess in your browser. Climb from Knight to King.

Pick a time control, face a bot matched to your rating, make it look the way you like, and watch the losing king go down in style.

[![Play now](https://img.shields.io/badge/▶_Play_now-luachess.github.io-81b64c?style=for-the-badge)](https://luachess.github.io/)
![HTML](https://img.shields.io/badge/HTML-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![No install](https://img.shields.io/badge/install-none-302e2b?style=flat-square)
![License](https://img.shields.io/badge/cost-free-3b82f6?style=flat-square)

<img src="https://luachess.github.io/assets/luachess1.png" alt="LuaChess gameplay screenshot" width="860">

</div>

---

## Contents

- [About](#-about)
- [Quick start](#-quick-start)
- [Features](#-features)
- [Ranks](#-ranks)
- [Customization](#-customization)
- [Controls](#-controls)
- [Privacy and saved data](#-privacy-and-saved-data)
- [How it works](#-how-it-works)
- [Run it locally](#-run-it-locally)
- [Contributing](#-contributing)

---

## ♟️ About

LuaChess is a free chess site that runs entirely in your browser. There is no account to create, nothing to install and no server to wait on. Open the page, choose a time control and start playing.

It is built around a simple loop: **play, win, gain rating, earn a rank**. The bot you face is matched to your current rating, so games stay close. Everything else, from the board colors to the way a king is checkmated, is up to you.

## 🚀 Quick start

1. Open **[luachess.github.io](https://luachess.github.io/)**.
2. Choose **Bullet**, **Blitz** or **Rapid**.
3. Play. Your rating starts at **100** and goes up as you win.

## ✨ Features

### Play

| | |
|---|---|
| ⏱️ **Three time controls** | Bullet (1 min), Blitz (3 min) and Rapid (10 min), each with its own separate rating. |
| 🤖 **Rating-matched bot** | The opponent scales with your rating. Weaker bots look one move ahead and make deliberate mistakes; stronger ones search deeper. |
| 📋 **Full chess rules** | Legal-move checking, castling, en passant, promotion, check, checkmate, stalemate and draws. |
| 👑 **Pawn promotion** | Pick a queen, rook, bishop or knight when a pawn reaches the last rank. |
| ⚡ **Premoves** | Optional. Queue your next move while the bot is thinking. Click the pre-moved piece to cancel it. |
| 🔁 **Next round** | Jump straight into the next game after each result. |
| 🏳️ **Resign** | Give up a game at any time. |

### Learn and review

| | |
|---|---|
| 📜 **Move list** | Every move is recorded in standard notation as you play. |
| 📖 **Opening names** | The current opening is shown above the move list, from the King's Pawn to the Queen's Gambit and many more. |
| ⏮️ **Game review** | Step through any finished game with the on-screen buttons or the left and right arrow keys. |
| 🏹 **Board arrows** | Right-click and drag to draw arrows on the board, and pick from several colors. |
| ♟️ **Captured pieces** | See what each side has taken and who is ahead in material. |
| 🧪 **Simulation mode** | A free sandbox board where you move both sides, with undo, flip and reset. |

### Profile and progress

| | |
|---|---|
| 👤 **Player profile** | Set your name and upload a profile picture. |
| 📈 **Ratings and ranks** | Track a separate rating for Bullet, Blitz and Rapid, and earn rank badges as you climb. |
| 🗂️ **Game history** | Browse past results, opponents, move counts and dates, and reopen any game for review. |
| 🔥 **Stats** | Win rate and win or loss streaks at a glance. |

### Style

| | |
|---|---|
| 🎨 **19 board themes** | Solid colors plus textured Paper, Wood and Metal boards. |
| ♞ **7 piece styles** | Classic, Neo, Staunton, Paper, Luca, Metal and Blind. |
| 💥 **16 checkmate animations** | The beaten king topples, bursts, burns, gets sliced, takes a trapdoor and more. |
| 😱 **Check reactions** | Your king can shake, look shocked or get dizzy when it is put in check. |
| 🚃 **5 movement styles** | Slide, instant, jump, minecart and portal. |
| 🔊 **Move sounds** | Default, Metal, Marble and Paper. |
| 📱 **Responsive layout** | Works on desktop, tablet and phone. |

## 🏆 Ranks

Ratings start at 100. Reach 800 to earn your first rank. The same badges are shown next to the bot, so you always know what you are up against.

| Rank | Rating |
|:---:|:---:|
| ♘ **Knight** | 800+ |
| ♗ **Bishop** | 1200+ |
| ♖ **Rook** | 1600+ |
| ♕ **Queen** | 2000+ |
| ♔ **King** | 2400+ |

## 🎨 Customization

Open **Settings** from the sidebar. Everything is grouped into tabs:

- **Board:** 19 themes, or pick your own light and dark square colors.
- **Pieces:** 7 piece styles, including Blind mode for an extra challenge.
- **Moves:** how pieces travel between squares.
- **Check:** how your king reacts to being in check.
- **Checkmate:** 16 animations for the end of a game. Hover to preview and click to choose.
- **Sound:** the sound played on each move.
- **Game:** gameplay options such as premoves.

<details>
<summary><b>All checkmate animations</b></summary>

Classic, Topple, Burst, Spin out, Fade away, Earthquake, Flash, Skyward, Ragdoll, Yeet, Inferno, Clock out, Trapdoor, Sliced, Anvil and Split.

</details>

## ⌨️ Controls

| Action | How |
|---|---|
| Move a piece | Click the piece, then click its destination, or drag and drop |
| Draw an arrow | Right-click and drag between two squares |
| Clear arrows | Left-click the board |
| Previous or next move (review) | `←` and `→` |
| Cancel a premove | Click the pre-moved piece |

## 🔒 Privacy and saved data

LuaChess has no backend. Nothing is sent to a server. If you accept the notice shown on your first visit, the site stores the following **in your own browser** using `localStorage`:

- Your Bullet, Blitz and Rapid ratings
- Your game history (results, opponents, moves, dates)
- Your profile name and picture
- Your settings (board colors, piece style, animations, sounds)
- A note that you accepted the notice

Choose **Reject All** and the site still works, but your progress will not be saved. Clearing your browser data removes everything the site has stored.

## 🧠 How it works

- **Engine:** a self-contained move generator and alpha-beta search written in plain JavaScript. The bot's search depth and amount of randomness depend on its rating, which is what makes low-rated bots beatable and high-rated bots sharper.
- **Rendering:** the board, pieces, effects and animations are built with HTML, CSS and the Web Animations API.
- **Audio:** move sounds are generated in the browser with the Web Audio API.
- **Dependencies:** none. No build step, no framework, no package manager.

## 💻 Run it locally

```bash
git clone https://github.com/luachess/luachess.github.io.git
cd luachess.github.io
```

Then open `index.html` in your browser, or serve the folder with any static server:

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

## 🤝 Contributing

Bug reports, ideas and pull requests are welcome.

1. [Open an issue](https://github.com/luachess/luachess.github.io/issues) describing the bug or idea.
2. Fork the repository and create a branch for your change.
3. Test it in the browser, on both desktop and mobile sizes if the change affects layout.
4. Open a pull request.

---

<div align="center">

**Made for chess lovers. ♟️**

[**Play LuaChess →**](https://luachess.github.io/)

</div>
