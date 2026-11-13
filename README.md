# KIDZVERSE — Children's Day Celebration App

A colourful, responsive, browser-based virtual amusement park built with HTML, CSS and vanilla JavaScript.

## Features
- Welcome screen with player name
- Five mini games: Number Guess, Rock Paper Scissors, Memory Match, Word Scramble and Star Catcher
- General Knowledge, Science and Computer quizzes with a 10-second timer
- Jokes, Children's Day wishes and fun facts
- Mystery gift room with a surprise reward
- Player dashboard with points, levels and achievements
- Responsive layout for desktop, tablet and mobile

## Run in VS Code
1. Extract `KIDZVERSE.zip`.
2. Open the extracted `KIDZVERSE` folder in Visual Studio Code.
3. Open `index.html` in your browser, or install the **Live Server** extension.
4. If using Live Server, right-click `index.html` and select **Open with Live Server**.

No backend, database, API key or build command is required.

## Project structure
```
KIDZVERSE/
├── index.html
├── style.css
├── script.js
└── README.md
```

## Notes
- Player progress is kept in memory for the current browser session; refreshing the page resets it.
- Google Fonts require an internet connection. The app still works with fallback fonts when offline.
- This is a front-end starter project. A real online leaderboard, accounts and cross-device progress would need a backend and database.


## KIDZVERSE 2.0 updates
- Expanded arcade with Math Blast, Color Match, Tic Tac Toe, Typing Dash and Whack-a-Mole.
- Daily login bonus: claim 20 coins once per day.
- Points and coins are saved in this browser using localStorage.
- Gift boxes require at least 25 points; the gift progress bar tracks the 100-point treasure milestone.
- Responsive arcade buttons, reward panels and hover effects.
- This is still a frontend-only game: saved progress stays on the same browser/device. No online leaderboard or cross-device account sync yet.


## KIDZVERSE 3.0 update
- New animated opening screen with three cartoon children and a Let's Play button.
- Brighter carnival colour theme, upgraded player dashboard, XP progress bar and more colourful game cards.
- Rock Paper Scissors now shows both the player's hand and the computer's hand with a reveal animation.
- Color Match now runs a changing 10-round colour challenge with shuffled options.
- Math Blast now has 10 questions, easy/medium/tough levels, a strict 5-second timer per question, and a win/loss result.
- Added five games: Reaction Rush, Odd One Out, Pattern Genius, Balloon Pop and Emoji Quiz.
- Existing 10 games and saved browser progress are retained.

## Run locally
1. Extract the ZIP folder.
2. Open the `KIDZVERSE` folder in VS Code.
3. Install the VS Code extension **Live Server** if needed.
4. Right-click `index.html` and choose **Open with Live Server**.
5. No `npm run dev` command is needed for this static HTML/CSS/JavaScript project.

Progress is saved in the current browser using localStorage. It does not sync between devices or browsers.


## KIDZVERSE 4.0
- Number Guess now uses 1–100 with 10 chances and reveals the secret number after a loss.
- Word Scramble has a 50-word pool and 10-word rounds.
- Star Catcher is a 60-second session with 15-star target and slower star movement.
- Color Match gives 15 seconds per colour round.
- Emoji Quiz includes 100+ different emoji questions; Odd One Out includes 120 different category/odd-item combinations.
- General Knowledge, Science and Computer quiz pools each contain 1,050 phrasing variations (3,150 total). These are locally generated from 30 curated facts per category with varied question wording and shuffled answer order; they are not 3,150 independently researched facts.
- Fun Zone includes extra silly jokes and fun facts.
- Gift Galaxy can award virtual character skins, pets, bicycles, scooters, karts, gems and in-game coins. Rewards are virtual only, not real money or physical items.
- Existing local browser progress remains saved in localStorage.

Run by extracting the ZIP and opening index.html with VS Code Live Server. No npm install or npm run dev is required.
